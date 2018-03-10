# smallspider 
几十行代码实现 一个简短的爬虫小程序 

### 共6个文件
```
DefaultDocumentListener.java
DocumentListener.java
LinkCollection.java
Logger.java
PageCrawer.java
PageCrawRunnable.java
```



##  启动方式 
1: 只带一个参数启动 
    java -jar  spider.jar  www.baidu.com
    
2:多个参数启动
java -jar  spider.jar   www.baidu.com  1000  D:/urls.md


### 启动参数说明
1. wwww.baidu.com  要爬取的网站,如上：
2. 1000            开启的线程数(可选，默认200)
3. D:/url.text     内容存放路径(默认不存储) 



#### [可以直接下载jar包体验](https://github.com/enohe/smallspider/blob/master/spider.jar)

##### 运行示例图:
![demo](https://github.com/enohe/smallspider/blob/master/20180310192521.png)
