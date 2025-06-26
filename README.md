如果你厌烦了openlist的单调界面，可以试试手动添加随机背景图片，每次打开都有不一样的背景哦。<br>
要得到随机背景，最好的方法就是使用随机图片api，这个网上可以找到很多，但是随机出来的图片质量未必如你所愿，索性干脆用docker自己搭建一个api，使用自己收集的心爱壁纸。<br>
以下就是具体的搭建步骤了<br>
一，这里使用的api搭建方法源于别的大神的项目，<a href="https://github.com/Nei-Xin/random-pic-api" target="_blank">点击跳转大神项目</a>,具体的compose代码在上面文件中自取<br>
二，将准备好的图片放到文件夹portrait和landscape中，前者放竖屏壁纸，后者放横屏的。<br>
三，分别在pc和手机浏览器中访问http://你的ip:1234  看是否能得到横竖正确的壁纸，如果可以，那么api就搭建完成了。<br>
四，打开openlist的管理-设置-全局，将上面文件head.txt中的代码复制到自定义头部中，对openlist的控件进行透明和毛玻璃处理。<br>
五，将body.txt中代码复制到自定义内容中，给界面添加背景。<br>
如果不想自己搭建api，使用网络上的成品api的话，跳过前三步，并将第五步中的api更换即可<br>
这里推荐一个网址，里面有好几条成品api，有需要可以取用<a href="https://api.vvhan.com/" target="_blank">api项目</a><br>
全部流程就结束了，以下是效果图。<br>
<img src="https://fs-im-kefu.7moor-fs1.com/ly/4d2c3f00-7d4c-11e5-af15-41bf63ae4ea0/1750821835707/横屏.png" alt="横屏图片"><br>
<img src="https://fs-im-kefu.7moor-fs1.com/ly/4d2c3f00-7d4c-11e5-af15-41bf63ae4ea0/1750821843380/竖屏.jpg" alt="竖屏图片" width="500">
