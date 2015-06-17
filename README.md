# 汉化swagger-ui

汉化了swagger-ui，修改了部分样式

# 修改文件

* swagger-ui.js，修改了部分js，在首页上，增加了显示api发布时间的tag
* lang/zh-CN.js，在lang文件中，增加了中文语言包，其中由于部分使用英文表达更准确，未更改
* index.html，修改了初始化swagger，为期增加了一个初始化加载完成后的回调
* screen.css，为了显示接口创建时间，修改了部分样式

# 使用方法

1. 直接clone该项目到本地，运行index.html文件，课获得我的demo样式
2. 根据自身实际情况修改demo.json文件，已完成自身api接口文档的书写
3. 如果json文件是在线的，请求改index.html文件中`url = "http://192.168.1.8/api/demo.json";`，将online url地址写在这里。

# 与我交流

第一个自己的github项目，如果对有何指教，欢迎联系
e-mail：helei5200@126.com
blog: http://blog.csdn.net/hel12he
