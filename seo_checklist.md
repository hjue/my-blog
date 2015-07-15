## SEO Checklist

### HTML Title 标签

`
￼<head>
<title> InfoQ - 促进软件开发领域知识与创新的传播 </title></head>
`
`
￼<head>
<title> 创建快乐的工作环境 - InfoQ </title></head>
`


* 每个网页的标题唯一
* 重要的关键字尽量靠前
* 50-80字

### HTML Meta Description 标签


`
<head><meta name="description" content="This is an example."></head>`

* 200-300字
* 每一页的描述必须唯一


### HTML Image 标签

`
<img src="img/keyword.jpg" alt="keyword" width="100" height="100">
`

### HTML 链接

`<a href="http://www.stuq.org/about.html">关于我们</a>`

`￼<a href="http://www.xxx.com/xxx" rel="nofollow">点击这里</>`

* 对不可信的内容使用`"nofollow"`,如论坛中用户添加的链接

### Canonical

http://www.stuq.org

http://stuq.org 

http://www.stuq.org/index.html

利用Canonical处理重复的URL

`<link href="https://example.com/" rel="canonical" />`
### URL
* 尽量采用短、可读的关键字作为组成URL的关键字
* 尽可能的使用根域名而非二级域名
### 分页
在head中使用 rel="next" 和 rel="prev" 说明分页的链接
> 第二页 - http://www.stuq.org/article?page=2

`    ￼<link rel="prev" href="http://www.stuq.org/article>
     ￼<link rel="next" href="http://www.stuq.org/article?page=3>`


### 管理员工具

Google 管理员工具：http://www.google.com/webmasters/
Baidu 站长平台 http://zhanzhang.baidu.com/
