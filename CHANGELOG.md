#### 版本更新说明

v1.0.0

1.重构JS桥代码以及引入BridgeTiny对象管理；    
2.支持X5内核的简单使用；   
3.简化项目集成难度；

v1.0.1

1.修改JS注入方式,弃用assets文件读取,直接以字符串引入；   
2.修复1.0.0版本中WebViewJavascriptBridge.js以js脚本引入路径错误不生效问题，   
  修改为直接使用webview.loadurl(javascript:str)方式插入H5中；




