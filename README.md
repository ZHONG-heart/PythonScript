__Author__  === """zhong""" <br>
__My profession__ === """Front-end web developer"""

## weiboAutoFollower.py

使用selenium控制浏览器，完成微博的账号的批量自动登录。如果微博页面出现验证码，会使用PIL里面的image把验证码给保存的本地，然后把验证码发送到第三方打码平台，打码平台返回的结果输入到浏览器，实现了验证阿的识别。（可以利用代码搭建微博爬虫cookie池）<br>
我的scrapySpider仓库下面有微博的爬虫代码，可以结合起来使用redis做成一套分布式爬虫系统。（本意是写个自动关注我微博号的脚本）


## AutoMation.py
使用了上面代码生成的cookie进行身份验证。自动给微博发送带有图片的评论，浏览器控制还是由selenium完成，鼠标的操作是使用PyAutoGui模块。<br>
----------禁止用于微博恶意灌水，评论谣言信息，误导用户-----------------
