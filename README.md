# prevent-href
web clip又称免签名封装，经测试 ios 13.4.1 及以下版本，点击a标签链接会出现跳转到safari浏览器的情况。

解决办法是将a标签默认的浏览器行为阻止，用window.location.href替换。

下载js代码，将<script src="你的目录/prevent-href.js"></script>放入项目所有的html文件的head中。

