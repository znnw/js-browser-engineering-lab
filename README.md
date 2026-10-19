# JavaScript 基础 · 进阶 · Web APIs

> 从语言机制到浏览器交互，用 16 个递进模块把 JavaScript 知识落到可运行的页面与案例中。

[![HTML5](https://img.shields.io/badge/HTML5-236%20pages-E34F26?logo=html5&logoColor=white)](#课程地图)
[![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?logo=javascript&logoColor=black)](#技术亮点)
[![CSS3](https://img.shields.io/badge/CSS3-UI%20Practice-1572B6?logo=css3&logoColor=white)](#课程地图)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

[中文](#javascript-基础--进阶--web-apis) · [English](#english)

<p>
  <img src="./docs/screenshots/product-detail.png" alt="小兔鲜儿商品详情页" width="68%" />
  <img src="./docs/screenshots/mobile-park.png" alt="游乐园移动端首页" width="24%" />
</p>

## 项目简介

这是一个以原生 JavaScript 为主线的浏览器开发实战仓库。内容覆盖语言基础、进阶机制、DOM/BOM、事件系统、数据持久化、正则表达式、移动端交互和综合页面重构，并通过逐日演进的示例，展示从单一知识点到完整交互功能的实现过程。

项目不依赖构建工具。每个模块的核心页面都可以直接在浏览器中运行，便于阅读源码、拆分实验、复现问题和观察 DOM 行为。

| 维度 | 内容 |
| --- | --- |
| 学习路径 | 16 个模块：基础语法 -> 进阶机制 -> Web APIs -> 综合案例 |
| 可运行页面 | 236 个 HTML 页面 |
| 源码规模 | 273 个 HTML/CSS/JS/LESS 文件，约 5 万行 |
| 静态资源 | 509 张图片 |
| 构建依赖 | 0，直接由浏览器运行 |

## 技术亮点

- **语言核心**：作用域链、闭包、变量与函数提升、`this`、`call` / `apply` / `bind`、箭头函数、解构、展开与剩余参数。
- **面向对象**：构造函数、实例成员与静态成员、原型、原型链、原型继承、面向对象封装和 `constructor` 关系。
- **函数与数据处理**：高阶函数、`forEach` / `map` / `filter` / `reduce`、递归、浅拷贝与深拷贝、异常抛出与捕获。
- **性能意识**：手写防抖与节流，并结合 `timeupdate` 和 `localStorage` 实现视频播放进度持久化。
- **DOM/BOM**：元素查询与节点操作、属性与样式控制、自定义属性、定时器、页面尺寸与滚动、`location` / `history` / `localStorage`。
- **事件系统**：事件监听、事件对象、冒泡、事件委托、默认行为拦截、键盘/焦点/触摸事件和事件解绑。
- **表单与数据校验**：用户名、手机号、验证码和密码正则校验，验证码倒计时、登录状态保存和前端表单交互。
- **交互实现**：轮播图、Tab 切换、电梯导航、全选反选、放大镜、评论发布、抽奖和移动端活动页。
- **工程习惯**：数据与视图分离的渲染函数、事件委托、复用函数、原型方法封装，以及 Lodash / Swiper 等第三方库的集成。

## 快速开始

### 直接打开

在文件管理器中打开任意模块的 `code` 目录，双击 HTML 文件即可运行。推荐从下面的代表案例开始。

### 本地静态服务

部分页面需要加载相对路径下的图片、字体或脚本，建议从仓库根目录启动静态服务器：

```powershell
python -m http.server 8000
```

然后访问：

```text
http://localhost:8000/JS基础Day1/code/01-体验js.html
```

也可以在 VS Code 中使用 Live Server 打开任意 HTML 页面。项目没有安装、构建或压缩步骤。

> 部分综合案例使用 CDN 视频、远程图片或第三方库。首次打开相关页面时需要网络连接。

## 课程地图

### JavaScript 基础

| 模块 | 核心内容 | 代表案例 |
| --- | --- | --- |
| `JS基础Day1` | 变量、数据类型、转换、输入输出、模板字符串 | [基础语法综合练习](<JS基础Day1/code/24-综合案例.html>) |
| `JS基础Day2` | 运算符、分支、循环、断点调试 | [简易 ATM 取款机](<JS基础Day2/code/20-综合案例-简易ATM取款机.html>) |
| `JS基础Day3` | for 循环、数组操作、嵌套循环 | [根据数据生成柱形图](<JS基础Day3/code/16-综合案例-根据数据生成柱形图.html>) |
| `JS基础Day4` | 函数、返回值、作用域、立即执行函数 | [函数综合案例](<JS基础Day4/code/16-综合案例.html>) |
| `JS基础Day5` | 对象、数组对象遍历、Math、随机数 | [学车在线首页](<JS基础Day5/code/综合作业素材/index.html>) |

### JavaScript 进阶

| 模块 | 核心内容 | 代表案例 |
| --- | --- | --- |
| `进阶JS第1天` | 闭包、解构、箭头函数、高阶函数 | [商品价格筛选](<进阶JS第1天/code/20-综合案例-价格筛选.html>) |
| `进阶JS第2天` | 对象静态方法、数组高级方法、`reduce` | [薪资计算案例](<进阶JS第2天/code/07-计算薪资案例.html>) |
| `进阶JS第3天` | 构造函数、原型链、原型继承、OOP 封装 | [模态框组件封装](<进阶JS第3天/code/08-综合案例-模态框封装.html>) |
| `进阶JS第4天` | 深拷贝、递归、异常、`this`、防抖与节流 | [节流与视频续播](<进阶JS第4天/code/17-节流综合案例.html>) |

### Web APIs

| 模块 | 核心内容 | 代表案例 |
| --- | --- | --- |
| `WEB APIS第1天` | DOM 查询、内容/属性/样式修改、间歇定时器 | [定时轮播图](<WEB APIS第1天/code/18-轮播图定时版.html>) |
| `WEB APIS第2天` | 事件监听、键盘与焦点事件、Tab 切换 | [Tab 栏切换](<WEB APIS第2天/code/18-tab栏切换.html>) |
| `WEB APIS第3天` | 事件流、事件委托、页面滚动、电梯导航 | [小兔鲜儿电梯导航](<WEB APIS第3天/code/电梯导航素材/电梯导航.html>) |
| `WEB APIS第4天` | Date、节点增删改、移动端触摸事件、Swiper | [游乐园移动端首页](<WEB APIS第4天/code/FC/index.html>) |
| `WEB APIS第5天` | BOM、定时器、`localStorage`、复杂数据存储 | [学生就业统计表](<WEB APIS第5天/code/综合案例-学生统计表/学生就业统计表案例.html>) |
| `WEB APIS第6天` | 正则表达式、表单校验、登录状态管理 | [小兔鲜儿注册页](<WEB APIS第6天/code/综合案例素材/register.html>) |
| `WEB APIS第7天` | 综合布局、缩略图切换、放大镜与事件协调 | [商品详情综合页](<WEB APIS第7天/code/product-dev.html>) |

## 代表案例

### 1. 小兔鲜儿商品详情页

[查看源码](<WEB APIS第7天/code/product-dev.html>)

- 通过事件委托处理缩略图切换，减少重复事件绑定。
- 基于 `getBoundingClientRect()`、页面滚动量计算遮罩位置，并同步控制放大区域的背景偏移。
- 处理鼠标进入/离开时的延迟隐藏，避免传入放大镜区域时闪烁。
- 将静态布局、图片列表、标签页与鼠标交互整合到同一个可运行页面中。

### 2. 学生就业统计表

[查看源码](<WEB APIS第5天/code/综合案例-学生统计表/学生就业统计表案例.html>)

- 使用对象数组描述学生数据，通过 `map` 和 `join` 完成列表渲染。
- 使用 `localStorage` 与 `JSON.stringify` / `JSON.parse` 实现数据持久化。
- 表单提交完成新增、重置与即时重绘，删除操作采用事件委托。
- 通过统一 `render()` 函数保持数据与视图同步。

### 3. 数据驱动轮播图

[查看源码](<WEB APIS第2天/code/08-轮播图完整版.html>)

- 以索引维护当前状态，处理首尾循环和指示器同步。
- 自动播放、鼠标停留暂停、离开恢复，以及前后按钮共用渲染逻辑。
- 图片、标题、主题色和小圆点由同一份数据驱动。

### 4. 登录、注册与正则校验

[查看注册页](<WEB APIS第6天/code/综合案例素材/register.html>) · [查看登录页](<WEB APIS第6天/code/综合案例素材/login.html>)

- 针对用户名、手机号、验证码和密码分别建立校验规则。
- 验证码倒计时使用 `setInterval` 管理，并在结束时清理状态。
- 登录后通过 `localStorage` 保存用户名，首页根据登录状态更新导航文案。

### 5. 面向对象模态框

[查看源码](<进阶JS第3天/code/08-综合案例-模态框封装.html>)

- 使用构造函数生成实例，并将 `open` / `close` 方法挂载到原型。
- 通过实例状态管理 DOM 节点，结合箭头函数保留 `this` 指向。
- 用同一份组件逻辑支持不同标题和提示内容。

### 6. 防抖、节流与播放进度恢复

[查看节流案例](<进阶JS第4天/code/17-节流综合案例.html>)

- 使用 Lodash `throttle` 控制高频 `timeupdate` 事件的写入频率。
- 将视频播放时间写入 `localStorage`，在 `loadeddata` 后恢复上次进度。
- 兼顾交互体验、DOM 性能与本地数据持久化。

## 项目结构

```text
.
|-- JS基础Day1 ... JS基础Day5/
|   `-- code/                 # 基础语法与页面练习
|-- 进阶JS第1天 ... 进阶JS第4天/
|   `-- code/                 # 语言机制、原型、拷贝与性能优化
|-- WEB APIS第1天 ... WEB APIS第7天/
|   `-- code/                 # DOM/BOM、事件、数据持久化与综合项目
|-- docs/screenshots/         # README 页面预览
|-- .github/                  # Issue 与 Pull Request 模板
|-- .editorconfig
|-- .gitattributes
|-- .gitignore
|-- CONTRIBUTING.md
|-- LICENSE
|-- NOTICE.md
|-- README.md
`-- SECURITY.md
```

每个学习日的 `code` 目录均按知识点编号组织，文件名直接描述当前示例的主题，方便按顺序学习，也方便单独定位和复现问题。

## 工程约定

- 优先使用浏览器原生能力，不引入不必要的运行时或构建链。
- 综合案例尽量拆分为数据、渲染和事件处理三个关注点。
- 列表交互优先使用事件委托，高频事件优先考虑防抖或节流。
- 新增示例应保持可独立运行，并放在对应模块的 `code` 目录中。
- 提交前检查控制台错误、断链资源、路径大小写和移动端显示。

## 使用边界

这是一个用于系统练习和作品展示的静态案例集，不是可直接上线的生产系统：

- 不包含后端服务、真实身份认证、支付或数据库。
- 表单校验仅用于前端交互演示，不能替代服务端校验。
- 项目以教学清晰度为目标，未配置打包、压缩和自动化测试流水线。
- 第三方课程素材、图片、字体和库的版权归各自权利人所有，详见 [NOTICE.md](NOTICE.md)。

## 参与贡献

欢迎提交问题反馈、案例修正或新的原生 JavaScript 实践。提交前请阅读 [CONTRIBUTING.md](CONTRIBUTING.md)，并避免在仓库中写入账号、令牌、密钥或其他敏感信息。

## 许可证

本仓库中由作者编写的源代码和文档采用 [MIT License](LICENSE)。第三方图片、字体、课程素材和库不自动包含在 MIT 授权范围内，具体说明见 [NOTICE.md](NOTICE.md)。

---

## English

### Overview

A structured vanilla JavaScript portfolio covering language fundamentals, advanced runtime behavior, DOM/BOM APIs, event systems, client-side persistence, regular expressions, mobile interactions, and integrated browser projects. The repository contains 16 progressive modules, 236 runnable HTML pages, and roughly 50,000 lines of source code in HTML, CSS, JavaScript, and LESS.

The main goal is to make each concept observable in a real browser. Core examples run without a build step, so the implementation can be inspected, modified, and tested directly.

### Technical Highlights

- **Language mechanics**: scope chains, closures, hoisting, `this`, `call` / `apply` / `bind`, arrow functions, destructuring, rest and spread syntax.
- **Object-oriented JavaScript**: constructors, instance and static members, prototypes, prototype chains, inheritance, and encapsulated UI components.
- **Functional data processing**: higher-order functions, `map` / `filter` / `reduce`, recursion, shallow and deep copying, and exception handling.
- **Browser APIs**: DOM traversal and mutation, attribute/style/class control, timers, scroll and viewport metrics, `location`, `history`, and `localStorage`.
- **Event architecture**: event delegation, bubbling, default behavior, keyboard/focus/touch events, and listener lifecycle management.
- **Validation and persistence**: regular-expression form validation, verification-code countdowns, JSON-based local storage, and login-state UI updates.
- **Interaction engineering**: carousels, tabs, elevator navigation, image magnifiers, comments, lotteries, and mobile landing pages.
- **Performance awareness**: debounce/throttle, throttled video progress writes, and state restoration from local storage.
- **Third-party integration**: practical use of Lodash and Swiper without hiding the underlying browser behavior.

### Quick Start

Open any HTML file under a module's `code` directory, or serve the repository locally:

```powershell
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000/JS基础Day1/code/01-体验js.html
```

No package installation or build step is required. Some integrated demos load remote media or CDN resources and therefore need internet access.

### Curriculum

| Stage | Modules | Topics |
| --- | --- | --- |
| JavaScript Basics | `JS基础Day1` to `JS基础Day5` | Data types, operators, control flow, arrays, functions, scope, objects, Math, and small UI exercises |
| Advanced JavaScript | `进阶JS第1天` to `进阶JS第4天` | Closures, destructuring, higher-order functions, prototypes, inheritance, copying, recursion, exceptions, `this`, debounce, and throttle |
| Web APIs | `WEB APIS第1天` to `WEB APIS第7天` | DOM/BOM, events, timers, scrolling, dates, node operations, local storage, regex validation, mobile events, and integrated projects |

### Featured Demos

- [Product detail page](<WEB APIS第7天/code/product-dev.html>): thumbnail delegation, delayed magnifier visibility, coordinate calculations, and synchronized preview.
- [Student employment table](<WEB APIS第5天/code/综合案例-学生统计表/学生就业统计表案例.html>): CRUD interactions, event delegation, rendered rows, and JSON persistence.
- [Full carousel](<WEB APIS第2天/code/08-轮播图完整版.html>): data-driven rendering, autoplay, pause-on-hover, indicators, and boundary handling.
- [Registration form](<WEB APIS第6天/code/综合案例素材/register.html>): field-level regex validation, countdown state, and client-side login flow.
- [OOP modal](<进阶JS第3天/code/08-综合案例-模态框封装.html>): constructor/prototype encapsulation with controlled DOM creation.
- [Throttled video resume](<进阶JS第4天/code/17-节流综合案例.html>): high-frequency event throttling and persisted playback position.

### Repository Layout

Each learning day contains a `code` directory with numbered, self-contained examples. Supporting screenshots live in `docs/screenshots`, while contribution, security, licensing, and GitHub templates are kept at the repository root or under `.github`.

### Scope

This is an educational and portfolio-oriented static project, not a production application. It has no backend, real authentication, payment flow, database, bundler, or automated test suite. Client-side validation is demonstrative only. Third-party course assets, images, fonts, and libraries remain subject to their original licenses and ownership.

### Contributing and License

See [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request. Original source code and documentation are released under the [MIT License](LICENSE). Third-party materials are excluded from that grant and are described in [NOTICE.md](NOTICE.md).
