# go-rocketmq-example

## Client
将`http://localhost:9876`替换为Rocketmq服务
```go
endPoint = []string{"http://localhost:9876"}
```

## Server
安装请移步到本人其它仓库的子目录:
https://github.com/Mandala-lab/docker-deploy/tree/main/rocketmq

`compose`目录为docker compose命令, 默认情况下, 只需要进入到该目录, 执行下条命令即可启动一个单副本RocketMQ:
```bash
docker compose up -d
```

`shell`目录为使用`docker run`来执行,对于低版本的Docker用帮助
