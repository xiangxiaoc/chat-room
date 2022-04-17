# 聊天室

## 构建
构建服务端
```shell
go build -o ./bin/chat-server ./server/main.go
```
构建客户端
```shell
go build -o ./bin/chat ./chat/main.go
```

## 运行服务端
```shell
./bin/chat-server
```
## 客户端命令

```shell
$ chat --help
使用 chat 命令即刻开始聊天吧

Usage:
  chat [command]

Available Commands:
  completion  Generate the autocompletion script for the specified shell
  help        Help about any command
  history     查看历史
  list        查询在线用户
  login       登录
  register    注册
  subscribe   收取聊天信息
  with        和指定用户聊天

Flags:
  -h, --help     help for chat
  -t, --toggle   Help message for toggle

Use "chat [command] --help" for more information about a command.

```