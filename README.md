# 本地抽水加密工具使用说明


本工具运行在客户显卡矿机上的工具。支持ETH，ETC，RVN，ERGO四大币种抽水


运行平台windows 10或以上版本。支持GPU矿机与专业矿机接入


相对于服务器端口抽水优点：


（1），抽水操作在本地完成，服务器只起到转发所以不占用服务器资源，2G内存的服务器只要带宽够，可以带N台无限算力的机子，节约服务器开消成本。


（2），工具采用TLS加密传输，更加安全。


（3），工具带有默认的TLS服务器接入，所以你无需再租用服务器。





# 使用自己的中转服，服务器端口操作方法：


## LINUX服务器下操作代码：


curl -s -L https://github.com/we-sk-open/netdata/releases/download/gost/gost


chmod a+x gost


nohup ./gost -L ss+mwss://chacha20:（加密密码）@:入站端口号 > bxdd1 2>&1 &


检察代码（查看gost是否正常运行）


ps -aux | grep "gost"





## 客户端编辑及编译说明



![1](https://user-images.githubusercontent.com/100226405/181734149-72935880-95db-4a9e-a87b-2af7012f5745.JPG)
![2](https://user-images.githubusercontent.com/100226405/181734170-9d2736eb-e5ff-48fa-990c-c158853a5c7a.JPG)
![3](https://user-images.githubusercontent.com/100226405/181734235-eea50d3d-690b-4b2b-a78a-772176b94b0f.JPG)
![4](https://user-images.githubusercontent.com/100226405/181734261-880f2bf9-0ace-452b-9e12-dc90d1ed08bb.JPG)
![5](https://user-images.githubusercontent.com/100226405/181734289-d6b665b2-d50d-4d99-9b30-d08f406e0c5d.JPG)
