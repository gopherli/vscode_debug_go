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
- 第三步：启动调试
```
1.侧边栏选择Run and Debug->顶层下拉选择Lauch
2.打点配合F5命令即可断点调试
```

## 远程DEBUG