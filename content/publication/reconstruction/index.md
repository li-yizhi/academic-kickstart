+++
title = "一种基于半峰值概率密度分布的三维重建方法"
date = 2019-05-27T20:04:23-04:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["从飞云", "**李慧敏**", "童水光"]
# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "国家知识产权局"
publication_short = ""

# Abstract and optional shortened version.
abstract = "本发明公开了一种基于半峰值概率密度分布的三维重建方法，包括以下步骤：将三维点云沿Z轴方向切片，得到N个空间层；提取第i个空间层内散点信息并将其投影至Zi平面；构建Zi平面各网格与散点的隶属度函数，绘制三维概率密度图；过三维概率密度图半峰值wmax/2作平行于XOY平面的平面，该平面与三维概率密度图相交后获得轮廓LXY，该轮廓LXY为第i个空间层对应的放射源重建轮廓；依次叠加N个空间层对应的放射源重建轮廓，获得放射源三维重建模型。本发明的方法能够应用于核电领域，能够实现核事故发生后放射源的快速重建及退役放射源轮廓精确重建。"
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = "reconstruction.png"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["移动机器人", "高精度定位导航"]

# Links (optional).
url_pdf = "http://oss.wanfangdata.com.cn/www/%E4%B8%80%E7%A7%8D%E5%9F%BA%E4%BA%8E%E5%8D%8A%E5%B3%B0%E5%80%BC%E6%A6%82%E7%8E%87%E5%AF%86%E5%BA%A6%E5%88%86%E5%B8%83%E7%9A%84%E4%B8%89%E7%BB%B4%E9%87%8D%E5%BB%BA%E6%96%B9%E6%B3%95.ashx?isread=true&type=patent&resourceId=CN201910446247.9"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = "http://d.wanfangdata.com.cn/patent/CN201910446247.9"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "reconstruction.png"
caption = ""

+++

