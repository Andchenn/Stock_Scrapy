# Stock
### 简介
#### 目标：获得上交所和深交所所有股票的名称和交易信息
#### 输出：保存到文件中
#### 技术路线：Scrapy 爬虫框架

###原理分析
#### (1)首先需要在框架中编写一个爬虫程序 spider,用于链接爬取和页面解析;
#### (2)编写 pipelines,用于处理解析后的股票数据并将这些数据存储到文件中.