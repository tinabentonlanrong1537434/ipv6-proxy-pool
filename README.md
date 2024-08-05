# ipv6-proxy-pool

原作者项目地址 [https://github.com/stmtc233/ipv6-proxy-pool](https://github.com/stmtc233/ipv6-proxy-pool)

修改内容:

  -去除了ipv6启动时的显示
  
  -新增时打印进度
  
  -修复某些解析ipv6地址时冒号存在的问题

以下是原Readmee

一个socks服务器 仅支持ipv6 访问时随机选择一个ip作为出口

仅供学习参考

## 说明
用chatgpt写的再加上一些东平西凑的代码所以有些乱

自动删除/添加/获取网卡的ipv6公网地址 访问时按照顺序作为出口

请确保你的网卡有至少一个64前缀长度的地址

__如果使用删除地址将会删除除64位前缀以为的其他ipv6地址__

默认绑定0.0.0.0:1080

## 演示
![ys](https://github.com/stmtc233/ipv6-proxy-pool/blob/e18f0033c9b5c21a41fdec4613f67e8059582896/ys.gif)

每次请求都是不同ip的
