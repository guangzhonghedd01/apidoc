# Swagger-doc
基于swagger-ui和swagger-editor做的在线api管理系统

## 下载
```shell
git clone https://github.com/guangzhonghedd01/apidoc.git
```

## 安装
```shell
npm install
```

## 运行
```shell
npm start
```

### 查看接口文档
* [http://127.0.0.1:8300/doc](http://127.0.0.1:8300/doc)
* [Editor](http://127.0.0.1:8300/editor)

## 配置
配置文件位于根目录下`config.json`
```javascript
{
  "port": 8300,     // 运行端口
  "apiPath": "api"  // api文档所在目录
}
```
swagger 文档丢到/api目录下，支持json yaml文档