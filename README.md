# 个人学习网站

基于原生 HTML5、CSS3 与 JavaScript 构建的个人学习管理网站（Web 前端课程综合项目），无框架、无构建工具，浏览器直接打开即可运行。

## 功能模块

| 页面 | 功能 |
| --- | --- |
| index.html | 首页：登录/注册弹窗（正则校验、密码可见切换）、课程轮播图、iframe 导航与实时时间 |
| introduce.html | 课程简介 |
| schedule.html | 课表：课程/教室表格，点击课程单元格显示详情 |
| book.html | 教材：各课程教材与参考书封面展示（hover 动效） |
| memo.html | 备忘录：备忘事项增删改、完成状态与等级标记、日期管理，localStorage 持久化 |
| chart.html | ECharts 图表演示：基础折线图、堆叠折线图、区域面积图、基础饼图 |
| account.html | 记账本：收支记录管理、收入/支出/结余汇总、分类与筛选，localStorage 持久化 |
| reading.html | 阅读清单：书籍管理（技术/文学/历史/哲学分类）、已读/在读/未读统计，localStorage 持久化 |

## 技术要点

- 原生 HTML5 / CSS3 / JavaScript，无任何框架与构建步骤
- HTML5 语义化标签（header / footer / article）
- Flex 弹性布局 + 响应式适配（media query）
- localStorage 本地数据持久化
- ECharts 图表（CDN 引入）
- iframe 内嵌框架导航、表单正则校验、密码可见性切换

## 运行方法

直接双击 `index.html` 用浏览器打开即可；或在 VSCode 中用 Live Server 插件启动，支持热更新。

## 目录结构

```text
study-web/
├─ index.html
├─ introduce.html
├─ schedule.html
├─ book.html
├─ memo.html
├─ chart.html
├─ account.html
├─ reading.html
├─ css/
│  └─ style.css
├─ js/
│  └─ utils.js
└─ imgs/
```

## 说明

- 个人课程学习项目，仅用于学习交流。
- 首页 footer 含个人姓名与学号信息，如需对外公开建议自行替换或删除。
