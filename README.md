## √任务要求

#### 研究目的

1. 研究 FAT 文件系统的物理布局
2. 掌握 FAT 文件系统中目录的结构与目录项定义
3. 掌握文件系统操作如建立目录、建立文件、删除文件、复制文件时，对 FAT 和目录的操作步骤。
4. 合理设计文件系统布局与数据结构（直接用数组模拟磁盘布局或建立一个文件模拟磁盘布局）
5. 编制程序模拟 FAT 文件系统，加深理解文件系统的功能与实现原理

#### 成果要求

1. 使用 C/C++/Java 代码实现

2. 实现基本的 Unix/Linux 命令

   基本命令

   | 命令                            | 功能                                                         |
   | ------------------------------- | ------------------------------------------------------------ |
   | 命令提示符                      | 进入系统时，以根目录为当前路径，如：`/>`。改变路径后，相应改变提示符，如：`/user/wang> `。且光标闪烁。 |
   | dir <路径名>                    | 列出当前目录或指定目录下的目录与文件。若文件为目录则末尾加上 <dir>，若不存在文件，则显示“没有这个目录”。 |
   | md <目录名>，md<路径/目录名>    | 创建当前目录或指定目录下的子目录。                           |
   | cd <目录名>，cd<路径/目录名>    | 改变当前目录。                                               |
   | rd<目录名>，rd<路径/目录名>     | 删除当前目录或指定目录下的子目录。**只允许删除空目录，如目录非空，则提示“目录非空，无法删除”**。 |
   | new<文件名>，new<路径/文件名>   | 在当前目录或指定目录创建新文件。                             |
   | del<文件名>，del<路径/文件名>   | 在当前目录或指定目录删除文件。                               |
   | edit<文件名>，edit<路径/文件名> | 在当前目录或指定目录编辑文件。                               |
   | type<文件名>，type<路径/文件名> | 在当前目录或指定目录查看文件。                               |

   扩展命令

   | 命令                                                         | 功能                                                         |
   | ------------------------------------------------------------ | ------------------------------------------------------------ |
   | copy <文件名> <文件名>，copy<路径/文件名> <文件名>，copy<文件名> <路径/文件名>，copy<路径/文件名> <路径/文件名> | 复制当前目录或者指定目录下的文件到当前目录或指定目录下       |
   | attr<文件名> +r -r +h -h，attr<路径/文件名> +r -r +h -h      | 设置文件属性。如隐藏属性h不可被dir列出，只读属性r不可以被编辑和删除。 |
   | exit                                                         | 退出系统                                                     |

   选作命令：通配符下的 dir、copy、del，如`*`代表任意字符，`?`代表某一字符。例子：

   ```c
   /user/wang> dir
   .             <dir>
   ..            <dir>
   picture       <dir>
   readme.md 
   test.txt
   readme.txt
   /user/wang> del *.txt
   已删除 test.txt readme.txt
   /user/wang> dir
   .             <dir>
   ..            <dir>
   picture       <dir>
   readme.md 
   ```

3. 按格式撰写设计报告

#### 考核方式

所有命令必须在绝对与相对路径下实现，完成基本命令可及格，完成扩展命令可以得良好，所有都完成可以得优秀。

#### 进度计划

1. 掌握FAT文件系统布局

2. 掌握FAT文件系统的基本操作。

3. 需求分析

4. 代码实现

## 研究报告···

#### 研究背景

#### 正文

#### 参考文献

## 成果展示

#### 运行环境

#### 系统展示

#### 操作指南