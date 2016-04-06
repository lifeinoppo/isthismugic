#关于 isthismusic 模块

##具体原理

* 文本行解析
* 分词工具
* POST 请求音乐API接口判断
* 请求缓存和负载均衡
* 返回结果和 可能的音乐链接

##详细介绍

###关于音乐API

主要是网易音乐的提供的API，具体如下：
	
	
	请求方式 ： GET
	请求地址 ： http://s.music.163.com/search/get/
	URL params : 
		* src : lofter
		* type : 1
		* s : 暖暖 (主要查询词，填入可能歌曲名称，超爱)
		* limit ： 3
		* offset ： 0 

