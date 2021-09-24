---
title: Git fatal
date: 2021-09-24 12:06:31
tags:
---

```shell
git config --global http.sslVerify "false"
```

产生原因：一般是这是因为服务器的SSL证书没有经过第三方机构的签署，所以才报错

参考网上解决办法：解除ssl验证后，再次git即可

可以使用如上命令。