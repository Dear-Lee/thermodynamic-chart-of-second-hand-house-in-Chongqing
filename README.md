# thermodynamic-chart-of-second-hand-house-in-Chongqing
# 重庆二手房房源信息热力图分析

#### 项目介绍
使用Python语言对重庆二手房房源信息进行热力图显示与分析。


2018/4/28 实现进度

1. 使用python爬取房天下重庆地区二手房数据；
2. 将爬取的数据中的房名，地址和报价筛选出来；
3. 调用百度地图根据地名查询经纬度API；
4. 把得到的经纬度lng,lat值和之前筛选得到的数据一并存入csv文件，用于热力图制作时提供数据；
5. 调用百度地图API，在线获取重庆地区地图；
6. 将爬取的数据导入API中，保存为 热力图.html网页文件；
7. 打开热力图.html文件，会在浏览器中以热力图方式显示出重庆地区二手房具体信息；
8. 可根据不同的比例尺查看不同范围大小的热力图情况。
