# Flutter 中使用 http 

这是一个示例 Flutter 应用程序，用于演示如何使用`http`包执行网络请求。使用[JSONPlaceholder](https://jsonplaceholder.typicode.com/)提供的演示 API 。

此应用程序中展示的 HTTP 功能如下：

- GET request
- POST request
- PUT request
- DELETE request

它还包括如何使用[Mockito](https://pub.dev/packages/mockito)测试网络请求。

## 套餐

此应用程序中使用的软件包如下：

- [dio](https://pub.dev/packages/dio)
- [json_annotation](https://pub.dev/packages/json_annotation)
- [json_serializable](https://pub.dev/packages/json_serializable)
- [build_runner](https://pub.dev/packages/build_runner)

使用`pubspec.yaml`文件将它们添加到您的项目中

```yaml
dependencies:
  http: ^0.13.3
  json_annotation: ^4.0.1

dev_dependencies:
  json_serializable: ^4.1.3
  build_runner: ^2.0.4
  mockito: ^5.0.10
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



如果大家喜欢的话，可以关注我的公众号”坚果前端“

![img](https://luckly007.oss-cn-beijing.aliyuncs.com/images3B1E633F742DA026057B26D3BA8FEB15.jpg)
