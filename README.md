seUIadmin
=========

公司管理框架学习,源自metronic.bootstrap

=================================================================================================================


#js库分析


### 1.jquery

&lt;script src="media/js/jquery-1.10.1.min.js" type="text/javascript"></script>

### 2. migrate  兼容1.9 以前的代码


&lt;script src="media/js/jquery-migrate-1.2.1.min.js" type="text/javascript"></script>

######IMPORTANT!   在 引入bootstrap.min.js 前引入 jquery-ui-1.10.1.custom.min.js 避免 bootstrap tooltip 与 jquery ui tooltip 冲突

### 3.jquery UI js
&lt;script src="media/js/jquery-ui-1.10.1.custom.min.js" type="text/javascript"></script>

### 4.bootstrap.js
&lt;script src="media/js/bootstrap.min.js" type="text/javascript"></script>

### 5.ie 浏览器
&lt;!--[if lt IE 9]>
&lt;!-- IE 支持 canvas -->
### 6. ie浏览器支持canvas 特性  excanvas.js
&lt;script src="media/js/excanvas.min.js"></script>
### 7.Respond.js 是一个快速、轻量的 polyfill，用于为 IE6-8 以及其它不支持 CSS3 Media Queries 的浏览器提供媒体查询的 min-width 和 max-width 特性，实现响应式网页设计（Responsive Web Design）。-->
&lt;script src="media/js/respond.min.js"></script>

<![endif]-->



### 7.滚动条 插件
&lt;script src="media/js/jquery.slimscroll.min.js" type="text/javascript"></script>

### 8.进行 AJAX 操作时模拟同步传输时锁定浏览器操作
&lt;script src="media/js/jquery.blockui.min.js" type="text/javascript"></script>

&lt;script src="media/js/jquery.cookie.min.js" type="text/javascript"></script>

### 9.美化 form 表单元素
<script src="media/js/jquery.uniform.min.js" type="text/javascript"></script>
