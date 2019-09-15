## Getting started

### Markdown语言

#### Windows编辑器

1. Typora
2. Visual Studio Code

#### 语法规则

1. **标题（#后加空格）**

   #表示一级标题

   ######表示六级标题

2. **列表**

   无序列表（*,+,-效果一样加空格）

   * 列表1

     * 子列表1

   有序列表（数字加点号加空格）

   1. 音乐（一级）

      1.童话（二级）

      2.在路上

3. **文字格式**

   * **粗体**

   ```
   语法：**文本** 或 __文本__
   ```

   + *斜体*

   ```
   语法：*文本*  或 _文本_
   ```

   + **_粗体加斜体_**

   ```
   语法：**_文本_**
   ```

   + ~~删除线~~

   ```
   语法：~~文本~~
   ```

4. **链接**

   - 直接设置

     [百度](http://www.baidu.com "百度一下，你就知道")

     ```
     语法：[替代文本](http://www.baidu.com "百度一下，你就知道")
     ```

   - 间接设置

     [百度][1]

     [1]:http://www.baidu.com "百度一下，你就知道"

     ```
     语法：[替代文本][1]
     [1]:http://www.baidu.com
     ```

   - 隐式设置

     [百度][]

     [百度]:http://www.baidu.com

     ```
     语法：[替代文本][]
     [ ]:http://www.baidu.com
     ```

5. **图片**（同上，仅仅是在替代文本前加 ！）

   - 直接设置

     ![Docker](https://github.com/zw-qiu/Bioinformatics-Study-Course-Note/blob/master/docker.PNG)

   - 间接设置

     ![Github][2]

     [2]: https://github.com/zw-qiu/Bioinformatics-Study-Course-Note/blob/master/github%20desktop.PNG

6. **引用**

   ```
   >一级引用
   >>二级引用
   >>>三级引用
   ```

7. **水平分割线**

   ```
   ___
   ***
   ```

8. **表格**

   ```
   |项目      | 价格|数量|
   |:--------|----:|:-:|(左对齐|右对齐|居中)
   |computer |1600Y| 5 |
   |phone    |  12Y| 12 |
   ```

9. **文档目录**

   在想放入目录结构的位置写[TOC]即可

10. **转义字符**

```
\加\   *    `  -  + #等等
```

