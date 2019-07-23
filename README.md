# nrm

## 什么是nrm
nrm 是一个 npm 源管理器，允许你快速地在 npm 源间切换。

## 安装nrm
在命令行执行命令，npm install -g nrm，全局安装nrm。

## nrm命令
### 查看
```
$ nrm ls　　// 查看所有的支持源（有*号的表示当前所使用的源,以下[name]表示源的名称）
```
其中，带*的是当前使用的源，上面的输出表明当前源是官方源。

### 切换
```
$ nrm use [name]　　// 将npm下载源切换成指定的源
```
如果要切换到taobao源，执行命令nrm use taobao。

### 帮助
```
$ nrm help　　// 查看nrm帮助
```

### 跳转到指定源的官网
```
$ nrm home [name]　　// 跳转到指定源的官网
```

### 删除
执行命令```nrm del <registry>```删除对应的源。

### 测试速度
你还可以通过 ```nrm test``` 测试相应源的响应时间。
