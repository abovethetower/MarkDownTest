# <center><font facr="楷体" size=5 font color=orange>Markdown入门</font></center>
### 一、基本语法

1. **标题**
    #一级标题
    ##二级标题
    ...

2. **引用**
  > 编辑这类教程文档好用

3. **列表**
    1. 无序列表
    - 列表1
    + 列表2
    * 列表3
    2. 有序列表
    3. 嵌套列表
    4. TodoList
        - [ ] a
        - [ ] b
        - [ ] c
4. **表格**
    | 左对齐 | 居中对齐 | 右对齐 |
    | :---- | :----: | ----: |
    | a | b | c |
5. **段落**
    - 换行？ —— 两个以上空格后回车/空一行
    - 分割线 —— 三个以上的*
    ***
    - 字体 
  
    | 字体 | 代码 |
    | :--: | :--: |
    | *斜体* | * *|
    |==高亮==|== ===|
    |**粗体**|** **|
    |***斜粗体***|*** ***|
    |~~删除~~|~~ ~~|
    |<u>下划线</u>|```<u> </u>```|
    - 脚注
    这里是一个脚注[^1]

6. **代码**
```
#include <stdio.h>

int main(void)
{
    printf("Hello, World!\n");
    return 0;
}
```

7. **超链接**
    - [更多使用教程可以参考网站]：https://www.runoob.com/markdown/md-link.html
 
    - 查看更多使用功能请[点击链接][教程]

8. **图片**
    使用图床保存图片并实现插入
    [路过图床]: https://imgse.com/
    [![pZeAOiD.png](https://s41.ax1x.com/2025/12/03/pZeAOiD.png)](https://imgchr.com/i/pZeAOiD)


### 三、其他操作
- **插入latex公式**
  - 行内显示公式：
$f(x)=ax+b$
$f(x)=∫lnxdx$
  - 块内显示数学公式：
$$
\begin{Bmatrix}
a & b \\
c & d
\end{Bmatrix}
$$
- **html/css语法**
    - ctrl+shift+p 搜索  
    "Markdown Preview Enhanced: Customize CSS"
    在style中使用css格式改标题格式等
- **个性化设置**
  File-Preferences-Settings  
      
    





[^1]: 这里有一个脚注。

[教程]: https://www.runoob.com/markdown/md-link.html