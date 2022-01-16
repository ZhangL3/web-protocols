# HTTP

## 03 浏览器发起 HTTP 请求的场景

* 浏览器发起 HTTP 请求的场景

	![browserUseCase-1](browserUseCase-1.png)

	![browserUseCase-2](browserUseCase-2.png)

* Hypertext Transform Protocol (HTTP)

	a ***stateless*** (无状态协议，连续的两个请求中，后一个请求不能依赖前一个请求的字段或者头部等)

	application-level ***request/resonse*** (基于一个连接，由客户端发起请求，然后服务器才能在这个连接上发起一个响应)

	protocol that uses ***extensible semantics*** (语义是可扩展的，如果服务器只支持 1.0, 但浏览器支持 1.1，两者仍然可以正常通信)

	and ***self-descriptive** (子描述的消息，从请求中就知道这段消息是视频还是音频等，而不需要依赖其他的请求)

	message payloads of flexible interaction with network-based ***hypertext information*** (超文本系统，传输的不止有文档, 还有图片等)


	systems

	(RFC7230 2014.6)