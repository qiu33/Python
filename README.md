## Python期末项目总结

### 项目合作人：17级唐颖欣 18级邱珊珊 18级卢继志

本项目主要是探讨网红背后的数据经济与热门移动端APP的发展是如何构建精准节点，实现庞大的经济效益

#### 项目分工
* 由17级唐颖欣负责提供数据和对数据故事具有表现力的地图等，包含两份数据，两份图表，还提供了ipynb文档
* 由18级卢继志和我共同部署一个网页，通过掌握到的python知识，比如*条件判断、推导式、循环等，实现了具有交互功能的html页面，比如下拉框和数据表格交互，下拉框和条形图交互，共同编写css、html等*，我也适当的从www.jq22.com引进了一些插件，对网页实现除数据外的交互效果，对网页进行美化，最后将*网页部署到Pythonanywhere*

* [Pythonanywhere URL](http://qiu33.pythonanywhere.com)：http://qiu33.pythonanywhere.com
* [Github URL](https://github.com/qiu33/Python)：https://github.com/qiu33/Python


分别有3个url
1.	[首页](http://qiu33.pythonanywhere.com)：该页面主要展示国内前100名mcn的分布情况
2.	[各省数据](http://qiu33.pythonanywhere.com/appadd?cici=手机淘宝)：该页面更加详细展示各省mcn机构数量
3.	[app发展](http://qiu33.pythonanywhere.com/select?city=北京)：该页面展示近两年9个常用app的增长情况


### [首页]( http://qiu33.pythonanywhere.com)

* 首页地图由17级唐颖欣提供，表格的呈现由我和卢继志负责，通过地图和表格可以看到国内前100名mcn的分布情况，由此可以看到mcn机构偏爱在江浙沪选址，紧靠传媒行业的发展和物流交通行业；
* 其中在左侧我引入了来自jq22网站的插件，项目人分别对应我们三个，并且链接到相应的github主页，同时，当页面往下滑动查看表格的时候，可以按左侧的按钮回到顶部，既方便又节约时间；
* 首页上面的三个按钮可以实现页面跳转，跳到相对应的页面

### [各省数据]( http://qiu33.pythonanywhere.com/select?city=北京)

* 在各省数据页面放置了不同于首页的地图和表格，地图颜色的深浅代表mcn机构数量的多少，颜色越深，数量越多，更加直观反映mcn机构集中分布在那个地区；
* 在这个页面除了按钮跳转页面以外，还有下拉框可以互动，实现数据过滤，选哪个地区表格就呈现哪个地区的mcn机构数据，、由此可以看到mcn机构在北京市分布最密集；
* 同时此页面右侧的悬浮球也引自jq22网，按住可以拖动，鼠标放上去会显示我们三个项目合作人的名字，同样也链接到个人的github主页，app对比页面也同样引入了此插件

### [app发展]( http://qiu33.pythonanywhere.com/appadd?cici=手机淘宝)

* 在这个页面用了条形图来对比2018年和2019年十一月份月份9个常用APP的增幅情况，除了全部合并在一起的条形图，我们还制作了单一对比的条形图，和下拉框实现交互，选择哪个app就呈现这个app 2018年和2019年的数据对比，更方便查看想要了解的app
* 通过这个页面的数据可以知道，在综合九个数据来看，除了天猫和苏宁易购的年度增长率在减低之外，其余七个软件在这两年增幅趋势都呈上升状态，而以抖音短视频为首的短视频平台加入更多电商直播带货功能，短视频类app如雨后春笋班茁壮成长，也带动了很多主播带货的现状，这在一定程度上体现出了网红背后带货的力量，与MCN机构构成了密不可分的关系。

