# 斗鱼弹幕抓取

方法比较愚，通过分析斗鱼的弹幕的HTML结构，解析数据，然后POST到服务端存储。

启动本地服务，把app/assets/javascripts/danmu.js的代码直接Copy到浏览器控制台，就OK了。

需要注意的有两点：

* 1.斗鱼是https请求，所以需要配置本地的nginx的ssl，然后通过https访问本地。

* 2.关闭rails的防跨站攻击。

可能斗鱼弹幕html结构会变换，得重新解析。

                                                                                      2017-07-31 21:50:11
