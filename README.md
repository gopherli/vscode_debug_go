# vscode_debug_go
vscode_debug

## 本地DEBUG
- 参考：https://gocn.vip/topics/9922
- 第一步：go get -u github.com/go-delve/delve/cmd/dlv
- 第二步：lunch.json文件配置
```
go.delveConfig生成默认配置即可
其他默认即可
```
- 第三步：在入口文件，启动调试
```
Launch  调试文件
Launch Package 调试包
Launch Program 调试程序
```

## 远程DEBUG（error）
- 参考：https://cloud.tencent.com/developer/article/1726411
- vscode下载插件
```
Remote Development
C/C++
```
- 开启远程调试
```
侧边栏点击Remote Explorer
点击加号user@127.0.0.1
右键输入密码建立连接
```