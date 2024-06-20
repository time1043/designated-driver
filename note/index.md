# designated-driver

- Reference - course

  [MSB designated driver (bilibili)](https://www.bilibili.com/video/BV1ii421o7Fr), 

- Reference - dev

  [Kratos org](https://go-kratos.dev/), [Kratos (github)](https://github.com/go-kratos/kratos), 

  



## 背景介绍

- Go微服务框架

  [Kratos (18k)](https://github.com/go-kratos/kratos): 2019, bilibili

  [go-kit (23k)](https://github.com/go-kit/kit): 2015

  [go-zero (20k)](https://github.com/zeromicro/go-zero): 2020, zeromicro (CNCF)

  [TarsGo (3k)](https://github.com/TarsCloud/TarsGo): 2018, TenXun

  [Jupiter (3k)](https://github.com/douyu/jupiter): 2020, douyu

  [Istio (31k)](https://github.com/istio/istio): 2017, Google + IBM + Lyft

  [CloudWeGo-Kitex (5k)](https://github.com/cloudwego/kitex): 2020, ByteDance

  [Go-micro / m3o (19k)](https://github.com/asim/go-micro): 2015, Micro Services + Inc

  [Dubbo-go (4k)](https://github.com/apache/dubbo-go): 2019, alibaba + Apache

- 技术选型

  `Kratos` (古希腊神话的战神 由凡人成为战神并展开弑神屠杀)

  Bilinili 开源的 轻量级 Go微服务框架

  提供了完整的工具箱





## 初始化环境

- 安装依赖

  [go1.19](https://go.dev/dl/), [protoc (protocol complier 编辑器)](https://github.com/protocolbuffers/protobuf), protoc-gen-go (protoc插件 用于生成go代码), kratos (框架配套脚手架)

- go1.19

  ```bash
  # go gopath goproxy
  go version
  go env
  
  
  go env -w GOPATH=D:\devenv\go\
  go env -w GOPROXY=https://goproxy.cn,direct
  
  # bin 添加到PATH
  $ENV:PATH  # win ps
  
  ```
  
- protoc-25.0-win64 (解压 bin添加到PATH)

  ```bash
  protoc --version
  
  ```

- protoc-gen-go

  ```bash
  go install google.golang.org/protobuf/cmd/protoc-gen-go@latest
  go install google.golang.org/grpc/cmd/protoc-gen-go-grpc@latest
  
  protoc-gen-go --version
  protoc-gen-go-grpc --version
  
  ```

- kratos

  ```bash
  go install github.com/go-kratos/kratos/cmd/kratos/v2@latest
  kratos -v
  
  ```

  



















































