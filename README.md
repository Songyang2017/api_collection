# 各大网站api数据收集 
 

#### 金山词霸  
检索列表：[http://m.iciba.com/index.php?c=search&m=getsuggest&nums=5&client=6&uid=0&is_need_mean=1&word='+词语+'&_=1515029307302&callback=jsonp4](http://m.iciba.com/index.php?c=search&m=getsuggest&nums=5&client=6&uid=0&is_need_mean=1&word='+词语+'&_=1515029307302&callback=jsonp4)  
精准查词：[http://www.iciba.com/index.php?a=getWordMean&c=search&list=1%2C3%2C4%2C8%2C9%2C12%2C13%2C15&word='+词语+'&_=1515030111835&callback=jsonp8](http://www.iciba.com/index.php?a=getWordMean&c=search&list=1%2C3%2C4%2C8%2C9%2C12%2C13%2C15&word='+词语+'&_=1515030111835&callback=jsonp8)
#### 微博 
微博搜索联想词接口:'https://m.weibo.cn/searchs/suggest?q='+关键词  
微博评论接口: https://m.weibo.cn/api/comments/show?id='+微博id+'&page='+页数  
例如：https://m.weibo.cn/api/comments/show?id=4221789343235387&page=3  可用来作上拉刷新练习
#### QQ
qq头像: http://q.qlogo.cn/headimg_dl?dst_uin=QQ号&spec=640&img_type=jpg  
qq昵称: http://r.pengyou.com/fcg-bin/cgi_get_portrait.fcg?uins=QQ号&get_nick=1&_=1441677004202

#### 上海交通卡余额查询
查询接口： http://shanghaicity.openservice.kankanews.com/public/traffic/Jtkapi?cardno=卡号  
来源： http://shanghaicity.openservice.kankanews.com/public/traffic/jtkye


### 影签  
淘宝七夕影签： https://market.m.taopiaopiao.com/markets/TaoBaoMovie/qixiyingqian?hsb=yes&s=ap&spm=dianying.ap.10.1&__webview_options__=bizScenario%3DALIPAY_HOME_ROTATION.2710.25873.1028951107671425024 
网易云音乐2017年度音乐榜单： https://music.163.com/nact/report2017  
滴滴2018七夕： https://page.xiaojukeji.com/package/lichengti08151/index.html


### 百度  
天气： http://api.map.baidu.com/telematics/v3/weather?location=上海&output=json&ak=ITI36hwGlm8GkwvqIGHmSHHZO4AqBG0f
