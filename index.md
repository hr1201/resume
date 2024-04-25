---
layout: cv
title: hr1201's Resume
email:
  url: mailto:568127468@qq.com
  text: 568127468@qq.com
homepage:
  url: https://www.rorrot.cc
  text:  blog：wwww.rorrot.cc
---

# 黄荣

{% include cv-contact.html %}

## 教育经历

### 广州城市理工学院(原华南理工大学广州学院)  本科  软件工程 `2021-至今`
### GPA: 3.31/4.0 (前15%)
### 在校荣誉: 校三好学生
### 校园经历: 机器人实验室的软件组，主要负责前端开发，开发过萝卜项管管理后台，用于组员时间统计和每周周报预览，帮助编写维护高校物资、萝卜项管两个小程序，具备一定的团队开发经验。

## 相关技能

- 熟练使用HTML、CSS，掌握Flex、grid的常用页面布局。
- 熟悉JavaScript基本特性，理解JS原型与原型链、闭包等概念，熟悉promise、async/await等ES6新特性。
- 熟练使用**Vue3全家桶+TS+Element--plus**进行开发，在项目中能运用**TypeScript、Less、Sass**进行开发。
- 开发中会对工具函数进行封装(**Axios二次封装，ECharts图表二次封装**)。
- 在开发中能使用**eslint+prettier**规范代码规范，使用**husky**对Git版本管理提交注释进行规范。
- 了解Webpack、vite等前端工程化工具。
- 了解 nodejs+Express+MySQL进行后端搭建，能和前端实现简单数据交互，能编写RestFul风格的接口。

## 项目经历

### **萝卜项管后台管理系统** *前端开发* `2023/09`
**项目简介:** 用来管理萝卜项管小程序，后台可以用来管理队员的crud、管理队员动态、以及预览队员的word文档周报、统计队员本周钉钉打卡时长。

**技术栈:** Vue3+Vite+TS+Element-Plus+Pinia+Axios+Vue-Router+Echarts

**主要职责:** 
- **首页大屏使用Echarts图表**实现大屏服务，组件销毁前注销Echarts实例，防止内存泄漏。
- 实现**Axios**封装，封装token请求头，设置baseURL和vite的proxy配置联合实现跨域。
- 使用**KeepAlive**实现组件间的切换来显示不同的功能，使得组件缓存放置重复污染。
- **大屏加载优化**，首次加载使用CSS的loading提示，优化用户体验。
- 使用**vue-office**实现组员word文档周报的预览。

### **个人博客** *前端开发* `2022/09-至今`
**项目简介:** 博客功能有搜索、评论、工具导航、图片预览、小动画、PWA，博客中会编写Vue组件当做demo来演示。

**技术栈:** Vitepress+Vue3+Vite+TS+Less

**项目难点:** 
- 实现自动生成侧边栏，使用**directory-tree**和**递归**获取到目录下的所有md文件，生成相应侧边栏结构。
- 对于md文件的crud时热更新，用vite的configureServer的watcher监听文件变化，变化时用restart重新加载。
- 工具导航需要加载图片较多，用directive实现自定义懒加载指令提高性能。

## 自我评价
- 经常浏览开源社区以及技术论坛，如Github，stack overflow，掘金等，能通过官方文档进行学习。
- 热爱前端开发、立志于深耕前端领域的技术，有上进心，能承受一定的工作压力。
