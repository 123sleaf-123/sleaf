---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

教育经历 Education
======
* **北京邮电大学** — 计算机技术 · 硕士，2024/09 – 2027/06（统招）
  * \[ICCV'25\] *From Abyssal Darkness to Blinding Glare: A Benchmark on Extreme Exposure Correction in Real World* — 实际二作，负责跑通 baselines 和采集数据集。
  * 一篇 ECCV'2026 第一作者在投，利用 GPT、Kimi、Qwen-VL 等大模型输出聚合为伪标签离线存储，作为辅助数据多任务训练提升视觉模型性能。

* **北京邮电大学** — 电子商务及法律 · 本科，2020/09 – 2024/08（统招）
  * 2020 年广东高考 615 分，以广东省内专业第一考入北京邮电大学国际学院电子商务及法律专业。
  * 是一门以计算机为主辅以少量商科法学的学科。
  * 专业成绩：推免排名前 13%，GPA 3.62/4.0。
  * 代表性课程成绩：高等数学（上）90、高等数学（下）95、线性代数 96、工程数学（数学物理方法）91、运筹学 97、C 语言程序设计 98、Java 编程入门 95、区块链技术及创新实践 95、互联网协议（计算机网络）93、数据挖掘 91、Design & Build（网页制作小学期）97、信号与系统 90、电信系统 94、互联网金融 96。

发表与在投论文 Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

项目经历 Projects
======
* **Occupancy Network 的复现与改进**（2023/07）
  * 在夏令营期间，对 CVPR 2019 Occupancy Network 进行深入研究。针对生成 3D 模型效果不佳、表征中缺乏空间信息的问题，使用深度图设计了新的数据集，增加了网络的空间特征信息，提高了生成质量。团队多次被表彰，本人与多人获得优秀营员。
  * 使用多视图联合生成，增强了模型空间信息感知能力，提高了模型的表现能力。
  * 重新编写了一个渲染器输出对应角度的深度图，建立新的数据集训练 encoder，使模型更关注空间信息。

* **狮牙仓库管理系统 Lowenzahn**（2022/07 – 2022/10）
  * 前后端分离架构的 WEB 应用，能对人员、货物、仓库和个人资料进行增删改查。
  * 使用 Vue 和 Spring，实现前后端分离架构网页端仓库管理应用。
  * 使用 Nginx，实现了服务器部署和在线访问。
  * 项目地址：[github.com/123sleaf-123/Lowenzahn](https://github.com/123sleaf-123/Lowenzahn)

* **基于命令行的中国象棋游戏**（C 语言，2023/02 – 2023/03）
  * 实现了棋子移动、寻路提示、击杀提示、玩家对弈和悔棋的功能。
  * 项目地址：[github.com/123sleaf-123/ChineseChess-](https://github.com/123sleaf-123/ChineseChess-)

* **《三天打鱼》— 基于 C# 和 Godot 的类幸存者肉鸽游戏**（2024/01 – 2024/03）
  * 实现了移动、射击、怪物生成、经验值掉落、升级与选项升级。

荣誉奖项 Honors & Awards
======
* 全国大学生数学竞赛，三等奖
