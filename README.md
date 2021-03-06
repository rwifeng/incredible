# Incredible

Incredible是为网络写作者提供的一款小而美，操作简单的图片云存储与云处理工具。Incredible基于[七牛云存储](http://qiniu.com)。

你可以通过Incredible快速地将本地图片上传到七牛云存储上，并进行云处理。





### 下载
- [Mac客户端 v0.3.2](http://ftp.leapoahead.com/download/incredible/incredible.0.3.2.mac.zip)


### 使用
##### 准备
使用Incredible前，你需要到[七牛云存储](http://qiniu.com)申请账号并登陆。登陆后，创建一个新的空间。请注意该空间必须为公开空间。

![创建新空间](http://cloudfront-tjwudi.qiniudn.com/5d4faf71cfe1021e75ca7636b4a99c69c6819d1e-b0df9d6fac6a47f4370e2b37ddec70f5e5cbc10c.png?imageView2/2/h/500/w/0/q/50)

这里假设我们新建空间名为`cloudfront-tjwudi`。接下来在账号设置-密钥中，复制并保存你的AK和SK，供后续步骤使用。

![查看AK和SK](http://cloudfront-tjwudi.qiniudn.com/7e64556fcd1c8103a96a92b5a5051a40d352bfae-e03218877fe38b2b5769d8c34290db64af72a1f6.png?imageView2/2/h/500/w/0/q/50)

同时你还应该配置对应的七牛域名（在七牛空间设置-域名设置中）


##### 配置
启动Incredible，在设置-七牛设置中，设置你的Bucket Name（刚才创建的空间名）。并用**Ctrl+V**复制你的AK和SK。（请Mac客户端用户注意，必须使用Ctrl键。我会在后续版本中改进这一问题）

![配置七牛](http://7qn8cx.com1.z0.glb.clouddn.com/be5d98b09ae291a0916ffe8ce32a72efc8073333-0e085936b2ea779e4755d6a2ed540bb5ac2554b2.png?imageView2/2/h/0/w/0/q/40)

##### 上传并获取图片地址
将要上传的图片选中（可以为多张），并拖拽到Incredible**上传界面**。点击“上传”即可上传所有图片。

![上传图片](http://cloudfront-tjwudi.qiniudn.com/fc708eb5c8dddd3eb12a8ac21cb26054241990f9-5c20dcbcfbab07ab6c2df7e27444d5ac2afca569.png?imageView2/2/h/500/w/0/q/50)

进入**管理界面**，右击图片将图片地址复制到剪贴板中。

![复制图片地址](http://cloudfront-tjwudi.qiniudn.com/dfd7c88f9cc9e7f3096b50f01f0b56847dca8517-278cadb5c5a600fd354bbb4a32acf34407bf98f0.png?imageView2/2/h/500/w/0/q/50)

##### 预设
如果想要对图片进行处理，可以在设置界面-预设管理添加预设。**预设对已经上传过的图片也有效，因为图片处理是在云端完成的**。

![预设管理](http://cloudfront-tjwudi.qiniudn.com/ad8abb6b39fcf48d95e7c1941a760b4f98061cc6-bd473197c461193ea9b6d317f4c236910d065887.png?imageView2/2/h/500/w/0/q/50)

参数设置方法请查看[七牛图片处理文档](http://developer.qiniu.com/docs/v6/api/reference/fop/image/imageview2.html)。

添加预设后，在**管理界面**右击图片，点击预设名，就可以获得该预设下对应的图片地址到剪贴板了。：）



##### 测试和文档
暂时不具备代码测试用例和文档，在接下来的版本中会立刻跟上。




##### 贡献
欢迎你为Incredible贡献代码！Incredible基于Node webkit，因此你需要下载[Node Webkit](https://github.com/rogerwang/node-webkit)。你可以通过下面任何方式给Incredible贡献建议或者代码

- Fork
- 发送Pull Request
- 创建issue
- [发送email](mailto:webmaster@leapoahead.com)



##### 版本记录

- 0.3.2 (Jan 1st 2015) 对应七牛官方域名策略变更
- 0.3.1 (Nov 15th 2014) 第一个正式发布版本



### 开源许可证
MIT