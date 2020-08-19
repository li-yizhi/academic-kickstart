+++
title = "基于STM32的叉车运行信息远程测控"
date_start = "2019-06-02"
date_end = "2020-02-20"
draft = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["物联网","远程测控"]


# Project summary to display on homepage.
summary = "负责部分：<br>叉车运行数据（温度/湿度/运行速度/位置信息/）采集盒设计及采集上传程序调试，实现叉车数据OneNET云平台实时上传监测<br>项目描述：<br>●基于F103ZET6主控制器，通过温湿度、加速度等传感器获取叉车运行信息；<br>●利用基于UWB的TDOA定位算法实现叉车室内环境下位置信息获取"

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
image = "headers/title.png"
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++

叉车运行数据（温度/湿度/运行速度/位置信息/）采集盒设计及采集上传程序调试，实现叉车数据OneNET云平台实时上传监测
{{< figure library="true" src="finish/基于STM32的叉车远程测控终端与维护系统.jpg" title="" >}}
基于F103ZET6主控制器，通过温湿度、加速度等传感器获取叉车运行信息
利用基于UWB的TDOA定位算法实现叉车室内环境下位置信息获取
