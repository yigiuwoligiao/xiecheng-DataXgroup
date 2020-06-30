# xiecheng-DataXgroup
这是上海观相数据(DataXgroup)的初步测试题,要求24小时做完,没来得及做完并且自然语言处理也不会,仅有爬虫部分,写的不是很好,做个记录,另外我是个菜鸡,大佬们不喜忽喷,欢迎指导

要求:
目标网站是携程单个酒店的评论和酒店回复,存到txt后用自然语言处理做旅客评论的情感分析（正面还是负面）


  ![图1](https://github.com/yigiuwoligiao/xiecheng-DataXgroup/blob/master/img/1.png)
  ![图2](https://github.com/yigiuwoligiao/xiecheng-DataXgroup/blob/master/img/2.png)
  ![图3](https://github.com/yigiuwoligiao/xiecheng-DataXgroup/blob/master/img/3.png)


反正电脑版的不会弄,涉及参数破解,eleven那个我太菜了搞不出来,看了一下别人之前有试过模拟手机h5页面打开也能拿到数据,也算是退而求其次吧
1.post请求拿到的数据是json的,用久了get可能不是很敏感,写了xpath才发现不对
2.酒店回复那个键'feedbackList',如果酒店不回复的话,键都不存在的,试过在if后面判断,发现都不进if,所以用这样的方式解决,也算有效果吧



  ![图4](https://github.com/yigiuwoligiao/xiecheng-DataXgroup/blob/master/img/%E9%85%92%E5%BA%97%E4%B8%8D%E5%9B%9E%E5%A4%8D.png)




其他的就没啥了相对比较简单
