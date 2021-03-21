+++
title = "Arduino制作简易小钢琴"
date_start = "2017-01-02"
date_end = "2017-06-20"
draft = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = [""]


# Project summary to display on homepage.
summary = "将电平输出转化为相应的频率从而使无源音响发出不同的声音"

# Slides (optional).
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Optional external URL for project (replaces project detail page).
external_link = ""

# Links (optional).
url_pdf = ""
url_code = ""
url_dataset = ""
url_slides = ""
url_video = ""
url_poster = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# links = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
准备好所需的组件：
Arduino UNO x 1   按钮 x 8(按钮越多，可以演奏的音调越全！哈哈我手边只找到4个)  小压电蜂鸣器（或小型扬声器）x 1  连接电线若干  面包板 x 1

然后我们来看看电路图
{{< figure library="true" src="电路/2.jpg" title="" >}}
蜂鸣器一端连接到Arduino的一个PWM引脚，另一端连接到GND
void setup()
{
pinMode(2,INPUT); //do
pinMode(3,INPUT); //re
pinMode(4,INPUT); //mi
pinMode(5,INPUT); //fa
pinMode(6,INPUT); //sol
pinMode(7,INPUT); //la
pinMode(8,INPUT); //si
pinMode(9,OUTPUT);
将2~9号引脚置为输入状态，以读取按键开关反馈的值
将10号引脚置为输出状态，向蜂鸣器输出信号

使用tone（）函数，定将音符频率与按键相关联
if(digitalRead(3)) tone(20,587,10);
if(digitalRead(4)) tone(20,659,10);
if(digitalRead(5)) tone(20,698,10);
if(digitalRead(6)) tone(20,784,10);
if(digitalRead(7)) tone(20,880,10);
if(digitalRead(8)) tone(20,1046,10);
按下开关，发出对应音调

