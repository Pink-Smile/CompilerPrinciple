﻿#### 程序结构
按照一下流程编写程序：
- Regex——>RPN:正则表达式到逆波兰式。先添加连接符，然后转换为逆波兰式
- RPN——>NFA：逆波兰式到NFA
- NFA——>DFA：NFA到DFA，根据课堂上讲的步骤
- DFA——>MiniDFA：也是按照课堂上步骤实现
#### 注意：

 - 程序输入后先点击 “**OK**” 按钮，然后再点击其他按钮。
 - 输入的正则表达式是字母，不要用数字
 - 空符号用 # 代替，正则表达式输入里面不能有空字符

##### 输入：
`a(a|b)*b`

##### 输出：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200414150610280.png)
***
#### 输入：
`ab|c(d*|a)`
#### 输出：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200414150819906.png)
***
#### 输入：(习题课例子）
`b(a|b)*a`
#### 输出：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200414150927251.png)
