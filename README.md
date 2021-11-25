# Flutter 中使用 dio

![](screenshots/dio_networking_cover.png)

这是一个示例 Flutter 应用程序，用于演示如何使用dio包执行网络请求。
使用[REQ | RES](https://reqres.in/)提供的演示 API 。


此应用程序中展示的 HTTP 功能如下：

* GET request
* POST request
* PUT request
* DELETE request
* Base options
* Uploading files
* Interceptors

## 演示

| Request Type | Demo |
| --- | --- |
| **GET** | ![](screenshots/dio_get.gif) |
| **POST** | ![](screenshots/dio_post.gif) |
| **PUT** | ![](screenshots/dio_put.gif) |
| **DELETE** | ![](screenshots/dio_delete.gif) |

## 软件包

此应用程序中使用的软件包如下：

* [dio](https://pub.dev/packages/dio)
* [json_annotation](https://pub.dev/packages/json_annotation)
* [json_serializable](https://pub.dev/packages/json_serializable)
* [build_runner](https://pub.dev/packages/build_runner)

使用pubspec.yaml文件将它们添加到您的项目中

```yaml
dependencies:
  dio: ^4.0.0
  json_annotation: ^4.0.1

dev_dependencies:
  json_serializable: ^4.1.3
  build_runner: ^2.0.4
```

## License

Copyright (c) 2021 Souvik Biswas

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
大家喜欢的话，可以关注我的公众号”坚果前端“

![img](https://camo.githubusercontent.com/1f0c0e25c1c0dbc15916ebbb35e7eac13dfe37874cf6a6b7eadb088cf8148def/68747470733a2f2f6c75636b6c793030372e6f73732d636e2d6265696a696e672e616c6979756e63732e636f6d2f696d6167657333423145363333463734324441303236303537423236443342413846454231352e6a7067)