# Hobot
这个名字取的和机器人差不多，叫Hack Robot

自己无聊写的机器人插件


机器人是用的 https://github.com/pandolia/qqbot
这位大神的机器人，因为略有改动，所以不是让大家装，我自己包含进来了

https://github.com/joepie91/python-whois
这个是我用的whois

因为我也是才开始混gayhub，所以很多规矩不懂，但是我知道贴出来自己在那里抄的源码绝对没毛病



下面说机器人的问题
需要作以下改动才可以用
	-main.py  18:图灵apikey
	          68:掉线自动登录的QQ
	          92:管理员QQ
	          116:关键词黑名单
	-plugin/address.py
	          7:百度地图精确定位api
	          32:百度API商店的key

都在代码里了，，我也不知道该怎么说，，太多了，
自带了一个pluginTemplate.py，这个是插件的模板

另有几个插件因为某些原因不能开源

注意：getsysteminfo不是跨平台的命令，是我写在树莓派上的，大家可以自行改改
