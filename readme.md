# 使用说明

* <font size=4>cookie: 知苗易约小程序cookie 获取预约人信息</font>

* <font size=4>医院id: 需要预约医院的id</font>

* <font size=4>tags: 由于现在疫苗的id是动态生成的 这里做了个标签快速定位到含有标签的疫苗 用 "," 分隔  例如: 九价,16-26</font>

* <font size=4>查询延时和下单延时 暂时固定了为 1ms</font>



# cookie和医院id获取方式：


* 抓包工具fiddler下载地址: [fiddler抓包工具](https://www.telerik.com/download/fiddler-everywhere)
* cookie获取方式![img_5.png](images/img_5.png)
* 医院id获取方式 ![img_6.png](images/img_6.png)
    





### 示例图
![yy.jpg](images/yy.jpg)

![img_4.png](images/img_4.png)




# 注意事项
* **<font size=4>一般来说使用工具抢苗需要提前打开 因为要刷苗 防止错过</font>**
* **<font size=4>由于我没有9价的号源地测试 所以此工具并非100%能帮助大家抢成功(在这里我希望大家都可以成功 ![img_7.png](images/img_7.png))</font>**
* **<font size=4>以上cookie的有效时长为1小时 另外我试过预约成功后的cookie会再次使用提交会201 如果在订单提交返回201的情况下 试试换一下cookie</font>**
* **<font size=4>目前今天2022-08-12 我测试过还能正常预约</font>**
* **<font size=4>最后祝愿女孩子都能抢到 男孩子都能帮女朋友抢到</font>**
* **<font size=4>有需要学习的可以issue来一下 创作不易希望大家喜欢(喜欢就动动手吧)</font>**
* **<font size=4>最最最最最重要的事情  请勿将此工具用于非法用途 不要乱来!!!!!!!!!!!! 谢谢大家 这里我就不放源码了</font>**


# 鸣谢

* <font size=4>这里要感谢一下[liuzhijie443](https://github.com/liuzhijie443/ZhiMiao_JiuJia) 大佬提供的思路