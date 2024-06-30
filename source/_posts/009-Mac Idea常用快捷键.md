---
layout: 009-mac
title: Mac Idea常用快捷键
date: 2024-06-30 18:29:28
tags: 工具
categories:
  - 计算机
description: Control+Space:基本的代码不全（类、方法、变量）
---
##  编辑（Editing）

|快捷键|作用|
|---    |--- |
|Control+Space|基本的代码不全（类、方法、变量）|
|Control+Shift+Space|智能代码补全（过滤方法列表和变量的预期类型）|
|Comand+Shift+Enter|自动结束代码，行末添加分号|
|Command+P    |显示方法的参数信息|
|Control+J    |快速查看文档|
|Command+鼠标放在代码上|显示代码简要信息|
|Command+N|生成代码（getter、setter、hashCode、toString、构造函数）|
|Control+O|覆盖方法（重写父类方法）|
|Control+I|实现接口中的方法|
|Command+Option+T|包围代码（使用if...else 、try...catch、for、synchronized等包围选中的代码块）|
|Command+/|注释、取消注释行代码|
|Command+Option+/|注释、取消注释块代码|
|Option+方向键上|连续选中代码块|
|Option+方向键下|减少当前选中代码块|
|Control+Shift+Q|显示上线文信息|
|Option+Enter|显示意向动作、快速修复代码|
|Command+Option+L|格式化代码|
|Control+Option+O|优化import|
|Control+Option+I|自动缩进线|
|Tab/ Shift+Tab|缩进代码/反缩进代码|
|Command+X|剪切当前行或者选定块代码到剪贴板|
|Command+C|复制当前行或者选定块代码到剪贴板|
|Command+V|从剪贴板粘贴|
|Command+Shift+V|从缓冲区粘贴|
|Command+D|复制当前行或选中的块|
|Command+Delete|删除当前行或选中的块|
|Control+Shift+J|智能的将代码拼接成一行|
|Command+Enter|智能的拆分拼接的行|
|Shift+Enter|开始新的一行|
|Command+Shift+U|大小写切换|
|Command+Shift+][|选择直到代码块结束、开始|
|Option+Fn+Delete|删除到单次末尾|
|Option+Delete|删除到单词开头|
|Command+加号、减号|展开、折叠代码块|
|Command+Shift+加号、减号|展开、折叠所有代码块|
|Commnd+W|关闭活动的编辑器选项卡|

## 查找/替换（Search/Replace）

|快捷键|作用|
|---|---|
|Double Shift|查找任何东西|
|Command+F|文件内查找|
|Command+G|查找模式，向下查找|
|Comand+Shift+G|查找模式，向上查找|
|Command+R|文件类替换|
|Command+Shift+F|全局查找（根据路径）|
|Command+Shift+R|全局替换（根据路径）|

## 使用查询（Usage Search）
|快捷键|作用|
|---|---|
|Option+F7/Command+F7|在文件中查找用法/在类中查找用法|
|Command+Shift+F7|在文件中突出显示用法|
|Command+Option+F7|显示用法|
## 编译和运行（Compile and Run）
|快捷键|作用|
|---|---|
|Command+F9|编译项目|
|Command+Shift+F9|编译选中的文件、包、模块|
|Control+Option+R|弹出Run的可选菜单|
|Control+Option+D|弹出Debug的可选菜单|
|Control+R|运行|
|Control+D|调试|

## 调试（Debuging）
|快捷键| 作用                                          |
|--- |---------------------------------------------|
|Command+Option+O｜前往指定的变量、方法|
|F8|进入下一步，如果当前行断点是一个方法，则不进入方法体内|
|F7| 进入下一步，如果当前行断点是一个方法，则进入方法体内。该方法还有方法，不会进入嵌套方法 |
|Shift+F7| 智能步入，断点上有多个方法，会弹出要进入那个方法让你选                 |
|Shift+F8| 跳出                                          |
|Option+F9| 运行到光标处，如果光标前有其他断点会进入到该断点                    |
|Option+F8| 计算表达式，可以改变值使其生效                             |
|Command+Option+R| 恢复程序运行，如果该断点后面还有断点则停留下一个断点                  |
|Command+F8| 切换断点，加上/取消断点                                |
|Command+Shift+F8| 查看断点信息                                      |

## 导航（Navigation）
|快捷键|作用|
|--- |--- |
|Command+O|查找类文件|
|Command+Shift+O|查找所有的类型文件、打开目录、打开文件，打开目录需要在输入的类容前面或者后面增加一个/|
|Command+Option+O|前往指定的变量、方法|
|Control+左/右方向键|左右切换打开的编辑Tab|
|F12|返回到前一个编辑窗口|
|Esc|从工具窗口进入代码编辑窗口|
|Esc+Shift|影藏当前或者最后一个活动窗口，且光标进入代码文件窗口|
|Command+L|当前文件跳转至指定处|
|Command+E|显示最近打开的文件记录列表|
|Option+方向键左/右|光标跳转当前单次左/右开头的位置|
|Command+Option+方向键左/右|退回/前进上一次操作的地方|
|Command+Shift+Delete|跳转到最后一次编辑的地方|
|Option+F1|显示当前文件选择目标弹出层，如在代码编辑窗口可以显示该文件的Finder|
|Command+B|进入光标所在方法、类的定义|
|Command+Option+B|跳到实现处，在调的方法名上会调到具体的实现处|
|Option+Space,Command+Y|快速打开光标所在方法、类的定义|
|Control+Shift+B|跳到类型声明处|
|Command+U|跳到光标所在方法的父类方法和接口声明处|
|Control+方向键上/下|当前光标跳转到文件的前一个/后一个方法名|
|Command+F12|弹出当前文件结构层|
|Control+H|显示当前类的层次结构|
|F2/F2+Shift|跳到下一个/上一个错误或者警告的位置|
|F4/Command+方向下键|查看源码|
|F3|选中文件夹/文件/代码块使用注记符号添加标签|
|F3+Option|选中文件夹/文件/代码块使用注记符号添加标签|
|Control + 0…Control + 9|定位到对应数值的书签位置(没有作用)|
|Command+F3|显示所有书签|


## 重构（Refactoring）
|快捷键|作用|
|--- |--- |
|F5|复制文件到指定目录|
|F6|移动文件到指定目录|
|Command+Delete|安全删除文件，弹出确认框|
|Shift+F6|重命名文件|
|Command+Option+M|将选中的代码提取为方法|
|Command+Option+V|提取变量|
|Command+Option+F|提取字段|
|Command+Option+C|提取常量|
|Command+Option+P|提取参数|

## 通用（General）
|快捷键|作用|
|--- |--- |
|Command + 1…Command + 9    |打开相应编号的工具窗口|
|Command+S|保存所有|
|Command+Option+Y|同步、刷新|
|Control+Command+F|切换全屏|
|Command+Shift+F12|切换最大化编辑器|
|Option+Shift+F|添加到收藏夹|
|Option+Shift+I|检查当前文件与当前配置|
|Contro+`|快速切换当前Scheme(主体、代码样式)|
|Command+,|打开IDEA系统设置|
|Command+;|打开项目结构对话框|
|Shift+Command+A|查找动作|


## 动态代码模板（Live Templates）
|快捷键|作用|
|--- |--- |
|Command + Option + J|弹出模板选择窗口，将选定的代码使用动态模板包住|
|Command + J|插入自定义动态代码模板|

## 版本控制（VCS）
|快捷键|作用|
|--- |--- |
|Command + K|提交代码到版本控制器|
|Command + T|从版本控制器更新代码|
|Option + Shift + C    |查看最近的变更记录|

## 存疑

|快捷键|作用|
|--- |--- |
|Command + ] / Command + [    |移动光标到当前所在代码的花括号开始 / 结束位置|
|Command + Shift + H|** 显示方法层次结构（不知道什么意思）**|    
|Option + Home|显示到当前文件的导航条(Mac 没有home键)|
|Command + F6    |更改签名(不知道怎么用)|
|Command + Option + N    |一致性（不知道怎么用）|
|Control + Shift + Tab|编辑窗口标签和工具窗口之间切换(没反应)|
|Control + C|快速弹出版本控制器操作面板|

**参考**：

-  https://juejin.cn/post/7134515183984214052
-  https://resources.jetbrains.com/storage/products/intellij-idea/docs/IntelliJIDEA_ReferenceCard.pdf