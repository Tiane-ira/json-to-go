[<img src="https://mholt.github.io/json-to-go/resources/images/json-to-go.png" alt="JSON-to-Go JSON转化为Go结构体"></a>](https://mholt.github.io/json-to-go)

将JSON转化为Go结构体。 

注意事项：

- 工具有时需要做一些假设, 请再浏览一遍输出的结果。
- 当数组中有多个对象时使用的第一个对象的结构。
- 输出结果有缩进，但是没有进行格式化。请使用`go fmt`进行格式化！
- 支持多个tag生成
- 粘贴时使用不带格式粘贴，避免粘贴了格式导致格式化错误

欢迎贡献代码！发起pull request修复bug或开启issue讨论新的特性和改动。

### 声明

JSON-to-Go由Matt Holt ([mholt6](https://twitter.com/mholt6))开发与维护。

图片中的Gopher卡通形象基于Renée French的设计改编而成。

JSON-to-Go中文版由hmldd ([hmldd](https://github.com/hmldd))翻译。
