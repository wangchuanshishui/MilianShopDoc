# 消息通知



> 消息通知插件，主要是邮件部分

#### 邮件模板设置 <a href="#you-jian-mu-ban-she-zhi" id="you-jian-mu-ban-she-zhi"></a>

[![](https://www.fecify.com/doc/cn-1.0/images/smananger\_notice\_1.png)](https://www.fecify.com/doc/cn-1.0/images/smananger\_notice\_1.png)

目前的邮件类型：

* 未完成订单召回：如果用户订单未完成，给用户发送的一封召回邮件，提醒用户支付该订单
* 订单退款： 订单售后退款后，给客户发送的一封订单售后退款信息邮件
* 订单取消： 客户订单取消操作后，给客户发送的一封订单已取消邮件
* 订单发货通知： 订单包裹发货后，给用户发送的已发货邮件
* 订单收货通知：订单包裹收货后，给用户发送的已收货邮件
* 用户contacts邮件： 顾客在contacts页面提交留言信息，给商家网站邮箱发送的一封订单信息邮件，商家邮箱在这里设置：[Fecify 基础设置](https://www.fecify.com/doc/cn-1.0/fecify-merchant-admin-config-base.html)
* 用户订单提交： 客户进行下单并且支付成功后，给客户发送的一封订单信息邮件
* 忘记密码邮件： 客户如果忘记密码，可以通过发送一封邮件到账号邮箱，通过点击邮件里面的连接进行重置密码
* 欢迎新注册会员邮件： 客户使用邮箱注册账号成功后，会给客户发送一封注册成功的邮件

#### 编辑邮件模板 <a href="#bian-ji-you-jian-mu-ban" id="bian-ji-you-jian-mu-ban"></a>

点击某个邮件模板，即可进入邮件模板编辑页面

[![](https://www.fecify.com/doc/cn-1.0/images/smananger\_notice\_2.png)](https://www.fecify.com/doc/cn-1.0/images/smananger\_notice\_2.png)

在底部，您可以填写自己的邮箱地址，进行邮件发送测试（前期：您需要先设置SMTP，并且开启队列服务）

#### 邮件设置 <a href="#you-jian-she-zhi" id="you-jian-she-zhi"></a>

[![](https://www.fecify.com/doc/cn-1.0/images/smananger\_notice\_3.png)](https://www.fecify.com/doc/cn-1.0/images/smananger\_notice\_3.png)

* 邮件开启：模板的开启状态
* 店铺名称：在邮件内容里面显示的店铺名称
* LOGO图片：邮件里面使用的LOGO图片
* logo图片宽度：邮件里面的logo宽度
* 联系邮箱地址：邮件里面显示的联系邮箱地址
* 联系电话号码：邮件里面显示的联系电话号码
* smtp host：
* smtp 账号：
* smtp 账号密码：
* smtp 端口：
* smtp 加密方式：

#### 邮件服务商推荐 <a href="#you-jian-fu-wu-shang-tui-jian" id="you-jian-fu-wu-shang-tui-jian"></a>

* SendGrid： [https://sendgrid.com/](https://sendgrid.com/)
* mailgun： [https://www.mailgun.com/](https://www.mailgun.com/)

#### 邮件服务商推荐 <a href="#you-jian-fu-wu-shang-tui-jian-1" id="you-jian-fu-wu-shang-tui-jian-1"></a>

无法收到邮件？参看：[fecify 邮件无法发送问题排查](https://www.fecify.com/doc/cn-1.0/fecify-shop-qa-email-not-send.html)
