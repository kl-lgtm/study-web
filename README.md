# 个人学习网站

基于原生 HTML5、CSS3、JavaScript 与 ECharts 构建的个人学习管理网站，无需构建工具与依赖，浏览器直接打开即可运行。

## 功能模块

| 页面 | 功能 |
| --- | --- |
| index.html | 首页总览 |
| introduce.html | 课程介绍 |
| memo.html | 学习备忘录 |
| reading.html | 阅读与读书笔记 |
| schedule.html | 计划安排 |
| chart.html | 学习数据图表统计（ECharts） |
| account.html | 账号管理 |
| book.html | 图书收藏 |

## 运行方法

直接双击 `index.html` 用浏览器打开即可；或在 VSCode 中用 Live Server 插件启动，支持热更新。

## 目录结构

```text
study-web/
├─ index.html
├─ introduce.html
├─ memo.html
├─ reading.html
├─ schedule.html
├─ chart.html
├─ account.html
├─ book.html
├─ css/
│  └─ style.css
├─ js/
│  └─ utils.js
└─ imgs/
```

## 说明

- 纯静态项目，无框架、无构建步骤，全部为原生 HTML/CSS/JS 实现。
- 图表功能基于 ECharts 通过 CDN 引入。
- 个人课程学习项目，仅用于学习交流。
