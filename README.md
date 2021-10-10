# JDC-Monitor-Easy
简单的京东云无线宝监工
本代码仅供个人爱好使用，不要商用（应该也没人屑于商用），商用者后果自负。


一、关于京东云无线宝监工的思考

1、首先我反对公有云模式的监工，毕竟大家要把key给到第三方，不安全。

2、其次个人觉得私有云模式的监工，大家还是有点需求的，我有个5台无线宝，也想看看每天的收入和流量的关系，有没很好的压榨运营商带宽，是否可以再挂一次无线宝？反正就是想获得更高的投资回报；也想看看负载怎么样，有没什么问题等等。何况有几百几千台的大户，所以我撸起袖子就干了。

3、每天起来，就喜欢看到收钱的数字，开启快乐的一天。

二、监工目标如下：

1、跑在树莓派里，最小消耗资源。运行环境 Raspberry PI 4,Debian 10 buster

2、简单，贼简单，只拉取只读信息，不做任何写操作。

3、监控对象：mac地址；监控指标：CPU使用率、内存使用率、上行速度、下行速度、插件名及已缓存容量、昨日积分收入、历史总积分。写到这里，我怎么发现用splunk做挺好。。。就是消耗点CPU

三、打法
1、用脚本从京东云无线宝的API拉取数据
2、

四、安装操作步骤


五、TODO
1、移动端也能看？
