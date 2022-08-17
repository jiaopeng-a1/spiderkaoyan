# 考研信息爬取程序
# 考研院校爬虫
# 爬虫爬取院校信息

> 用户安装所需的库后可以直接运行，通过pip install安装库的方法不再赘述

此程序用来收集你想要的研招网专业院校的考研信息，有一点需要注意，此程序对研究方向>30个的院校处理尚未完善，
同一个院校的研究方向最多爬取到30条，不过影响不大，只有极少数院校的研究方向会超过30

**声明：** 此程序也并不是我完全原创，我是根据github上的一个项目进行的修改，具体忘了参考哪位大佬的了

目标网址：https://yz.chsi.com.cn/zsml/queryAction.do

使用方法：
1. 在上述的网址中选择完学科类别必填项，记住此必填项对应的代码
2. 代码默认为全日制，如想爬取非全，需要修改代码中的'xxfs': '1'为'xxfs': '2'
3. 直接在终端运行，而后输入你第一步得到的代码，然后输入保存的文件名，坐等爬取结束即可

说明：此代码对换行、\r、\n等这类特殊符号处理不是很好，爬取结束后需要手动在excel中替换
