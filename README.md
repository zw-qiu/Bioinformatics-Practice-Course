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

     ![清华园](https://image.baidu.com/search/detail?ct=503316480&z=0&ipn=d&word=%E6%B8%85%E5%8D%8E%E5%9B%AD&step_word=&hs=2&pn=1&spn=0&di=22000&pi=0&rn=1&tn=baiduimagedetail&is=0%2C0&istype=0&ie=utf-8&oe=utf-8&in=&cl=2&lm=-1&st=undefined&cs=2388525319%2C402051134&os=1418120982%2C1179407277&simid=4062227275%2C774795877&adpicid=0&lpn=0&ln=1213&fr=&fmq=1568540326768_R&fm=&ic=undefined&s=undefined&hd=undefined&latest=undefined&copyright=undefined&se=&sme=&tab=0&width=undefined&height=undefined&face=undefined&ist=&jit=&cg=&bdtype=0&oriquery=&objurl=http%3A%2F%2Fwww.wuyueart.com%2Fuploads%2Fallimg%2F140616%2F11-140616112506334.jpg&fromurl=ippr_z2C%24qAzdH3FAzdH3Fooo_z%26e3Bo7y7jw6p_z%26e3Bv54AzdH3F4AzdH3Fetjo_z%26e3Brir%3Fwt1%3Dd808&gsm=0&rpstart=0&rpnum=0&islist=&querylist=&force=undefined "清华园")

   - 间接设置

    ![清华大学][1]
    [1]:https://image.baidu.com/search/detail?ct=503316480&z=0&ipn=d&word=%E6%B8%85%E5%8D%8E%E5%A4%A7%E5%AD%A6&step_word=&hs=0&pn=10&spn=0&di=135960&pi=0&rn=1&tn=baiduimagedetail&is=0%2C0&istype=2&ie=utf-8&oe=utf-8&in=&cl=2&lm=-1&st=-1&cs=1085396503%2C1319789480&os=4138859548%2C548366201&simid=3508421715%2C555530223&adpicid=0&lpn=0&ln=1029&fr=&fmq=1568539262841_R&fm=result&ic=0&s=undefined&hd=&latest=&copyright=&se=&sme=&tab=0&width=&height=&face=undefined&ist=&jit=&cg=&bdtype=0&oriquery=&objurl=http%3A%2F%2F5b0988e595225.cdn.sohucs.com%2Fq_70%2Cc_zoom%2Cw_640%2Fimages%2F20181125%2Faed17193169843f5a8dc3e15ea2111ed.jpeg&fromurl=ippr_z2C%24qAzdH3FAzdH3F4_z%26e3Bf5i7_z%26e3Bv54AzdH3FwAzdH3Fd0009m9nn_mdn089&gsm=0&rpstart=0&rpnum=0&islist=&querylist=&force=undefined




