# php_http_proxy
## 概要 
当前一些php的http服务，在获取proxy的信息的时候，都是通过`$_SERVER`变量进行运算和获取， 有些一些不明的真相的用户，不太清楚proxy传递过来的准确信息，因此作者统一返回了RFC中写的标准的proxy信息，方便其他的人的使用，以上， 一个简单的php proxy信息,如果有不足，请多提意见。


