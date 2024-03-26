## 简介

这是我封装的一些aardio库，目前的库列表：

- goquery: 封装goquery，用于css选择器解析html
- htmlquery: 封装htmlquery，用于xpath解析html
- jsonquery: 封装jsonquery，用于解析json
- sunny: sunny.dll的封装，用于监听本地数据包，类似mitmproxy
- tlsClient: tls-client封装，用于http请求。支持http2.0和tls指纹
- xmlquery: 封装xmlquery，用于解析xml
- redis: redis客户端

## 使用方法

下载`extlibs.aardio`文件放到`aardio\tools`这个目录下，该目录下有个`1.ext.aardio`这是官方扩展库，后面就和官方扩展库一样的安装使用了

#### 目录结构

- dist: 打包后的文件，用于远程下载安装
- lib: 库代码
- res: 库的使用案例

