## jar包启动服务

### maven 打包(跳过测试用例)
```
mvn clean package -Dmaven.test.skip=true
```
首次运行会下载依赖的jar，可能会耗时较长，等待完成