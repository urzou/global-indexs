#### stock-index-dashboard

全球主要股票市场指数看板，其中包含纳斯达克，道琼斯，标普500，沪深，日经，恒生，富时，德国DAX等指数、指数涨跌幅。利用github action工作流，执行爬虫脚本fetch.py，每隔一小时从数据源抓取一次数据放入data.json文件，最后使用html+js展示出来，

##### 项目结构：

```cmd
├───.github #workflow配置
│   └───workflows
│   	└───update.yml
├───docs 
│   └───data.json #抓取的数据
│   └───index.html #展示页面
└───fetch.py #爬取脚本
```

