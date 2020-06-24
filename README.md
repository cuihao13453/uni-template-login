# uni-template-login

基于uni-app & uniCloud的前后一体登录模板

![](https://img-cdn-qiniu.dcloud.net.cn/7E6B79E2-B469-4CF3-8F4D-7502E72C4CB8.png?imageView2/0/w/375)
![](https://img-cdn-qiniu.dcloud.net.cn/659AE293-95F8-46E1-AC1F-D62FE3B080DB.png?imageView2/0/w/375)

## 快速体验

手机扫码体验：

![](https://img.cdn.aliyun.dcloud.net.cn/uni-app/uni-template-login-qr.png)

## 本地运行

1. 将项目拖入[HbuilderX](http://www.dcloud.io/hbuilderx.html)
2. 创建服务空间，上传云函数，详情参考[uniCloud快速上手](https://uniapp.dcloud.net.cn/uniCloud/quickstart)
3. 运行到Chrome直接体验
4. 如果运行到小程序，注意在小程序后台配置域名白名单，[详见](https://uniapp.dcloud.net.cn/uniCloud/quickstart?id=%e5%b0%8f%e7%a8%8b%e5%ba%8f%e4%b8%ad%e4%bd%bf%e7%94%a8unicloud%e7%9a%84%e7%99%bd%e5%90%8d%e5%8d%95%e9%85%8d%e7%bd%ae)

## 特点
* 兼容微信小程序和APP
* 服务端基于uniCloud实现
* 使用vuex管理登录状态
* 包含账户密码登录和第三方登录方式（微信、微博、QQ）

## 注意事项
* 页面初始化完毕后马上跳转页面可能会失败，可以尝试延迟执行
