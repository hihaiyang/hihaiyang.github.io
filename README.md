# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
这是正常内容

*-_ 分割线 *-_ 

```
*** 
---
___
```
---
***
---

<br>

# 字体样式

[//]: # (哈哈我是注释，不会在浏览器中显示。)
[^_^]: # (哈哈我是注释，不会在浏览器中显示。)

```说明:
一个[*|_]表示斜体
两个**或__表示粗体
三个***或___表示既斜又粗
两个~~表示删除
<sub>下标</sub>
<sup>上标</sup>
- [ ] 待办事项
- [x] 已完成的待办事项
```

正常<sub>下标</sub>

正常<sup>上标</sup>

*斜体*
_斜体_
<br>
**加粗**
__加粗__
<br>
~~删除~~
<br>
__又粗又斜__
~~***又粗又斜又删除***~~

- [ ] 待办事项
- [x] 已完成的待办事项

<br>

# 文字引用
```
[>]数量代表层级
格式:>引用文字
```
>文字引用
>
>>文字引用
>>>文字引用

<br>

# 链接
```
[百度](http://www.baidu.com "搜索一下")

[link-url]:https://hihaiyang.github.io/index.html "搜索一下"
[引用链接][link-url]
```
[百度](http://www.baidu.com "搜索一下")

[link-url]:https://hihaiyang.github.io/index.html "搜索一下"
[引用链接][link-url]

<br>

# 图片引用
```
普通图片
![alt图片文字](https://img-blog.csdnimg.cn/img_convert/048633409207f962f994fe57ae7ed812.png "title=文字说明")

带链接的图片
[![图片例子](https://www.baidu.com/img/PCgkdoodle_293edff43c2957071d2f6bfa606993ac.gif "图片说明文字")](http://www.baidu.com/ "链接说明文字")
```
![alt图片文字](https://img-blog.csdnimg.cn/img_convert/048633409207f962f994fe57ae7ed812.png "title=文字说明")

<img src="https://csdnimg.cn/release/blogv2/dist/pc/themesSkin/skin-number/images/bg-nav.png" title="文字说明" width="100" height="100">

[link_img]:https://csdnimg.cn/release/blogv2/dist/pc/themesSkin/skin-number/images/bg-nav.png "baidu.com 其实就是HTML 的<a> 标签的 Title 属性"
![引用式图片链接例子][link_img]

[![图片例子](https://www.baidu.com/img/PCgkdoodle_293edff43c2957071d2f6bfa606993ac.gif "图片说明文字")](http://www.baidu.com/ "链接说明文字")

<br>

# 代码块生成
```
普通代码块:
\```或
<pre><code>code</pre></code>
```
`this is code`

    class Demo {
        def say() {
            这是代码
        }
    }

<pre><code>class Demo {
    String say() {
        这是代码
    }   
}</code></pre>    

高亮显示代码 在代码块前后用三个反引号(``\`)围起来 然后在第一个(```)末尾标识语言类型
```javascript
// A highlighted block
var foo = 'bar';
```

```python
# A highlighted block
foo = 'bar'
def say():
    print('hello')
```

diff高亮语法:
```\diff
+ var x = 200;
- var x = 100;
* var x = 100;
```
```diff 
var foo = 'bar';
+ var x = 200;
- var x = 100;
* var x = 100;
```

<br>

# 有序列表
1. First item
1. First item
    1. Second item
        1. Third item
1. Second item
    1. Second item
1. Third item
5. Fourth item

# 无序列表
```
+ 一层
    - 两层
        * 三层
            + 四层
            
                输入内容
            + 四层-1
                
                输入内容
+ 二层
```
+ 一层
    - 两层
        * 三层
            + 四层
            
                输入内容
            + 四层-1
                
                输入内容
+ 二层
  
<br>

# 表格
`语法: 使用 | 来分隔不同的单元格，使用 - 来分隔表头和其他行。`
<br>
`说明
-: 设置内容和标题栏居右对齐。
:- 设置内容和标题栏居左对齐。
:-: 设置内容和标题栏居中对齐。`

```
| 左左左对齐 | 右右右对齐 | 居中对齐 |
| :-----| ----: | :----: |
| 单元格 | 单元格 | 单元格 |
| 单元格 | 单元格 | 单元格 |
```

| 左左左对齐 | 右右右对齐 | 居中对齐 |
| :-----| ----: | :----: |
| 单元格 | 单元格 | 单元格 |
| 单元格 | 单元格 | 单元格 |

<br>

# 视频
<video src="视频链接" width="320" height="180" controls="controls"></video> 
