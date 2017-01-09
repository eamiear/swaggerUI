# SwaggerUI

### **`demo`: [`http://172.16.8.60:8080/apis/`](http://172.16.8.60:8080/apis/)**

> 说明： `Restfull API`展示页，提供符合格式要求的`json`或`yml`数据即会自动生成`API`页面。数据来源，可以是手动编辑的存放于服务中的或与第三方库集成返回的`json`数据。
> 此处的 `SwaggerUI`的样式做了部分调整 。


### **使用**

 - 下载 `Swagger UI`项目到本地
 - 双击执行`dist/index.html`
 - 浏览器将展示Swagger UI页面，默认渲染`http://172.16.8.60:8080/swagger2/v2/api-docs` 的`API`数据。需要查看demo时请确保`http://172.16.8.60:8080/`已启动 

#### 修改默认`API`
 
```
    window.swaggerUi = new SwaggerUi({
            url: url, // here goes correct url
            …
        });
```

> 可以在上面构造函数中修改默认的`API`

### 自定义
#### 源代码结构

>下载源文件查看代码结构，可以在源代码的基础上定制样式或主题。

#### 构造函数接受的参数
#### `HTTP`方法及`API`
#### `Header`参数
#### 本地化
#### 对自定义源文件进行构建`build`

> 具体使用查看 官方文档：**[`swagger.io docs`](http://swagger.io/docs/)**