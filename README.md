## Code Modules（代码模块）

### Modules List（模块列表）

| 名称      |     说明 |  贡献者 |
| :-------- |:-------- | :--------: | 
| [ParseUrl](./lib/parseUrl)    |  将URL参数转化为JSON对象  |    | 
| [DateFormatter](./lib/dateFormatter)   |   将日期转化为指定格式 | [ZadaWu](https://github.com/ZadaWu)|

### How to contribute（如何贡献代码）

```bash
module_name
    ├── demo #演示目录（非必须）
    │   └── index.html
    ├── lib #模块资源目录（非必须）
    │   └── index.js
    ├── test #测试资源目录（非必须）
    │   └── index.js
    ├── index.js #资源入口文件（必须）
    ├── index.test.js #测试入口文件（必须）
    └── README.md #使用说明（必须）
```