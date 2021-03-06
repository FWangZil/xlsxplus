# xlsxPlus：一个能同时处理xls与xlsx的go扩展库

## 文档

See the [English Document](https://github.com/FWangZil/xlsxplus/blob/master/README_zh.md) for document in English.

## 项目介绍

工作中时常会碰到一些需要处理Excel文件的业务，比如常见的数据导入导出，虽然现在常见的Excel文件基本都是xlsx格式了，但是因为一些历史遗留问题或者对接的客户方使用的office/wps版本的原因，偶尔也会遇到需要处理xls的情况。但是目前貌似没有一个可以同时处理这两种格式文件的go的库。

我自己在之前的开发过程中遇到这种情况时经常需要同时写两套业务逻辑分别调用不同的Excel处理库来适配不同的文件格式，这自然就给项目后期的维护引入了过高的复杂度，故而我想能不能基于前辈们的成果试着在简单的一些逻辑下兼容新旧两种格式，于是有了该项目的尝试。

### 项目开始于

* [tealeg/xlsx](https://github.com/tealeg/xlsx) v3.2.0
* [extrame/xls](https://github.com/extrame/xls) 6fdb969 8fb5669

## 版本维护历史

## 功能点

- [ ] 完成两种格式的文件内容读取
- [ ] 完成两种格式的文件内容修改

## 注意

本项目不保证生产环境的稳定性，仅仅是一次尝试，本菜鸡能力有限，各位路过的大佬请谨慎引入。
