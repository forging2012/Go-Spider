# Go-Spider


> Golang 爬虫上手指南



### 1. 基本思路

- 清晰需要的内容
- 分析网页
- 获取网页信息
- 解析网页信息

### 2. 分析网页

- Chrome 浏览器审查元素，查看网页源代码

### 3. 网页响应值的类型

- json: 一般是调用的API，比较好分析，解析json 数据即可
- xml: 不常见
- html: 常见，使用正则表达式、CSS 选择器、XPATH 获取需要的内容

### 4. 请求的类型

- Get : 常见，直接请求即可
- Post : 需要分析请求的参数，构造请求，向对方服务器端发送请求，再解析响应值

### 5. 请求头部信息

- Uer-Agent 头部信息

### 6. 存储

- 本地: text、json、csv
- 数据库: 关系型（postgres、MySQL）, 非关系型（mongodb）, 搜索引擎（elasticsearch） 

### 7. 图片处理

- 请求
- 存储

### 8. 其他

- 代理: ip 池
- User-Agent: 模拟浏览器
- APP:  APP 数据需要使用抓包工具：Mac(Charles)、Windows(Fiddler)(分析出Api)


### 9. 难点

- 分布式
- 大规模抓取


>  本教程讲述前8节
>  演示使用 Mac, IDE 选择的是 Goland





