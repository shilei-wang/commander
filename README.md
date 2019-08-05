# Commander
提供一个Restful API，通过Post请求发送命令在宿主机上执行，并返回执行结果 

**注意：只用于测试环境，禁止在生产环境服务器部署**

## 安装

```$shell
cd /Users/sherlock/go/src/github.com/irisnet/commander
//外网
dep ensure
go install
```

参数
http://${commanderIP}:8080

x-www-form-urlencoded:
command iriscli keys list
args    1234567890
escapes  --param,--idl-content

## 运行

```$shell
commander
```

## 调用

