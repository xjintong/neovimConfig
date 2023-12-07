# 当前nvim快捷键

## 复制、粘贴、删除

### 复制

- **yy**：复制光标所在行
- **y$**：复制从光标位置到本行末尾
- **nyy**：n是要复制的行数，从当前行开始

- **:%y**：复制整个文件

### 粘贴

- **pp**：在下一行粘贴

- **p（小写）**：在当前行的下一行进行粘贴，并移动到新插入行的开头
- **P（大写）**：和小p差不多，不同的是粘贴在当前行的上一行
- **gp**：粘贴在下一行，然后跳到粘贴行的下一行的开头
- **gP**：与gp差不多，就是跳到粘贴行的上一行的开头

### 删除

- **dd**：删除当前行
- **ndd**：删除从当前行开始的n个行
- **d0**：删除光标之前到行首的字符
- **D**：删除从当前光标位置到行尾
- **x**：删除当前光标位置的字符
- **d + shift + g**：删除光标所在行到文件末尾

## 插入模式

- **i**：在当前光标前插入文本
- **I**：在当前行开始处插入文本
- **o（小写）**：在当前行的下一行插入文本
- **O（大写）**：在当前行的上一行插入文本
- **a**：在当前光标后插入文本
- **A**：在当前行最后插入文本
- **r**：对当前光标处的字符进行替换
- **R**：从当前光标处开始一直往后替换（如果替换后想回退按 Backspace）


## 快速移动

- **0（零）**：跳到行首
- **$**：跳到行尾
- **gg**：跳到文件头
- **shift + g**：跳到文件末尾

- **fx**：移动到光标右侧第一个x字符，其他字符同理
- **Fx**：和上面的差不多，只是向左侧查找
- **3fx**：右侧第三个x字符

## 查找

- **/ ____**：在那个下划线输入要查找的字符

## 文件树

光标移动到在左侧文件导航那

- nvim . ：设置当前目录为根目录，打开neo-tree
- s：打开文件(竖直分割窗口打开新文件)
- S：打开文件（水平分割窗口打开新文件）
- a：创建文件/文件夹（文件夹以**/**结尾）
- A：创建文件夹
- I：文件信息
- R：修改名字
- .：更换文件树的根目录
- z：关闭所有文件夹的打开状态
- t：在当前窗口打开文件夹，并且关闭左方导航栏
- **]b**：打开了多个文件，跳到当前文件的右边文件光标位置
- **[b**：和上一个差不多，只是跳到左边的文件
- D：在当前根目录及其子目录寻找文件夹
- /：在当前根目录及其子目录中寻找文件
- q：关闭当前左边导航


## 注释
Comment.nvim插件的默认快捷方式。

- **gc2j**：这是个例子，就是注释当前行和当前行下面的2行；也可以及gc2k.....这里的注释是单行注释，在c中是``//``
- **gcc**：注释当前行j
- **gb2j**：这也是个例子，和gc2j差不多，只是向上。这里是块注释，在c中是``/* */``
- **gco**：在下面创建一个新行，开头会有注释符号
- **gcO**：在上面创建一个新行，开头会有注释符号
- **gcA**：在行尾添加注释
- **gcw**：注释单词
- **gb%**：光标移动到左括号或右括号，然后用这个可以注释括号和括号内的语句

## 杂

- **]b**：打开了多个文件，跳到当前文件的右边文件光标位置
- **[b**：和上一个差不多，只是跳到左边的文件


