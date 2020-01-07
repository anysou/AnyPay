# AnyPay

收款精灵：一篮子个人收款自动服务系统。

实现微信、支付宝、云闪付、QQ、收钱吧、工银商户之家、银行短信、等一系列个人收款管理服务。

## APP (Android Studio 4.0)

**技术要点**

1、TLog 日志工具 记录 收款信息。
2、LiveEventBus 消息总线框架。
3、

**流程**

1、AndroidManifest.xml -> application -> android:name=".MainApplication"
  
  设置全局变量、全局方法、启动监测服务、初始化TLog(日志工具)、设置LiveEventBus(消息总线框架)
  
2、Android 9.0 http 网络请求的问题解决： AndroidManifest.xml -> application -> android:networkSecurityConfig="@xml/network_security_config"

3、
