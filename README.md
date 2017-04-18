## 使用方法

- [项目地址](https://github.com/eruerua/feedRead)下载文件后解压缩后打开index.html就可以享用，app.js中默认加入了udacity blog, css tricks, html5 rocks, linear digressions, 我自己加入了一天世界，engadget的rss，自己动手做做吧😊。
- Google Feed Reader API已经停止使用了，app.js使用了udacity 自己类似的服务，但是google.load('feeds', '1'); google.setOnLoadCallback(init);就没有必要了吧。类似服务还有rss2json.com
- 已按要求完成相对应的测试。对于内容改变的测试采用随机rss下比较默认情况下rss的title，是否有更好的比较方法。