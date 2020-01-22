# Alfred-Workflow_List-Processing
[Mac Alfred Workflow] Columns and rows transposition; List Deduplication; List sorting.

## [Mac Alfred workflow] 列表快速格式化  
## 竖排 & 逗号分隔 互转, 去重, 排序

在做运维的时候 (其实数据分析也会遇到...), 经常需要将一些竖排的列表转成逗号分隔的形式写进 Python 或 SQL 中, 亦或者需要将多段列表合并之后去重, 亦或者将逗号分割的转成竖排的列表. 虽然用 Excel 或者 Sublime 也可以很快的达成目的, 但是每次操作都要点击点击再点击, 还是会觉得操作很不连贯, 没有效率, 莫得灵魂.

于是乎, Bob 做了一个简单的 Alfred workflow...

可以一键达成目的, 不用跳出当前应用, 也不用再在应用间切来切去...效果如下:  
  
![](https://github.com/bobleer/Alfred-Workflow_List-Processing/blob/master/Alfred-Workflow_List-Processing.gif?raw=true)
  
注意! 要使用本workflow请先在您的Mac上安装好Alfred:  
[1. 点击直达 Alfred 下载页面.](https://www.alfredapp.com/)  
[2. 点击直达 Workflow 下载页面.](https://github.com/bobleer/Alfred-Workflow_List-Processing/raw/master/processing.alfredworkflow)  
  
## 连续时间周期生成

工作中经常需要用到连续的时间周期, Excel并不能特别好的生成(每次新建一个表也挺慢的)
于是本着磨刀不误砍柴工的精神, 写了一个脚本来自动生成.
生成的周期是格式如下, 如有其它需求自行修改代码吧~

![](https://github.com/bobleer/Alfred-Workflow_List-Processing/blob/master/DSgenerator.gif?raw=true)

支持:  
月周期(6位)  
e.g. 201912,202001  
天周期(8位)  
e.g. 20191231,20200101  
小时周期(10位)  
e.g. 2019123122,2019123123,2020010100,2020010101  
分钟周期(12位)  
e.g. 201912312340,201912312350,202001010000,202001010010  
  
注意! 要使用本workflow请先在您的Mac上安装好Alfred:  
[1. 点击直达 Alfred 下载页面.](https://www.alfredapp.com/)  
[2. 点击直达 Workflow 下载页面.](https://github.com/bobleer/Alfred-Workflow_List-Processing/raw/master/processing.alfredworkflow)  
## 多表格多主键多外键自动合并
[参见bobleer/Multi_Tables_Join项目](https://github.com/bobleer/Multi_Tables_Join)
![](https://github.com/bobleer/Multi_Tables_Join/raw/master/Multi_Tables_Join_demo.jpg?raw=true)
