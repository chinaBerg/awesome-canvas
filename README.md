![](./assets/logo.png)
## awesome-canvas
精心收录Canvas相关的资源并整理分类，部分同类资源库也收录SVG/WebGL相关的资源。

## 目录

- [awesome-canvas](#awesome-canvas)
- [目录](#目录)
- [仓库](#仓库)
  - [图形绘制](#图形绘制)
  - [图表库](#图表库)
  - [3D库](#3d库)
  - [全景图](#全景图)
  - [流程图](#流程图)
  - [甘特图](#甘特图)
  - [组织图/脑图](#组织图脑图)
  - [Excel/电子表格](#excel电子表格)
  - [截图/图片生成](#截图图片生成)
  - [数据处理](#数据处理)
  - [图像处理](#图像处理)
  - [画板](#画板)
  - [游戏引擎/物理引擎](#游戏引擎物理引擎)
  - [波纹](#波纹)
  - [粒子/路径动画](#粒子路径动画)
  - [二维码](#二维码)
  - [验证码](#验证码)
  - [运行时](#运行时)
  - [其他](#其他)
- [文档/教程](#文档教程)
- [文章](#文章)
- [效果/案例](#效果案例)
- [贡献者](#贡献者)
- [协议](#协议)

## 仓库
### 图形绘制
  - [fabric.js](http://fabricjs.com/) [[在线演示](http://fabricjs.com/demos/)] - Fabric.js是一个可以轻松处理Canvas元素的框架,也是SVG-to-Canvas和Canvas-to-SVG的解析器 ![](https://img.shields.io/github/stars/fabricjs/fabric.js?style=social) ![](https://img.shields.io/github/forks/fabricjs/fabric.js?style=social)
    - [vue-fabric](https://github.com/purestart/vue-fabric) - 基于canvas fabric.js库 创建的vue fabric组件，定制画板，图片组合绘制 ![](https://img.shields.io/github/stars/purestart/vue-fabric?style=social) ![](https://img.shields.io/github/forks/purestart/vue-fabric?style=social)
    - [fabric-js-editor](https://github.com/danielktaylor/fabric-js-editor) - 基于Fabric.js构建的HTML5矢量图像编辑器 ![](https://img.shields.io/github/stars/danielktaylor/fabric-js-editor?style=social) ![](https://img.shields.io/github/forks/danielktaylor/fabric-js-editor?style=social)
    - [fabric-brush](https://github.com/tennisonchan/fabric-brush) [[在线示例](https://tennisonchan.github.io/fabric-brush/)] - Crayon是基于一个很棒的框架Fabric.js的Canvas笔刷 ![](https://img.shields.io/github/stars/tennisonchan/fabric-brush?style=social) ![](https://img.shields.io/github/forks/tennisonchan/fabric-brush?style=social)
  - [two.js](https://two.js.org/#introduction) [[在线演示](https://two.js.org/examples/)] - 一个渲染器无关的Web 2D绘图API ![](https://img.shields.io/github/stars/jonobr1/two.js?style=social) ![](https://img.shields.io/github/forks/jonobr1/two.js?style=social)
  - [EaselJS](https://www.createjs.com/getting-started/easeljs) - EaselJS是一个用于在HTML5中构建高性能交互式2D内容的库 ![](https://img.shields.io/github/stars/CreateJS/EaselJS?style=social) ![](https://img.shields.io/github/forks/CreateJS/EaselJS?style=social)
  - [spritejs](https://spritejs.org/#/) [[在线演示](https://spritejs.org/demo/)] - 一个跨平台的高性能图形系统 ![](https://img.shields.io/github/stars/spritejs/spritejs?style=social) ![](https://img.shields.io/github/forks/spritejs/spritejs?style=social)
  - [konva](https://konvajs.org/) [[在线演示](https://konvajs.org/docs/sandbox/index.html)] - Konva.js是一个HTML5 Canvas JS框架，通过扩展2D context让桌面和移动应用的Canvas支持交互性 ![](https://img.shields.io/github/stars/konvajs/konva?style=social) ![](https://img.shields.io/github/forks/konvajs/konva?style=social)
    - [konva中文文档](http://konvajs-doc.bluehymn.com/docs/)
    - [react-konva](https://konvajs.org/) [[在线演示](https://codesandbox.io/s/5m3nwp787x)] - 基于[konva](https://konvajs.org/), 用于使用React绘制复杂画布图形的JavaScript库 ![](https://img.shields.io/github/stars/konvajs/react-konva?style=social) ![](https://img.shields.io/github/forks/konvajs/react-konva?style=social)
    - [vue-konva](https://github.com/konvajs/vue-konva) - 基于Vue和[konva](https://konvajs.org/)绘制复杂canvas图形的js库 ![](https://img.shields.io/github/stars/konvajs/vue-konva?style=social) ![](https://img.shields.io/github/forks/konvajs/vue-konva?style=social)
    - [react-proto](https://github.com/React-Proto/react-proto) - 为开发人员和设计人员的React原型工具应用 ![]() ![]()
  - [concretejs](http://www.concretejs.com/) [[在线演示](http://www.concretejs.com/#examples)]- Concrete是一个超快、轻量级的Html5 Canvas框架，支持hit检测、分层、像素比率管理、导出和下载 ![](https://img.shields.io/github/stars/ericdrowell/concrete?style=social) ![](https://img.shields.io/github/forks/ericdrowell/concrete?style=social)
  - [cax](https://github.com/dntzhang/cax/blob/master/README.CN.md) [[在线演示](https://github.com/dntzhang/cax/blob/master/README.CN.md)] - 小程序、小游戏以及 Web 通用 Canvas 渲染引擎 ![](https://img.shields.io/github/stars/dntzhang/cax?style=social) ![](https://img.shields.io/github/forks/dntzhang/cax?style=social)
  - [wxDraw](https://bobiscool.github.io/wxDrawDocs/#/) [[在线演示](https://github.com/bobiscool/wxDraw#wxdraw%E5%88%9B%E4%BD%9C%E7%9A%84%E5%8A%A8%E7%94%BB%E6%BC%94%E7%A4%BA)] - 微信小程序2d动画库 ![](https://img.shields.io/github/stars/bobiscool/wxDraw?style=social) ![](https://img.shields.io/github/forks/bobiscool/wxDraw?style=social)
  - [atrament.js](https://github.com/jakubfiala/atrament.js) - 一个小型 JS 库，用于在 HTML Canvas 上进行漂亮的绘图和手绘 ![](https://img.shields.io/github/stars/jakubfiala/atrament.js?style=social) ![](https://img.shields.io/github/forks/jakubfiala/atrament.js?style=social)

### 图表库
  - [D3](https://github.com/d3/d3) [[在线演示](https://observablehq.com/@d3/gallery)] - D3(或D3.js)是一个用于web标准可视化数据的JS库。 ![](https://img.shields.io/github/stars/d3/d3?style=social) ![](https://img.shields.io/github/forks/d3/d3?style=social)
    - [awesome-d3](https://github.com/wbkd/awesome-d3) ![](https://img.shields.io/github/stars/wbkd/awesome-d3?style=social) ![](https://img.shields.io/github/forks/wbkd/awesome-d3?style=social)
    - [angular-charts](https://github.com/chinmaymk/angular-charts) - 基于D3创建Angular创建图表的指令库 ![](https://img.shields.io/github/stars/chinmaymk/angular-charts?style=social) ![](https://img.shields.io/github/forks/chinmaymk/angular-charts?style=social)
    - [nvd3](http://nvd3-community.github.io/nvd3/examples/documentation.html) [[在线演示](http://nvd3-community.github.io/nvd3/)] - 一个用d3.js编写的可重用图表库 ![](https://img.shields.io/github/stars/novus/nvd3?style=social) ![](https://img.shields.io/github/forks/novus/nvd3?style=social)
    - [c3](https://c3js.org/) [[在线演示](https://c3js.org/examples.html)] - 一个基于D3的可重用图表库 ![](https://img.shields.io/github/stars/c3js/c3?style=social) ![](https://img.shields.io/github/forks/c3js/c3?style=social)
    - [dc.js](https://github.com/dc-js/dc.js) [[在线演示](http://dc-js.github.io/dc.js/)] - 基于D3使用corssfilter渲染的多维图表 ![](https://img.shields.io/github/stars/dc-js/dc.js?style=social) ![](https://img.shields.io/github/forks/dc-js/dc.js?style=social)
    - [britecharts](https://britecharts.github.io/britecharts/) [[在线演示](https://britecharts.github.io/britecharts/tutorial-bar.html)] - 基于D3.js v5的客户端可重用图表库 ![](https://img.shields.io/github/stars/britecharts/britecharts?style=social) ![](https://img.shields.io/github/forks/britecharts/britecharts?style=social)
    - [neo4jd3](https://github.com/eisman/neo4jd3) [[在线演示](https://britecharts.github.io/britecharts/tutorial-bar.html)] - 使用D3.js的Neo4j图形可视化。![](https://img.shields.io/github/stars/eisman/neo4jd3?style=social) ![](https://img.shields.io/github/forks/eisman/neo4jd3?style=social)

  - [echarts](https://github.com/apache/echarts) [[在线演示](https://echarts.apache.org/examples/zh/index.html)] - 一个强大的交互式图表和数据可视化库 ![](https://img.shields.io/github/stars/apache/echarts?style=social) ![](https://img.shields.io/github/forks/apache/echarts?style=social)
    - [v-charts](https://v-charts.js.org/#/) [[在线演示](https://codesandbox.io/s/z69myovqzx)] - 基于 Vue2.0 和 ECharts 封装的图表组件 ![](https://img.shields.io/github/stars/ElemeFE/v-charts?style=social) ![](https://img.shields.io/github/forks/ElemeFE/v-charts?style=social)
    - [echarts-for-weixin](https://github.com/ecomfe/echarts-for-weixin) - Apache ECharts (incubating) 的微信小程序版本 ![](https://img.shields.io/github/stars/ecomfe/echarts-for-weixin?style=social) ![](https://img.shields.io/github/forks/ecomfe/echarts-for-weixin?style=social)

  - [Chart.js](https://github.com/chartjs/Chart.js) [[在线演示](https://www.chartjs.org/docs/latest/samples/bar/vertical.html)] - 给开发和设计人员的简单而灵活的js图表 ![](https://img.shields.io/github/stars/chartjs/Chart.js?style=social) ![](https://img.shields.io/github/forks/chartjs/Chart.js?style=social)
    - [vue-chartjs](https://vue-chartjs.org/zh-cn/) [[在线演示](http://demo.vue-chartjs.org/)] - 基于Chart.js的Vue图表组件 ![]() ![]()
    - [react-chartjs](https://github.com/reactjs/react-chartjs) [[在线演示]()] - 基于chart.js的React图表组件 ![](https://img.shields.io/github/stars/reactjs/react-chartjs?style=social) ![](https://img.shields.io/github/forks/reactjs/react-chartjs?style=social)
    - [angular-chart.js](http://jtblin.github.io/angular-chart.js/) [[在线演示](http://jtblin.github.io/angular-chart.js/#top)] - 基于Chart.js的AngularJS响应式、漂亮的图表库 ![](https://img.shields.io/github/stars/jtblin/angular-chart.js?style=social) ![](https://img.shields.io/github/forks/jtblin/angular-chart.js?style=social)

  - [highcharts](https://github.com/highcharts/highcharts) [[在线演示](https://www.highcharts.com/demo)] - 基于SVG的JavaScript图表库,支持旧浏览器 ![](https://img.shields.io/github/stars/highcharts/highcharts?style=social) ![](https://img.shields.io/github/forks/highcharts/highcharts?style=social)

  - [F2](https://antv-f2.gitee.io/zh/docs/tutorial/getting-started) [[在线演示](https://antv-f2.gitee.io/zh/examples/gallery)] - 一个专注于移动，开箱即用的可视化解决方案，完美支持 H5 环境同时兼容多种环境（node, 小程序，weex） ![](https://img.shields.io/github/stars/antvis/F2?style=social) ![](https://img.shields.io/github/forks/antvis/F2?style=social)

  - [wx-charts](https://github.com/xiaolin3303/wx-charts) [[在线演示](https://github.com/xiaolin3303/wx-charts-demo)] - 微信小程序图表charts组件 ![](https://img.shields.io/github/stars/xiaolin3303/wx-charts?style=social) ![](https://img.shields.io/github/forks/xiaolin3303/wx-charts?style=social)

  - [wordcloud2.js](https://github.com/timdream/wordcloud2.js) [[在线演示](https://wordcloud2-js.timdream.org/#love)] - 2D Canvas/Html词云 ![](https://img.shields.io/github/stars/timdream/wordcloud2.js?style=social) ![](https://img.shields.io/github/forks/timdream/wordcloud2.js?style=social)

  - [chartist-js](https://github.com/gionkunz/chartist-js) [[在线演示](http://gionkunz.github.io/chartist-js/examples.html)] - 简单的响应式图表 ![](https://img.shields.io/github/stars/gionkunz/chartist-js?style=social) ![](https://img.shields.io/github/forks/gionkunz/chartist-js?style=social)

  - [charts](https://frappe.io/charts/docs) [[在线演示](https://frappe.io/charts)] - 零依赖的、简单的、响应快的、现代SVG图表 ![](https://img.shields.io/github/stars/frappe/charts?style=social) ![](https://img.shields.io/github/forks/frappe/charts?style=social)

  - [flot](http://www.flotcharts.org/) [[在线演示](http://www.flotcharts.org/flot/examples/)] - 基于Jquery为工程和科学应用程序派生的JS绘图库 ![](https://img.shields.io/github/stars/flot/flot?style=social) ![](https://img.shields.io/github/forks/flot/flot?style=social)

  - [apexcharts.js](https://apexcharts.com/) [[在线演示](https://apexcharts.com/javascript-chart-demos/)] - 基于SVG的交互式JavaScript图表 ![](https://img.shields.io/github/stars/apexcharts/apexcharts.js?style=social) ![](https://img.shields.io/github/forks/apexcharts/apexcharts.js?style=social)

  - [plotly.js](https://github.com/plotly/plotly.js) [[在线演示](https://plotly.com/javascript/)] - Ploty和Dash的JavaScript版本的开源图表库 ![](https://img.shields.io/github/stars/plotly/plotly.js?style=social) ![](https://img.shields.io/github/forks/plotly/plotly.js?style=social)

  - [easy-pie-chart](https://github.com/rendro/easy-pie-chart) - 一个轻量级插件，为单个值绘制简单带动画的饼图 ![](https://img.shields.io/github/stars/rendro/easy-pie-chart?style=social) ![](https://img.shields.io/github/forks/rendro/easy-pie-chart?style=social)

  - [react-vis](https://github.com/uber/react-vis) [[在线演示](http://uber.github.io/react-vis/examples/showcases/axes)] - React的数据可视化组件 ![](https://img.shields.io/github/stars/uber/react-vis?style=social) ![](https://img.shields.io/github/forks/uber/react-vis?style=social)
  - [vega](https://vega.github.io/vega) [[在线演示](https://vega.github.io/vega/examples/)] - 可视化语法，使用Vega，您可以用JSON格式描述数据可视化，并使用HTML5 Canvas或SVG生成交互式视图 ![](https://img.shields.io/github/stars/vega/vega?style=social) ![](https://img.shields.io/github/forks/vega/vega?style=social)
  - [heatmap.js](https://github.com/pa7/heatmap.js) - 基于HTML5 Canvas的Js热力图 ![](https://img.shields.io/github/stars/pa7/heatmap.js?style=social) ![](https://img.shields.io/github/forks/pa7/heatmap.js?style=social)
  - [zeu](https://github.com/shzlw/zeu) [[在线演示](https://shzlw.github.io/zeu/examples/my-command-center.html)] - 用于构建实时电视仪表板、监控UI和物联网Web界面的JS库 ![](https://img.shields.io/github/stars/shzlw/zeu?style=social) ![](https://img.shields.io/github/forks/shzlw/zeu?style=social)
  - [HQChart](https://github.com/jones2000/HQChart) - HQChart - H5, 微信小程序 沪深/港股/数字货币/期货/美股 K线图(kline),走势图,缩放,拖拽,十字光标,画图工具,截图,筹码图 ![](https://img.shields.io/github/stars/jones2000/HQChart?style=social) ![](https://img.shields.io/github/forks/jones2000/HQChart?style=social)
  - [canvas-gauges](https://github.com/Mikhus/canvas-gauges) [[在线演示](http://canvas-gauges.com/documentation/examples/)] - 使用纯 JavaScript 和 HTML5 画布的高度可配置仪表盘。没有依赖性。由于代码库最少，因此适用于物联网设备 ![](https://img.shields.io/github/stars/Mikhus/canvas-gauges?style=social) ![](https://img.shields.io/github/forks/Mikhus/canvas-gauges?style=social)

### 3D库
  - [three.js](https://github.com/mrdoob/three.js) [[在线演示](https://threejs.org/examples/)] - 创建易于使用、轻量级、跨浏览器的通用3d js库 ![](https://img.shields.io/github/stars/mrdoob/three.js?style=social) ![](https://img.shields.io/github/forks/mrdoob/three.js?style=social)
  - [zdog](https://github.com/metafizzy/zdog) [[在线演示](https://zzz.dog/)] - 基于canvas和SVG设计师友好的伪3D引擎 ![](https://img.shields.io/github/stars/metafizzy/zdog?style=social) ![](https://img.shields.io/github/forks/metafizzy/zdog?style=social)
  - [curtainsjs](https://www.curtainsjs.com/get-started.html) [[在线演示](https://www.curtainsjs.com/get-started.html#basic-setup)] - curtains.js是一个轻量级的WebGL js库，可以将HTML DOM元素转换为交互式纹理平面 ![](https://img.shields.io/github/stars/martinlaxenaire/curtainsjs?style=social) ![](https://img.shields.io/github/forks/martinlaxenaire/curtainsjs?style=social)
  - [obelisk.js](https://github.com/nosir/obelisk.js) - 用HTML5 canvas构建立体图形库 ![](https://img.shields.io/github/stars/nosir/obelisk.js?style=social) ![](https://img.shields.io/github/forks/nosir/obelisk.js?style=social)
  - [seen](http://seenjs.io/) [[在线示例](http://seenjs.io/demo-simple-interactive.html)] - 使用SVG或Canvas渲染3D场景 ![](https://img.shields.io/github/stars/themadcreator/seen?style=social) ![](https://img.shields.io/github/forks/themadcreator/seen?style=social)
  - [Oimo.js](https://github.com/lo-th/Oimo.js) [[在线示例](http://lo-th.github.io/Oimo.js/index.html#basic)] - 轻量级的JS 3D物理引擎 ![](https://img.shields.io/github/stars/lo-th/Oimo.js?style=social) ![](https://img.shields.io/github/forks/lo-th/Oimo.js?style=social)
  - [troika](https://protectwise.github.io/troika/) [[在线示例]()] - 用于交互式 3D 和 2D 可视化的 JavaScript 框架 ![](https://img.shields.io/github/stars/protectwise/troika?style=social) ![](https://img.shields.io/github/forks/protectwise/troika?style=social)
  - [phoria.js](https://github.com/kevinroast/phoria.js) [[在线示例](http://www.kevs3d.co.uk/dev/phoria/index.html)] - 用于在 HTML5 画布 2D 渲染器上进行简单 3D 图形和可视化的 JavaScript 库。它不使用 WebGL。适用于所有 HTML5 浏览器，包括桌面、iOS 和 Android ![](https://img.shields.io/github/stars/kevinroast/phoria.js?style=social) ![](https://img.shields.io/github/forks/kevinroast/phoria.js?style=social)

### 全景图
  - [Panolens.js](https://github.com/pchen66/panolens.js) [[在线演示](https://pchen66.github.io/Panolens/)] - Panolens.js基于Three.JS，主要研究领域是全景、虚拟现实和潜在的增强现实。 ![](https://img.shields.io/github/stars/pchen66/panolens.js?style=social) ![](https://img.shields.io/github/forks/pchen66/panolens.js?style=social)
  - [Pannellum](https://github.com/mpetroff/pannellum) [[在线演示](https://pannellum.org/)] - Pannellum是一个轻量级的、免费的、开源的web全景查看器。 ![](https://img.shields.io/github/stars/mpetroff/pannellum?style=social) ![](https://img.shields.io/github/forks/mpetroff/pannellum?style=social)
  - [Marzipano](https://github.com/google/marzipano) [[在线演示](https://www.marzipano.net/demos/sample-tour/)] 可让您轻松为您的网站创建 360 度媒体播放器。 ![](https://img.shields.io/github/stars/google/marzipano?style=social) ![](https://img.shields.io/github/forks/google/marzipano?style=social)
  - [JS-Cloudimage-360-View](https://github.com/scaleflex/js-cloudimage-360-view) [[在线演示](https://scaleflex.github.io/js-cloudimage-360-view/)] 一个简单的、交互式的资源，可以用来提供您的产品的虚拟游览。 ![](https://img.shields.io/github/stars/scaleflex/js-cloudimage-360-view?style=social) ![](https://img.shields.io/github/forks/scaleflex/js-cloudimage-360-view?style=social)
  - [A-Frame](https://github.com/aframevr/aframe) [[在线演示](https://aframe.io/)] A-Frame 除了帮助您构建 360 度媒体播放器外，它还提供了许多附加功能。其他功能可帮助您增强网站的虚拟现实体验。 ![](https://img.shields.io/github/stars/aframevr/aframe?style=social) ![](https://img.shields.io/github/forks/aframevr/aframe?style=social)
  - [exokit](https://github.com/exokitxr/exokit) [[在线示例](https://exokit.org/)] - 基于JavaScript的原生VR / AR / XR引擎 ![](https://img.shields.io/github/stars/exokitxr/exokit?style=social) ![](https://img.shields.io/github/forks/exokitxr/exokit?style=social)

### 流程图
  - [GOJS](https://gojs.net/latest/index.html) [[在线演示](https://gojs.net/latest/samples/)] - 交互式流程图、组织结构图、设计工具、规划工具、可视化语言的JavaScript图表库![](https://img.shields.io/github/stars/NorthwoodsSoftware/GoJS?style=social) ![](https://img.shields.io/github/forks/NorthwoodsSoftware/GoJS?style=social)
  - [Drawflow](https://github.com/jerosoler/Drawflow) [[在线演示](https://jerosoler.github.io/Drawflow/)] - 仅用4行代码即可创建基于dom和svg的流程图 ![](https://img.shields.io/github/stars/jerosoler/Drawflow?style=social) ![](https://img.shields.io/github/forks/jerosoler/Drawflow?style=social)
  - [Flowy](https://github.com/alyssaxuu/flowy) [[在线演示](https://alyssax.com/x/flowy/)] - 用于创建流程图的最小javascript库 ![](https://img.shields.io/github/stars/alyssaxuu/flowy?style=social) ![](https://img.shields.io/github/forks/alyssaxuu/flowy?style=social)
  - [flowchart.js](https://github.com/adrai/flowchart.js) - 可以运行在浏览器和终端的流程图DSL和SVG流程图 ![](https://img.shields.io/github/stars/adrai/flowchart.js?style=social) ![](https://img.shields.io/github/forks/adrai/flowchart.js?style=social)
  - [mermaid](https://github.com/mermaid-js/mermaid) [[在线演示](https://mermaidjs.github.io/mermaid-live-editor/#/edit/eyJjb2RlIjoiZ3JhcGggVERcbiAgICBBW0hhcmRdIC0tPnxUZXh0fCBCKFJvdW5kKVxuICAgIEIgLS0-IEN7RGVjaXNpb259XG4gICAgQyAtLT58T25lfCBEW1Jlc3VsdCAxXVxuICAgIEMgLS0-fFR3b3wgRVtSZXN1bHQgMl0iLCJtZXJtYWlkIjp7InRoZW1lIjoiZGVmYXVsdCJ9fQ)] - 通过解析类Markdown语法生成图表和流程图等 ![](https://img.shields.io/github/stars/mermaid-js/mermaid?style=social) ![](https://img.shields.io/github/forks/mermaid-js/mermaid?style=social)
  - [wireflow](https://github.com/vanila-io/wireflow) [[在线演示](https://app.wireflow.co/)] - 用户流程图实时协作工具 ![](https://img.shields.io/github/stars/vanila-io/wireflow?style=social) ![](https://img.shields.io/github/forks/vanila-io/wireflow?style=social)
  - [butterfly](https://github.com/alibaba/butterfly) [[在线演示](https://butterfly-dag.gitee.io/butterfly-dag/demo/analysis)] - 基于JavaScript/React/Vue2的流程图组件 ![](https://img.shields.io/github/stars/alibaba/butterfly?style=social) ![](https://img.shields.io/github/forks/alibaba/butterfly?style=social)
  - [X-Flowchart-Vue](https://github.com/OXOYO/X-Flowchart-Vue) [[在线演示](http://oxoyo.co/X-Flowchart-Vue/)] - 基于G6和Vue的可视化图形编辑器 ![](https://img.shields.io/github/stars/OXOYO/X-Flowchart-Vue?style=social) ![](https://img.shields.io/github/forks/OXOYO/X-Flowchart-Vue?style=social)

### 甘特图
  - [gantt](https://github.com/frappe/gantt) [[在线演示](https://frappe.io/gantt)] - 开源的Javascript甘特图。基于SVG ![](https://img.shields.io/github/stars/frappe/gantt?style=social) ![](https://img.shields.io/github/forks/frappe/gantt?style=social)
  - [gantt-schedule-timeline-calendar](https://github.com/neuronetio/gantt-schedule-timeline-calendar) [[在线演示](https://gantt-schedule-timeline-calendar.neuronet.io/examples)] - JS甘特图，项目甘特图，时间线，调度图，甘特时间线，预订时间线，React甘特图，Angular甘特图，Vue甘特图，svelte甘特图 ![](https://img.shields.io/github/stars/neuronetio/gantt-schedule-timeline-calendar?style=social) ![](https://img.shields.io/github/forks/neuronetio/gantt-schedule-timeline-calendar?style=social)
  - [jQueryGantt](https://github.com/robicch/jQueryGantt) [[在线演示](https://gantt.twproject.com/)] - Jquery甘特图编辑器 ![](https://img.shields.io/github/stars/robicch/jQueryGantt?style=social) ![](https://img.shields.io/github/forks/robicch/jQueryGantt?style=social)

### 组织图/脑图
  - [OrgChart](https://github.com/dabeng/OrgChart/blob/master/README.zh-cn.md) [[在线演示](https://dabeng.github.io/OrgChart/)] - 简单直接的组织图插件，任何时候你想要一个树状的图表，都可以使用OrgChart ![](https://img.shields.io/github/stars/dabeng/OrgChart?style=social) ![](https://img.shields.io/github/forks/dabeng/OrgChart?style=social)

### Excel/电子表格
  - [x-spreadsheet](https://hondrytravis.com/x-spreadsheet-doc/) [[在线演示](https://myliang.github.io/x-spreadsheet/)] - 基于webJavaScript(canvas)Excel表格 ![](https://img.shields.io/github/stars/myliang/x-spreadsheet?style=social) ![](https://img.shields.io/github/forks/myliang/x-spreadsheet?style=social)
  - [Luckysheet](https://github.com/mengshukeji/Luckysheet/blob/master/README-zh.md) [[在线演示](https://mengshukeji.github.io/LuckysheetDemo/)] - 一个类似于excel的在线电子表格，功能强大，配置简单，完全开源 ![](https://img.shields.io/github/stars/mengshukeji/Luckysheet?style=social) ![](https://img.shields.io/github/forks/mengshukeji/Luckysheet?style=social)
  - [sheetsee.js](https://github.com/jlord/sheetsee.js) - 可视化谷歌Spreadsheet的数据 ![](https://img.shields.io/github/stars/jlord/sheetsee.js?style=social) ![](https://img.shields.io/github/forks/jlord/sheetsee.js?style=social)
  - [SlickGrid](https://github.com/mleibman/SlickGrid) [[在线演示](http://6pac.github.io/SlickGrid/examples/example4-model.html)] - 极快的JavaScript网格/电子表格 ![](https://img.shields.io/github/stars/mleibman/SlickGrid?style=social) ![](https://img.shields.io/github/forks/mleibman/SlickGrid?style=social)
  - [handsontable](https://github.com/handsontable/handsontable) [[在线演示](https://handsontable.com/demo)] - Js带电子表格的数据网格，可以在React、Angular、Vue中使用 ![](https://img.shields.io/github/stars/handsontable/handsontable?style=social) ![](https://img.shields.io/github/forks/handsontable/handsontable?style=social)
  - [canvas-datagrid](https://github.com/TonyGermaneri/canvas-datagrid) [[在线示例](https://canvas-datagrid.js.org/demo.html)] - 基于Canvas的数据网格web组件。能够在单个画布元素上显示数百万连续的分层行和列，而无需分页或加载 ![](https://img.shields.io/github/stars/TonyGermaneri/canvas-datagrid?style=social) ![](https://img.shields.io/github/forks/TonyGermaneri/canvas-datagrid?style=social)
  - [cheetah-grid](https://github.com/future-architect/cheetah-grid) [[在线示例](https://future-architect.github.io/cheetah-grid/#/)] - 最快的网络开源数据表 ![](https://img.shields.io/github/stars/future-architect/cheetah-grid?style=social) ![](https://img.shields.io/github/forks/future-architect/cheetah-grid?style=social)
  - [Jspreadsheet CE](https://github.com/jspreadsheet/ce) [[在线示例](https://bossanova.uk/jspreadsheet/v4/examples)] - Jspreadsheet是一个轻量级的JS插件，创建基于web的交互式表格和电子表格，可以与其他电子表格软件兼容 ![](https://img.shields.io/github/stars/jspreadsheet/ce?style=social) ![](https://img.shields.io/github/forks/jspreadsheet/ce?style=social)

### 截图/图片生成
  - [html2canvas](https://html2canvas.hertzen.com/) [[在线演示](https://html2canvas.hertzen.com/)] - JS截图插件 ![](https://img.shields.io/github/stars/niklasvh/html2canvas?style=social) ![](https://img.shields.io/github/forks/niklasvh/html2canvas?style=social)
  - [dom-to-image](https://github.com/tsayen/dom-to-image) - 使用HTML5 Canvas从DOM节点生成图像 ![](https://img.shields.io/github/stars/tsayen/dom-to-image?style=social) ![](https://img.shields.io/github/forks/tsayen/dom-to-image?style=social)
  - [html-to-image](https://github.com/bubkoo/html-to-image) - 使用HTML5 Canvas和SVG从DOM节点生成图像。Fork自dom-to-image但是添加一些功能 ![](https://img.shields.io/github/stars/bubkoo/html-to-image?style=social) ![](https://img.shields.io/github/forks/bubkoo/html-to-image?style=social)
  - [canvas2image](https://github.com/hongru/canvas2image) [[在线演示](https://github.com/hongru/canvas2image/blob/master/index.html)] - 用于保存或转换Canvas为图片的工具 ![](https://img.shields.io/github/stars/hongru/canvas2image?style=social) ![](https://img.shields.io/github/forks/hongru/canvas2image?style=social)
  - [mp_canvas_drawer](https://github.com/kuckboy1994/mp_canvas_drawer) [[在线演示](https://github.com/kuckboy1994/mp_canvas_drawer#%E6%BC%94%E7%A4%BA)] - 微信小程序上canvas绘制图片助手，一个json就制作分享朋友圈图片 ![](https://img.shields.io/github/stars/kuckboy1994/mp_canvas_drawer?style=social) ![](https://img.shields.io/github/forks/kuckboy1994/mp_canvas_drawer?style=social)

### 数据处理
  - [html2pdf.js](https://github.com/eKoopmans/html2pdf.js) - 纯JS的客户端HTML生成PDF ![](https://img.shields.io/github/stars/eKoopmans/html2pdf.js?style=social) ![](https://img.shields.io/github/forks/eKoopmans/html2pdf.js?style=social)
  - [rasterizeHTML.js](https://github.com/cburgmer/rasterizeHTML.js) - 将HTML渲染到浏览器的Canvas中 ![](https://img.shields.io/github/stars/cburgmer/rasterizeHTML.js?style=social) ![](https://img.shields.io/github/forks/cburgmer/rasterizeHTML.js?style=social)
  - [JavaScript-Canvas-to-Blob](https://github.com/blueimp/JavaScript-Canvas-to-Blob) - 一个将Canvas元素转换为Blob对象的函数 ![](https://img.shields.io/github/stars/blueimp/JavaScript-Canvas-to-Blob?style=social) ![](https://img.shields.io/github/forks/blueimp/JavaScript-Canvas-to-Blob?style=social)
  - [jsgif](https://github.com/antimatter15/jsgif) - 将HTML5 Canvas保存到GIF和动画。一个AS3GIF Gifplayer到JS的港口 ![](https://img.shields.io/github/stars/antimatter15/jsgif?style=social) ![](https://img.shields.io/github/forks/antimatter15/jsgif?style=social)
  - [whammy](https://github.com/antimatter15/whammy) - 基于Canvas来Hack的实时JS webm编码器 ![](https://img.shields.io/github/stars/antimatter15/whammy?style=social) ![](https://img.shields.io/github/forks/antimatter15/whammy?style=social)

### 图像处理
  - [tui.image-editor](https://github.com/nhn/tui.image-editor) [[在线演示](http://nhn.github.io/tui.image-editor/latest/tutorial-example01-includeUi)] - 基于Canvas功能完整的照片图像编辑器。 ![](https://img.shields.io/github/stars/nhn/tui.image-editor?style=social) ![](https://img.shields.io/github/forks/nhn/tui.image-editor?style=social)
  - [merge-images](https://github.com/lukechilds/merge-images) - 轻松将图像组合在一起，且不会弄脏周围的画布 ![](https://img.shields.io/github/stars/lukechilds/merge-images?style=social) ![](https://img.shields.io/github/forks/lukechilds/merge-images?style=social)
  - [we-cropper](https://we-plugin.github.io/we-cropper/#/) [[在线演示](https://unpkg.com/we-cropper@1.2.0/docs/assets/online.jpg)] - 微信小程序图片裁剪工具 ![](https://img.shields.io/github/stars/we-plugin/we-cropper?style=social) ![](https://img.shields.io/github/forks/we-plugin/we-cropper?style=social)
  - [miniPaint](https://github.com/viliusle/miniPaint) [[在线演示](https://viliusle.github.io/miniPaint/)] - 在线图片编辑器 ![](https://img.shields.io/github/stars/viliusle/miniPaint?style=social) ![](https://img.shields.io/github/forks/viliusle/miniPaint?style=social)
  - [animockup](https://github.com/alyssaxuu/animockup) [[在线演示](https://animockup.com/)] - 在浏览器中创建动画模型，并导出为视频或动画GIF ![](https://img.shields.io/github/stars/alyssaxuu/animockup?style=social) ![](https://img.shields.io/github/forks/alyssaxuu/animockup?style=social)
  - [vintageJS](https://github.com/rendro/vintageJS) - 使用HTML5 Canvas元素为图像添加复古/复古效果 ![](https://img.shields.io/github/stars/rendro/vintageJS?style=social) ![](https://img.shields.io/github/forks/rendro/vintageJS?style=social)
  - [glitch-canvas](https://github.com/snorpey/glitch-canvas) [[在线示例](https://snorpey.github.io/jpg-glitch/)] - 给画布元素添加故障效果 ![](https://img.shields.io/github/stars/snorpey/glitch-canvas?style=social) ![](https://img.shields.io/github/forks/snorpey/glitch-canvas?style=social)

### 画板
  - [jspaint](https://github.com/1j01/jspaint) [[在线演示](https://jspaint.app/#local:5ee9c6aab5992)] - Web版的经典MS Paint翻版 ![](https://img.shields.io/github/stars/1j01/jspaint?style=social) ![](https://img.shields.io/github/forks/1j01/jspaint?style=social)
  - [drawingboard.js](https://github.com/Leimi/drawingboard.js) [[在线演示](http://leimi.github.io/drawingboard.js/)] ![](https://img.shields.io/github/stars/Leimi/drawingboard.js?style=social) ![](https://img.shields.io/github/forks/Leimi/drawingboard.js?style=social)
  - [drawingboard](https://github.com/vipstone/drawingboard) [[在线演示](https://vipstone.github.io/drawingboard/drawingboard/index.html)] - 高级画板—自由绘、直/虚线、箭头、所有几何图形

### 游戏引擎/物理引擎
  - [matter-js](https://brm.io/matter-js/) [[在线演示](https://brm.io/matter-js/demo/#mixed)] - 用于web的2D刚体物理引擎 ![](https://img.shields.io/github/stars/liabru/matter-js?style=social) ![](https://img.shields.io/github/forks/liabru/matter-js?style=social)
  - [Hilo](https://github.com/hiloteam/Hilo/blob/dev/README_ZH.md) [[在线演示](https://hiloteam.github.io/examples/index.html)] - 阿里巴巴集团开发的跨平台HTML5游戏开发解决方案 ![](https://img.shields.io/github/stars/hiloteam/Hilo?style=social) ![](https://img.shields.io/github/forks/hiloteam/Hilo?style=social)
  - [melonJS](https://melonjs.org/) [[在线演示](https://www.melongaming.com/)] - 一个全新的轻量级javascript游戏引擎 ![](https://img.shields.io/github/stars/melonjs/melonJS?style=social) ![](https://img.shields.io/github/forks/melonjs/melonJS?style=social)
  - [Phaser](https://github.com/photonstorm/phaser)  [[在线演示](https://phaser.io/examples)] - Phaser 是一个有趣、免费且快速的 2D 游戏框架，用于为桌面和移动网络浏览器制作 HTML5 游戏，支持 Canvas 和 WebGL 渲染 ![](https://img.shields.io/github/stars/photonstorm/phaser?style=social) ![](https://img.shields.io/github/forks/photonstorm/phaser?style=social)
    - [phaser-examples](https://github.com/photonstorm/phaser-examples) - 包含数百个Phaser HTML5 游戏框架的源代码示例 ![](https://img.shields.io/github/stars/photonstorm/phaser-examples?style=social) ![](https://img.shields.io/github/forks/photonstorm/phaser-examples?style=social)
    - [games](https://github.com/channingbreeze/games) - 一个基于Phaser的小游戏集合 ![](https://img.shields.io/github/stars/channingbreeze/games?style=social) ![](https://img.shields.io/github/forks/channingbreeze/games?style=social)
    - [phaser3-examples](https://github.com/photonstorm/phaser3-examples) - phaser3例子 ![](https://img.shields.io/github/stars/photonstorm/phaser3-examples?style=social) ![](https://img.shields.io/github/forks/photonstorm/phaser3-examples?style=social)
    - [phaser-ce](https://github.com/photonstorm/phaser-ce) - Phaser CE 是一个有趣、免费且快速的2D游戏框架，用于为桌面和移动端Web制作HTML5游戏，支持 Canvas和WebGL渲染 ![](https://img.shields.io/github/stars/photonstorm/phaser-ce?style=social) ![](https://img.shields.io/github/forks/photonstorm/phaser-ce?style=social)
    - [phaser3-project-template](https://github.com/photonstorm/phaser3-project-template) - Phaser3项目模板 ![](https://img.shields.io/github/stars/photonstorm/phaser3-project-template?style=social) ![](https://img.shields.io/github/forks/photonstorm/phaser3-project-template?style=social)
  - [taro](https://github.com/Cloud9c/taro) [[在线示例](https://www.echou.xyz/taro/examples/#Cube)] - 轻量级3D游戏引擎。 ![](https://img.shields.io/github/stars/Cloud9c/taro?style=social) ![](https://img.shields.io/github/forks/Cloud9c/taro?style=social)

### 波纹
  - [wavesurfer.js](https://wavesurfer-js.org/) [[在线演示](https://wavesurfer-js.org/examples/)] - 以Web音频和Canvas的音频波纹 ![](https://img.shields.io/github/stars/katspaugh/wavesurfer.js?style=social) ![](https://img.shields.io/github/forks/katspaugh/wavesurfer.js?style=social)
  - [waveforms](https://github.com/joshwcomeau/waveforms) - 一个互动的、可探索的声波纹描绘特效 ![](https://img.shields.io/github/stars/joshwcomeau/waveforms?style=social) [[在线演示](https://pudding.cool/2018/02/waveforms/)] ![](https://img.shields.io/github/forks/joshwcomeau/waveforms?style=social)
  - [siriwave](https://github.com/kopiro/siriwave) [[在线演示](http://kopiro.github.io/siriwave/)] - JS实现的Apple® Siri 波纹特效 ![](https://img.shields.io/github/stars/kopiro/siriwave?style=social) ![](https://img.shields.io/github/forks/kopiro/siriwave?style=social)
  - [waves](https://github.com/dli/waves) [[在线演示](http://david.li/waves/)] - 模拟海浪效果 ![](https://img.shields.io/github/stars/dli/waves?style=social) ![](https://img.shields.io/github/forks/dli/waves?style=social)
  - [waveform-playlist](https://github.com/naomiaro/waveform-playlist) [[在线演示](http://naomiaro.github.io/waveform-playlist/)] - 具有画布波形预览的多轨网络音频编辑器和播放器。 ![](https://img.shields.io/github/stars/naomiaro/waveform-playlist?style=social) ![](https://img.shields.io/github/forks/naomiaro/waveform-playlist?style=social)
  - [wavedrom](https://github.com/wavedrom/wavedrom) [[在线演示](https://wavedrom.com/editor.html)] - 一个免费的开源在线数字时序图（波形）渲染引擎 ![](https://img.shields.io/github/stars/wavedrom/wavedrom?style=social) ![](https://img.shields.io/github/forks/wavedrom/wavedrom?style=social)

### 粒子/路径动画
  - [Proton](https://projects.jpeer.at/proton/) [[在线演示](http://drawcall.github.io/Proton/#examples)] - Javascript粒子动画库 ![](https://img.shields.io/github/stars/drawcall/Proton?style=social) ![](https://img.shields.io/github/forks/drawcall/Proton?style=social)
  - [three.proton](https://github.com/drawcall/three.proton/) [[在线演示]()] - Three.proton 是一个神奇的 3d 粒子引擎，使用了three.js库和Proton ![](https://img.shields.io/github/stars/drawcall/three.proton?style=social) ![](https://img.shields.io/github/forks/drawcall/three.proton?style=social)
  - [bubbly-bg](https://github.com/tipsy/bubbly-bg) [[在线演示](https://tipsy.github.io/bubbly-bg/)] - 小于 1kB 的漂亮气泡背景(750 字节 gzipped) ![](https://img.shields.io/github/stars/tipsy/bubbly-bg?style=social) ![](https://img.shields.io/github/forks/tipsy/bubbly-bg?style=social)
  - [react-particle-effect-button](https://github.com/transitive-bullshit/react-particle-effect-button) [[在线演示](https://transitive-bullshit.github.io/react-particle-effect-button/)] - 基于React的爆裂粒子效果按钮 ![](https://img.shields.io/github/stars/transitive-bullshit/react-particle-effect-button?style=social) ![](https://img.shields.io/github/forks/transitive-bullshit/react-particle-effect-button?style=social)
  - [pasition](https://github.com/dntzhang/pasition) [[在线演示](https://dntzhang.github.io/pasition/)] - 轻量级 Path 过渡库，可以渲染到任何地方 ![](https://img.shields.io/github/stars/dntzhang/pasition?style=social) ![](https://img.shields.io/github/forks/dntzhang/pasition?style=social)

### 二维码
  - [qrious](https://github.com/neocotic/qrious) [[在线演示](https://github.com/neocotic/qrious#examples)] - 使用Canvas生成二维码的纯JavaScript库 ![](https://img.shields.io/github/stars/neocotic/qrious?style=social) ![](https://img.shields.io/github/forks/neocotic/qrious?style=social)
  - [qrcodejs](https://github.com/davidshimjs/qrcodejs) - 基于JavaScript的跨浏览器二维码生成器 ![](https://img.shields.io/github/stars/davidshimjs/qrcodejs?style=social) ![](https://img.shields.io/github/forks/davidshimjs/qrcodejs?style=social)
  - [node-qrcode](https://github.com/soldair/node-qrcode) - 二维码生成器 ![](https://img.shields.io/github/stars/soldair/node-qrcode?style=social) ![](https://img.shields.io/github/forks/soldair/node-qrcode?style=social)
  - [wifi-card](https://github.com/bndw/wifi-card) [[在线演示](https://wificard.io/)] - 打印您连接的 WiFi 二维码(wificard.io) ![](https://img.shields.io/github/stars/bndw/wifi-card?style=social) ![](https://img.shields.io/github/forks/bndw/wifi-card?style=social)
  - [jsqrcode](https://github.com/LazarSoft/jsqrcode) [[在线演示](https://webqr.com/)] - Javascript 二维码生成器 ![](https://img.shields.io/github/stars/LazarSoft/jsqrcode?style=social) ![](https://img.shields.io/github/forks/LazarSoft/jsqrcode?style=social)
  - [instascan](https://github.com/schmich/instascan) [[在线演示](https://schmich.github.io/instascan/)] - 使用网络摄像头的 HTML5 二维码扫描仪 ![](https://img.shields.io/github/stars/schmich/instascan?style=social) ![](https://img.shields.io/github/forks/schmich/instascan?style=social)
  - [qrcode.react](https://github.com/zpao/qrcode.react) - 用于React的二维码组件 ![](https://img.shields.io/github/stars/zpao/qrcode.react?style=social) ![](https://img.shields.io/github/forks/zpao/qrcode.react?style=social)
  - [qrbtf](https://github.com/ciaochaos/qrbtf) [[在线演示](https://qrbtf.com/)] - 艺术二维码生成器 ![](https://img.shields.io/github/stars/ciaochaos/qrbtf?style=social) ![](https://img.shields.io/github/forks/ciaochaos/qrbtf?style=social)
  - [Awesome-qr.js](https://github.com/SumiMakito/Awesome-qr.js) [[在线演示]()] - 一个用 JavaScript 编写的很棒的二维码生成器 ![](https://img.shields.io/github/stars/SumiMakito/Awesome-qr.js?style=social) ![](https://img.shields.io/github/forks/SumiMakito/Awesome-qr.js?style=social)
  - [jquery-qrcode](https://github.com/jeromeetienne/jquery-qrcode) - JQ二维码独立生成（不依赖于外部服务） ![](https://img.shields.io/github/stars/jeromeetienne/jquery-qrcode?style=social) ![](https://img.shields.io/github/forks/jeromeetienne/jquery-qrcode?style=social)
  - [vue-qrcode-reader](https://github.com/gruhn/vue-qrcode-reader) [[在线演示](https://gruhn.github.io/vue-qrcode-reader/demos/DecodeAll.html)] - 一组用于检测和解码二维码的 Vue.js 组件 ![](https://img.shields.io/github/stars/gruhn/vue-qrcode-reader?style=social) ![](https://img.shields.io/github/forks/gruhn/vue-qrcode-reader?style=social)
  - [weapp-qrcode](https://github.com/yingye/weapp-qrcode) [[在线演示](https://github.com/yingye/weapp-qrcode#demo)] - 在 微信小程序 中，快速生成二维码 ![](https://img.shields.io/github/stars/yingye/weapp-qrcode?style=social) ![](https://img.shields.io/github/forks/yingye/weapp-qrcode?style=social)
  - [qr-image](https://github.com/alexeyten/qr-image) - 另一个二维码生成器 ![](https://img.shields.io/github/stars/alexeyten/qr-image?style=social) ![](https://img.shields.io/github/forks/alexeyten/qr-image?style=social)

### 验证码
  - [jigsaw](https://github.com/yeild/jigsaw) [[在线示例](https://yeild.github.io/jigsaw/demo.html)] - canvas滑动验证码 ![](https://img.shields.io/github/stars/yeild/jigsaw?style=social) ![](https://img.shields.io/github/forks/yeild/jigsaw?style=social)

### 运行时
  - [skia-canvas](https://github.com/samizdatco/skia-canvas) - 关于Canvas的Node.js环境 ![](https://img.shields.io/github/stars/samizdatco/skia-canvas?style=social) ![](https://img.shields.io/github/forks/samizdatco/skia-canvas?style=social)

### 其他
  - [paper.js](http://paperjs.org/) [[在线演示](http://paperjs.org/examples/)] - 矢量图形脚本的瑞士军刀 ![](https://img.shields.io/github/stars/paperjs/paper.js?style=social) ![](https://img.shields.io/github/forks/paperjs/paper.js?style=social)
  - [react-canvas](https://github.com/Flipboard/react-canvas) - 将React组件渲染成Canvas而不是DOM ![](https://img.shields.io/github/stars/Flipboard/react-canvas?style=social) ![](https://img.shields.io/github/forks/Flipboard/react-canvas?style=social)

## 文档/教程
- [HTML5 Canvas MDN教程](https://developer.mozilla.org/zh-CN/docs/Web/API/Canvas_API)
- [Internet Explorer 9 开发人员指南：HTML5 Canvas](https://docs.microsoft.com/en-us/previous-versions/hh410106(v=msdn.10)?redirectedfrom=MSDN#_HTML5_canvas)
- [Draw on the Web](https://airingursb.gitbooks.io/canvas/content/)
- [Computer Graphics And Visualization](https://ng-tech.icu/CGDataVis-Series/#/)
- [HTML5草案标准中的Canvas元素文档](https://html.spec.whatwg.org/multipage/canvas.html#the-canvas-element)
- [HTML5 Canvas 基础教程](https://dev.opera.com/articles/html5-canvas-basics/)
- [HTML5 Canvas 菜鸟教程](https://www.runoob.com/html/html5-canvas.html)
- [HTML5 Canvas W3school教程](https://www.w3school.com.cn/html/html5_canvas.asp)
- [HTML5 Canvas 廖雪峰教程](https://www.liaoxuefeng.com/wiki/1022910821149312/1023022423592576)
- [HTML5 Canvas 慕课网教程](https://www.imooc.com/wiki/html5/canvas.html)
- [CanvasStudy](https://github.com/827652549/CanvasStudy) ![](https://img.shields.io/github/stars/827652549/CanvasStudy?style=social) ![](https://img.shields.io/github/forks/827652549/CanvasStudy?style=social)

## 文章
- [JS之使用Canvas绘图](https://www.jianshu.com/p/802c3bd2df34)
- [一个少女心满满的例子带你入门 Canvas](https://juejin.cn/post/6844903490020442125)
- [为了让她10分钟入门canvas，我熬夜写了3个小项目和这篇文章](https://juejin.cn/post/6986785259966857247)
- [更优雅地基于 canvas 在前端画海报](https://juejin.cn/post/6844903870276206606)
- [【🎨万物皆可动】详解Canvas路径动画](https://juejin.cn/post/6924866572972457992)
- [产品经理：你能不能用div给我画条龙？](https://juejin.cn/post/6963476650356916254)
- [Canvas性能优化](https://juejin.cn/post/6844903682761310216) - 掘金 @清夜
- [为了让你们进阶Canvas，我花7小时写了3个有趣的小游戏！！！](https://juejin.cn/post/6989003710030413838) - 掘金 @Sunshine_Lin
- [十分钟实现灭霸打响指灰飞烟灭的效果](https://juejin.cn/post/6844903840249020429) - 掘金 @wangzy2019

## 效果/案例
- [canvas-confetti](https://github.com/catdad/canvas-confetti) [[在线演示](https://www.kirilv.com/canvas-confetti/)] - 一个撒花/纸屑效果插件 ![](https://img.shields.io/github/stars/catdad/canvas-confetti?style=social) ![](https://img.shields.io/github/forks/catdad/canvas-confetti?style=social)
- [lucky-canvas](https://100px.net/) [[在线演示](https://100px.net/demo/wheel.html)] - 基于 TS + Canvas 开发的【大转盘 / 九宫格】抽奖插件，rainbow 一套源码适配多端框架 JS / Vue / React / Taro / UniApp / 微信小程序等 ![](https://img.shields.io/github/stars/buuing/lucky-canvas?style=social) ![](https://img.shields.io/github/forks/buuing/lucky-canvas?style=social)
- [CanvasInput](https://github.com/goldfire/CanvasInput) [[在线演示](https://goldfirestudios.com/canvasinput-html5-canvas-text-input)] - HTML5 Canvas文本输入框 ![](https://img.shields.io/github/stars/goldfire/CanvasInput?style=social) ![](https://img.shields.io/github/forks/goldfire/CanvasInput?style=social)
- [curvejs](https://github.com/AlloyTeam/curvejs) [[在线演示](https://github.com/AlloyTeam/curvejs#demos)] - 魔幻线条 ![](https://img.shields.io/github/stars/AlloyTeam/curvejs?style=social) ![](https://img.shields.io/github/forks/AlloyTeam/curvejs?style=social)
- [canvas-nest.js](https://github.com/hustcc/canvas-nest.js/blob/master/README-zh.md) - 一个基于 html5 canvas 绘制的网页背景效果。 ![](https://img.shields.io/github/stars/hustcc/canvas-nest.js?style=social) ![](https://img.shields.io/github/forks/hustcc/canvas-nest.js?style=social)
- [canvas-special](https://github.com/bxm0927/) - 超多经典 Canvas 实例，动态离子背景、炫彩小球、贪吃蛇、坦克大战、是男人就下100层、心形文字等 ![](https://img.shields.io/github/stars/bxm0927/canvas-special?style=social) ![](https://img.shields.io/github/forks/bxm0927/canvas-special?style=social)
- [canvas效果集合](https://github.com/sunshine940326/canvas) ![](https://img.shields.io/github/stars/sunshine940326/canvas?style=social) ![](https://img.shields.io/github/forks/sunshine940326/canvas?style=social)
- [shape-shifter](https://github.com/kennethcachia/shape-shifter) [[在线示例](http://www.kennethcachia.com/shape-shifter/)] - 这是一个基于用户输入使用一组粒子来渲染不同形状的画布实验。它支持多种模式:文本，倒计时，时间和图标 ![](https://img.shields.io/github/stars/kennethcachia/shape-shifter?style=social) ![](https://img.shields.io/github/forks/kennethcachia/shape-shifter?style=social)

## 贡献者

感谢以下人员对项目的贡献^V^：

- [zyf214329704](https://github.com/zyf214329704)

## 协议

[MIT](./LICENSE)
