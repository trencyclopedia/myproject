Wimdows terminals, command line interfaces --- PowerShell

# **useage of apps, short-cuts, tricks in Widows and linux OS**

# Contents

**[Linux systems 1](#_Toc89970339)**

**[Wildcards and Regular Expression &Shell scripting 1](#_Toc89970340)**

**[Bash 1](#_Toc89970341)**

**[shell](#_Toc89970342)****里的特殊字符 **** 1**

**[Wildcards 2](#_Toc89970343)**

[Bash Wildcards(](#_Toc89970344)通配符): 2

[wildcards in Glob patterns( a function used by Shell) 2](#_Toc89970345)

[Wildcard in SQL[edit] 3](#_Toc89970346)

**[Regular expression (regex or regexp): 3](#_Toc89970347)**

[Regex Usage in Text editors 4](#_Toc89970348)

**[wildcat vs regular expression 5](#_Toc89970349)**

**[Shell Scripting 6](#_Toc89970350)**

**[学习经验和过程](#_Toc89970351)**  **6**

[一：起因](#_Toc89970352) 6

[二：知识点介绍](#_Toc89970353) 7

[三：体会心得](#_Toc89970354) 10

**[Shell](#_Toc89970355)****脚本编程 ****30**** 分钟入门 **** 10**

**[重定义变量](#_Toc89970356)**  **11**

**[多行注释](#_Toc89970357)**  **11**

**[Bash shell syntax 12](#_Toc89970358)**

[3.1.2 Quoting 12](#_Toc89970359)

**[3.2](#_Toc89970360)****Shell Commands 13**

**[Bash Shell scripting 14](#_Toc89970361)**

[How do I count all the files recursively through directories](#_Toc89970362) 15

**[Linux System](#_Toc89970363)****， **** Terminals, Commands 15**

**[Linux trick 15](#_Toc89970364)**

**[Linux terminals 15](#_Toc89970365)**

**[Shell types (Bourne sh, bash, csh, tcsh, ksh,) 15](#_Toc89970366)**

**[Linux Basic commands 16](#_Toc89970367)**

**[Man(manual) page shortcuts 20](#_Toc89970368)**

[MOVING 20](#_Toc89970369)

[SEARCHING 20](#_Toc89970370)

[JUMPING 21](#_Toc89970371)

**[Piping and redirection 23](#_Toc89970372)**

**[Linux intermediate commands 25](#_Toc89970373)**

**[System admin 25](#_Toc89970374)**

**[Package management commands 28](#_Toc89970375)**

**[Virtual session uninterruptable 29](#_Toc89970376)**

[1. Multitask & co-processing in bash shell 29](#_Toc89970377)

[Screen 29](#_Toc89970378)

[3.Tmux 30](#_Toc89970379)

[4.Nohup 31](#_Toc89970380)

**[Linux File system 31](#_Toc89970381)**

**[1.](#_Toc89970382)****basic file structure 31**

**[2.](#_Toc89970383)****import folders/files 31**

**[3.](#_Toc89970384)****ect 32**

**[A.](#_Toc89970385)****Everything is a File. 32**

**[B.](#_Toc89970386)****File access permission 32**

**[Linux Tools 35](#_Toc89970387)**

**[Vi vim emacs Text Edito & Processing: 35](#_Toc89970388)**

**[Emacs 37](#_Toc89970389)**

**[Parallel computing 39](#_Toc89970390)**

**[Exascience tutorial 39](#_Toc89970391)**

**[GUI connection 41](#_Toc89970392)**

**[Use Jupyter on remote cluster 43](#_Toc89970393)**

**[accessing the ipython notebook running the cluster locally 43](#_Toc89970394)**

**[System overview 43](#_Toc89970395)**

**[Generally Available 45](#_Toc89970396)**

**[GPU nodes 46](#_Toc89970397)**

**[GPU-01 and GPU-02 46](#_Toc89970398)**

**[[edit]GPU-03 47](#_Toc89970399)**

**[Linux system on windows 49](#_Toc89970400)**

**[cygwin 49](#_Toc89970401)**

**[WINDOWS SUBSYSTEM FOR LINUX 49](#_Toc89970402)**

**[What is WSL 49](#_Toc89970403)**

**[Windows interoperability with Linux 49](#_Toc89970404)**

**[Files and Home Directory across OS file systems 49](#_Toc89970405)**

**[Run Windows tools from Linux 51](#_Toc89970406)**

**[Wimdows terminals, command line interfaces 52](#_Toc89970407)**

**[Windows Command line 52](#_Toc89970408)**

**[Basics 52](#_Toc89970409)**

**[Pipe 53](#_Toc89970410)**

**[System-wise Command 53](#_Toc89970411)**

**[PowerShell 54](#_Toc89970412)**

**[What is powershell 54](#_Toc89970413)**

**[shell, scripting language, configuration management framework 54](#_Toc89970414)**

**[.NET 56](#_Toc89970415)**

**[keyboard Shortcuts in Windows OS 57](#_Toc89970416)**

**[Windows 10 keyboard shortcuts 57](#_Toc89970417)**

**[Essential shortcuts 57](#_Toc89970418)**

**[Desktop shortcuts 58](#_Toc89970419)**

**[File Explorer shortcuts 62](#_Toc89970420)**

**[Command Prompt shortcuts 63](#_Toc89970421)**

**[Windows key shortcuts 64](#_Toc89970422)**

**[navigate Windows using a keyboard. 68](#_Toc89970423)**

**[Comparing Keyboard shortcuts in different OS & Applications 69](#_Toc89970424)**

**[Widows application 71](#_Toc89970425)**

**[Office 71](#_Toc89970426)**

**[Common Shortcuts in Word, Excel, and PowerPoint 2016 71](#_Toc89970427)**

**[Word Shortcut 72](#_Toc89970428)**

[Frequently used shortcuts 72](#_Toc89970429)

[Align and format paragraphs 73](#_Toc89970430)

[Insert special characters 74](#_Toc89970431)

[Outline a document 75](#_Toc89970432)

**[Word 75](#_Toc89970433)**

**[Word Intermediate to advanced skills 75](#_Toc89970434)**

[Operating parameter limitations and specifications in Word 75](#_Toc89970435)

[Add Chapter Title To Header Or Footer In Word Document? 76](#_Toc89970436)

[Skills to handle large word documents 77](#_Toc89970437)

[Styles 78](#_Toc89970438)

[Word TOC 79](#_Toc89970439)

[Section break and (reusable) quick parts 79](#_Toc89970440)

**[Advanced Tables in Word: Table Styles, Breaks and Formulas 80](#_Toc89970441)**

[5 ways to link one document with another 80](#_Toc89970442)

**[Excel 85](#_Toc89970443)**

**[Visual Basic for Applications (VBA) 85](#_Toc89970444)**

**[Note taking and knowledge management tools 86](#_Toc89970445)**

**[Knowledge management 86](#_Toc89970446)**

**[Personal knowledge management 86](#_Toc89970447)**

[Skills[edit source] 87](#_Toc89970448)

[PKM has also been linked to these tools:[_citation needed_] 87](#_Toc89970449)

**[User modelling or User Profile 88](#_Toc89970450)**

**[Methods and Tools for Managing Knowledge and Information 88](#_Toc89970451)**

**[Peronal wiki 88](#_Toc89970452)**

[Personal wiki software[edit source] 88](#_Toc89970453)

[Hosted-only software[edit source] 89](#_Toc89970454)

[Content management and social software with wiki functionality[edit source] 89](#_Toc89970455)

[Java-based[edit source] 89](#_Toc89970456)

**[notetaking 90](#_Toc89970457)**

[Comparison of note-taking software 90](#_Toc89970458)

[Zettelkasten 94](#_Toc89970459)

[Outlier processor (tree structure text files) 94](#_Toc89970460)

[Tag (metadata) 96](#_Toc89970461)

[concept- and mind-mapping software 96](#_Toc89970462)

[Graph-drawing brainstorming 107](#_Toc89970463)

**[Web surfuing, Chrome 109](#_Toc89970464)**

**[Chrome search Trics 109](#_Toc89970465)**

**[Refine web searches 109](#_Toc89970466)**

**[Refine image searches 109](#_Toc89970467)**

**[Common search techniques 109](#_Toc89970468)**

[Search social media 109](#_Toc89970469)

[Search for a price 109](#_Toc89970470)

[Search hashtags 109](#_Toc89970471)

[Exclude words from your search 109](#_Toc89970472)

[Search for an exact match 109](#_Toc89970473)

[Search within a range of numbers 110](#_Toc89970474)

[Combine searches 110](#_Toc89970475)

[Search for a specific site 110](#_Toc89970476)

[Search for related sites 110](#_Toc89970477)

[See Google's cached version of a site 110](#_Toc89970478)

**[Chrome Keyboard Shortcuts for Windows and Linux 110](#_Toc89970479)**

**[Google Chrome feature shortcuts 110](#_Toc89970480)**

**[Tab and window shortcuts 111](#_Toc89970481)**

**[Address bar shortcuts 111](#_Toc89970482)**

**[Webpage shortcuts 111](#_Toc89970483)**

**[Mouse shortcuts 112](#_Toc89970484)**

**[Chrome Extentions 112](#_Toc89970485)**

**[Vimium](#_Toc89970486)****（ ****Extent ions**** ） **** in Chrome 112**

**[字符编码 标准](#_Toc89970487)**  **114**

**[Character encoding 114](#_Toc89970488)**

**[标准编码格式](#_Toc89970489)**  **114**

**[字符集与编码](#_Toc89970490)**  **114**

[字符与编码的发展](#_Toc89970491) 114

[American National Standards Institute](#_Toc89970492)（ANSI）编码 117

[Unicode](#_Toc89970493)（Universal Coded Character Set） 字符集 （144,697 characters） 118

[How is encoding handled correctly during copy-paste between programs? 122](#_Toc89970494)

[CJKV](#_Toc89970495)（The Chinese, Japanese, Korean and Vietnam） Unified Ideographs[edit source] 123

**[Data processing 132](#_Toc89970496)**

**[Power Query 132](#_Toc89970497)**

**[Power BI 132](#_Toc89970498)**

# **Linux systems**

# Wildcards and Regular Expression &Shell scripting

[https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular\_Expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions)

I will outline the basic building blocks of re's below, then follow on with a set of examples to demonstrate their usage.

[http://tldp.org/LDP/GNU-Linux-Tools-Summary/html/x11655.htm](http://tldp.org/LDP/GNU-Linux-Tools-Summary/html/x11655.htm)

### Bash

- Echo $SHELL
- $SHELL --verison

GNU bash, version 5.0.17(1)-release (x86\_64-pc-linux-gnu)

Copyright (C) 2019 Free Software Foundation, Inc.

**Bash**  is a [Unix shell](https://en.wikipedia.org/wiki/Unix_shell) and [command language](https://en.wikipedia.org/wiki/Command_language) written by [Brian Fox](https://en.wikipedia.org/wiki/Brian_Fox_(computer_programmer)) for the [GNU Project](https://en.wikipedia.org/wiki/GNU_Project) as a [free software](https://en.wikipedia.org/wiki/Free_software) replacement for the [Bourne shell](https://en.wikipedia.org/wiki/Bourne_shell).

 it supports filename [globbing](https://en.wikipedia.org/wiki/Glob_(programming)) (wildcard matching), [piping](https://en.wikipedia.org/wiki/Pipeline_(Unix)), [here documents](https://en.wikipedia.org/wiki/Here_document), [command substitution](https://en.wikipedia.org/wiki/Command_substitution), [variables](https://en.wikipedia.org/wiki/Variable_(programming)), and [control structures](https://en.wikipedia.org/wiki/Control_flow) for [condition-testing](https://en.wikipedia.org/wiki/Conditional_(programming)) and [iteration](https://en.wikipedia.org/wiki/Iteration). The [keywords](https://en.wikipedia.org/wiki/Keyword_(computer_programming)), [syntax](https://en.wikipedia.org/wiki/Syntax_(programming_languages)), [dynamically scoped](https://en.wikipedia.org/wiki/Scope_(computer_science)#Dynamic_scoping) variables and other basic features of the [language](https://en.wikipedia.org/wiki/Language_(computer_science)) are all copied from [sh](https://en.wikipedia.org/wiki/Bourne_shell). Other features, e.g., [history](https://en.wikipedia.org/wiki/C_shell#History), are copied from [csh](https://en.wikipedia.org/wiki/C_shell) and [ksh](https://en.wikipedia.org/wiki/KornShell). Bash is a [POSIX](https://en.wikipedia.org/wiki/POSIX)-compliant shell, but with a number of extensions.

### shell里的特殊字符

和其他编程语言一样，shell里也有特殊字符。常见的有美元符号（$），反斜线（\）和引号。

1. **#**  **英镑（**** pound ****）**  **#**  **注释**
2. **: #**** 连续命令执行分隔符**
3. **~ #**  **用户主文件目录**
4. **/ #**  **目录分隔符**
5. **\>, \>\>**  **#**  **数据流重定向，分别代表替换 和 添加**
6. **\<,\<\<**  **#**  **数据流重定向，分别代表替换 和 添加**
7. **| (pipe symbol)** #- the logical OR operation.
8. **$**  **美元符号** #美元符号表示变量替换，即用其后面指定的变量的值来代替变量。
9. **& ampersand**  **#**  **作业（**** job ****）控制， 将命令在背景执行**
10. **\**  **反斜线**** #**"\"为转义字符，转义字符告诉shell不要对其后面的那个字符进行特殊处理，只是当做普通字符。
11. **"**  **双引号（****" ****）** # 由双引号括起来的字符，除$，倒引号（`）和反斜线（\）仍保留其特殊功能外，其余字符均作为普通字符对待。
12. **'**  **单引号（****' ****）**** #** 由单引号括起来的字符都作为普通字符出现。
13. **`**  **倒引号（**** ` ****）**** # tab ****键上面那个原始字符** 由倒引号括起来的字符串被shell解释为命令行，在执行时，shell会先执行该命令，并以它的标准输出结果取代整个引号部分。
14. **()**  **#-** allows us to group several characters to behave as one.
15. **{} (curly brackets)****#**terms are separated by commas and each term must be the name of something or a wildcard. This wildcard will copy anything that matches either wildcard(s), or exact name(s) (an "or" relationship, one or the other).

    1. **cp {\*.doc,\*.pdf} ~** #This will copy anything ending with .doc or .pdf to the users home directory. Note that spaces are not allowed after the commas (or anywhere else).
  1. **mv \*{.py,.sh} new\_folder** #会移动所有\*.py 和\*.sh 文件
  2. **touch {foo,bar}/{a..h}** #创建foo/a, foo/b, ... foo/h, bar/a, bar/b, ... bar/h这些文件

### Wildcards

#### Bash Wildcards(通配符):

- **\* (asterisk)** - represents zero or more characters #
  1. If you specified a "cd\*" it would use "cda", "cdrom", "cdrecord" and anything that starts with "cd" also including "cd" itself.
  2. "m\*l" could by mill, mull, ml, and anything that starts with an m and ends with an l.
- **? (question mask)** - represents a single character #
  1. If you specified something at the command line like "hd?" GNU/Linux would look for hda, hdb, hdc and every other letter/number between a-z, 0-9.
- **[] (square brackets)** - represents a single character from a range of characters #
  1. **m[aou]m** #it can become: mam, mum, mom
  2. **m[a-d]m** #it can become anything that starts and ends with m and has any character a to d in between.
  3. **[****^****aou]** # it means anything otherthan a,o,u
  4. **[!]** #it'll match any character, as long as it is not listed between the [and]. This is a logical NOT.

  - **rm myfile[!9]** #will remove all myfiles\* (ie. myfiles1, myfiles2 etc) but won't remove a file with the number 9 anywhere within it's name.

#### wildcards in Glob patterns( a function used by Shell)

| Wildcard | Description | Example | Matches | Does not match |
| --- | --- | --- | --- | --- |
| **\*** | matches any number of any characters including none
 | Law\* | Law, Laws, or Lawyer | GrokLaw, La, or aw |
| \*Law\* | Law, GrokLaw, or Lawyer. |
 |
| **?** | matches any single character | ?at | Cat, cat, Bat or bat | at |
| **[abc]** | matches one character given in the bracket | [CB]at | Cat or Bat | cat, bat or CBat |
| **[a-z]** | matches one character from the (locale-dependent) range given in the bracket | Letter[0-9] | Letter0, Letter1, Letter2 up to Letter9 | Letters, Letter or Letter10 |

Normally, the path separator character (/ on Linux/Unix, MacOS, etc. or \ on Windows) will never be matched. Some shells, such as [Bash](https://en.wikipedia.org/wiki/Bash_(Unix_shell)) have functionality allowing users to circumvent this. [[5]](https://en.wikipedia.org/wiki/Glob_(programming)#cite_note-5)

Traditionally, globs do not match hidden files in the form of Unix [dotfiles](https://en.wikipedia.org/wiki/Dotfiles); to match them the pattern must explicitly start with .. For example, \* matches all visible files while .\* matches all hidden files.

Globs do not include syntax for the [Kleene star](https://en.wikipedia.org/wiki/Kleene_star) which allows multiple repetitions of the preceding part of the expression;

#### Wildcard in SQL[[edit](https://en.wikipedia.org/w/index.php?title=Glob_(programming)&action=edit&section=5)]

The [SQL](https://en.wikipedia.org/wiki/SQL) LIKE operator has an equivalent to ? and \* but not […].

| **Common wildcard** | **SQL wildcard** | **Description** |
| --- | --- | --- |
| ? | \_ | matches any single character |
| \* | % | matches any number of any characters including none |

### Regular expression (regex or regexp):

A  **regular expression**  (shortened as  **regex**  or  **regexp** ;[[1]](https://en.wikipedia.org/wiki/Regular_expression#cite_note-1) also referred to as  **rational expression** [[2]](https://en.wikipedia.org/wiki/Regular_expression#cite_note-Mitkov2003-2)[[3]](https://en.wikipedia.org/wiki/Regular_expression#cite_note-Lawson2003-3)) is a sequence of [characters](https://en.wikipedia.org/wiki/Character_(computing)) that specifies a _search _[_pattern_](https://en.wikipedia.org/wiki/Pattern_matching). The concept arose in the 1950s when the American mathematician [Stephen Cole Kleene](https://en.wikipedia.org/wiki/Stephen_Cole_Kleene) formalized the description of a [_regular language_](https://en.wikipedia.org/wiki/Regular_language).

Regular expressions are used in [search engines](https://en.wikipedia.org/wiki/Search_engine), search and replace dialogs of [word processors](https://en.wikipedia.org/wiki/Word_processor) and [text editors](https://en.wikipedia.org/wiki/Text_editor), in [text processing](https://en.wikipedia.org/wiki/Text_processing) utilities such as [sed](https://en.wikipedia.org/wiki/Sed) and [AWK](https://en.wikipedia.org/wiki/AWK) and in [lexical analysis](https://en.wikipedia.org/wiki/Lexical_analysis). Many [programming languages](https://en.wikipedia.org/wiki/Programming_language) provide regex capabilities either built-in or via [libraries](https://en.wikipedia.org/wiki/Library_(computing)), as it has uses in many situations.

\<\< linux command line and shell scripting bible\>\>The biggest problem with using regular expressions is that there isn't just one set of them. Several different applications use different types of regular expressions in the Linux environment. A regular expression is implemented using a _regular expression engine._

###### The Linux world has two popular regular expression engines:

  - The POSIX Basic Regular Expression (BRE) engine --\>(grep)
  - The POSIX Extended Regular Expression (ERE) engine ---\>(egrep)

###### These special characters are recognized by regular expressions:

**.\*[]^${}\+?|()**

If you want to use one of the special characters as a text character, you need to _escape_ it using \.

- **. (dot)** - a single character. the dot matches any character except a newline
- **?** - the preceding character matches 0 or 1 times only.
- **\*** - the preceding character matches 0 or more times.
- **+** - the preceding character matches 1 or more times.
- **{n}** - the preceding character matches exactly n times.
  - **{n,m}** - the preceding character matches at least n times and not more than m times.
- **[agd]** - the character is one of those included within the square brackets.
  - **[^agd]** - the character is not one of those included within the square brackets.
  - **[c-f]** - the dash within the square brackets operates as a range. In this case it means either the letters c, d, e or f.
- **()** - allows us to group several characters to behave as one.
- **|** (pipe symbol) - the logical OR operation.
- **^** - matches the beginning of the line.
- **$** - matches the end of the line. [

#### Regex Usage in Text editors

1. **sed** # The sed editor is called a _stream editor_, as opposed to a normal interactive text editor like vim.A stream editor edits a stream of data based on a set of rules you supply ahead of time, before the editor processes the data.
  1. **Sed 's/dog/cat/' data.txt # s** substitutes dog with cat in the contents of data.txt, and then stream to stdout. The source data is not changed.
  2. **sed -e 's/brown/green/; s/dog/cat/' data1.txt** ## -e multiple commands, substitutes brown with green, dog with cat in the contents of data.txt, and then stream to stdout.
  3. **sed -e '** # the first single quotation mark open interactive input

**\> s/brown/green/**

**\> s/fox/elephant/**

**\> s/dog/cat/' data1.txt**

1. **gawk** #works with POSIX ERE patterns
  1. **gawk '{print $n}' data.txt # print out the nth world in each line of data.txt**
  2. **gawk -F: '{print $1}' /etc/passwd** # show the second word separated by : in each line of the passwd file
  3. **echo "my name is eric" | gawk '{$4="donghui Zhai"; print $0}'** # replace the 4th world with donghui zhai and then print out the whole sentence to the stdout.
  4. $ **gawk 'BEGIN {print "The data3 File Contents:"}** # interactive input mode , first command show the message in the beginning of the file

\> **{print $0}** # second command

\> **END {print "End of File"}' data3.txt** # last command, show the message at the end of the file

1. **grep [options] pattern [files]#** searching plain-text data sets for lines that match a regular expression. Its name comes from the ed command g/re/p ( **g** lobally search a **r** egular **e** xpression and **p** rint), which has the same effect: doing a global search with the regular expression and printing all matching lines. **Use Unix-style regular expression to match pattern** [http://www.robelle.com/smugbook/regexpr.html](http://www.robelle.com/smugbook/regexpr.html)
  1. **grep John /etc/passwd** #grep looks for the text John inside /etc/passwd file and displays all the matching lines.
  2. **grep -v John /etc/passwd**  **#** Option -v, will display all the lines except the match.

1. **grep -n 'mellon' mysampledata.**** txt** #know not only which lines matched but their line number as well.
2. **grep -c John /etc/passwd** #Option -c, will display the total number of matching lines
3. **grep -cv John /etc/passwd #** total number of unmatching lines
4. **grep -e for -e \*ubject?? LOSO\_cross\_val\_log.txt | sort -n #** use the -e parameter to specify each individual pattern, here the pattern is "for \* ubject??"
5. **grep '[0-9][0-9]' LOSO\_cross\_val\_log.txt |sort -n**
6. **grep -i john /etc/passwd #**** option -i (ignore case), which will ignore the case while searching.**
7. **grep -ri john /home/users #** option -r (recursive) .earch all subdirectories for a text matching a specific pattern

1. **egrep [command line options] \<pattern\> [path]**#egrep is a program which will search a given set of data and print every line which contains a given pattern. It is an extension of a program called grep. Enable POSIX extended regular expressions
  1. **egrep -n 'mellon' mysampledata.**** txt** #know not only which lines matched but their line number as well.
  2. **egrep -c 'mellon' mysampledata.txt** #know how many lines did match.
  3. **egrep '[aeiou]{2,}' mysampledata.txt**#identify any line with two or more vowels in a row.
  4. **egrep '2.+' mysampledata.txt** #any line with a 2 on it which is not the end of the line.

### wildcat vs regular expression

[https://unix.stackexchange.com/questions/57957/how-do-regular-expressions-differ-from-wildcards-used-to-filter-files](https://unix.stackexchange.com/questions/57957/how-do-regular-expressions-differ-from-wildcards-used-to-filter-files)

[Shell file name globbing](http://en.wikipedia.org/wiki/Globbing) and [regular expressions](http://en.wikipedia.org/wiki/Regular_expression) use some of the same characters, and they have similar purposes, but you're right, they aren't compatible. File name globbing is a much less powerful system. Wildcards 代表的是bash操作接口的一个模糊指代功能，而Regular Expression 则是一种字符串处理的功能；

| **Common wildcard** | **Equivalent regular expression** | **Meaing** |
| --- | --- | --- |
| ? | . | Any one character |
| \* | .\* | Any zero/more chars |

Globs attempt to match the entire string (for example, S\*.DOC matches S.DOC and SA.DOC, but not POST.DOC or SURREY.DOCKS), whereas, depending on implementation details, regular expressions may match a substring.

In [regular expressions](https://en.wikipedia.org/wiki/Regular_expression), the [period](https://en.wikipedia.org/wiki/Full_stop) (., also called "dot") is the wildcard pattern which matches any single character. Combined with the [asterisk](https://en.wikipedia.org/wiki/Asterisk) operator .\* it will match any number of any characters.In this case, the asterisk is also known as the [Kleene star](https://en.wikipedia.org/wiki/Kleene_star).

## Shell Scripting

**Dfdsf ddfd fdsfdsd**

### 学习经验和过程

[汤哥在北京](https://www.zhihu.com/people/tang-ge-71-52)马哥教育核心研发人，专注Linux云计算和Python人才培训。

3 人赞同了该回答

看了很多的Shell学习计划，但是最后都没有完成，下面说说我们马哥Linux学习社群的一个人的经历。

#### 一：起因

**（**** 0 ****）也许由于一时的冲动使得你开始关注并学习**** shell ****编程；亦许由于是"道听途说"**** shell ****的威力很大；亦许由于**** shell ****编程的魅力；亦许由于作为一个**** coder ****的偏好；亦许……**

**（**** 1 ****）先来搞清楚为什么要学**** shell, ****学习要有目的性**  **----**  **简单的说**** shell ****就是一个包含若干行**** Shell ****或者**** Linux ****命令的文件。对于一次编写，多次使用的大量命令，就可以使用单独的文件保存下来，以便日后使用。**

- **shell**** 简单、灵活、高效 ****,**** 特别适合处理一些系统管理方面的小问题**
- **shell**** 可以实现自动化管理 ****,**** 让系统管理员的工作变得容易、简单、高效**
- **shell**** 可以把一些经常需要用的命令或者操作，以文件的形式存储起来，每一次调用即可，不用重复的键入命令**
- shell脚本可移植性好,在unix/linux系统中可灵活移植,几乎不用任何设置就能正常运行
- shell脚本可轻松方便读取和修改源代码,不需要编译 掌握shell可以帮你解决一些故障问题,比如脚本引起的故障问题
- 掌握shell是一个中级以上系统工程师必需要会的 掌握shell是你系统管理进阶的必经之路
- 掌握shell是你面试更高级职位的一块敲门砖

**（**** 2 ****）那什么时候不使用**** Shell **** 脚本 ****?**

- 资源密集型的任务,尤其在需要考虑效率时(比如排序,hash 等)
- **需要处理大任务的数学操作**** , ****尤其是浮点运算**** , ****精确运算**** , ****或者复杂的算术运算**** ( ****这种情况一般使用**** C++ ****或**** FORTRAN **** 来处理****)**
- 有跨平台移植需求(一般使用C 或Java) **复杂的应用**** , ****在必须使用结构化编程的时候**** ( ****需要变量的类型检查**** , ****函数原型**** , ****等等**** )**
- 对于影响系统全局性的关键任务应用。 对于安全有很高要求的任务,比如你需要一个健壮的系统来防止入侵,破解,恶意破坏等等. 项目由连串的依赖的各个部分组成。
- **需要大规模的文件操作 或** 需要多维数组的支持 **需要数据结构的支持**** , ****比如链表或数等数据结构**
- **需要产生或操作图形化界面**  **GUI** 需要直接操作系统硬件 **需要**  **I/O**  **或**** socket **** 接口**
- 需要使用库或者遗留下来的老代码的接口 私人的,闭源的应用(shell 脚本把代码就放在文本文件中,全世界都能看到)

**如果你的应用符合上边的任意一条**** , ****那么就考虑一下更强大的语言吧**** -- ****或许是**** Perl,Python,Ruby, **** 或者是更高层次的编译语言比如 ****C/C++,Java**

#### 二：知识点介绍

**（**** 1 ****）从脚本编写和执行开始 —— 编写用**** vim ****即可，保存为**** filename.sh ****文件即可；执行前需要更改为可执行文件或者**** sh filename.sh ****来执行：**

**1**** ）通常 ****shell**** 脚本以 ****.sh**** 为后缀 **。在编写shell时，** 第一行一定要指明系统需要哪种 ****shell**** 解释用户的 ****shell**** 程序，如： ****#!/bin/sh**** ， ****#!/bin/bash** ，#!/bin/csh，，#!/bin/tcsh和，#!/bin/ksh等。下面的run.sh则指明使用bash执行。 #!bin/bash ls -l 通常，shell脚本会以#!/bin/sh作为默认的shell程序。执行shell的方式有两种：第一种是为shell脚本加上可执行权限并执行，第二种是通过sh命令执行shell脚本，例如执行当前目录下的run.sh脚本，命令如下： //为shell脚本直接加上可执行权限并执行 **chmod 755 run.sh****./run.sh**

2）//通过sh命令执行shell脚本

**sh run.sh** 注意：那为何『 sh shell.sh 』也可以运行呢？ 这是因为 /bin/sh 其实就是 /bin/bash(连结档)，使用 sh shell.sh 亦即告诉系统，我想要直接以 bash 的功能来运行 shell.sh 这个文件内的相关命令的意思，所以此时你的 shell.sh 只要有 r 的权限即可被运行喔！而我们也可以利用 sh 的参数，如 -n 及 -x 来检查与追踪 shell.sh 的语法是否正确呢 sh -x filename.sh 这会执行脚本并显示脚本中所有变量的取值，也可以使用参数-n，它并不执行脚本，只是返回所有的语法错误。 **（**** 2 ****）下面我们从经典的"**** hello world" ****入手，看一看最简单的**** Shell ****脚本的模样**

sudo vim hello.sh:

#!/bin/sh #print hello world in the console window

a="hello world"

echo "Hi, ${a}s"

chmod 755 hello.sh 更改为可执行文件 rwx(4,2,1)

sh hello.sh 或者 ./hello.sh
**（**** 3 ****）**** shell ****里的特殊字符**

和其他编程语言一样，shell里也有特殊字符。常见的有美元符号（$），反斜线（\）和引号。

**1**** ）美元符号**

美元符号表示变量替换，即用其后面指定的变量的值来代替变量。反斜线"\"为转义字符，转义字符告诉shell不要对其后面的那个字符进行特殊处理，只是当做普通字符。

**2**** ）双引号（ ****"**** ）**

由双引号括起来的字符，除$，倒引号（`）和反斜线（\）仍保留其特殊功能外，其余字符均作为普通字符对待。

**3**** ）单引号（ ****'**** ）** 由单引号括起来的字符都作为普通字符出现。

**4**** ）倒引号（ ****`**** ） **** tab ****键上面那个原始字符**

由倒引号括起来的字符串被shell解释为命令行，在执行时，shell会先执行该命令，并以它的标准输出结果取代整个引号部分。

**5)****示例**

示例1的代码及输出如下： #echo "My current directory is `pwd` and logname is $LOGNAME"【双引号中的倒引号和美元符号保持原来的功能】 My current directory is /root and logname is root 示例2的代码及输出如下： #echo "My current directory is `pwd` and logname is \$LOGNAME"【双引号中的转义字符保持原来的功能】 My current directory is /root and logname is $LOGNAME 示例3的代码及输出如下： #echo 'My current directory is `pwd` and logname is $LOGNAME'【单引号里面的内容不变】 My current directory is `pwd`and logname is $LOGNAME

**6**** ）变量**

shell的变量非常类似于JS 和 python，不用声明；但是有一点需要注意，变量和等号（即等号前后无任何空格）如 num=10；但是if [${num} eq 10];then …… fi 这其中的空格必须得有的

**（**** 4 ****）**** shell ****脚本的注释**

shell脚本和其它编程语言一样，也拥有注释。注释方法为在注释行前加#号。 例如以下脚本： #!/bin/sh #Filename: comment.sh #Description：this script explains how to make a comment echo "This script explains how to make a comment "

**创建脚本时，脚本的第一行通常称为**** shbang ****（**** #! ****）行。当脚本启动后，**** UNIX ****内核检查文件的第一行以决定将要执行的程序类型。**

shbang符号（#!）后面的路径是用来解释此脚本的shell位置。要正确使用这个特性，#！必须是文件中最前面的两个字符。如果 文件头部有空格字符或者空白行，则此特性被忽略，该行被解释为普通的注释行。

**(5)****再看 ****sh**** 脚本执行的奥秘**

打开文本编辑器，新建一个文件， **扩展名为**** sh ****（**** sh ****代表**** shell ****），扩展名并不影响脚本执行，见名知意就好** ，如果你用php写shell 脚本，扩展名就用php好了。
输入一些代码：
 #!/bin/bash
 echo "Hello World !"
**"#!"**  **是一个约定的标记，它告诉系统这个脚本需要什么解释器来执行** ，即使用哪一种Shell。echo命令（ **最好用**** $printf "" ****具有更好的可移植性** ）用于向窗口输出文本。
将上面的代码保存为test.sh，并 cd 到相应目录：

**chmod +x ./test.sh #**** 使脚本具有执行权限**
 **./test.sh #**  **执行脚本**
注意， **一定要写成****./test.sh ****，而不是**** test.sh ****。运行其它二进制的程序也一样，直接写**** test.sh ****，**** linux ****系统会去**** PATH ****里寻找有没有叫**** test.**sh的，而只有/bin, /sbin, /usr/bin，/usr/sbin等在PATH里，你的当前目录通常不在PATH里，所以写成test.sh是会找不到命令的，要用./test.sh告诉系统说，就在当前目录找。
通过这种方式运行bash脚本，第一行一定要写对，好让系统查找到正确的解释器。
这里的"系统"，其实就是shell这个应用程序（想象一下Windows Explorer），但我故意写成系统，是方便理解，既然这个系统就是指shell，那么一个使用/bin/sh作为解释器的脚本是不是可以省去第一行呢？是的。

#### 三：体会心得

**（**** 1 ****）简单的说**** shell ****就是一个包含若干行**** Shell ****或者**** Linux ****命令的文件。对于一次编写，多次使用的大量命令，就可以使用单独的文件保存下来，以便日后使用。**
例如：你用c编写一个工程，里面有很多.h文件,.c文件等等，每一次更改你都得需要重新 g++ filenames.c filenames.h -o filenames,过于麻烦，这时就需要编写一个小小shell文件，就可以解决问题了。

**（**** 2 ****）记得自己上次写**** python ****的基础学习，** 应该是一个月前了，这次重新学一个新的语言（脚本语言），间隔的时间非常短；越发的感觉，必须掌握精通一门语言，之后学习其他语言非常容易上手 —— 仅仅是入门，如果想在某一门语言上进阶或者深入，只能说"路漫漫其修远兮亦"！

[编辑于](https://www.zhihu.com/question/28377046/answer/249751575)2017-10-25

a="hello world"

echo "Hi, ${a}. Eric"

#$: character after $ is a varialbe, use its vaule to replace its position

#\: chacter after \ will be treated as normal character without special meanning

#`: character within ` will be interpreted as command

# $ ` \ inside double quote will keep their special functionality

echo "My current directory is `pwd` and logname is $LOGNAME"

# all the character within single quote will be treated as normal characters

echo 'My current directory is `pwd` and logname is $LOGNAME'

#character after \ will be treated as normal character with no special meaning anymore

echo "My current directory is `pwd` and logname is \$LOGNAME"

### Shell脚本编程30分钟入门

[https://github.com/qinjx/30min\_guides/blob/master/shell.md](https://github.com/qinjx/30min_guides/blob/master/shell.md)

1. Variable:

your\_name="qinjx"

echo $your\_name

echo ${your\_name} #{} are optional, just to separate the variable well from the others

for file in `ls /etc`

#!/bin/sh

cd ~

mkdir shell\_tut

cd shell\_tut

for ((i=0; i\<10; i++)); do

touch test\_$i.txt

done

### 重定义变量

已定义的变量，可以被重新定义，如：

your\_name="qinjx"

echo $your\_name

your\_name="alibaba"

echo $your\_name

这样写是合法的，但注意，第二次赋值的时候不能写$your\_name="alibaba"，使用变量的时候才加美元符。

### 多行注释

sh里没有多行注释，只能每一行加一个#号。就像这样：

#--------------------------------------------

# 这是一个自动打ipa的脚本，基于webfrogs的ipa-build书写：https://github.com/webfrogs/xcode\_shell/blob/master/ipa-build

# 功能：自动为etao ios app打包，产出物为14个渠道的ipa包

# 特色：全自动打包，不需要输入任何参数

#--------------------------------------------

##### 用户配置区开始#####

#

#

# 项目根目录，推荐将此脚本放在项目的根目录，这里就不用改了

# 应用名，确保和Xcode里Product下的target\_name.app名字一致

#

##### 用户配置区结束#####

如果在开发过程中，遇到大段的代码需要临时注释起来，过一会儿又取消注释，怎么办呢？每一行加个#符号太费力了，可以把这一段要注释的代码用一对花括号括起来，定义成一个函数，没有地方调用这个函数，这块代码就不会执行，达到了和注释一样的效果。

## Bash shell syntax

[https://www.gnu.org/software/bash/manual/bash.html](https://www.gnu.org/software/bash/manual/bash.html)

a shell is simply a macro processor that executes commands. The term macro processor means functionality where text and symbols are expanded to create larger expressions.

metacharacter

A character that, when unquoted, separates words. A metacharacter is a space, tab, newline, or one of the following characters: '|', '&', ';', '(', ')', '\<', or '\>'.

control operator

A token that performs a control function. It is a newline or one of the following: '||', '&&', '&', ';', ';;', ';&', ';;&', '|', '|&', '(', or ')'.

！# history expansion character.

History expansions are introduced by the appearance of the history expansion character, which is '!' by default

The following is a brief description of the shell's operation when it reads and executes a command. Basically, the shell does the following:

1. Reads its input from a file (see [Shell Scripts](https://www.gnu.org/software/bash/manual/bash.html#Shell-Scripts)), from a string supplied as an argument to the -c invocation option (see [Invoking Bash](https://www.gnu.org/software/bash/manual/bash.html#Invoking-Bash)), or from the user's terminal.
2. Breaks the input into words and operators, obeying the quoting rules described in [Quoting](https://www.gnu.org/software/bash/manual/bash.html#Quoting). These tokens are separated by metacharacters. Alias expansion is performed by this step (see [Aliases](https://www.gnu.org/software/bash/manual/bash.html#Aliases)).
3. Parses the tokens into simple and compound commands (see [Shell Commands](https://www.gnu.org/software/bash/manual/bash.html#Shell-Commands)).
4. Performs the various shell expansions (see [Shell Expansions](https://www.gnu.org/software/bash/manual/bash.html#Shell-Expansions)), breaking the expanded tokens into lists of filenames (see [Filename Expansion](https://www.gnu.org/software/bash/manual/bash.html#Filename-Expansion)) and commands and arguments.
5. Performs any necessary redirections (see [Redirections](https://www.gnu.org/software/bash/manual/bash.html#Redirections)) and removes the redirection operators and their operands from the argument list.
6. Executes the command (see [Executing Commands](https://www.gnu.org/software/bash/manual/bash.html#Executing-Commands)).
7. Optionally waits for the command to complete and collects its exit status (see [Exit Status](https://www.gnu.org/software/bash/manual/bash.html#Exit-Status)).

#### 3.1.2 Quoting

Quoting is used to remove the special meaning of certain characters or words to the shell. Quoting can be used to disable special treatment for special characters, to prevent reserved words from being recognized as such, and to prevent parameter expansion.

Each of the shell metacharacters (see [Definitions](https://www.gnu.org/software/bash/manual/bash.html#Definitions)) has special meaning to the shell and must be quoted if it is to represent itself.

1. \ #escape character 转义字符

 It preserves the literal value of the next character that follows, with the exception of newline. If a \newline pair appears, and the backslash itself is not quoted, the \newline is treated as a line continuation (that is, it is removed from the input stream and effectively ignored).

1. ' #single quote 单引号

Enclosing characters in single quotes (''') preserves the literal value of each character within the quotes. A single quote may not occur between single quotes, even when preceded by a backslash.

The special parameters '\*' and '@' have special meaning when in double quotes (see [Shell Parameter Expansion](https://www.gnu.org/software/bash/manual/bash.html#Shell-Parameter-Expansion)).

1. " # double quote 双引号

Enclosing characters in double quotes ('"') preserves the literal value of all characters within the quotes, with the exception of '$', '`', '\', and, when history expansion is enabled, '!'.

- **Echo "starting program at $(date)"** # date commond will be executed

  1.
### Shell Commands

\<\< linux command line and shell scripting bible\>\>

1. **printenv** # show global environment variables which are usually using uppercase letters.
  1. **echo $HOME** # show the value of a environment variable, refer to the book for more information
  2. **echo $PATH**
  3. **PATH=$PATH:/home/zhai/miniconda/bin** #temporally add a new search directory to the end of PATH variable
  4. **PATH=$PATH:. #** temporally add current directory to the end of PATH variable

1. **env #** show global environment variables
2. **set #** show both global and local variables
3. **user-defined variables** # variables which are created using equal sign and usually use lowercase letters. And they are only available within the same shell process
  1. **my\_variable=Eric**
  2. **echo $my\_variable # if you're doing anything with the variable, use the dollar sign**
  3. **my\_variable1="hello world"** #for a string value with space, it must be quoted within a single or double quote
  4. **export my\_variable # if you're doing anything to the variable, don't use the dollar sign** created a global enrionment variables which are visible from any child processes created by the parent process that sets the variable
  5. **unset my\_variable** # remove an existing environment variable

## Bash Shell scripting

1. Write shell script

#!/bin/bash

# A simple demonstration of variables

# Ryan 30/8/2017

name='Ryan'

echo Hello $name

- the signal (#!) at the beginning of the script is called [shebang](https://en.wikipedia.org/wiki/Shebang_(Unix)) (hashbang/pund-bang). It specify the interpreter directive(声明编译器的路径)
  - #!/bin/sh – Execute the file using the [Bourne shell](https://en.wikipedia.org/wiki/Bourne_shell), or a compatible shell, with path /bin/sh
  - #!/bin/bash – Execute the file using the [Bash shell](https://en.wikipedia.org/wiki/Bash_(Unix_shell)).
  - #!/bin/csh -f – Execute the file using csh, the [C shell](https://en.wikipedia.org/wiki/C_shell), or a compatible shell, and suppress the execution of the user's .cshrcfile on startup
  - #!/usr/bin/perl -T – Execute using [Perl](https://en.wikipedia.org/wiki/Perl) with the option for [taint checks](https://en.wikipedia.org/wiki/Taint_checking)
  - #!/usr/bin/env python – Execute using [Python](https://en.wikipedia.org/wiki/Python_(programming_language)) by looking up the path to the Python interpreter automatically via [env](https://en.wikipedia.org/wiki/Env)
- # signal starts comments
- When we set a variable, we specify it's name, followed directly by an equals sign ( = ) followed directly by the value. (So, no spaces on either side of the = sign.)
- When we refer to a variable, we must place a dollar sign ( $ ) before the variable name.

1. Run shell script
  1. A script must have the execute permission before we may run it (even if we are the owner of the file). For safety reasons, you don't have execute permission by default so you have to add it. A good command to run to ensure your script is set up right is chmod 755 \<script\>.
  2. When we run a script, there are several variables that get set automatically for us. Here are some of them:

$ cat myscript

#!/bin/bash

echo "First arg: $1"

echo "Second arg: $2"

$ ./myscript hello world

First arg: hello

Second arg: world

- **$0** - The name of the script.
- **$1 - $9** - Any command line arguments given to the script. $1 is the first argument, $2 the second and so on.
- **$#** - How many command line arguments were given to the script.
- **$\*** - All of the command line arguments.

1. **\* \* \* \* command to execute** # Cron stands for Command Run ON. It is a mechanism that allows you to tell the system to run certain commands at certain times.

  1. \* \* \* \* \* /bin/myscript.sh # Execute myscript.sh every minute.
  2. 30 3 \* \* 4 /bin/myscript.sh # Execute myscript.sh every Thursday at 3:30am.
  3. crontab -l # To view a list of what tasks you currently have scheduled you may run the following command:
  4. crontab -e # To edit your scheduled tasks, run the following command. It will open up in your default text editor which is normally Vim.

Where the \*'s represent (in order from left to right:

- Minutes (0 - 59)
- Hours (0 - 23)
- Day of Month (1 - 31)
- Months (1 - 12)
- Day of week (0 - 7) (0 and 7 are Sunday)

#### [How do I count all the files recursively through directories](https://unix.stackexchange.com/questions/4105/how-do-i-count-all-the-files-recursively-through-directories)

find . -maxdepth 1 -type d | while read -r dir

do printf "%s:\t" "$dir"; find "$dir" -type f | wc -l; done

# Linux System， Terminals, Commands

## Linux trick

1. **No undo**

The Linux command line does not have an undo feature. Perform destructive actions carefully.

1. **Ctrl+d** # generates an EOF character, sometimes used to end a program
2. **\<Ctrl\> + c** # which is the universal signal for Cancel in Linux.
3. **Crl+r, \<command\>** #search command matched in the input history
  1. **Ctr+r, then typing: egre** #search command started with egrep in history
  2. Ctr+r #once got a match, ctr+r can go over to the next match

1. **History** # print a list of commands along with a numeric index
  1. ! n # refer to a command line n
  2.
2. **. filename** # dot space filename When a script is run using `source' it runs within the existing shell, any variables created or modified by the script will remain available after the script completes **.**
  1. **source filename** # dot is synonym of the builtin source
  2. **. loadmodules #** in loadmodules file: module load HDF5/1.8.16-foss-2.16a

## Linux terminals

### Shell types (Bourne sh, bash, csh, tcsh, ksh,)

terminal is nothing but shell, and Unix provides different flavors of shells:

- Bourne shell (sh)
- C shell (csh)
- TC shell (tcsh)
- Korn shell (ksh)
- Bourne Again shell (bash)

Type below to know the shell type

echo $SHELL or echo $0

1. **echo $SHELL or echo $0** #check the shell type
2. **cat /etc/shells** # check types of shells available
3. **sh or bash** # type in shell name to switch
4. **echo $PATH** #system environment parameter used to searching for executable commands typed in the shell **;** On Linux & Mac systems, the system will first check for an [alias](http://tldp.org/LDP/abs/html/aliases.html) matching the command; if this fails it references the $PATH environment variable:
  1. **export PATH=$PATH:/home/zhai65/python3** # add a new dir into the end of the search path; Permanently change the path setting by adding the same line to your ~/.bashrc file

**3. Basic Linux shell command (Bash shell)**

[https://ryanstutorials.net/linuxtutorial/](https://ryanstutorials.net/linuxtutorial/)

1. source code of the GNU Core Utilities( basic commands)

[http://www.maizure.org/projects/decoded-gnu-coreutils/index.html](http://www.maizure.org/projects/decoded-gnu-coreutils/index.html)

[**鸟哥的****  **](http://cn.linux.vbird.org/linux_basic/linux_basic.php)**Linux  ****私房菜**  **--**  **基础学习篇目录**

## Linux Basic commands

[https://www.youtube.com/watch?v=ZtqBQ68cfJc](https://www.youtube.com/watch?v=ZtqBQ68cfJc) The 50 Most Popular Linux & Terminal Commands

![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_5606694879bcfb61.png)

1. **clear** # clear the screen
  1. **Ctrl+l** #shortkey

1. **who** #list out the users logged on to the system now
2. **which \<command\> #** locate a command. Returns a pathname of the file
  1. **which modulename** /verify the loaded module version
  2. **Which python /- installed versions**
  3. **Which bash #** GNU Bourne-Again SHell
3. **whatis \<command\>** # give a one line description of the command
  1. **man -f \<topic\_name\>** # silmilar to whatis \<topic\_name\> give a one line description of the command
4. **whereis \<command\>** # locate the executable file, source code, and manual pages for a Program
  1. **Whereis -b #only report executable name**
  2. **Whereis -m #only report the location of the manual page**
  3. **Whereis -s #only search for source files**

1. **group \<username \>** # print the groups a user is in
2. **strace \<command\>** #tells us all activities behind the command
3. **apropos \<key\_word\>** # search the manual page names and descriptions
4. **type \<command\>** #tells you the current version/source of command that is active
  1. **which \<command\> #similar**

1. **man \<command to look up\>** # Look up the manual page for a particular command.
  1. man -k \<search term\> # do a keyword search on the Manual pages

          1. /term #search keyword once in the manual page,
          2. n #go to the next searched results
          3. q #exit manual

  1. **man -f \<topic\_name\>** #silmilar to **whatis \<topic\_name\>** give a one line description of the command
1. **info** # to display useful explanation about a system variable
2. **echo** # display/print something

  1. **echo $SHELL** #to display a system variable stating your current shell.
  2. **echo $PATH** # display the default search path of linux os
  3. **echo 'hello world' \> readme**

1. **write \<user\_name\> \<tty\_id\>** #send a message to user working on the system

1. **cd [location]**# Change Directories - ie. move to another directory.
  1. **cd /home/zhai65** #Absolute direcotry reference starting with a forward slash /
  2. **cd Desktop** # relative directory refecnce doesn't start with a forward slash
  3. **cd ../linux\_practise** #
2. **pwd** # printing current working directory. A lot of commands on the terminal will rely on you being in the right location. As you're moving around, it can be easy to lose track of where you are at.

1. **ls [options] [location]**# List the contents of a directory.

  1. ls -F # distinguish files from directories
  2. **ls -FR** # recursively shows files that are contained within subdirectories in the current directories.
  3. Ls -a [path] #list out hidden files
  4. Ls -l [ path #show more infomation
  5. **Ls -- all** #long hand command line options begin with two dashes ( -- ) and short hand options begin with a single dash ( - ).
  6. **Ls -alh** #options combined together
  7. ls /home/ryan/linuxtutorialwork/\*.txt
  8. ls ?i\*
  9. ls \*.???
  10. ls -l [sv]\* # limit to a subset of characters
  11. ls -lhF \*[0-9]\* # include a set by using a hyphen
  12. ls [^a-k]\* # sing the caret ( ^ ) which means look for any character which is not one of the following.
  13. ls -ld # View the permissions for a specific directory.
  14. ls -l –time=atime \<dir/file name\> #show the access time of the file instead of modification time

1. **file [path]** # check the type of file. In other systems such as Windows the extension is important and the system uses it to determine what type of file it is. Under Linux the system actually ignores the extension and looks inside the file to determine what type of file it is.

1. **chown \<newowner\> foo** #used from the root account to change the owner of the file
2. **chgrp \<newgroup\> foo** # used from the file's owner or root account to change the group of the file
3. **chmod [permissions] [path]** #used from the file's owner or root account to change file and directory access permissions. It stands for change file mode bits. change permissions on a file or directory

1. chmod g+x frog.png
2. chmod 751 frog.png #using octal number shorthand 7:111, 5:101, 1:001
3. chmod -R 751 \<folder\> # change files in a folder recursively

- Who are we changing the permission for? [ugoa] - user (or owner), group, others, all
- Are we granting or revoking the permission - indicated with either a plus ( + ) or minus ( - )
- Which permission are we setting? - read ( r ), write ( w ) or execute ( x )

1. **touch [options] \<filename\>**# Creating a Blank File. Touch is actually a command we may use to modify the access and modification times on a file
  1. touch \<filename\> # change the modification time of a file
  2. **touch -a \<filename\>** # only change the access time of the file
2. **mkdir [options] \<Directory\>** # Make Directory - ie. Create a directory.

1. **mkdir /home/ryan/foo**
2. **mkdir -p /home/eric/new\_project/data** # The -p option on the mkdir command makes any missing parent directories as needed
3. **rmdir -p current\_dir/sub\_dir/child-dir #** remove DIRECTORY and its ancestors; e.g., 'rmdir -p a/b/c' is similar to 'rmdir a/b/c a/b a'
4. **mkdir ./blah** #relative path
5. **mkdir ../dir1**
6. **mkdir ~/linuxtutorialwork/dir2**
7. **cd Holiday\ Photos** #file name is case sensitive, use escape character to input space
8. mkdir 'holiday photos' # white paces in file and directory names are perfectly valid but we need to be a little careful with them. As you would remember, a space on the command line is how we seperate items.

1. **rmdir [options] \<Directory\>** #remove **empty** directories- ie. Delete a directory.
2. **rm [options] \<file\>**# Removing a File (and non empty Directories). By default, it does not remove directories.
  1. **rm -i/I**  **#** prompt before every removal. use in combination with r is i which stands for interactive. This option will prompt you before removing each file and directory and give you the option to cancel the command.
  2. **rm -r/-R [dirname]** # remove all files and directory in current directory recursively. When rm is run 'with the -r option it allows us to remove directories and all files and directories contained within.
  3. **rm -d [dirname] #** remove empty directories

1. **read**
  1. read -p "enter a number:" num # read in a value stored in num variable from the standin
2. **cp [options] \<source\> \<destination\>**#Copying a File or Directory. In it's default behaviour cp will only copy a file.

1. **cp -R ~/folder/!(\*.exe) ~/destination\_folder/** #copy all files except files with .exe extension, Using the **-r option** , which stands for recursive, we may copy directories
2. **cp -R ~/folder/!(\*.exe) .** #copy all files except files with .exe extension into current working directory
3. **cp filename1 filename2** #make a copy of filename1 with a new name as filename2

1. **ln** # create a symbolic/hard link to files
  1. **ln -s soure\_file link\_file # created a symbolic(soft) link to source files, when the source file is deleted, the linkfile doesn't work anymore.**
  2. **ln source\_file hard\_linked\_file #** created ( hard link)file is identical to the source file, if it's changed, the source file will be updated as well, verse vasa. When the source file is deleted, the hard\_linked\_file still (function/works) points to the same file.
2. **scp** #secure copy (remote file copy program), copy files to/from a remote machine. It uses ssh(1) for data transfer, and uses the same authentication and provides the same security as ssh(1). Unlike rcp(1), scp will ask for passwords or passphrases if they are needed for authentication.
  1. **scp [[user@]host1:]filename1[[user@]host2:]filename2**# scp temp.ps login.msi.umn.edu:/scratch/temp.ps
3. **mv [options] \<source\> \<destination\>**# Moving a File or Directory . if we specify the destination to be the same directory as the source, but with a different name, then we have effectively used mv to rename a file or directory.
  1. **mv old\_file\_name new\_file\_name** # move/rename a file or folder
4. **locate #** search for files in a directory hierarchy
5. **find #**** search for files in a directory hierarchy**
  1. **find [serch\_dir] -name imec** # find the file by its name starting from the specified directroy
    1. **find . -name "SR\_S5\*" -type f** # list out only files(-type f) matching name "SR\_S5.." in the current directory and subdirectory
    2. **find . -name "CB\_S5\_\*" -type f -exec du -ch {} +** # list out only files(-type f) matching name "SR\_S5.." in the current directory and subdirectory and their corresponding sizes(du -ch, -c: total, -h: human readable)
    3. **find . -name "CB\_S5\_\*" -type f -exec du -ch {} + | grep total$** #this command only show the total size.
  2. **Find . -size +100M** # find files with size larger than 100M
  3. **find [serch\_dir] -atime 1** # find the files accessed one day ago
    1. **find [serch\_dir] -exec** # find the executable files
    2. **find [serch\_dir] -name \*.bin** # find the files ended by .bin
    3. **find [serch\_dir] -maxdepth 1 -type d** # list out all subfolders within a directory
    4. **find [serch\_dir] -maxdepth 1 -type d | wc -l** # count the number of subfolders within a directory
6. locale # displays information about the current locale, or all locales, on standard output.
  1. Locale # show the setting about
    1. 比较和排序习惯(LC\_COLLATE): c.UTF-8 (c for computer)
    2. 语言符号及其分类(LC\_CTYPE)
    3. 信息主要是提示信息,错误信息,状态信息,标题,标签,按钮和菜单等(LC\_MESSAGES)
    4. 货币单位(LC\_MONETARY)
    5. 数字(LC\_NUMERIC)
    6. 时间显示格式(LC\_TIME)
7. Xargs #execute commd lines from standard intput( or pipe) and turn them into arguments that other commands could accept.
  1. Find . -size +1G | xargs ls -al # transfer the standard output from find and give them as arguments to ls, otherwise find . -size +1G | ls -al won't work, because ls don't receive arguments from standard input such as those from pipe.
  2. cat rm\_list.txt | xargs rm # xargs receive the output from cat rm\_list.txt, and hand them over as arguemnts to rm
  3.

### Man(manual) page shortcuts

**Keyboard shortcuts to read**

**/skim through man page in linux/unix system,**

**copied from linux system**

**SUMMARY OF LESS COMMANDS**

Commands marked with \* may be preceded by a number, N.

Notes in parentheses indicate the behavior if N is given.

A key preceded by a caret indicates the Ctrl key; thus ^K is ctrl-K.

h H Display this help.

q :q Q :Q ZZ Exit.

---------------------------------------------------------------------------

#### MOVING

**e ^E j ^N CR \* Forward one line (or N lines).**

**y ^Y k ^K ^P \* Backward one line (or N lines).**

**f ^F ^V SPACE \* Forward one window (or N lines).**

**b ^B ESC-v \* Backward one window (or N lines).**

z \* Forward one window (and set window to N).

w \* Backward one window (and set window to N).

ESC-SPACE \* Forward one window, but don't stop at end-of-file.

d ^D \* Forward one half-window (and set half-window to N).

u ^U \* Backward one half-window (and set half-window to N).

ESC-) RightArrow \* Left one half screen width (or N positions) .

ESC-( LeftArrow \* Right one half screen width (or N positions).

F Forward forever; like "tail -f".

r ^R ^L Repaint screen.

R Repaint screen, discarding buffered input.

---------------------------------------------------

Default "window" is the screen height.

Default "half-window" is half of the screen height.

---------------------------------------------------------------------------

#### SEARCHING

**/pattern \* Search forward for (N-th) matching line.**

**?pattern \* Search backward for (N-th) matching line.**

**&pattern \* Display only matching lines**

n \* Repeat previous search (for N-th occurrence).

N \* Repeat previous search in reverse direction.

ESC-n \* Repeat previous search, spanning files.

ESC-N \* Repeat previous search, reverse dir. & spanning files.

ESC-u Undo (toggle) search highlighting.

---------------------------------------------------

A search pattern may be preceded by one or more of:

^N or ! Search for NON-matching lines.

^E or \* Search multiple files (pass thru END OF FILE).

^F or @ Start search at FIRST file (for /) or last file (for ?).

^K Highlight matches, but don't move (KEEP position).

^R Don't use REGULAR EXPRESSIONS.

---------------------------------------------------------------------------

#### JUMPING

g \< ESC-\< \* Go to first line in file (or line N).

G \> ESC-\> \* Go to last line in file (or line N).

p % \* Go to beginning of file (or N percent into file).

t \* Go to the (N-th) next tag.

T \* Go to the (N-th) previous tag.

{ ( [\* Find close bracket } )].

} ) ] \* Find open bracket { ( [.

ESC-^F \<c1\> \<c2\> \* Find close bracket \<c2\>.

ESC-^B \<c1\> \<c2\> \* Find open bracket \<c1\>

---------------------------------------------------

Each "find close bracket" command goes forward to the close bracket

matching the (N-th) open bracket in the top line.

Each "find open bracket" command goes backward to the open bracket

matching the (N-th) close bracket in the bottom line.

m\<letter\> Mark the current position with \<letter\>.

'\<letter\> Go to a previously marked position.

'' Go to the previous position.

^X^X Same as '.

---------------------------------------------------

A mark is any upper-case or lower-case letter.

Certain marks are predefined:

^ means beginning of the file

$ means end of the file

---------------------------------------------------------------------------

**CHANGING FILES**

:e [file] Examine a new file.

^X^V Same as :e.

:n \* Examine the (N-th) next file from the command line.

:p \* Examine the (N-th) previous file from the command line.

:x \* Examine the first (or N-th) file from the command line.

:d Delete the current file from the command line list.

= ^G :f Print current file name.

---------------------------------------------------------------------------

**MISCELLANEOUS COMMANDS**

-\<flag\> Toggle a command line option [see OPTIONS below].

--\<name\> Toggle a command line option, by name.

\_\<flag\> Display the setting of a command line option.

\_\_\<name\> Display the setting of an option, by name.

+cmd Execute the less cmd each time a new file is examined.

!command Execute the shell command with $SHELL.

|Xcommand Pipe file between current pos & mark X to shell command.

v Edit the current file with $VISUAL or $EDITOR.

V Print version number of "less".

---------------------------------------------------------------------------

**OPTIONS**

Most options may be changed either on the command line,

or from within less by using the - or -- command.

Options may be given in one of two forms: either a single

character preceded by a -, or a name preceded by --.

-? ........ --help

Display help (from command line).

-a ........ --search-skip-screen

Search skips current screen.

-A ........ --SEARCH-SKIP-SCREEN

Search starts just after target line.

-b [N] .... --buffers=[N]

Number of buffers.

-B ........ --auto-buffers

Don't automatically allocate buffers for pipes.

-c ........ --clear-screen

Repaint by clearing rather than scrolling.

-d ........ --dumb

Dumb terminal.

-D [xn.n] . --color=xn.n

Set screen colors. (MS-DOS only)

-e -E .... --quit-at-eof --QUIT-AT-EOF

Quit at end of file.

-f ........ --force

Force open non-regular files.

-F ........ --quit-if-one-screen

Quit if entire file fits on first screen.

-g ........ --hilite-search

Highlight only last match for searches.

-G ........ --HILITE-SEARCH

Don't highlight any matches for searches.

-h [N] .... --max-back-scroll=[N]

Backward scroll limit.

-i ........ --ignore-case

Ignore case in searches that do not contain uppercase.

-I ........ --IGNORE-CASE

Ignore case in all searches.

-j [N] .... --jump-target=[N]

Screen position of target lines.

-J ........ --status-column

Display a status column at left edge of screen.

-k [file] . --lesskey-file=[file]

Use a lesskey file.

-K --quit-on-intr

Exit less in response to ctrl-C.

-L ........ --no-lessopen

Ignore the LESSOPEN environment variable.

-m -M .... --long-prompt --LONG-PROMPT

Set prompt style.

-n -N .... --line-numbers --LINE-NUMBERS

Don't use line numbers.

-o [file] . --log-file=[file]

Copy to log file (standard input only).

-p [pattern] --pattern=[pattern]

Start at pattern (from command line).

-P [prompt] --prompt=[prompt]

Define new prompt.

-q -Q .... --quiet --QUIET --silent --SILENT

Quiet the terminal bell.

-r -R .... --raw-control-chars --RAW-CONTROL-CHARS

Output "raw" control characters.

-s ........ --squeeze-blank-lines

Squeeze multiple blank lines.

-S ........ --chop-long-lines

Chop (truncate) long lines rather than wrapping.

-t [tag] .. --tag=[tag]

Find a tag.

-T [tagsfile] --tag-file=[tagsfile]

Use an alternate tags file.

-u -U .... --underline-special --UNDERLINE-SPECIAL

Change handling of backspaces.

-V ........ --version

Display the version number of "less".

-w ........ --hilite-unread

Highlight first new line after forward-screen.

-W ........ --HILITE-UNREAD

Highlight first new line after any forward movement.

-x [N[,...]] --tabs=[N[,...]]

Set tab stops.

-X ........ --no-init

Don't use termcap init/deinit strings.

-y [N] .... --max-forw-scroll=[N]

Forward scroll limit.

-z [N] .... --window=[N]

Set size of window.

-" [c[c]] . --quotes=[c[c]]

Set shell quote characters.

-~ ........ --tilde

Don't display tildes after end of file.

-# [N] .... --shift=[N]

Horizontal scroll amount (0 = one half screen width)

........ --no-keypad

Don't send termcap keypad init/deinit strings.

........ --follow-name

The F command changes files if the input file is renamed.

---------------------------------------------------------------------------

**LINE EDITING**

These keys can be used to edit text being entered

on the "command line" at the bottom of the screen.

RightArrow ESC-l Move cursor right one character.

LeftArrow ESC-h Move cursor left one character.

ctrl-RightArrow ESC-RightArrow ESC-w Move cursor right one word.

ctrl-LeftArrow ESC-LeftArrow ESC-b Move cursor left one word.

HOME ESC-0 Move cursor to start of line.

END ESC-$ Move cursor to end of line.

BACKSPACE Delete char to left of cursor.

DELETE ESC-x Delete char under cursor.

ctrl-BACKSPACE ESC-BACKSPACE Delete word to left of cursor.

ctrl-DELETE ESC-DELETE ESC-X Delete word under cursor.

ctrl-U ESC (MS-DOS only) Delete entire line.

UpArrow ESC-k Retrieve previous command line.

DownArrow ESC-j Retrieve next command line.

TAB Complete filename & cycle.

SHIFT-TAB ESC-TAB Complete filename & reverse cycle.

ctrl-L Complete filename, list all.

## Piping and redirection

**Piping and redirection** is the means by which we may connect these streams between programs and files to direct data in interesting and useful ways.

Every program we run on the command line automatically has three data streams connected to it.

- STDIN (0) - Standard input (data fed into the program)
- STDOUT (1) - Standard output (data printed by the program, defaults to the terminal)
- STDERR (2) - Standard error (for error messages, also defaults to the terminal

![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_5a734c4fe65bad40.png)

1. **l** # pipe output to a new command
  1. **ls | head -3** #a mechanism for sending data from one program to another. It's called piping and the operator we use is ( | ). What this operator does is feed the output from the program on the left as input to the program on the right.
  2. **ls | head -3 | tail -1**
  3. **ls -l /etc | tail -n +2 | sort** #we are sorting the listing of a directory so that all the directories are listed first.
  4. **ls -l /etc | less** #feed the output of a program into the program less so that we can view it easier.
  5. **ls -l ~ | grep '^.....w'** #Identify all files in your home directory which the group has write permission for.
  6. **ls -l /projects/ghosttrail | tail -n +2 | sed 's/\s\s\*/ /g' | cut -d ' ' -f 3 | sort | uniq -c** #Create a listing of every user which owns a file in a given directory as well as how many files and directories they own.

Only some commands(touch) receive inputs from standard input(etc. pipe), other commands (rm) don't.

1. **\>** #output re-direction, overwrite. Save output to a file.
  1. **nohup ./script\_stingray.sh \>nohup\_stingray.out**
  2. **ls \> myoutput** #The greater than operator ( \> ) indicates to the command line that we wish the programs output (or whatever it sends to STDOUT) to be saved in a file instead of printed to the screen. If we redirect to a file which does not exist, it will be created automatically for us. If we save into a file which already exists, however, then it's contents will be cleared, then the new output saved to it

1. **\>\>**  **#** Append output to a file.
  1. **nohup ./script\_stingray.sh \>\> nohup\_stingray.out**
  2. **ls \>\> myoutput** #We can instead get the new data to be appended to the file by using the double greater than operator ( \>\> ).
2. **\<** #Read input from a file
  1. **parallel --gnu -j 8 ./run\_stingray.sh \<userlist.txt**
  2. **wc -l \< myoutput** # print out the line numbers in myoutput. If we use the less than operator ( \< ) then we can send data the other way. We will read data from the file and feed it into the program via it's STDIN stream. whenever we use redirection or piping, the data is sent anonymously. So in the above example, wc recieved some content to process, but it has no knowledge of where it came from so it may not print this information.
  3. **wc -l \< barry.txt \> myoutput #** output the line numbers of file barry.txt into myoutput file
  4.

1. **2\>** # Redirect error messages.Send the output from one program as input to another program.
  1. **ls -l video.mpg blah.foo 2\> errors.txt** #STDERR is stream number 2 and we may use these numbers to identify the streams. If we place a number before the \> operator then it will redirect that stream (if we don't use a number, like we have been doing so far, then it defaults to stream 1).
  2. **ls -l video.mpg blah.foo \> myoutput 2\>&1** #save both normal output and error messages into a single file. This can be done by redirecting the STDERR stream to the STDOUT stream and redirecting STDOUT to a file. We redirect to a file first then redirect the error stream. We identify the redirection to a stream by placing an & in front of the stream number (otherwise it would redirect to a file called 1).

## Linux intermediate commands

### System admin

1. su # switch user account
2. sudo # root command , to make some system wide change
  1. sudo apt install package-name #
3. **env** # Set each NAME to VALUE in the environment and run COMMAND. shows all the enviornmetal variable used in the current setting of the system
  1. **env | more** # show only one screen
  2. **env |less** # navigate through the available env variables
  3. **env | grep zhai** # show the variable match the key word: zhai

1. **Who** # Show who is logged on and what they are doing.displays information about the users currently on the machine, and their processes. The header shows, in this order, the current time, how long the system has been running, how many users are currently logged on, and the system load averages for the past 1, 5, and 15 minutes.
  1. **uptime #** one line information the same information contained in the header line displayed by w(1).
2. **uptime** #Tell how long the system has been running.gives a one line display of the following information. The current time, how long the system has been running, how many users are currently logged on, and the system load averages for the past 1, 5, and 15 minutes This is the same information contained in the header line displayed by w(1).

1. **groups [user\_name**] #show the group a user belongs to

  1. **getent group** #give you a list of _all_ groups in the same format the /etc/group-file uses.
  2. **getent group | egrep -n 'ichange'** # show all the users within the ichange group

1. **less /proc/cpuinfo** # show the cpu information
2. **less /proc/meminfo # show memory info**
3. **ps** # ps stands for processes. displays information about a selection of the active processes. If you want repetitive update of the selection and the displayed information, use top(1) instead. **Refer to \<linux-command line and shell scripting bible\>**

    - Unix-style parameters, which are preceded by a dash
    - BSD-style parameters, which are not preceded by a dash
    - GNU long parameters, which are preceded by a double dash

  1. **ps** # show you just the processes running in your current terminal (which is usually not very much).
  2. **ps a** # show the process owned by yourself
  3. **ps aux | grep 'firefox'** # If we add the argument aux then it will show a complete system view which is a bit more helpful.
  4. **ps -u [username]**#see process run by user id or username
  5. **ps -fu [username]**#see process run by user id or username
  6. **ps axjf -u [username****]** # print a process tree
  7. **pstree** **-u [username]** #shows running processes by a user as a tree
  8. **ps -ef | grep** \<username\> #show every process on the system used by a specific user
  9. **ps --forest #** display the processes and their relative relationship
1. **top** # top program provides a dynamic real-time view of a running system. # a repetitive update of what process is currently running on the system.a dynamic real-time view of a running system.f
  1. **top -hv|-bcHiOSs -d secs -n max -u|U user -p pid -o fld -w [cols**] #display linux processes,
2. **htop** #interactive processes viewer

1. **killall \<process\_name\> #** End the running of a process by its name
  1. **killall http\*** #kill all processes start with http
2. **kill [signal] \<PID\>** # End the running of a process. **Refer to \<linux-command line and shell scripting bible\>**
  1. **kill -s HUP 8399** #
3. **pkill -u \<username\>** #kill all the process owned by a specific user
  1. **Killall -u \<username\>** #kill all the process owned by a specific user
  2. **Kill $(pgrep -u \<username\>)** #kill all the process owned by a specific user

1. **sleep** # start a process and then run in the background. All sleep does is wait a given number of seconds and then quit.

  1. **sleep 5 &** # put an ampersand ( & ) at the end of the command then we are telling the terminal to run this process in the background.

1. **count &** #Run a unix process in the backgroud. In Unix, a background process executes independently of the shell, leaving the terminal free for other work. To run a process in the background, include an & (an ampersand) at the end of the command you use to run the job. Following are some examples:

  1. **count &** # put an ampersand ( & ) at the end of the command then we are telling the terminal to run this process in the background.
  2. **jobs** # show currently running background processes/jobs for us
  3. **fg** #bring a background process to the foreground

1. **wait #** Suspend script execution until all jobs running in background have terminated, or until the job number or process ID specified as an option terminates. Returns the [exit status](http://tldp.org/LDP/abs/html/exit-status.html#EXITSTATUSREF) of waited-for command.

1. **jobs or jobs -l** # lists currently running background processes/jobs for us# show the id of running background processes/jobs

bash$ **sleep 100 &**

[1] 1384

bash $ **jobs**

[1]+ Running sleep 100 &

1. "1" is the job number (jobs are maintained by the current shell).
2. "1384" is the [PID](http://tldp.org/LDP/abs/html/internalvariables.html#PPIDREF) or process ID number (processes are maintained by the system). To kill this job/process, either a kill %1 or a kill 1384 works.
3. " **+**" is "current" job (last job stopped in foreground or started in background)
4. " **-**" last job

# nohup isub -p wildcat ./script\_minifornax.sh \> nohup\_sting

# [CTRL-Z]

[1]+ Stopped nohup isub -p wildcat ./script\_minifornax.sh \> nohup\_sting

# bg

#jobs

[1]+ Running nohup isub -p wildcat ./script\_minifornax.sh \> nohup\_sting &

1. **ctrl+Z** #suspend a program/job, then execute bg
2. **bg** #Restart a stopped/suspended background process
3. **fg**** [%job\_id]#**bring it to the foreground. When executed without arguments, it will take the most recent background job to the foreground.

  1. **kill pid or kill %job\_number** # kill the job. To kill this job/process, either a  **kill %1**  or a  **kill 1384 ** works.

1. **disown** # Remove job(s) from the shell's table of active jobs.
2. **fg/bg \<job number\>** # The fg command switches a job running in the background into the foreground. The bg command restarts a suspended job, and runs it in the background. If no job number is specified, then the fg or bg command acts upon the currently running job. We can then use a program called fg which stands for foreground to bring background processes into the foreground.

  1. **CTRL + C** # If you press **CTRL + C** , the currently running foreground process will be killed
  2. **CTRL + z** # If you press **CTRL + z** then the currently running foreground process will be paused and moved into the background.

1. **df [option] [file]**# Show information about t **he file system** on which each FILE resides, or all file systems by default. displays the amount of disk space available on the file system containing each file name argument. If no file name is given, the space available on all currently mounted file systems is shown.

  1. **df -h** # show the disk usage statistics in human readable unit
  2. **df -h /\*** # show the disk usage statistics under root directory

1. **du [option] [file]**# measure disk usage of **every files in a certain directory**

  1. **du -h ~/ASSIST\_study** #display the disk usage of files within the folder in human readable unit: B, KB, MB, GB
  2. **du -hs [file/folder]** #-s summary. show the total size of the specified file/directroy
  3. **du -h --max-depth=1 | sort -hr #** show the size of all sub-folders(level 1) in the current directory. The output will be sorted(largest folder on top)

1. **quota** # displays users' disk usage and limits
  1. **quota -us** #u: user, s: human readable size
  2.
2. **free** # Display amount of free and used memory in the system
  1. **free -k #** Display the amount of memory in kilobytes. This is the default.
  2. **free -h #** Show all output fields automatically scaled to shortest three digit unit and display the units of print out. Following units are used.

total used free shared buffers cached

Mem: 47G 45G 2.0G 2.1M 4.8G 24G

-/+ buffers/cache: 15G 31G

Swap: 9.8G 1.5G 8.3G

[https://www.linux.com/blog/5-commands-check-memory-usage-linux](https://www.linux.com/blog/5-commands-check-memory-usage-linux)

  1. **free -h**
1. **mount** # display a list of hard disk devices mounted on the system
2. cat /proc/meminfo # read the /proc/meminfo file to check memory usage

### Package management commands

1. **isub – help** # a script written by Minnesota Supercomputing Institute
  1. **isub -status** /list out the resources status, 'L'=locked, 'F'=free
  2. **isub** #-reserves whatever node is available in whatever node /assign resources to you
  3. **isub -p fat** #the hosts are organized in several pools, which you can select for each isub invocation through a -p \<pool\> argument. There are multiple pools, mentioned in the table of machines at the top of the page (e.g. "lynx", "fat", "mic", "wildcat"). The ly-x-yy cluster nodes are in the "lynx" pool (default).
  4. **Isub -status -p wildcat (or lynx)** #- check the occupation of host in different pool
  5. **Isub -n 4** #- 4 nodes at the same time set number of hosts to allocate The default walltime, cores, and memory that isub will request can be modified with command-line options.
  6. **Ctrl-d** #To deallocate the host(s) simply exit the interactive session.
  7. **isub -n nodes=1:ppn=4 -m 8GB** # request 8GB of memory (in one node and 4 processors).By default isub on the reserved interactive nodes requests 2GB of memory, one processor core, and two hours of connectivity. If you need more than these, be sure to specify them when launching isub.
  8. **isub -n nodes=1:ppn=4 -m 16GB -w 24:00:00** # This command requests 16 GB of memory and wall clock execution time of 24 hours.
  9.
2. **module [options] sub-command [args ...]**_/load the module into the user's cluster note_
  1. **module -h**
  2. _ **module load/add/unload/del modulenameversion** _ _/load/unload the module into the user's cluster note_
  3. _ **module unload octave** _ _/_ [http://lmod.readthedocs.io/en/latest/015\_writing\_modules.html](http://lmod.readthedocs.io/en/latest/015_writing_modules.html)
  4. _ **module list** _ _/list out all the loaded modules._
  5. **module help** _/_get a list of all the commands that module knows about
  6. **module avail** /check available modules/softwares
  7. **module spider** _ **modulename** _ _/list specification for this module name_
3. **apt** #(Advanced Package Tool) is the command-line tool for handling packages. In debian based linux system
  1. **apt list –installed** #display the installed packages on the systems
  2. **apt list –installed \>./home/installed\_packages.txt** #output the installed packages on the systems
  3. **apt-get # more low-level command options**
  4. **apt-cache #**
4. **aptitude #** a interactive program for package management in debian based linux system
  1. **aptitude show package\_name #**
  2. **aptitude search package\_name #**
  3. **aptitude install package\_naem #**
5. **dpkg** #package manager for Debian. A tool to install, build, remove and manage debian packages.
  1. **dpkg -l** #list all packages with short description
  2. **dpkg -L package\_name #** #list all packages associated with a particular software package
  3. **dpkg --search absolute\_file\_name #** find out what the specific file belongs to which package name
6. yum # red hat and Fedora system

### Virtual session uninterruptable

#### 1. Multitask & co-processing in bash shell

1. **pwd ; ls ; cd /etc** ; #multiple command can put in one sentence and seperated by semicolon to create a command list
  1. ( **pwd ; ls ; cd /etc** ;) # a process list, which creates a subshell to execute the commands
  2. { **pwd ; ls ; cd /etc** ;} # another command group which will not create subshells.
  3. **(tar -cf eric.tar /home/eric ; tar -cf data.tar ~/data) &**
2. **long-running-command &** # Add & after a shell script will put it run in the background

  1. **jobs** #show programs/jobs running in the background
  2. **fg**** [%job\_id]#**bring it to the foreground

# nohup isub -p wildcat ./script\_minifornax.sh \> nohup\_sting

# [CTRL-Z]

[1]+ Stopped nohup isub -p wildcat ./script\_minifornax.sh \> nohup\_sting

# bg

#jobs

[1]+ Running nohup isub -p wildcat ./script\_minifornax.sh \> nohup\_sting &

  1. **ctrl+Z** #suspend a program/job, then execute bg to restart the job in the background
  2. **bg** #Restart a stopped/suspended background process , and run it in the background
  3. **fg %job\_id #** bring the specified background job into the foreground

1. coproc # Co-processing performs almost identically to putting a command in background mode, except for the fact that it creates a subshell.
  1. coproc job\_name { command 1 ; command 2 ; } # create a job running in the background of a subshell
  2. Jobs # check background jobs/commands
2. cop

#### Screen

[https://www.tecmint.com/screen-command-examples-to-manage-linux-terminals/](https://www.tecmint.com/screen-command-examples-to-manage-linux-terminals/)

/ a program gives you virtual window(agent) to do jobs without interference and interruption

1. **Screen [-L]**#enter the screen or log all the commands you do in the screen session
  1. **Screen -h** # show the usage of the screen command
  2. **Screen -L** # log the output into file 'screenlog.n'
  3. **screen -S session\_name** # create a new screen session named by session\_name
  4. **screen -L -Logfile logfile\_name\_to\_be\_used command\_to\_be\_executed** # -Logfile file : By default logfile name is "screenlog.0". You can set new logfile name with the "-Logfile" option.
  5. **Ctrl-a and ?** # ctr-A-shift-?/ see all commands or parameters on screen
  6. **Space-bar or enter** # exit help screen
  7. **Ctrl-a and x** #lock your screen, use your linux password to reenter
2. Enter and detach from a screen program
  1. **Echo $STY** #check whether in a screen or not. If yes, it gives t
  2. **Ctrl-a and d** #detach from the screen, jobs will still run on that detached screen even you log off from the sever
  3. **Ctrl-d** #quit and terminate the screen
  4. **Ctrl-a and "K"** # kill the screen
  5. **Screen -d** #detach a session
3. **Screen -list /-ls** #list out active screen sessions

pungki@mint ~ $ screen -ls

There are screens on:

**7849.pts-0.mint** (10/06/2013 01:50:45 PM) (Detached)

5561.pts-0.mint (10/06/2013 11:12:05 AM) (Detached)

2 Sockets in /var/run/screen/S-pungk

  1.

1. **Screen -r \<session id\>** #reattach to one of the seesions
  1. **Screen -r 7849 #** reattach to one specified screen
2. **Nested screen** #create a new screen within the current screen
  1. **Ctrl-a and c** #create a new screen
  2. **Ctrl-a and n** #move to the next screen
  3. **Ctrl-a and p** #move to the previous screen
3. Multiple screen
4. To write the entire contents of the scrollback buffer to a file, type
  1. Ctrl + A and : to get to command mode, then
  2. hardcopy -h \<filename\>
5.

#### 3.Tmux

multiplex several virtual consoles, allowing a user to access multiple separate terminal sessions inside a single terminal window or remote terminal session. A terminal multiplexer can run a command in a separate session, detached from the current terminal, which means that if the current session ends, the detached session and its associated processes keeps running. One can then reattach to the session later on.Its function is quite similiar to screen.

1. **tmux** # create a session that you can detach and re-attach later on
  1. **tmux new**
  2. **tmux new -s [session-name]** #create a new session
2. show created sessions
  1. **Ctrl-b s** #
  2. **Tmux ls**
3. **Tmux a** # connect to the first available session
  1. **Tmux a -t \<session-name\>** #attach to a specific session
4. **Tmux detach** #detach from a session
  1. **Ctrl-b d** #detach from a session
  2. **Ctrl-b** & #kill the current session
  3. **Tmux kill-session -t** \<session-name\> #killing a session

#### 4.Nohup

nohup is a POSIX command to ignore the HUP (hangup) signal. Run a Command or Shell-Script Even after You Logout

1. **nohup command-with-options &** # put an ampersand ( & ) at the end of the command then we are telling the terminal to run this process in the background.
  1. **nohup sh custom-script.sh &** # run the script.sh through sh program

# Linux File system

1.
## basic file structure

Unix/Linus systems convention

Root directory: / #根目录

zhai65@lynx:/$ pwd

/

zhai65@lynx:/$ ls -a #根目录文件夹

. boot dev home-old lib libnss3.so mnt proc sbin sys var

.. bulk etc initrd.img lib32 lost+found newopt root scratch tmp vmlinuz

bin data home initrd.img.old lib64 media opt(installed packages) run srv usr vmlinuz.old

![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_4317ea1e5e007a28.png)

A Unix filesystem tree

1. cat /etc/passwd
2. ls -F /bin #common and basic built-in shell commands, like bash, cd, history # can run itself, don't need a child process
  1. type bash
  2. which bash
  3.
3. ls -F /usr/bin # external commands which run as a child process within another process
4. ls -l /bin/bash
5. ls-lF /bin/csh
6. ls -lF /bib/tcsh

1.
## import folders/files

1. **/proc/** # store the basics infomation about the system(cpu, memory, pid, etc.
  1. **/proc/cpuinfo** # info about cpu
  2. **/proc/meminfo** # info about memory
  3. Linux implementation includes a directory for each running process, including [kernel](https://en.wikipedia.org/wiki/Kernel_(computer_science)) processes, in directories named /proc/PID, where PID is the process number. Each directory contains information about one process, including:
    1. /proc/PID/cmdline, the command that originally started the process.
    2. /proc/PID/cwd, a [symlink](https://en.wikipedia.org/wiki/Symlink) to the [current working directory](https://en.wikipedia.org/wiki/Working_directory) of the process.
    3. /proc/PID/environ contains the names and values of the environment variables that affe
2. fdf

1.
## ect

1.
## Everything is a File.

**Absolute paths** specify a location (file or directory) in relation to the root directory. You can identify them easily as they always begin with a forward slash ( / ); /home/zhai65/pyth

**Relative paths** specify a location (file or directory) in relation to where we currently are in the system. They will not begin with a slash. ~/python; ./textfile; ../work;

**Linux is an Extensionless System.** The dot has no special meaning as a separator, and extensions can be any length. But in practice, users can still use extension to indicate the file types for themselves, such as .txt, .c(C program source file), .a(archive file/library), .tar(tar archive), .gz/.tgz

**Hidden files/directories** : Filenames that begin with a period are treated specially by the shell: wildcards won't match them unless you include the period (like .\*). The ls command, which lists your files, ignores files whose names begin with a period unless you give it a special option (ls -a )

1.
## File access permission

Linux permissions dictate 3 things you may do with a file, read, write and execute. They are referred to in Linux by a single letter each.

- **r** read - you may view the contents of the file.
- **w** write - you may change the contents of the file.
- **x** execute - you may execute or run the file if it is a program or script.

1. For the file, each corresponding permission allows following actions.

- The read (r) permission allows owner to examine contents of the file.
- The write (w) permission allows owner to modify the file.
- The execute (x) permission allows owner to run the file as a command.

1. For the directory, each corresponding permission allows following actions.

- The read (r) permission allows owner to list contents of the directory.
- The write (w) permission allows owner to add or remove files in the directory.
- The execute (x) permission allows owner to access files in the directory.

For every file we define 3 sets of people for whom we may specify permissions.

- **owner** - a single person who owns the file. (typically the person who created the file but ownership may be granted to some one else by certain users)
- **group** - every file belongs to a single group.
- **others** - everyone else who is not in the group or the owner.

1. drwxrwxr-x 4 zhai65 zhai65 4.0K Aug 29 21:18 ASSIST\_project
2. -rw-r--r-- 1 zhai65 zhai65 0 Aug 29 20:05 typescript

In the above example the first 10 characters of the output are what we look at to identify permissions.

1. The first character identifies the file type. If it is a dash ( - ) then it is a normal file. If it is a d then it is a directory.
2. The following 3 characters represent the permissions for the owner. A letter represents the presence of a permission and a dash ( - ) represents the absence of a permission. In this example the owner has all permissions (read, write and execute).
3. The following 3 characters represent the permissions for the group. In this example the group has the ability to read but not write or execute. Note that the order of permissions is always read, then write then execute.
4. Finally the last 3 characters represent the permissions for others (or everyone else). In this example they have the execute permission and nothing else.
5. Number of hard links to the file
6. Name of the user who owns the file
7. Name of the group which the file belongs to
8. Size of the file in characters (bytes)
9. Date and time of the file (mtime)
10. Name of the file

1. Set user ID, set group ID, sticky bit

In addition to the basic permissions discussed above, there are also three bits of information defined for files in Linux:

[http://www.zzee.com/solutions/linux-permissions.shtml](http://www.zzee.com/solutions/linux-permissions.shtml)

[https://evolt.org/node/263](https://evolt.org/node/263)

- **SUID or setuid: change user ID on execution**. If setuid bit is set, when the file will be executed by a user, the process will have the same rights as the owner of the file being executed.
- **SGID or setgid: change group ID on execution**. Same as above, but inherits rights of the group of the owner of the file on execution. For directories it also may mean that when a new file is created in the directory it will inherit the group of the directory (and not of the user who created the file).
- **Sticky bit**. It was used to trigger process to "stick" in memory after it is finished, now this usage is obsolete. Currently its use is system dependant and it is mostly used to suppress deletion of the files that belong to other users in the folder where you have "write" access to.

# Linux Tools

## Vi vim emacs Text Edito & Processing:

Edit and view text document:

基本上vi 共分为三种模式，分别是『一般模式』、『编辑模式』与『指令列命令模式』。这三种模式的作用分别是：[http://cn.linux.vbird.org/linux\_basic/0310vi.php](http://cn.linux.vbird.org/linux_basic/0310vi.php)

- **一般模式** ：
以vi 打开一个档案就直接进入一般模式了(这是默认的模式)。在这个模式中，你可以使用『上下左右』按键来移动光标，你可以使用『删除字符』或『删除整行』来处理档案内容，也可以使用『复制、贴上』来处理你的文件数据。
- **编辑模式** ：
在一般模式中可以进行删除、复制、贴上等等的动作，但是却无法编辑文件内容的！要等到你按下『i, I, o, O, a, A, r, R』等任何一个字母之后才会进入编辑模式。注意了！通常在Linux 中，按下这些按键时，在画面的左下方会出现『 INSERT 或REPLACE 』的字样，此时才可以进行编辑。而如果要回到一般模式时，则必须要按下『 **Esc** 』这个按键即可退出编辑模式。
- **指令列命令模式** ：
在一般模式当中，输入『 : / ? 』三个中的任何一个按钮，就可以将光标移动到最底下那一行。在这个模式当中，可以提供你『搜寻资料』的动作，而读取、存盘、大量取代字符、离开vi 、显示行号等等的动作则是在此模式中达成的！

简单的说，我们可以将这三个模式想成底下的图标来表示：

![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_341bddfaa839bb2f.gif)
图2.1、vi 三种模式的相互关系

Copy, cut and paste[https://vim.fandom.com/wiki/Copy,\_cut\_and\_paste](https://vim.fandom.com/wiki/Copy,_cut_and_paste)

Here is how to cut-and-paste or copy-and-paste text using a visual selection in Vim. See [Cut/copy and paste using visual selection](https://vim.fandom.com/wiki/Cut/copy_and_paste_using_visual_selection) for the main article.

**Cut and paste:**

1. Position the cursor where you want to begin cutting.
2. Press v to select characters, or uppercase V to select whole lines, or Ctrl-v to select rectangular blocks (use Ctrl-q if Ctrl-v is mapped to paste).
3. Move the cursor to the end of what you want to cut.
4. Press d to cut (or y to copy).
5. Move to where you would like to paste.
6. Press P to paste before the cursor, or p to paste after.

**Copy and paste**  is performed with the same steps except for step 4 where you would press y instead of d:

- d stands for _delete_ in Vim, which in other editors is usually called _cut_
- y stands for _yank_ in Vim, which in other editors is usually called _copy_

1. **Nano** # a simple editor
2. **vim \<file\>** # enhanced version of vi, Vi IMproved. a command line text editor. It's a single window with text input and output. It only has two modes**: normal (shortkey esc**), **insert (shortkey** **i)**.
3. **vi \<file\>** # edit a file. a command line text editor. It's a single window with text input and output. It only has two modes: normal mode (shortkey esc), insert (shortkey i).
  1. **normal mode** # the default mode.

    1. **x** # delete a single character
      1. **nx** # delete n characters (eg 5x deletes five characters)
    2. **dw** # delete the word at the current cursor postion
      1. **dn -** d followed by a movement command. Delete to where the movement command would have taken you. (eg d5w means delete 5 words)
      2. **dd** #delete the line at the current cursor postion
    3. **p** # past the deleted text into current cursor position
    4. **u** # Undo the last action (you may keep pressing u to keep undoing)
      1. **U** (Note: capital) - Undo all changes to the current line
    5. **v** # select the text you want to copy, then move the cursor to where you what to edit, then press either x or y to cut or copy.
    6. **y** # paste the text into the current position
    7. Arrow keys - move the cursor around
    8. j, k, h, l - move the cursor down, up, left and right (similar to the arrow keys)
    9. **^ (caret**) - move cursor to beginning of current line
    10. **$** - move cursor to end of the current line
    11. **G** - move to the last line
      1. **nG** - move to the nth line (eg 5G moves to 5th line)
    12. **w** - move to the beginning of the next word
      1. nw - move forward n word (eg 2w moves two words forwards)
    13. **b** - move to the beginning of the previous word
      1. nb - move back n word
    14. { - move backward one paragraph
    15. } - move forward one paragraph

  1. **Command mode** # u when enter any of these three signs :, /, ? under normal mode, it will enter command mode.

1. **ZZ** (Note: capitals) - Save and exit
2. **:** # open interactive command line input
3. **:q!** - discard all changes, since the last save, and exit
4. **:w** - save file but don't exit
5. **:wq** - again, save and exit
6. **:set nu** # it will enable line numbers

Any command beginning with a colon ( : ) requires you to hit \<enter\> to complete the command. Several of them also allow us to precede them with a number to move that many times.

  1. **Editorial mode #** when type i, o or a under normal mode, it will switch to edit mode

Most commands within vi are executed as soon as you press a sequence of keys.

### Emacs

1. **Emacs** #document display editor(GUI) [https://www.gnu.org/software/emacs/tour/#header](https://www.gnu.org/software/emacs/tour/#header)
  1. **Ctrl-h r or Ctrl-h t** #start turorial in Emacs
  2. **Ctrl-x ctrl-s** #save a file
  3. **Ctrl-/** #undo
2. **cat \<file\>** # view a file. actually stands for concatenate. It's main purpose is to join files together but in it's most basic form it is useful for just viewing files. It's suitable for a small file to view
  1. **cat -n \<file\>** #toggle the line number in the file
  2. **cat -n \<file\>** #only toggle line number for non-empty lines

1. **more** # a filter for paging through text one screenful at a time. Similar to less
2. **less \<file\>** # better suited for larger files , less allows you to move up and down within a file using the arrow keys.
  1. **SpaceBar** #You may go forward a whole page using the SpaceBar or back a page by pressing
  2. **b** #You may go back a whole page by using b
  3. **q** #When you are done you can press q for quit.
3. **head [-number of lines to print] [path]**#prints the first so many lines of it's input. By default it will print the first 10 lines
  1. head -n 4 mysampledata.txt
  2. head -4 mysampledata.txt # same with the above
4. **tail [-number of lines to print] [path]**#prints the last so many lines of it's input. By default it will print the last 10 lines
  1. **tail -n 20 [path/filename] # show the last 20 lines in the file**
  2. **tail -20 [path/filename] #**

1. **sort [-options] [path]**# sort lines of text files. Write sorted concatenation of all FILE(s) to standard output. By default it will sort alphabetically but there are many options available to modify the sorting mechanism.

  1. **Sort -n \<file/directory\>** # sort by number
  2. **sort -t ':' -k 3 -n /etc/passwd** # sort contents based on the 3rd filed seperated by : in the /etc/passwd file
  3. **du -h --max-depth=1 | sort -hr** # show the size of all sub-folders(level 1) in the current directory. The output will be sorted(largest folder on top)

1. **nl [-options] [path]** #number lines

  1. **nl -s '. ' -w 10 mysampledata.txt** #The first one -s specifies what should be printed after the number while the second one -w specifies how much padding to put before the numbers

1. **wc [-options] [path]**# **word count** and it does just that (as well as characters and lines. By default it will give a count of all 3 but using command line options we may limit it to just what we are after.

  1. **wc -l mysampledata.txt** #-l will give us lines only, -w will give us words and -m will give us characters.
  2. **wc -lw mysampledata.txt** # line and word

1. **cut [-options] [path]** #a nice little program to use if your content is separated into fields (columns) and you only want certain fields. cut defaults to using the TAB character as a separator to identify fields. In our file we have used a single space instead so we need to tell cut to use that instead. this is what the -d option does (we include the space within single quotes so it knows this is part of the argument). The -f option allows us to specify which field or fields we would like.

  1. **cut -f 1,2 -d ' ' mysampledata.txt**

1. **sed \<expression\> [path]**#Stream Editor and it effectively allows us to do a search and replace on our data. A basic expression is of the following format:

  1. sed 's/oranges/bananas/g' mysampledata.txt

s/search/replace/g #The initial s stands for substitute and specifies the action to perform (there are others but for now we'll keep it simple). Then between the first and second slashes ( / ) we place what it is we are searching for. Then between the second and third slashes, what it is we wish to replace it with. The g at the end stands for global and is optional. If we omit it then it will only replace the first instance of search on each line. With the g option we will replace every instance of search that is on each line.

1. **uniq [options] [path]**#remove duplicate lines from the data One limitation however is that those lines must be adjacent (ie, one after the other)
2. **tac [path]**#The program tac is actually cat in reverse. It was named this as it does the opposite of cat. Given data it will print the last line first, through to the first line.
3. **tar** # stores and extracts files from a tape or disk archive.
  1. **tar -cvf \<file.tar\> \<dir\_name\>** # -c: create a new tar archive file, -v list files as they are processed, -f output resutls into file
  2. **tar -cvf test.tar data/ data1** / # create an archive file called test.tar containing the contents of both the data directory and the data1 directory,
  3. **tar -tf test.tar** # list but doesn't extract the contents of the tar file test.tar
  4. **tar -xvf text.tar** # extracts the contents of the tar file test.tar

# Parallel computing

1. **parallel [options] [command [arguments]] \< list\_of\_arguments** # build and execute shell command lines from standard input in parallel. GNU parallel is a shell tool for executing jobs in parallel using one or more computers
  1. **parallel --gnu -j 8 ./run\_stingray.sh \<userlist.txt** # -j 8 :8 jobs in parallel when run the script ./run\_stingray.sh with then content in userlist.txt as input.
2.

# Exascience tutorial

[Linux computer servers (imec policy)](https://imec.service-now.com/sp/?id=kb_article_view&sys_kb_id=5313a3424fc1e7c0966e7d918110c7bc)

There are several compute servers within imec. Make sure you read read this to find the right one

Which Linux Compute Servers should I use?

In general, you should only use the servers of your own division or group. There is however no publicly available list that specifies which servers belong to which groups.

Within STS, over 100 servers are grouped in a batch-processing cluster. You can find more information about this [here](https://imecwww.imec.be/~wikimec/SGE).

If you're not sure on which server to use, contact the Linux key-users within your division or group:

- **STS** : Geoffrey Pourtois, Jeroen Van de Kerkhove
- **ICLINK** : Stat Verhaege
- **SE** : Eddy De Greef

[Imec unixwiki:](https://imecwww.imec.be/~wikimec/UNIX)

**Tutorial for imec linux server**

1. **Login:** Using Putty for ssh connections, download and install Putty

1. Via putty,

Host name: login01 with port:22

##Run in the console, establish the connection using imec pc credentials

## after login to imex linux server, you can use the following command to connect with exascience cluster

ssh [zhai65@lab.exascience.com](mailto:zhai65@lab.exascience.com) -p 22

![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_48db016b0a2bf84d.png)

**Tutorial for exascience cluster**

[https://wiki.exascience.org/](https://wiki.exascience.org/)

**Login basics :**

1. Download and install openVPN (on windows): search and download from the internet

Copy your cluster credentials to its config folder

Start as administrator

Only internet explorer is working. [https://wiki.exascience.org/](https://wiki.exascience.org/)

Ssh-keygen

1. **Login:** Using Putty for ssh connections, download and install Putty

Winscp for transferring

1. Via putty,

Host name: wiki.exascience.org with port:22

/Run in the console, establish the connection

1. Via bash console/git console

\>ssh [zhai65@lynx.exascience.org](mailto:zhai65@lynx.exascience.org) -p 22 / first, login through head node

\> ssh [zhai65@lab.exascience.com](mailto:zhai65@lab.exascience.com) -p 22 / it also works

1. **fileZilla:** login to a lynx node:

host: ly-2-05.exascience.org #specify a node

protocol: STFP – SSH File Transfer Protocol

logon Type: Normal

user: zhai

Password:

1.   **Foss:** free and open source software

Intel: may run faster

Versions may be chosen

1. Cygwin

ssh [zhai65@lynx.exascience.org](mailto:zhai65@lynx.exascience.org)

password

**Command:**

1. **man \<module\>** #look for the manual page for usage of the command
2. **isub – help**  **#** a script written by [Minnesota Supercomputing Institute](https://www.msi.umn.edu/content/interactive-queue-use-isub)
  1. **isub** #-reserves whatver node is available in whatever node/assign resources to you
  2. **isub -p fat/lynx/mic/wildcat** # second, choose one server pool from these four, allocate a node to your task. #the hosts are organized in several pools, which you can select for each isub invocation through a -p \<pool\> argument. There are multiple pools, mentioned in the table of machines at the top of the page (e.g. "lynx", "fat", "mic", "wildcat"). The ly-x-yy cluster nodes are in the "lynx" pool (default).
  3. **isub -status** #report host allocation status list out the resources status, 'L'=locked, 'F'=free
  4. **isub -status -p wildcat (or lynx)** #- check the occupation of host in different pool
  5. **isub -n 4** #- 4 nodes at the same time
  6. **isub -n**  **#** set number of hosts to allocate The default walltime, cores, and memory that isub will request can be modified with command-line options.
  7. **isub -n nodes=1:ppn=4 -m 8GB**  **#** request 8GB of memory (in one node and 4 processors).By default isub on the reserved interactive nodes requests 2GB of memory, one processor core, and two hours of connectivity. If you need more than these, be sure to specify them when launching isub.
  8. **isub -n nodes=1:ppn=4 -m 16GB -w 24:00:00 #** This command requests 16 GB of memory and wall clock execution time of 24 hours.
  9. **Ctrl-d** #To deallocate the host(s) simply exit the interactive session.

We are using the Lmod [[1]](https://www.tacc.utexas.edu/research-development/tacc-projects/lmod) module system. Documentation is avail at [[2]](http://lmod.readthedocs.org/). For example:

1. **module [options] sub-command [args ...]**_/load the module into the user's cluster note_
  1. **module -h**
  2. **module load/add/unload/del modulenameversion** _# /load/unload the module into the user's cluster note_
  3. **module unload octave** _/_ [http://lmod.readthedocs.io/en/latest/015\_writing\_modules.html](http://lmod.readthedocs.io/en/latest/015_writing_modules.html)
  4. **module list** #/list out all the loaded modules_._
  5. **module help** # /get a list of all the commands that module knows about
  6. **module avail**** [softwarename]** #/check available modules/softwares
  7. **module spider modulename** _# /list specification for this module name_

## GUI connection

/X Forwarding in Windows using Putty and Xming for graphic user interface

[https://virtualizationreview.com/articles/2017/02/08/graphical-programs-on-windows-subsystem-on-linux.aspx](https://virtualizationreview.com/articles/2017/02/08/graphical-programs-on-windows-subsystem-on-linux.aspx)

**option 1: putty and xming:**

1. **install Xming on windows, open Xming, configure Putty and log on to the remote linux server through Xming** # [http://www.cs.umd.edu/~nelson/classes/utilities/xforwarding.shtml](http://www.cs.umd.edu/~nelson/classes/utilities/xforwarding.shtml)
  1. **jupyter notebook** # input the command in the remote linux shell(putty to login the remote server), it will open the notebook in the Xming window locally. (not recommended approach as xming rendering is super slow compared to this command jupyter notebook –ip="lx-00-01")
2. **xterm &** # x terminal emulator. start standard terminal emulator for the X Window System.

**option 2: vnc server(remote linux) and VNC viewer(on local Windows):**

VNC (Virtual Network Computing) is a very useful network graphics protocol (applications running on one computer but displaying their windows on another) in the spirit of X, however, unlike X, the viewing-end is very simple and maintains no state. It is a remote framebuffer (RFB) protocol.[http://www.karlrunge.com/x11vnc/](http://www.karlrunge.com/x11vnc/)

Create a virtual graphical desktop using vnc server on the remote cluster and then access it through a vnc viewer running on local PC: [https://www.tightvnc.com/vncserver.1.php](https://www.tightvnc.com/vncserver.1.php)

1. **vncserver -list** #
  1. vncserver -kill:session\_number #
2. **tightvncserver & # create a virtual graphical desktop** (Virtual Network Computing(VNC))  which can be accessed through vnc viewer running on the local pc. With TightVNC, you can  **see the desktop of a remote machine and control it**  with your local mouse and keyboard, just like you would do it sitting in the front of that computer.
  1. **Tightvncserver #** Start tightvncserver directly in the console of Exascicence cluster( without allocation a node),it will then shows something like " nex 'X' desktop is lynx:1"
  2. **Lynx.exascience.org:port\_numver** # replace the port\_numer with the one shown in the exascience console.
3. ![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_173dc4b2705636d1.png)

## Use Jupyter on remote cluster

1. **Login on to the cluster, subscribe for a node using isub**
  1. **zhai65@lynx:~$ isub**
  2. **zhai65@ly-2-03:~$ jupyter notebook --ip="ly-2-03"**
2. **copy the url onto the browser of local PC.**
3.

## accessing the ipython notebook running the cluster locally

1. **Login on to the cluster, subscribe for a node using isub**
  1. **zhai65@lynx:~$ isub**
  2. **zhai65@ly-2-03:~$ jupyter notebook --ip="ly-2-03"**
2. **copy the url onto the browser of local PC.**

[https://coderwall.com/p/ohk6cg/remote-access-to-ipython-notebooks-via-ssh](https://coderwall.com/p/ohk6cg/remote-access-to-ipython-notebooks-via-ssh)

1. **zhai65@lynx:~$ jupyter notebook --no-browser --port=8890** # start the ipython notebook server on the remote cluster with port no.=8889. It doen't work on the lynx node.
  1. **zhai65@ly-2-00:~$ jupyter notebook #** start the jupyter server on one of the note in the cluster, so that it can access dataset in /lustre/projects.. directory
2. **ssh -N -f -L localhost:8891:localhost:8890** [zhai65@lynx.exascience.org](mailto:zhai65@lynx.exascience.org) **#** ssh(cygwin) forward the ipython notebook server running on the cluster to the localhost:8891
  1. **ssh -N -f -L localhost:8889:localhost:8888 zhai65@ly-2-00 #**
3. **localhost:8891** #put the command in the local browser

1. **another way through putty(not working yet)**

[https://stackoverflow.com/questions/46276612/remote-access-jupyter-notebook-from-windows](https://stackoverflow.com/questions/46276612/remote-access-jupyter-notebook-from-windows)

## System overview

[Pretty pictures](https://wiki.exascience.org/w/Lynx_Hardware_and_Sysadmin#Pictures)

| **host** | **type** | **CPU** | **RAM** | **Disk space** | **isub pool** | **comment** |
| --- | --- | --- | --- | --- | --- | --- |
| lynx.exascience.org | DL360G7 storage node | 2 socket, 4 core [E5620](http://ark.intel.com/products/47925) @ 2.40GHz | 48 GB | 12 TB | none (headnode) | 2 cpu\*4 core = 8 processors |
| wt-x-yy.exascience.org
 x = [1:2], yy = [00:27,00:03] | Wildcat Pass Black
 (32 nodes) | 2 socket, 18 core [E5-2699 v3](http://ark.intel.com/products/81061/Intel-Xeon-Processor-E5-2699-v3-45M-Cache-2_30-GHz) (Haswell-EP) @ 2.3 GHz, HT | 256 GB | 2x400GB SSD, 2x4TB SATA (in Cephfs filesystem) | wildcat | 2 cpu\*18 core \*2 hyperthreadding = 72 processors |
| ly-x-yy.exascience.org
 x = [1:2], yy = [00:15] | DL170e G6 blade
 (32 nodes) | 2 socket, 6 core [X5660](http://ark.intel.com/products/47921) (Westmere-EP) @ 2.8 GHz, HT | 96 GB | 500 GB | lynx (default) | 2 cpu\*6 core \*2 hyperthreadding = 24 processors |
| ly-dl580.exascience.org | DL580G7 | 4 socket, 10 core [E7-4870](http://ark.intel.com/products/53579) (Westmere-EX) @ 2.4 GHz | 512 GB | 450 GB | fat | 4 cpu\*10 core = 40 processors |
| ly-dl980.exascience.org | DL980G7 | 8 socket, 8 core [E7-2830](http://ark.intel.com/products/53674) (Westmere-EX) @ 2.13 GHz | 1 TB | 450 GB | fat | 8 cpu\*10 core = 80 processors |
| knc-yy.exascience.org
 yy = [10:13] | KNC | 2 socket, 10 core [[1]](http://ark.intel.com/products/75279) (Ivy Bridge EP) @ 3GHz
 Dual Xeon Phi 3120A [[2]](http://ark.intel.com/products/75797) | 128 GB | 1 TB | mic |
 |

_**Ubuntu 14.04.5 LTS (GNU/Linux 3.19.0-80-generic x86\_64)**_

_**GNU bash, version 4.3.11 (1)-release (x86\_64-pc-linux-gnu)**_

which _modulename /verify the loaded module version_

Which python /- installed versions

Less /proc/cpuinfo #check cpu info

Less /proc/meminfo # check memory info [https://unix.stackexchange.com/questions/146051/number-of-processors-in-proc-cpuinfo](https://unix.stackexchange.com/questions/146051/number-of-processors-in-proc-cpuinfo)

**Hyperthreading** (超线程) means that some parts of a core are duplicated. A core with hyperthreading is sometimes presented as an assemblage of two "virtual cores" — meaning not that each core is virtual, but that the plural is virtual because these are not actually separate cores and they will sometimes have to wait while the other core is making use of a shared part.

![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_cd607f730d0a1e67.png)

Module load Python...

pip install --user pyorient /install python package

python / start python

## Generally Available

| **Hostname** | **CPUs (socket x cores)** | **Description/Comments** |
| --- | --- | --- |
| wildcat -- wt-\*-\* | 2 x 18 | Xeon E5-2699 v3, 18 cores @ 2.3GHz (max turbo: 3.6 GHz);[Geekbench max: 185GFlops (2x18cores)](http://browser.primatelabs.com/geekbench3/1404561)Caches: 18x 32kB L1 instruction cache, 18x 32kB L1 data cache 18x 256 kB L2, 45 MB L3 (shared);RAM: 256GB (2x8x16) GB ECC DDR4-2133; |
| lynx -- ly-\*-\* | 2 x 6 | Xeon X5660, 6 cores @ 2.8GHz;[Geekbench max: 25GFlops](http://browser.primatelabs.com/geekbench2/view/300144)Caches: 6x 32kB L1, 6x 256 kB L2, 12 MB L3 (shared);RAM: 96GB (2x6x8) GB DDR3-10600;Maximum bandwidth is 10.67 GB/s per socket. |
| lynx -- DL580 | 4 x 10 | Xeon E7-4870 Westmere, 10 cores @ 2.4 GHz;[Geekbench max: 81GFLOPS](http://browser.primatelabs.com/geekbench3/596549)Caches: 10 x 32 kB L1, 10 x 256 kB L2, 30 MB L3 (shared);RAM: 512 (4x16x8) GB 1333 MHz DDR3;Maximum bandwidth is 10.67 GB/s per socket. |
| lynx -- DL980 | 8 x 8 | Xeon E7-2830 Westmere EX, 8 cores @ 2.13GHz;Caches: 8 x 32 kB L1, 8x 256 kB L2, 24 MB L3 (shared);RAM: 1024 (8x16x8) GB DDR3, \*presumably\* at 1333 MHz;Maximum bandwidth \*presumably\* is 10.67 GB/s per socket. |
| knc-10 up to knc-13 | 2 x 10 | [Xeon E5-2690 v2 Ivy Bridge EP](http://ark.intel.com/products/75279), 10 cores @ 3GHz;[Geekbench max: 56GFLOPS](http://browser.primatelabs.com/geekbench3/2723158)Caches: 10 x 64 kB L1, 10 x 256 kB L2, 25 MB L3 (shared);RAM: 128 (2x4x16) GB DDR3, at 1600 MHz;Maximum bandwidth is 12.8 GB/s per socket. |
| KNC -- mic0/mic1 | 1x61x4 | See [[MIC](http://wiki.exascience.org/w/MIC#Available_machines)] page |

Notes:

- RAM notation is (CPU sockets with directly coupled RAM x the amount of DRAM bars connected to each socket x capacity of each such bar).
- Cache sizes correspond to a single processor only, and to data sizes only (instruction cache sizes are not counted).
- Each Xeon Phi core has 4 hardware threads. Scalar instructions may be fused. The vector-unit may not be addressed by the same hardware thread in two consecutive cycles.
- Xeon Phi bandwidth of up to 150GB/s are claimed, but the number of transfers is definitely 5.5 GT/s. Assuming 8-byte words, then a single controller should go up to 44 GB/s. There are four groups of memory controllers on the ring. Each group contains two controllers. This totals to 44\*4\*2=352GB/s. Bandwidth close to 350GB/s has indeed been observed on SpMV computations.

## GPU nodes

### GPU-01 and GPU-02

Appollo 2000 chassis (2U high), with two ProLiant XL190r Gen9 nodes (side by side).

Node config:

- CPU: Intel(R) Xeon(R) CPU E5-2630 v4 @ 2.20GHz (10 core
- RAM: 64 GB DDR4

gpu-02 has two NVidia K80 GPUs.

Management username is Administrator, password: see table.

- gpu-01 ([ILOCZ3640SVPL](https://ilocz3640svpl.exascience.org/) - TUH6RVZC) - 70:10:6f:b5:22:b4
- gpu-02 ([ILOPFHPH0DLM310](https://ilopfhph0dlm310.exascience.org/) - B26RJ2H8) - 70:10:6f:ac:a4:7a

Installed notes

- Configure RAID array using F10
- Boot PXE using legacy boot

### [[edit](https://wiki.exascience.org/mediawiki/index.php?title=GPU_nodes&action=edit&section=2)]GPU-03

GPU-03 is a re-used [KNC](https://wiki.exascience.org/w/MIC) node (2nd from top in the rack and still labelled knc-12). Contains a GeForce GTX 1080 Ti.

isub

zhai65@ly-X-YY:~$ ipython notebook --ip="ly-X-YY" #to start notebook in the browser

When logging out things need to keep on running:

Tmux detach/unatach

[Detached]

Virtualenv: virtual installation with all the necessary folders

Pip: python package installer

Jupyter: package which provides the notebooks

Notebooks: the code runs on the server the output appears on the window

We should keep our own backups - large data sets will not be backed up.

Report issue to [sysadmin@exascience.org](mailto:sysadmin@exascience.org)

Unix/Linus systems convention

Root directory: / #根目录

zhai65@lynx:/$ pwd

/

zhai65@lynx:/$ ls -a #根目录文件夹

. boot dev home-old lib libnss3.so mnt proc sbin sys var

.. bulk etc initrd.img lib32 lost+found newopt root scratch tmp vmlinuz

bin data home initrd.img.old lib64 media opt(installed packages) run srv usr vmlinuz.old

# **Linux system on windows**

# cygwin

linux environment under Windows system

**run the cygwin as administrator!!**

1. **apt-cyg # package management suite**

lynx -source rawgit.com/transcode-open/apt-cyg/master/apt-cyg \> apt-cyg

install apt-cyg /bin # install the apt-cyg package

  1. " **apt-cyg install \<package names\>**" to install packages
" **apt-cyg remove \<package names\>**" to remove packages
" **apt-cyg update**" to update setup.ini
" **apt-cyg show**" to show installed packages
"**apt-cyg find \<pattern(s)\>**" to find packages matching patterns
"**apt-cyg describe \<pattern(s)\>**" to describe packages matching patterns
" **apt-cyg packageof \<commands or files\>**" to locate parent packages

# WINDOWS SUBSYSTEM FOR LINUX

### What is WSL

[https://docs.microsoft.com/en-us/windows/wsl/about](https://docs.microsoft.com/en-us/windows/wsl/about)

The Windows Subsystem for Linux lets developers run a GNU/Linux environment -- including most command-line tools, utilities, and applications -- directly on Windows, unmodified, without the overhead of a traditional virtual machine or dualboot setup.

You can:

- Choose your favorite GNU/Linux distributions [from the Microsoft Store](https://aka.ms/wslstore).
- Run common command-line tools such as grep, sed, awk, or other ELF-64 binaries.
- Run Bash shell scripts and GNU/Linux command-line applications including:
  - Tools: vim, emacs, tmux
  - Languages: [NodeJS](https://docs.microsoft.com/en-us/windows/nodejs/setup-on-wsl2), Javascript, [Python](https://docs.microsoft.com/en-us/windows/python/web-frameworks), Ruby, C/C++, C# & F#, Rust, Go, etc.
  - Services: SSHD, [MySQL](https://docs.microsoft.com/en-us/windows/wsl/tutorials/wsl-database), Apache, lighttpd, [MongoDB](https://docs.microsoft.com/en-us/windows/wsl/tutorials/wsl-database), [PostgreSQL](https://docs.microsoft.com/en-us/windows/wsl/tutorials/wsl-database).
- Install additional software using your own GNU/Linux distribution package manager.
- Invoke Windows applications using a Unix-like command-line shell.
- Invoke GNU/Linux applications on Windows.

## Windows interoperability with Linux

### Files and Home Directory across OS file systems

[https://docs.microsoft.com/en-us/windows/wsl/compare-versions](https://docs.microsoft.com/en-us/windows/wsl/compare-versions) 6/26/2021

**We recommend against working across operating systems with your files, unless you have a specific reason for doing so. For the fastest performance speed, store your files in the WSL file system if you are working in a Linux command line (Ubuntu, OpenSUSE, etc). If you're working in a Windows command line (PowerShell, Command Prompt), store your files in the Windows file system.**

For example, when storing your WSL project files:

- Use the Linux file system root directory: \\wsl$\Ubuntu-18.04\home\\<user name\>\Project
- Not the Windows file system root directory: C:\Users\\<user name\>\Project

All currently running distributions (wsl -l) are accessible via network connection. To get there run a command [WIN+R] (keyboard shortcut) or type in File Explorer address bar \\wsl$ to find respective distribution names and access their root file systems.

An important consideration: when you enable WSL and install a Linux distribution, you are installing a new file system, separated from the Windows NTFS C:\ drive on your machine. In Linux, drives are not given letters. They are given mount points. The root of your file system / is the mount point of your root partition, or folder, in the case of WSL. Not everything under / is the same drive. For example, on my laptop, I've installed two version of Ubuntu (20.04 and 18.04), as well as Debian. If I open those distributions, select the home directory with the command cd ~, and then enter the command  **explorer.exe**., Windows File Explorer will open and show me the directory path for that distribution.

| **Linux distro** | **Windows Path to access home folder** |
| --- | --- |
|
| |
|
| |
| Ubuntu 20.04 | \\wsl$\Ubuntu-20.04\home\username |
| --- | --- |
| Ubuntu 18.04 | \\wsl$\Ubuntu-18.04\home\username |
| Debian | \\wsl$\Debian\home\username |
| Windows PowerShell | C:\Users\username |

  **Tip**

If you are seeking to access the Windows file directory from your WSL distribution command line, instead of C:\Users\username, the directory would be accessed using  **/mnt/c/Users/username** , because the Linux distribution views your Windows file system as a mounted drive.

you can also access your local machine's file system from within the Linux Bash shell – you'll find your local drives mounted under the  **/mnt****  folder. For example, your  ****C:****  drive is mounted under  ****/mnt/c**

[https://docs.microsoft.com/en-us/windows/wsl/interop](https://docs.microsoft.com/en-us/windows/wsl/interop) Saturday, June 26, 2021

### Run Windows tools from Linux

WSL can run Windows tools directly **from the WSL command line using **** [tool-name].exe ****. For example, **** notepad.exe ****.**

Applications run this way have the following properties:

- Retain the working directory as the WSL command prompt (for the most part -- exceptions are explained below).
- Have the same permission rights as the WSL process.
- Run as the active Windows user.
- Appear in the Windows Task Manager as if directly executed from the CMD prompt.

Windows executables run in WSL are handled similarly to native Linux executables -- piping, redirects, and even backgrounding work as expected.

To run the Windows tool ipconfig.exe, use the Linux tool grep to filter the "IPv4" results, and use the Linux tool cut to remove the column fields, from a Linux distribution (for example, Ubuntu) enter:

BashCopy

ipconfig.exe | grep IPv4 | cut -d: -f2

# **Wimdows terminals, command line interfaces**

# Windows Command line

[https://ryanstutorials.net/linuxtutorial/](https://ryanstutorials.net/linuxtutorial/)

1. Cls #clear the screen
2. **Help** # show the available commands
  1. **\<comand\> /?** # show detailed usage method for a specific command
  2. **Help command** #
3. **set [variable=[sting]]**# display/set the environment parameters for cmd.exe
  1. set #display the current environment variable
  2. set PROGRAM\_HOME=C:\Users\zhai65\installed\_folder #set a variable
  3. set PATH=%PATH%;%PROGRAM\_HOME%\bin # set the installed directory of a program into the path variable of the windows system

## Basics

1. **C:** #Go to the C: drive. Similarly A: and D: etc.
2. **CD** #Change directory. When you change directory, the prompt changes, showing the path of the directory you are currently in.
  1. **CD\** # takes you to the top of the directory tree (typically to C:) .
  2. **CD..** #moves you one level up the directory tree (i.e. up towards the root directory)
  3. **CD \<DIRECTORYNAME\>** #takes you to that directory. You can use one or more subdirectory names, separated by \ e.g.
  4. **CD WINNT\Media** #takes you to the directory C:\WINNT\Media
  5. CD \WINDOWS\SYSTEM # To change to another path, type the full path with slashes. e.g.

1. **MD/MKDIR** #Make Directory creates a new directory below the current one. (The command can also be written as MKDIR.)
  1. **MD \<NEWDIR\>** #creates a new directory called Newdir.
2. **RD/RMDIR \<DIRECTORYNAME** \> #Remove directory. Removes a sub-directory of the current directory. The directory you want to remove must be empty of all files. (The command can also be written as RMDIR)
3. **RENAME \<OLDNAME.EXE\> \<NEWNAME.EXE\>** # Rename a file. You must use the full file name including the suffix.
4. **Del \<file\>** #Delete one or more files in the current directory. Can be used with the  **\***  and the  **?**  wildcards.
  1. **Del \*.\*** # will delete all files in the current directory, use with caution
  2. **Del \*.jpg** #will delete all files with the extension JPG.
  3. **DEL MY\*.\***  #will delete all files beginning with MY and with any extension.
  4. **DEL MY??.\***  #will delete files that are 4 characters long and begin with MY and with any extension.
5. **dir** # list all files and subdirectories in a folder.You can use the \* and the ? wildcards to search for a particular file. The ? character represents ONE character, and the \* character represents multiple characters.
  1. **dir /s #** Displays files in all subdirectories.
  2. **dir /b #** Uses bare format (no heading information or summary).
  3. **dir /o #** List by files in sorted order.
  4. **DIR /AH** #displays all hidden files.
  5. **DIR \*.\*** #lists all the files in a directory.
  6. **DIR \*.JPG** #displays all files with the extension JPG in the current directory and all subdirectories.
  7. **DIR MY??.\*** #displays all files beginning with MY, exactly 4 characters long, and with any extension.
6. **TREE [drive:][path] [/F] [/A] #** list folders and files like graphical directory tree
  1. **Tree /F #** Display the names of the files in each folder.
  2. **Tree /A** #Use ASCII instead of extended characters.
7. **ATTRIB #** Change file attributes. + adds an attribute, - removes it. Attributes are: A=archive; R=read only; S=system; H=hidden.
  1. **ATTRIB -R -A -S -H \<VIRUS.EXE\>** #All these attributes will be removed from virus.exe.
8. **TYPE #** Displays the contents of a file on the screen. If you use this command on a file which is not a text file, the display will be unintelligible.
  1. **TYPE C:\README.TXT|MORE** #Use with |MORE to display the text on a page by page basis, and prevent it scrolling off the screen. | is a pipe character.

### Pipe

1. \> #When you run a DOS command, output is usually sent to the screen. Use \> to redirect output from the screen to a file. It runs the command preceding the \>, creates a file in the current directory with the name you specify, and sends the information/output returned by the command, to that file.
  1. COMMAND \> FILENAME.TXT #SWEEP \> REPORT.TXT The details of any infected files reported by SWEEP are sent to a file called REPORT.TXT.

# System-wise Command

1. **Start "title" "idle.exe"** #start a program in a separate window with a title
2. **TASKLIST [/S system [/U username [/P [password]]]] [/M [module] | /SVC | /V] [/FI filter] [/FO format] [/NH]** # This tool displays a list of currently running processes on either a local or remote machine.
  1. **Tasklist**
  2. **Tasklist /V** #display verbose task information
3. **TASKKILL [/S system [/U username [/P [password]]]] { [/FI filter] [/PID processid | /IM imagename] } [/T] [/F]** # This tool is used to terminate tasks by process id (PID) or image name.
  1. **Taskkill /F /IM python.exe** #kill a process specified by name forcefully
  2. **Taskkill /PID** #kill a process\_id #kill a process specified by id
4. **SHUTDOWN [/i | /l | /s | /r | /g | /a | /p | /h | /e] [/f] [m \\computer][/t xxx][/d [p|u:]xx:yy [/c "comment"]] #**
  1. **Shutdown /i** # display the GUI
  2. **Shutdown /l** #log off
  3. **Shutdown /s** #shutdown the computer
  4. **Shutdown /r** #shutdown and restart the computer
  5. **Shutdown /g #** shutdown and restart the computer with any registered application.

1. **ipconfig /all** #display the ip configuration of the PC
2. **netstat -i** #display the statistic information of the network
3. **Tracert [url]** #show the ip address of the corresponding url

  1. **Tracert www.baidu.com**

# PowerShell

## What is powershell

### shell, scripting language, configuration management framework

[https://docs.microsoft.com/en-us/powershell/scripting/overview?view=powershell-5.1](https://docs.microsoft.com/en-us/powershell/scripting/overview?view=powershell-5.1)

developed since windows 7, to be used as the default terminal on windows.PowerShell is developed from .NET framework and consists of scripting language and command line.PowerShell is a cross-platform task automation solution made up of **a command-line shell, a scripting language, and a configuration management framework.** PowerShell runs on Windows, Linux, and macOS.

PowerShell is a modern command shell that includes the best features of other popular shells. Unlike most shells that only accept and return text, PowerShell accepts and returns .NET objects. The shell includes the following features:

- Robust command-line history
- Tab completion and command prediction (See about\_PSReadLine)
- Supports command and parameter aliases
- Pipeline for chaining commands
- In-console help system, similar to Unix man pages

[PowerShell Beginner tutorial Full Course](https://www.youtube.com/watch?v=UVUd9_k9C6A)

Learn how PowerShell works and how to make PowerShell work for you from the experts Jeffrey Snover, the inventor of PowerShell, together with Jason Helmick, Senior Technologist at Concentrated Technology.

1. Get-help [cmdlet-name] [-online] # show the help message (about a command, services)
  1. Get-verb # show all the verbs in the first-name of cmdlests of powershell
  2. Get-help [cmdlet-name] [-ShowWindow] # show the message in a separate window
2. Get-command
  1. Get-command # list out all the commands
  2. Get-command ipconfig # list the command ipconfig
  3.
3. Get-alias # list out all the aliases
  1. **ls [options] [location]**# -\> Get-ChildItem List the contents of a directory.
    1. Ls -a [path] #list out hidden files
    2. Ls -l [ path #show more infomation
    3. Ls -- all #long hand command line options begin with two dashes ( -- ) and short hand options begin with a single dash ( - ).
    4. Ls -alh #options combined together
    5. ls /home/ryan/linuxtutorialwork/\*.txt
    6. ls ?i\*
    7. ls \*.???
    8. ls [sv]\* # limit to a subset of characters
    9. ls \*[0-9]\* # include a set by using a hyphen
4. **chown \<newowner\> foo** #used from the root account to change the owner of the file
5. **chgrp \<newgroup\> foo** # used from the file's owner or root account to change the group of the file
6. **chmod [permissions] [path]** #used from the file's owner or root account to change file and directory access permissions. It stands for change file mode bits. change permissions on a file or directory
  1. chmod g+x frog.png
  2. chmod 751 frog.png #using octal number shorthand 7:111, 5:101, 1:001

- Who are we changing the permission for? [ugoa] - user (or owner), group, others, all
- Are we granting or revoking the permission - indicated with either a plus ( + ) or minus ( - )

# **.NET**

.NET is a free, cross-platform, open source developer platform for building many different types of applications.

With .NET, you can use multiple languages, editors, and libraries to build for web, mobile, desktop, gaming, and IoT.

You can write .NET apps in C#, F#, or Visual Basic.

- C# is a simple, modern, object-oriented, and type-safe programming language.
- F# is a cross-platform, open-source, functional programming language for .NET. It also includes object-oriented and imperative programming.
- Visual Basic is an approachable language with a simple syntax for building type-safe, object-oriented apps.

The Visual Studio product family provides a great .NET development experience on Windows, Linux, and macOS.

# **keyboard Shortcuts in Windows OS**

# Windows 10 keyboard shortcuts

If the mouse is slowing you down, this complete list includes the most useful keyboard shortcuts to perform tasks on Windows 10 a little faster.

- [Essential shortcuts](https://www.windowscentral.com/best-windows-10-keyboard-shortcuts#essential_key_shortcuts_windows10)
- [Desktop shortcuts](https://www.windowscentral.com/best-windows-10-keyboard-shortcuts#desktop_key_shortcuts_windows10)
- [File Explorer shortcuts](https://www.windowscentral.com/best-windows-10-keyboard-shortcuts#file_explorer_key_shortcuts_windows10)
- [Command Prompt shortcuts](https://www.windowscentral.com/best-windows-10-keyboard-shortcuts#cmd_key_shortcuts_windows10)
- [Windows key shortcuts](https://www.windowscentral.com/best-windows-10-keyboard-shortcuts#windowskey_shortcuts_windows10)

## Essential shortcuts

These are the essential keyboard shortcuts that every Windows 10 user should know.

| Keyboard shortcut | Action |
| --- | --- |
| Ctrl + A | Select all content. |
| --- | --- |
| Ctrl + C (or Ctrl + Insert) | Copy selected items to clipboard. |
| Ctrl + X | Cut selected items to clipboard. |
| Ctrl + V (or Shift + Insert) | Paste content from clipboard. |
| Ctrl + Z | Undo an action, including undelete files (limited). |
| **Ctrl + Y** | **Redo an action.** |
| Ctrl + Shift + N | Create new folder on desktop or File Explorer. |
| **Ctrl + F4** | Close active window. (If no active window present, then shutdown box appears.) |
| Ctrl + D | Delete selected item to the Recycle Bin. |
| F2 | Rename selected item. |
| ESC | Close current task. |
| Shift + Delete | Delete selected item permanently skipping Recycle Bin. |
| Alt + Tab | Switch between open apps. |
| Windows key + I | Open Settings app. |
| Windows key + E | Open File Explorer. |
| Windows key + A | Open Action center. |
| Windows key + D | Display and hide the desktop. |
| Windows key + L | Lock device. |
| Windows key + V | Open Clipboard bin. |
| Windows key + period (.) or semicolon (;) | Open emoji panel. |
| **Windows key + PrtScn** | **Capture full screenshot in the "Screenshots" folder.** |
| **Windows key + Shift + S** | **Capture part of the screen in a screenshot.** |
| Windows key + Left arrow key | Snap app or window left. |
| Windows key + Right arrow key | Snap app or window right. |

## Desktop shortcuts

You can use these keyboard shortcuts to open, close, navigate, and complete specific tasks more quickly throughout the desktop experience, including on Start menu, taskbar, Settings, and more.

| Keyboard shortcut | Action |
| --- | --- |
| Ctrl + Esc (or Windows key) | Open Start menu. |
| --- | --- |
| Ctrl + Arrow keys | Change Start menu size. |
| Ctrl + Shift + Esc | Open Task Manager. |
| Ctrl + Shift | Switch keyboard layout. |
| **Ctrl + F4** | Close active window. (If no active window present, then shutdown box appears.) |
| Ctrl + F5 (or R) | Refresh current window. |
| Ctrl + Alt + Tab | View open apps. |
| Ctrl + Arrow keys (to select) + Spacebar | Select multiple items on desktop or File Explorer. |
| Alt + Tab | Switch between open apps while pressing Tab multile times. |
| **Alt + Left arrow key** | **Go back.** |
| Alt + Right arrow key | Go forward. |
| Alt + Page Up | Move up one screen. |
| Alt + Page down | Move down one screen. |
| Alt + Esc | Cycle through open windows. |
| Alt + Spacebar | Open context menu for the active window. |
| Shift + click app button | Open another instance of an app from the taskbar. |
| Ctrl + Shift + click app button | Run app as administrator from the taskbar. |
| Shift + Right-click app button | Show window menu for the app from the taskbar. |
| Ctrl + Click a grouped app button | Cycle through windows in the group from the taskbar. |
| Shift + Right-click a grouped app button | Show window menu for the group from the taskbar. |
| Ctrl + Left arrow key | Move the cursor to the beginning of the previous word. |
| Ctrl + Right arrow key | Move the cursor to the beginning of the next word. |
| Ctrl + Up arrow key | Move the cursor to the beginning of the previous paragraph |
| Ctrl + Down arrow key | Move the cursor to the beginning of the next paragraph. |
| Ctrl + Shift + arrow key | Select block of text. |
| Ctrl + Spacebar | Enable or disable Chinese IME. |
| Shift + F10 | Open context menu for selected item. |
| Shift + Arrow keys | Select multiple items. |
| Windows key + X | Open Quick Link menu. |
| Windows key + Number (0-9) | Open app in number position from the taskbar. |
| **Windows key + T** | **Cycle through apps in the taskbar.** |
| Windows key + Alt + Number (0-9) | Open Jump List of the app in number position from the taskbar. |
| Windows key + D | Display and hide the desktop. |
| **Windows key + M** | **Minimize all windows.** |
| **Windows key + Shift + M** | **Restore minimized windows on the desktop.** |
| **Windows key + Home** | **Minimize or miximize all but the active desktop window.** |
| Windows key + Shift + Up arrow key | Stretch desktop window to the top and bottom of the screen. |
| **Windows key + Shift + Down arrow key** | **Maximize or minimize active desktop windows vertically while maintaining width.** |
| Windows key + Shift + Left arrow key | Move active window to monitor on the left. |
| Windows key + Shift + Right arrow key | Move active window to monitor on the right. |
| Windows key + Left arrow key | Snap app or window left. |
| Windows key + Right arrow key | Snap app or window right. |
| Windows key + S ( or Q) | Open Search. |
| **Windows key + Alt + D** | **Open date and time in the taskbar.** |
| **Windows key + Tab** | **Open Task View.** |
| Windows key + Ctrl + D | Create new virtual desktop. |
| Windows key + Ctrl + F4 | Close active virtual desktop. |
| Windows key + Ctrl + Right arrow | Switch to the virtual desktop on the right. |
| Windows key + Ctrl + Left arrow | Switch to the virtual desktop on the left. |
| Windows key + P | Open Project settings. |
| Windows key + A | Open Action center. |
| Windows key + I | Open Settings app. |
| Backspace | Return to Settings app home page. |

## File Explorer shortcuts

On Windows 10, File Explorer includes a lot of keyboard shortcuts to help you complete tasks a little quicker.

Here's a list with the most useful shortcuts for File Explorer.

| Keyboard shortcut | Action |
| --- | --- |
| Windows key + E | Open File Explorer. |
| --- | --- |
| Alt + D | Select address bar. |
| Ctrl + E (or F) | Select search box. |
| Ctrl + N | Open new window. |
| Ctrl + W | Close active window. |
| Ctrl + F (or F3) | Start search. |
| Ctrl + mouse scroll wheel | Change view file and folder. |
| Ctrl + Shift + E | Expands all folders from the tree in the navigation pane. |
| Ctrl + Shift + N | Create new folder on desktop or File Explorer. |
| Ctrl + L | Focus on the address bar. |
| Ctrl + Shift + Number (1-8) | Changes folder view. |
| Alt + P | Display preview panel. |
| Alt + Enter | Open Properties settings for the selected item. |
| Alt + Right arrow key | View next folder. |
| Alt + Left arrow key (or Backspace) | View previous folder. |
| Alt + Up arrow | Move up a level in the folder path. |
| F11 | Switch active window full screen mode. |
| F5 | Refresh the instance of File Explorer. |
| F2 | Rename selected item. |
| F4 | Switch focus to address bar. |
| F5 | Refresh File Explorer's current view. |
| F6 | Cycle through elements on the screen. |
| Home | Scroll to top of the window. |
| End | Scroll to bottom of the window. |

## Command Prompt shortcuts

If you use Command Prompt, you can use these keyboard shortcuts to work a little more efficiently.

| Keyboard shortcut | Action |
| --- | --- |
| Ctrl + A | Select all content of the current line. |
| --- | --- |
| Ctrl + C (or Ctrl + Insert) | Copy selected items to clipboard. |
| Ctrl + V (or Shift + Insert) | Paste content from clipboard. |
| Ctrl + M | Starts mark mode. |
| Ctrl + Up arrow key | Move screen up one line. |
| Ctrl + Down arrow key | Move screen down one line. |
| Ctrl + F | Open search for Command Prompt. |
| Left or right arrow keys | Move cursor left or right in the current line. |
| Up or down arrow keys | Cycle through command history of the current session. |
| Page up | Move cursor one page up. |
| Page down | Move cursor one page down. |
| Ctrl + Home | Scroll to top of the console. |
| Ctrl + End | Scroll to the bottom of the console. |

## Windows key shortcuts

Using the Windows key in combination with other keys, you can perform a number of useful tasks, such as launch Settings, File Explorer, Run command, apps pinned in the taskbar, or you can open specific features like Narrator or Magnifier. In addition, you can accomplish tasks like controlling windows, virtual desktops, take screenshots, lock your device, and a lot more.

Here's a list with all the most common keyboard shortcuts using the Windows key.

| Keyboard shortcut | Action |
| --- | --- |
| Windows key | Open Start menu. |
| --- | --- |
| Windows key + A | Open Action center. |
| Windows key + S ( or Q) | Open Search. |
| Windows key + D | Display and hide the desktop. |
| Windows key + L | Lock device. |
| Windows key + M | Minimize all windows. |
| Windows key + B | Set focus notification area in the taskbar. |
| Windows key + O | Lock device orientation. |
| Windows key + T | Cycle through apps in the taskbar. |
| Windows key + Z | Switch input between the desktop experience and Windows Mixed Reality. |
| Windows key + G | Open Game bar. |
| Windows key + H | Open dictation feature. |
| **Windows key + E** | **Open File Explorer.** |
| Windows key + I | Open Settings. |
| **Windows key + R** | **Open Run command.** |
| Windows key + K | Open Connect settings. |
| Windows key + X | Open Quick Link menu. |
| Windows key + V | Open Clipboard bin. |
| Windows key + W | Open the Windows Ink Workspace. |
| Windows key + U | Open Ease of Access settings. |
| Windows key + Ctrl + Enter | Open Narrator. |
| Windows key + Plus (+) | Zoom in using the magnifier. |
| Windows key + Minus (-) | Zoom out using the magnifier. |
| Windows key + Esc | Exit magnifier. |
| Windows key + forward-slash (/) | Start IME reconversion. |
| **Windows key + Comma (,)** | **Temporarily peek at the desktop.** |
| Windows key + Up arrow key | Maximize app windows. |
| Windows key + Down arrow key | Minimize app windows. |
| **Windows key + Home** | **Minimize or miximize all but the active desktop window.** |
| Windows key + Shift + M | Restore minimized windows on the desktop. |
| Windows key + Shift + Up arrow key | Stretch desktop window to the top and bottom of the screen. |
| Windows key + Shift + Down arrow key | Maximize or minimize active windows vertically while maintaining width. |
| Windows key + Shift + Left arrow key | Move active window to monitor on the left. |
| Windows key + Shift + Right arrow key | Move active window to monitor on the right. |
| Windows key + Left arrow key | Snap app or window left. |
| Windows key + Right arrow key | Snap app or window right. |
| Windows key + Number (0-9) | Open app in number position in the taskbar. |
| Windows key + Shift + Number (0-9) | Open another instance of the app in number position in the taskbar. |
| Windows key + Ctrl + Number (0-9) | Switch to last active window of the app in number position in the taskbar. |
| Windows key + Alt + Number (0-9) | Open Jump List of the app in number position in the taskbar. |
| Windows key + Ctrl + Shift + Number (0-9) | Open another instance as an administrator of the app in number position in the taskbar. |
| Windows key + + Ctrl + Spacebar | Change previous selected input option. |
| Windows key + Tab | Open Task View. |
| **Windows key + Ctrl + D** | **Create a virtual desktop.** |
| **Windows key + Ctrl + F4** | **Close active virtual desktop.** |
| Windows key + Ctrl + Right arrow | Switch to the virtual desktop on the right. |
| Windows key + Ctrl + Left arrow | Switch to the virtual desktop on the left. |
| Windows key + Ctrl + Shift + B | Wake up the device when black or a blank screen. |
| **Windows key + PrtScn** | **Capture full screenshot in the "Screenshots" folder.** |
| Windows key + Shift + S | Create part of the screen screenshot. |
| Windows key + Shift + V | Cycle through notifications.. |
| Windows key + Ctrl + F | Open search for device on a domain network. |
| Windows key + Ctrl + Q | Open Quick Assist. |
| Windows key + Alt + D | Open date and time in the taskbar. |
| Windows key + period (.) or semicolon (;) | Open emoji panel. |
| Windows key + Pause | Show System Properties dialog box. |

# [navigate Windows using a keyboard.](https://www.computerhope.com/issues/ch000791.htm)

[https://www.computerhope.com/issues/ch000542.htm](https://www.computerhope.com/issues/ch000542.htm)

Press  **Left Alt + Left Shift + Num Lock**  on your computer to toggle Mouse Keys on and off.

The following table shows each of the keys on the Numeric Keypad and how they interact with the mouse cursor. Make sure you're  **only using the Keypad**  to execute these actions.

| Desired Action | Key Combination |
| --- | --- |
| Move up and to the left | Press 7 |
| Move up | Press 8 |
| Move up and to the right | Press 9 |
| Move left | Press 4 |
| Move right | Press 6 |
| Move down and to the left | Press 1 |
| Move down | Press 2 |
| Move down and to the right | Press 3 |
| Select the left mouse button | Press / |
| Select both of the mouse buttons | Press \* |
| Select the right mouse button | Press - |
| Click | With the left button selected, press 5. |
| Right-click | With the right button selected, press 5. |
| Double-click | With the left button selected, press +. |
| Drag an item | Point to the item, then press 0. |
| Drop the item you are dragging | Press . ([period](https://www.computerhope.com/jargon/p/period.htm)) |

# Comparing [Keyboard shortcuts](https://en.wikipedia.org/wiki/Table_of_keyboard_shortcuts) in different OS & Applications

Some of the combinations are not true for localized versions of operating systems.  Furthermore, many shortcuts (such as Ctrl+Z, Alt+E, etc.) are just common conventions and are  **not**  handled by the operating system. Whether such commands are implemented (or not) depends on how an actual application program (such as an editor) is written. Not all applications follow (all of) these conventions, so if it doesn't work, it isn't compatible.

![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_41f814be4b0c50ec.png)

# **Widows application**

# Office

## Common Shortcuts in Word, Excel, and PowerPoint 2016

| **To do this** | **With the mouse** | **With the keyboard** |
| --- | --- | --- |
| Open a file | File→Open | Ctrl+O |
| Create a new file | File→New | Ctrl+N |
| Print active document | File→Print | Ctrl+P |
| Save your work (first time), or resave with same settings | File→Save | Ctrl+S |
| Save your work with different name, location, or type | File→Save As | F12 |
| Copy selection to Clipboard | Home→ Copy | Ctrl+C |
| Cut selection to Clipboard | Home→ Cut | Ctrl+X |
| Paste selection to Clipboard | Home→ Paste | Ctrl+V |
| Open the Paste Special dialog box | Home→Paste→Paste Special | Ctrl+Shift+V |
| Display shortcut menu for selected item | Right-click item | Shift+F10 |
| Left-align a paragraph | Home→ Left Align | Ctrl+L |
| Center a paragraph | Home→ Center | Ctrl+E |
| Right-align a paragraph | Home→ Right Align | Ctrl+R |
| Make text bold | Home→ Bold | Ctrl+B |
| Make text italicized | Home→ Italic | Ctrl+I |
| Make text underlined | Home→Underline | Ctrl+U |
| Make text larger | Home→Increase Font Size | Ctrl+\> |
| Make text smaller | Home→Decrease Font Size | Ctrl+\< |
| Undo previous action | Undo button on Quick Access toolbar | Ctrl+Z |
| Redo previous Undo | Redo button on Quick Access toolbar | Ctrl+Y |
| Insert hyperlink | Insert→Hyperlink | Ctrl+K |
| Get help | Type in Tellme what you want to do box | F1 |
| Close the active file | File→Close | Ctrl+F4 |
| Close the application | Close button on application window | Alt+F4 |
| Check spelling | Review→Spelling | F7 |

### Word Shortcut

[https://support.microsoft.com/en-us/topic/keyboard-shortcuts-in-word-95ef89dd-7142-4b50-afb2-f762f663ceb2?ui=en-us&rs=en-us&ad=us#bkmk\_navigatewin](https://support.microsoft.com/en-us/topic/keyboard-shortcuts-in-word-95ef89dd-7142-4b50-afb2-f762f663ceb2?ui=en-us&rs=en-us&ad=us#bkmk_navigatewin)

#### Frequently used shortcuts

This table shows the most frequently used shortcuts in Microsoft Word.

| To do this | Press |
| --- | --- |
| Open a document. | Ctrl+O |
| --- | --- |
| Create a new document. | Ctrl+N |
| Save the document. | Ctrl+S |
| Close the document. | Ctrl+W |
| Cut the selected content to the Clipboard. | Ctrl+X |
| Copy the selected content to the Clipboard. | Ctrl+C |
| Paste the contents of the Clipboard. | Ctrl+V |
| Select all document content. | Ctrl+A |
| Apply bold formatting to text. | Ctrl+B |
| Apply italic formatting to text. | Ctrl+I |
| Apply underline formatting to text. | Ctrl+U |
| Decrease the font size by 1 point. | Ctrl+[ |
| Increase the font size by 1 point. | Ctrl+] |
| Center the text. | Ctrl+E |
| Align the text to the left. | Ctrl+L |
| Align the text to the right. | Ctrl+R |
| Cancel a command. | Esc |
| Undo the previous action. | Ctrl+Z |
| Redo the previous action, if possible. | Ctrl+Y |
| Adjust the zoom magnification. | Alt+W, Q, then tab in Zoom dialog box to the value you want. |
| Split the document window. | Ctrl+Alt+S |
| Remove the document window split. | Alt+Shift+C or Ctrl+Alt+S |

##### Paste plain text in world

There seems to be no direct shortcut for that, but here's something you can do:

Paste text (Ctrl+V) and then press Ctrl for paste options to appear and then press T for pasting the text with "Keep text only" paste option.

Or, you can simply set the keyboard shortcut for PasteTextOnly to Ctrl+Shift+V, then it works like before again.

That shortcut is a bit hidden though, so here's the steps how to get there:

- File \> Options \> Customize Ribbon \> Keyboard shortcuts: Customize...
- Under Categories, select All Commands
- Under Commands, look for PasteTextOnly
- Set the keyboard shortcut for PasteTextOnly to Ctrl+Shift+V

#### Align and format paragraphs

| To do this | Press |
| --- | --- |
| Center the paragraph. | Ctrl+E |
| --- | --- |
| Justify the paragraph. | Ctrl+J |
| Align the paragraph to the left. | Ctrl+L |
| Align the paragraph to the right. | Ctrl+R |
| Indent the paragraph. | Ctrl+M |
| Remove a paragraph indent. | Ctrl+Shift+M |
| Create a hanging indent. | Ctrl+T |
| Remove a hanging indent. | Ctrl+Shift+T |
| Remove paragraph formatting. | Ctrl+Q |
| Apply single spacing to the paragraph. | Ctrl+1 |
| Apply double spacing to the paragraph. | Ctrl+2 |
| Apply 1.5-line spacing to the paragraph. | Ctrl+5 |
| Add or remove space before the paragraph. | Ctrl+0 (zero) |
| Enable AutoFormat. | Ctrl+Alt+K |
| Apply the  **Normal**  style. | Ctrl+Shift+N |
| Apply the  **Heading 1**  style. | Ctrl+Alt+1 |
| Apply the  **Heading 2**  style. | Ctrl+Alt+2 |
| Apply the  **Heading 3**  style. | Ctrl+Alt+3 |
| Display the  **Apply Styles**  task pane. | Ctrl+Shift+S |
| Display the  **Styles**  task pane. | Ctrl+Alt+Shift+S |

#### Insert special characters

| To do this | Press |
| --- | --- |
| Insert a line break. | Shift+Enter |
| --- | --- |
| Insert a page break. | Ctrl+Enter |
| Insert a column break. | Ctrl+Shift+Enter |
| Insert an em dash (—). | Ctrl+Alt+Minus sign (on the numeric keypad) |
| Insert an en dash (–). | Ctrl+Minus sign (on the numeric keypad) |
| Insert an optional hyphen. | Ctrl+Hyphen (-) |
| Insert a nonbreaking hyphen. | Ctrl+Shift+Hyphen (-) |
| Insert a nonbreaking space. | Ctrl+Shift+Spacebar |
| Insert a copyright symbol (©). | Ctrl+Alt+C |
| Insert a registered trademark symbol (®). | Ctrl+Alt+R |
| Insert a trademark symbol (™). | Ctrl+Alt+T |
| Insert an ellipsis (…) | Ctrl+Alt+Period (.) |
| Insert the Unicode character for the specified Unicode (hexadecimal) character code. For example, to insert the euro currency symbol ( ![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_784febf2de1bf642.gif)), type 20AC, and then hold down Alt and press X. **Tip: ** To find out the Unicode character code for a selected character, press Alt+X. | The character code, then press Alt+X |
| Insert the ANSI character for the specified ANSI (decimal) character code. For example, to insert the euro currency symbol, hold down Alt and press 0128 on the numeric keypad. | Alt+the character code (on the numeric keypad) |

#### Outline a document

These shortcuts only apply when the document is in the  **Outline**  view.

| To do this | Press |
| --- | --- |
| Promote a paragraph. | Alt+Shift+Left arrow key |
| --- | --- |
| Demote a paragraph. | Alt+Shift+Right arrow key |
| Demote the paragraph to body text. | Ctrl+Shift+N |
| Move the selected paragraphs up. | Alt+Shift+Up arrow key |
| Move the selected paragraphs down. | Alt+Shift+Down arrow key |
| **Expand the text under a heading.** | **Alt+Shift+Plus sign** |
| **Collapse the text under a heading.** | **Alt+Shift+Minus sign** |
| **Expand or collapse all text or headings.** | **Alt+Shift+A** |
| Hide or display the character formatting. | Forward slash (/) (on the numeric keypad) |
| Switch between showing the first line of body text and showing all body text. | Alt+Shift+L |
| **Show all headings with the Heading 1 style.** | **Alt+Shift+1** |
| **Show all headings with the specified heading level.** | **Alt+Shift+Heading level number** |
| Insert a tab character. | Ctrl+Tab |

## Word

[https://shaunakelly.com/word.html](https://shaunakelly.com/word.html)

[http://wordfaqs.ssbarnhill.com/tutorials.htm](http://wordfaqs.ssbarnhill.com/tutorials.htm)

### Word Intermediate to advanced skills

#### Operating parameter limitations and specifications in Word

[https://docs.microsoft.com/en-us/office/troubleshoot/word/operating-parameter-limitation](https://docs.microsoft.com/en-us/office/troubleshoot/word/operating-parameter-limitation)

Word 2007 and later versions limits

| **WORD 2007 AND LATER VERSIONS LIMITS** |
| --- |
| **Operating parameter** | **Limit** |
|
| |
|
| |
| Maximum number of bookmarks | 2,147,483,647 |
| --- | --- |
| (Style Definition) maximum number of styles | 4,079 |
| --- | --- |
| Maximum number of lists | 2,047 |
| --- | --- |
| Maximum number of comments | 2,147,483,647 |
| --- | --- |
| Maximum number of fields | 2,147,483,647 |
| --- | --- |
| Number of subdocuments in a master document | 255 |
| --- | --- |
| Maximum number of moves | 2,147,483,647 |
| --- | --- |
| (Range Permission) maximum number allowed | 2,147,483,647 |
| --- | --- |
| Size of file Word can open | 512 MB |
| --- | --- |
| Maximum number of records to display in recipients list dialog | 10,000 |
| --- | --- |
| Maximum paper size | 22" x 22" |
| --- | --- |

#### Add Chapter Title To Header Or Footer In Word Document?

[https://www.extendoffice.com/documents/word/5449-word-add-chapter-title-to-header.html](https://www.extendoffice.com/documents/word/5449-word-add-chapter-title-to-header.html)

Add Chapter Title To Header Or Footer In Word Document

To insert each chapter title to header or footer, you can use the Quick Parts feature to achieve it, please do as this:

1. Firstly, you should apply a paragraph style to the chapter title that you want to insert as header or footer, in this example, my chapter title is styled as Heading 1, see screenshot:

2. Then click Home \> Header / Footer, and choose one header or footer style, see screenshot:

3. And then, click Quick Parts \> Field under the Design tab, see screenshot:

![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_783ffdf477b1052c.png) 4. In the popped out Field dialog box, do the following operations:

(1.) Select Links and References from the Categories drop down list;

(2.) In the Field names list box, please choose StyleRef option;

(3.) And then, find and select Heading 1 which is your chapter style you created from the Style name list box.

![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_109c20f6e3026c21.png)

5. After finishing the settings, please click OK button, and now, the chapter title has been inserted into the header or footer, see screenshot:

Notes:

1. If there's more than one Heading 1 on one page, only the first appeared one will be inserted into the header or footer.

2. The header or footer will be changed automatically when the chapter title is changing.

#### Skills to handle large word documents

[https://answers.microsoft.com/en-us/msoffice/forum/all/maximum-pages-in-a-word-doc/85a7735a-3081-44ab-9bbb-c6da8887a5e5?auth=1](https://answers.microsoft.com/en-us/msoffice/forum/all/maximum-pages-in-a-word-doc/85a7735a-3081-44ab-9bbb-c6da8887a5e5?auth=1)

Word really has no real maximum page limit, there is a limit on file size, which I think is 0.5Gb (512MB).
 The relevant measurements are file size, and text size. I have a similar document that I use daily. currently about 3000 pages, recently up to 68MB in total size.

Adding graphics can bloat the total size, and that can lead to slowdowns in performance.

.

One thing you can do is simplify the document. If you are pasting from many sources, like from the internet, your settings may also copy styles. That can create a lot of "clutter" and complexity in the document that could slow it down.

Display the style pane and see how many styles you have in the document. If you see a lot of strange ones, you can start deleting them. If the styles represent formatting you are not using, or they look like normal, you can simply delete them, the formatting will revert to the NORMAL style.

PS: with a big slow document, you should also be making periodic backup copies of the file just in case it crashes.

However, Word will become unstable with that many pages,

Some tips to maximize the ability of Word to handle a big document:

1. Learn how to use  **styles**  for your formatting, and then actually use them. You want virtually no direct formatting.
[Importance of Styles in Word](http://www.addbalance.com/usersguide/styles.htm#Overview)
[Tips for Understanding Styles in Word by Shauna Kelly](http://www.shaunakelly.com/word/styles/stylesms.html)
[Managing Word Styles by Suzanne Barnhill, MVP](http://wordfaqs.ssbarnhill.com/ManageStyles.htm)
2. Use the  **built-in heading styles**  to organize your document.  Use the Navigation Pane and / or a T[able of Contents](http://www.addbalance.com/usersguide/complex_documents.htm#Table%20of%20Contents) to move around.
[Why use Microsoft Word's built-in heading styles?](http://www.addbalance.com/usersguide/10HeadingStyles.htm)
[Moving/Reorganizing Pages in Microsoft Word](http://addbalance.com/word/MovePages.htm#PageStart)
3. Use  **page-break before paragraph formatting**  in the heading style you want at the top of a new page. Do not use a manual page break or the Enter key
[Word Doesn't Know What a Page Is](https://wordmvp.com/Mac/PagesInWord.html)
4. Do not use the Enter key for vertical spacing -  **avoid empty paragraphs**
[2.2 Why you should press Enter only once to end a paragraph](http://www.shaunakelly.com/word/concepts/rules_enterparagraphs.html)
5. No unnecessary  **Section breaks**
 The main reason I see for these is changes in header or footers that could have been handled using a StyleRef field.
[StyleRef Field](http://www.addbalance.com/usersguide/fields.htm#STYLEREF)
[Header/Footer Settings Recap](http://www.addbalance.com/usersguide/sections2007.htm#Recap_of_Header/Footer_settings)
6. **Minimize the use of floating graphics**. Put them in-line-with text when you can.
7. Keep at least two  **backups** , at least one not on your computer's hard drive.
 See: [Save in two places by Graham Mayor, MVP](http://www.gmayor.com/SaveInTwoPlacesAddIn.htm) and [Save Numbered Versions by Graham Mayor, MVP](http://www.gmayor.com/SaveVersionsAdd-In.htm)

You should find Word more responsive in  **Draft view**.

Lots of  **RAM**  on your computer will also help, probably more than it came with. It is usually one of the least-expensive upgrades. I would say that 16Gb is a minimum although Word works with much less. (I use 32 Gb.)

#### Styles

Some tips to maximize the ability of Word to handle a big document:

1. Learn how to use  **styles**  for your formatting, and then actually use them. You want virtually no direct formatting.
[Importance of Styles in Word](http://www.addbalance.com/usersguide/styles.htm#Overview)
[Tips for Understanding Styles in Word by Shauna Kelly](http://www.shaunakelly.com/word/styles/stylesms.html)
[Managing Word Styles by Suzanne Barnhill, MVP](http://wordfaqs.ssbarnhill.com/ManageStyles.htm)
2. Use the  **built-in heading styles**  to organize your document.  Use the Navigation Pane and / or a T[able of Contents](http://www.addbalance.com/usersguide/complex_documents.htm#Table%20of%20Contents) to move around.
[Why use Microsoft Word's built-in heading styles?](http://www.addbalance.com/usersguide/10HeadingStyles.htm)
[Moving/Reorganizing Pages in Microsoft Word](http://addbalance.com/word/MovePages.htm#PageStart)

#### Word TOC

##### Map a custom style(Summary) to a TOC level

[https://support.microsoft.com/en-us/office/video-advanced-tables-of-contents-10e89d4e-ec5a-4f31-b4d6-a61077427951](https://support.microsoft.com/en-us/office/video-advanced-tables-of-contents-10e89d4e-ec5a-4f31-b4d6-a61077427951)

Let's say we want to add brief descriptions under each heading entry. To do that, we'll use a custom style.

1. Select the text that we want to appear in the Table of Contents. The text is now formatted as  **Normal**  with the rest of the paragraph.
2. Open  **Styles**  gallery \>  **Create a Style**  \>  **OK**.
3. Click ahead of the Table of Contents. Then, open the  **Table of Contents**  gallery, and click  **Custom Table of Contents**  \>  **Options**.
4. The first three  **Heading Styles**  are mapped to the first three  **TOC levels**. Scroll down to the new style, and map it to level 4, and click  **OK**.
5. The preview now shows the new style under  **Heading 3**. Click  **OK**  \>  **Yes**  to replace the current table.

#####  Modify a TOC with field codes ( remove page number)

[https://support.microsoft.com/en-us/office/video-modify-a-toc-with-field-codes-63aced07-0eca-4b29-a3ba-0a5a1d4701d6?ui=en-US&rs=en-US&ad=US#ID0EAABAAA=Overview](https://support.microsoft.com/en-us/office/video-modify-a-toc-with-field-codes-63aced07-0eca-4b29-a3ba-0a5a1d4701d6?ui=en-US&rs=en-US&ad=US#ID0EAABAAA=Overview)

{TOC \h \z \n 7-7 \t "heading1,2,Heading 2,3,Subtitle,1, Intense Quote,3"

#### Section break and (reusable) quick parts

[https://www.youtube.com/watch?v=i2kFsu\_3OfM](https://www.youtube.com/watch?v=i2kFsu_3OfM) Wednesday, June 30, 2021

##### Cereate separate sections

[https://www.youtube.com/watch?v=Fvrtt0h84Mg](https://www.youtube.com/watch?v=Fvrtt0h84Mg)

(change to portrait/lanscape, two columns, order page number, only in that section)

in Layout-\>breaks-\>section breaks-\>continuous

compared with page break, section beak can create separate sections in the same word document that are independent of each other in many features (such as, page numbering, layout, columns, orientation, etc.)

##### create resuable quick parts

select the parts that you want to reuse it in other documents or places.

in Incert-\>text-\>quick parts-\>save section to quick parts gallery.

##### Scale and personalize Mailing

Edit your mail in word

In Mailing-\>start mail merge-\>letters/e-mail

##### Line Spacing before heading at top of page (my phd thesis)

[https://answers.microsoft.com/en-us/msoffice/forum/msoffice\_word-mso\_windows8-mso\_o365b/office-365-line-spacing-before-heading-at-top-of/6e982003-9a60-43f0-a1d7-5a9458efa3c3](https://answers.microsoft.com/en-us/msoffice/forum/msoffice_word-mso_windows8-mso_o365b/office-365-line-spacing-before-heading-at-top-of/6e982003-9a60-43f0-a1d7-5a9458efa3c3)

The default behavior in recent versions of Word, as you have noticed, is to suppress the paragraph Spacing Before at the top of each page, unless the paragraph is at beginning of a new section.

As a workaround, you can save in an older file format or you can add frame formatting to your heading paragraph style.

The workarounds are

    1. insert a section break (New Page or Odd Page) before each chapter heading,
    2. save the document in \*.doc format, although that shouldn't be done if the document contains anything created by features that are new since Word 2003, or
    3. add a frame with a fixed height to the definition of the Heading 1 style.

To add a frame, Here is how to do it:

[https://www.toweringskills.com/writing/microsoft-word-vertical-space-before-chapter-headings/](https://www.toweringskills.com/writing/microsoft-word-vertical-space-before-chapter-headings/)

- On the  **Home**  tab, go to the  **Styles ** group.
- Right click on the desired  **Heading style**  (for example Heading 1), and select  **Modify**.
- Click on  **Format ** (in the lower left corner), and select  **Paragraph** , and set the  **Spacing Before**  and  **Spacing After**  as desired.  Then click  **OK**.
- Click on  **Format ** again, and select  **Frame** , and set the  **Text Wrapping**  to  **None**.  Also set the desired  **Horizontal Position**  (for example to Center, as in the illustration shown in this article).  Then click  **OK**.

### Advanced Tables in Word: Table Styles, Breaks and Formulas

[https://www.youtube.com/watch?v=6IXJs3U27nQ](https://www.youtube.com/watch?v=6IXJs3U27nQ)

select the table,

in Layout -\> Formula-\>

#### 5 ways to link one document with another

[https://www.datanumen.com/blogs/5-smart-ways-link-one-word-document-another/](https://www.datanumen.com/blogs/5-smart-ways-link-one-word-document-another/)

There are many times when we need to link two or more related documents, so an update in source file can also refresh the text pasted on another one. Speaking of this, Word provides several distinct solutions. Let's take a look to find out more details.

![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_a91ecc4ca76d076d.jpg)

##### Method 1: Use "Paste Link" Option

1. Firstly, copy a range of text or the entire source document.
2. Then put insertion pointer properly and click "Paste" under "Home" tab.
3. Next choose "Paste Special" to open the same name dialog box. ![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_4af88341051f675a.jpg)
4. In the "Paste Special" box, select "Paste link".
5. And click to select a link type, such as "Formatted Text" or "Unformatted Text".
6. Lastly, click "OK". ![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_608af9a2bd87b3f6.jpg)

Any change made in source text should reflect in the new document if you update the link by right click and choosing "Update Link". ![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_7e08e30b771b2912.jpg)

##### Method 2: Insert an Object

1. To begin with, click "Insert" tab then click "Object" in "Text" group. ![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_67602f437887a6dc.jpg)
2. Next in "Object" box open, click "Create from File" tab first.
3. Then click "Browse" to select a file.
4. And check "Link to file" box.
5. Finally, click "OK". ![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_a0be8164ee6115fe.jpg)

Notice that you will insert the whole document into the new location. You can use the same way in method 1 to update the link.

##### Method 3: Create a Master Document Linking to Its Subdocument

It's also a good choice to create a master document that link to subdocument to connect the two files. We have a previous article that explains every detailed step. You can refer to this link: [How to Create a Master Document that Links to Multiple Subdocuments in Your Word](https://www.datanumen.com/blogs/create-master-document-links-multiple-subdocuments-word/)

##### Method 4: Hyperlink a Bookmark from Source Document

1. First and foremost, create a bookmark for a block of texts in the source document.
2. Then in a new document, put insertion pointer at a proper location. Click "Insert" tab and choose "Hyperlink". ![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_cb21d3c7b7eb22a0.jpg)
3. Put cursor at the "Address" text box and click "Browse for File" tab to select the file which contains the texts you need.
4. Next click "Bookmark" tab to open the "Select Place in Document" box.
5. Select the bookmark just created and click "OK" in both 2 boxes open. ![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_bf45dc97f6712106.jpg)

You will get a hyperlink as bellow: ![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_9ae9f1dd7fcb3b7b.jpg)

You can visit the source document through "Ctrl+ Click".

##### Method 5: Utilize the "IncludeText" Field

1. Click "Insert" tab first and the "Quick Parts" next.
2. Then choose "Field" on the drop-down menu. ![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_1b328fc38aeb4e8f.jpg)
3. In "Field" dialog box, choose "Links and References" for the "Categories".
4. Next select "IncludeText" field.
5. Enter the file name of the source document.
6. Lastly, click "OK". ![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_9653a4c30cda650a.jpg)

All texts of the source file shall be visible by now in the new document. To update the field, you can click on it and press "F9".

## Excel

Tuesday, June 22, 2021

[https://www.youtube.com/c/ExcelForFreelancers/videos](https://www.youtube.com/c/ExcelForFreelancers/videos) expert on Excel and VBA

[https://www.excelforfreelancers.com/product/150-of-my-best-excel-workbooks/](https://www.excelforfreelancers.com/product/150-of-my-best-excel-workbooks/)

[https://tongasoft.com/200-excel-workbook-for-free-downloads/](https://tongasoft.com/200-excel-workbook-for-free-downloads/)

### Visual Basic for Applications (VBA)

[https://docs.microsoft.com/en-us/office/vba/library-reference/concepts/getting-started-with-vba-in-office](https://docs.microsoft.com/en-us/office/vba/library-reference/concepts/getting-started-with-vba-in-office) Tuesday, June 22, 2021

# **Note taking and knowledge management tools**

# Knowledge management

[https://en.wikipedia.org/wiki/Knowledge\_management](https://en.wikipedia.org/wiki/Knowledge_management)

**Knowledge management**  ( **KM** ) is the process of creating, sharing, using and managing the [knowledge](https://en.wikipedia.org/wiki/Knowledge) and information of an organization.[[1]](https://en.wikipedia.org/wiki/Knowledge_management#cite_note-Davenport-1) It refers to a multidisciplinary approach to achieve organisational objectives by making the best use of knowledge.[[2]](https://en.wikipedia.org/wiki/Knowledge_management#cite_note-2UNC-2)

An established [discipline](https://en.wikipedia.org/wiki/List_of_academic_disciplines) since 1991,[[3]](https://en.wikipedia.org/wiki/Knowledge_management#cite_note-37HBR-3) KM includes courses taught in the fields of [business administration](https://en.wikipedia.org/wiki/Business_administration), [information systems](https://en.wikipedia.org/wiki/Information_systems), management, [library](https://en.wikipedia.org/wiki/Library_science), and [information science](https://en.wikipedia.org/wiki/Information_science).[[3]](https://en.wikipedia.org/wiki/Knowledge_management#cite_note-37HBR-3)[[4]](https://en.wikipedia.org/wiki/Knowledge_management#cite_note-39Nonaka-4) Other fields may contribute to KM research, including information and media, [computer science](https://en.wikipedia.org/wiki/Computer_science), [public health](https://en.wikipedia.org/wiki/Public_health) and [public policy](https://en.wikipedia.org/wiki/Policy).[[5]](https://en.wikipedia.org/wiki/Knowledge_management#cite_note-17Mental-5) Several universities offer dedicated [master's degrees](https://en.wikipedia.org/wiki/Master%27s_degree) in knowledge management.

## Personal knowledge management

[https://en.wikipedia.org/wiki/Personal\_knowledge\_management](https://en.wikipedia.org/wiki/Personal_knowledge_management)

**Personal knowledge management**  ( **PKM** ) is a process of collecting information that a person uses to gather, classify, store, search, retrieve and share [knowledge](https://en.wikipedia.org/wiki/Knowledge) in their daily activities ([Grundspenkis 2007](https://en.wikipedia.org/wiki/Personal_knowledge_management#CITEREFGrundspenkis2007)) and the way in which these processes support work activities ([Wright 2005](https://en.wikipedia.org/wiki/Personal_knowledge_management#CITEREFWright2005)). It is a response to the idea that [knowledge workers](https://en.wikipedia.org/wiki/Knowledge_worker) need to be responsible for their own growth and learning ([Smedley 2009](https://en.wikipedia.org/wiki/Personal_knowledge_management#CITEREFSmedley2009)). It is a bottom-up approach to [knowledge management](https://en.wikipedia.org/wiki/Knowledge_management) (KM) ([Pollard 2008](https://en.wikipedia.org/wiki/Personal_knowledge_management#CITEREFPollard2008)).

#### Skills[[edit source](https://en.wikipedia.org/w/index.php?title=Personal_knowledge_management&action=edit&section=4)]

Skills associated with personal knowledge management include:

- Reflection. [Continuous improvement](https://en.wikipedia.org/wiki/Kaizen) on how the individual operates.
- Manage learning. Manage how and when the individual learns.
- [Information literacy](https://en.wikipedia.org/wiki/Information_literacy). Understanding what information is important and how to find unknown information.
- Organizational skills. Personal [librarianship](https://en.wikipedia.org/wiki/Librarian). Personal [categorization](https://en.wikipedia.org/wiki/Categorization) and [taxonomies](https://en.wikipedia.org/wiki/Taxonomy_(general)).
- [Networking](https://en.wikipedia.org/wiki/Social_network) with others. Knowing what your network of people knows. Knowing who might have additional knowledge and resources to help you
- Researching, [canvassing](https://en.wikipedia.org/wiki/Canvassing), paying [attention](https://en.wikipedia.org/wiki/Attention), [interviewing](https://en.wikipedia.org/wiki/Interviewing) and [observational](https://en.wikipedia.org/wiki/Observation) "cultural anthropology" skills
- Communication skills. [Perception](https://en.wikipedia.org/wiki/Perception), [intuition](https://en.wikipedia.org/wiki/Intuition_(knowledge)), [expression](https://en.wikipedia.org/wiki/Emotional_expression), [visualization](https://en.wikipedia.org/wiki/Mental_image) and [interpretation](https://en.wikipedia.org/wiki/Interpretation_(logic)).
- Creative skills. Imagination, [pattern recognition](https://en.wikipedia.org/wiki/Pattern_recognition), appreciation, innovation, inference. Understanding of [complex adaptive systems](https://en.wikipedia.org/wiki/Complex_adaptive_systems).
- [Collaboration](https://en.wikipedia.org/wiki/Collaboration) skills. Coordination, [synchronization](https://en.wikipedia.org/wiki/Synchronization), [experimentation](https://en.wikipedia.org/wiki/Experimentation), [cooperation](https://en.wikipedia.org/wiki/Cooperation) and [design](https://en.wikipedia.org/wiki/Design).

#### PKM has also been linked to these tools:[[_citation needed_](https://en.wikipedia.org/wiki/Wikipedia:Citation_needed)]

- [Social bookmarking](https://en.wikipedia.org/wiki/Social_bookmarking) and [enterprise bookmarking](https://en.wikipedia.org/wiki/Enterprise_bookmarking)
- Knowledge logs (k-logs)
- Email, calendars, task managers
- [Virtual assistants](https://en.wikipedia.org/wiki/Virtual_assistant_(occupation))
- [Wikis](https://en.wikipedia.org/wiki/Wiki), including [personal wikis](https://en.wikipedia.org/wiki/Personal_wiki) and [semantic wikis](https://en.wikipedia.org/wiki/Semantic_wiki)

Other useful tools include stories and [narrative inquiry](https://en.wikipedia.org/wiki/Narrative_inquiry), [decision support systems](https://en.wikipedia.org/wiki/Decision_support_system), various kinds of [node–link diagram](https://en.wikipedia.org/wiki/Graph_(discrete_mathematics)) (such as [argument maps](https://en.wikipedia.org/wiki/Argument_map), [mind maps](https://en.wikipedia.org/wiki/Mind_map), [concept maps](https://en.wikipedia.org/wiki/Concept_map)), and similar [information visualization](https://en.wikipedia.org/wiki/Information_visualization) techniques. Individuals use these tools to capture ideas, expertise, experience, opinions or thoughts, and this "voicing" will encourage cognitive diversity and promote free exchanges away from a centralized policed knowledge repository.[[_citation needed_](https://en.wikipedia.org/wiki/Wikipedia:Citation_needed)] The goal is to facilitate knowledge sharing and personal content management.

Davies and colleagues mentioned the following as examples of [software applications](https://en.wikipedia.org/wiki/Software_application) that have been used to build PKBs:[[1]](https://en.wikipedia.org/wiki/Personal_knowledge_base#cite_note-Davies_2005-1)

[**Open source**](https://en.wikipedia.org/wiki/Open_source)

- [Compendium (software)](https://en.wikipedia.org/wiki/Compendium_(software))
- [Haystack (MIT project)](https://en.wikipedia.org/wiki/Haystack_(MIT_project))

**Closed source**

- [MyLifeBits](https://en.wikipedia.org/wiki/MyLifeBits)
- [NoteCards](https://en.wikipedia.org/wiki/NoteCards)
- [Personal Knowbase](https://en.wikipedia.org/wiki/Personal_Knowbase)
- [TheBrain](https://en.wikipedia.org/wiki/TheBrain)
- [Tinderbox (application software)](https://en.wikipedia.org/wiki/Tinderbox_(application_software))

### User modelling or User Profile

[https://en.wikipedia.org/wiki/User\_modeling](https://en.wikipedia.org/wiki/User_modeling)

Information about users can be gathered in several ways. There are three main methods:

- **Asking for specific facts while (first) interacting with the system**[[2]](https://en.wikipedia.org/wiki/User_modeling#cite_note-JohnsonTaatgen-2)

Mostly this kind of data gathering is linked with the registration process. While registering users are asked for specific facts, their likes and dislikes and their needs. Often the given answers can be altered afterwards.

- **Learning users' preferences by observing and interpreting their interactions with the system** [[2]](https://en.wikipedia.org/wiki/User_modeling#cite_note-JohnsonTaatgen-2)

In this case users are not asked directly for their personal data and preferences, but this information is derived from their behavior while interacting with the system. The ways they choose to accomplish a tasks, the combination of things they takes interest in, these observations allow inferences about a specific user. The application dynamically learns from observing these interactions. Different [machine learning](https://en.wikipedia.org/wiki/Machine_learning) algorithms may be used to accomplish this task.

- **A hybrid approach which asks for explicit feedback and alters the user model by adaptive learning** [[5]](https://en.wikipedia.org/wiki/User_modeling#cite_note-Montaner-5)

This approach is a mixture of the ones above. Users have to answer specific questions and give explicit feedback. Furthermore, their interactions with the system are observed and the derived information are used to automatically adjust the user models.

## Methods and Tools for Managing Knowledge and Information

### Peronal wiki

[https://en.wikipedia.org/wiki/Personal\_wiki](https://en.wikipedia.org/wiki/Personal_wiki)

A  **personal wiki**  is [wiki](https://en.wikipedia.org/wiki/Wiki) software that allows individual users to organize information on their [desktop](https://en.wikipedia.org/wiki/Desktop_environment) or [mobile computing devices](https://en.wikipedia.org/wiki/Mobile_computing) in a manner similar to [community wikis](https://en.wikipedia.org/wiki/Wiki#Communities), but without [collaborative software](https://en.wikipedia.org/wiki/Collaborative_software) or multiple users.

Personal wiki software can be broadly divided into two categories:

- Multi-user applications with personal editions (such as [MoinMoin](https://en.wikipedia.org/wiki/MoinMoin) or [TWiki](https://en.wikipedia.org/wiki/TWiki)), installed for standalone use and inaccessible to outside users, which may require additional software such as a [web server](https://en.wikipedia.org/wiki/Web_server), [database management system](https://en.wikipedia.org/wiki/Database_management_system) and/or [WAMP](https://en.wikipedia.org/wiki/WAMP)/[LAMP](https://en.wikipedia.org/wiki/LAMP_(software_bundle)) bundle[[1]](https://en.wikipedia.org/wiki/Personal_wiki#cite_note-1)
- Applications designed for single users, not dependent on a database engine or web server

[https://en.wikipedia.org/wiki/List\_of\_wiki\_software#Personal\_wiki\_software](https://en.wikipedia.org/wiki/List_of_wiki_software#Personal_wiki_software)

#### Personal wiki software[[edit source](https://en.wikipedia.org/w/index.php?title=List_of_wiki_software&action=edit&section=9)]

_Further information: _[_Personal wiki_](https://en.wikipedia.org/wiki/Personal_wiki)

- [ConnectedText](https://en.wikipedia.org/wiki/ConnectedText) is a [commercial](https://en.wikipedia.org/wiki/Non-free_software) Windows-based personal wiki system with features including [full text searches](https://en.wikipedia.org/wiki/Full-text_search), [visual link tree](https://en.wikipedia.org/wiki/Tree_(data_structure)), customizable interface, image and file control, CSS-based page display, exports to HTML and HTML Help, and plug-ins.
- [Journler](https://en.wikipedia.org/wiki/Journler) is a free, open-source personal information manager with personal wiki features for OS X.
- [MyInfo](https://en.wikipedia.org/wiki/MyInfo) is a commercial, Windows-based personal information manager with wiki features.
- [TiddlyWiki](https://en.wikipedia.org/wiki/TiddlyWiki) is a free, open-source personal use (single-machine) wiki based on HTML/JavaScript for any browser and OS. It supports customization and a wide range of addons.
- [WhizFolders](https://en.wikipedia.org/wiki/Whizfolders) is a commercial Windows-based personal wiki software with rich text wiki items that support inserting links to other wiki items or external files.
- [Zim](https://en.wikipedia.org/wiki/Zim_(software)) is a free, open-source standalone wiki based on Python and GTK with a WYSIWYG editor.

#### Hosted-only software[[edit source](https://en.wikipedia.org/w/index.php?title=List_of_wiki_software&action=edit&section=10)]

_Further information: _[_Wiki hosting service_](https://en.wikipedia.org/wiki/Wiki_hosting_service)

- [Knowledge Plaza](https://en.wikipedia.org/wiki/Knowledge_Plaza) is a knowledge management tool that provides both wiki environments for collaborative topic/project work and an [enterprise bookmarking](https://en.wikipedia.org/wiki/Enterprise_bookmarking) tool.
- [Nuclino](https://en.wikipedia.org/wiki/Nuclino) is a [real-time](https://en.wikipedia.org/wiki/Collaborative_real-time_editor) [wiki](https://en.wikipedia.org/wiki/Wiki_software) for team collaboration.

#### Content management and social software with wiki functionality[[edit source](https://en.wikipedia.org/w/index.php?title=List_of_wiki_software&action=edit&section=11)]

_Further information: _[_Content management system_](https://en.wikipedia.org/wiki/Content_management_system)_ and _[_Enterprise social software_](https://en.wikipedia.org/wiki/Enterprise_social_software)

#### Java-based[[edit source](https://en.wikipedia.org/w/index.php?title=List_of_wiki_software&action=edit&section=12)]

- [ConcourseConnect](https://en.wikipedia.org/wiki/ConcourseConnect) is a freely available [J2EE](https://en.wikipedia.org/wiki/Jakarta_EE) application made by [Concursive](https://en.wikipedia.org/wiki/Concursive) which brings together Corporate [Social Networking](https://en.wikipedia.org/wiki/Social_Networking), [Online Community](https://en.wikipedia.org/wiki/Online_Community), [Business directory](https://en.wikipedia.org/wiki/Business_directory), and [Customer relationship management](https://en.wikipedia.org/wiki/Customer_relationship_management) capabilities. Features include wiki, blog, [document management](https://en.wikipedia.org/wiki/Document_management), ratings, reviews, online classified advertising]]\\, and project management modules. The wiki allows both wiki markup and WYSIWYG editing.
- [Confluence](https://en.wikipedia.org/wiki/Confluence_(software)) is a commercial J2EE application which combines wiki and some [blog](https://en.wikipedia.org/wiki/Blog) functionality. Its features include PDF page export and page refactoring, and it can be run on any application server using any RDBMS backend.
- [IBM Connections](https://en.wikipedia.org/wiki/IBM_Connections) is an [Enterprise Social Software](https://en.wikipedia.org/wiki/Enterprise_Social_Software) made by [IBM](https://en.wikipedia.org/wiki/IBM) which combines Wikis, Blogs, Files, Forums, Microblogging, Social Analytics, and document management.
- [Jive](https://en.wikipedia.org/wiki/Jive_(software)) (formerly known as Clearspace, Jive SBS and Jive Engage) is a commercial J2EE application, made by [Jive Software](https://en.wikipedia.org/wiki/Jive_Software), which combines wiki, blog and document management functionality. Jive uses WYSIWYG editing, and includes workflow management.
- [Liferay](https://en.wikipedia.org/wiki/Liferay) is an open source enterprise portal project with a built-in web content management and web application framework. Core portlets offer a great number of functionalities, including Wiki (both Creole and MediaWiki syntax).
- [Mindquarry](https://en.wikipedia.org/wiki/Mindquarry) creates a WYSIWYG wiki for each team. It is built using [Apache Cocoon](https://en.wikipedia.org/wiki/Apache_Cocoon) and thus based on Java (Mozilla Public License)
- [Traction TeamPage](https://en.wikipedia.org/wiki/Traction_TeamPage) is a commercial enterprise wiki also incorporating blog, project management, document management, discussion and tagging capabilities. The wiki has a draft moderation capability allowing administrators to indicate who can read published vs. draft versions, and who can publish vs. author and edit. The dynamic view architecture allows for easy organization of pages and to collect any set of pages for view, email or export. It is based on the principles of [Douglas Engelbart](https://en.wikipedia.org/wiki/Douglas_Engelbart)'s [On-Line System](https://en.wikipedia.org/wiki/On-Line_System) (NLS) which aggregates multiple blog/wiki spaces using a sophisticated permission and inline comment model.
- [XWiki](https://en.wikipedia.org/wiki/XWiki) includes the standard wiki functionality as well as WYSIWYG editing, [OpenDocument](https://en.wikipedia.org/wiki/OpenDocument) based document import/export, semantic annotations and tagging, and advanced permissions management.

### notetaking

#### Comparison of note-taking software

[https://en.wikipedia.org/wiki/Comparison\_of\_note-taking\_software](https://en.wikipedia.org/wiki/Comparison_of_note-taking_software)

| **Name** | **Developer(s)** | [**License**](https://en.wikipedia.org/wiki/Software_license) | **Platforms** |
| --- | --- | --- | --- |
| [**AllMyNotes Organizer**](https://en.wikipedia.org/wiki/AllMyNotes_Organizer) | Vladonai Software | [Proprietary](https://en.wikipedia.org/wiki/Proprietary_software), [Freemium](https://en.wikipedia.org/wiki/Freemium) | Microsoft Windows |
| --- | --- | --- | --- |
| [**BasKet Note Pads**](https://en.wikipedia.org/wiki/BasKet_Note_Pads) | [KDE](https://en.wikipedia.org/wiki/KDE) | [GPL-2.0-or-later](https://en.wikipedia.org/wiki/GNU_General_Public_License) | [Unix-like](https://en.wikipedia.org/wiki/Unix-like) ([KDE](https://en.wikipedia.org/wiki/KDE)) |
| [**CintaNotes**](https://en.wikipedia.org/wiki/CintaNotes) | Cinta Software | [Proprietary](https://en.wikipedia.org/wiki/Proprietary_software), [Freemium](https://en.wikipedia.org/wiki/Freemium) | Microsoft Windows |
| [**ConnectedText**](https://en.wikipedia.org/wiki/ConnectedText) | Eduardo Mauro | [Proprietary](https://en.wikipedia.org/wiki/Proprietary_software), [Commercial](https://en.wikipedia.org/wiki/Commercial_software) | Microsoft Windows |
| [**Day One**](https://en.wikipedia.org/wiki/Day_One_(app)) | Bloom Built | [Proprietary](https://en.wikipedia.org/wiki/Proprietary_software), [Commercial](https://en.wikipedia.org/wiki/Commercial_software) | macOS, iOS, Android |
| [**Dropbox Paper**](https://en.wikipedia.org/wiki/Dropbox_Paper) | Dropbox | [Proprietary](https://en.wikipedia.org/wiki/Proprietary_software), [Freemium](https://en.wikipedia.org/wiki/Freemium) | Android, IOS, web-based |
| [**Evernote**](https://en.wikipedia.org/wiki/Evernote) | Evernote Corporation | [Proprietary](https://en.wikipedia.org/wiki/Proprietary_software), [Freemium](https://en.wikipedia.org/wiki/Freemium) for personal use, per-seat licensing for business | Android, iOS, macOS, Microsoft Windows 7/8/10, Microsoft Windows Phone, and [web-based](https://en.wikipedia.org/wiki/Software_as_a_service) |
| [**Gnote**](https://en.wikipedia.org/wiki/Gnote) | Aurimas Černius | [GPL-3.0-or-later](https://en.wikipedia.org/wiki/GNU_General_Public_License) | Linux |
| [**Google Keep**](https://en.wikipedia.org/wiki/Google_Keep) | [Google](https://en.wikipedia.org/wiki/Google) | [Proprietary](https://en.wikipedia.org/wiki/Proprietary_software), no-cost | Android, iOS, Chrome OS, browser based |
| [**Joplin**](https://en.wikipedia.org/wiki/Joplin_App) | [laurent22](https://github.com/laurent22) et al | [MIT](https://en.wikipedia.org/wiki/MIT_License) | Microsoft Windows, Mac, Linux, iOS, Android |
| [**KeyNote NF**](https://en.wikipedia.org/wiki/Keynote_(notetaking_software)) | Marek Jedliński, Tranglos Software | [MPL-2.0](https://en.wikipedia.org/wiki/Mozilla_Public_License) | Microsoft Windows |
| [**Memonic**](https://en.wikipedia.org/wiki/Memonic) | Nektoon AG | [Proprietary](https://en.wikipedia.org/wiki/Proprietary_software), [Freemium](https://en.wikipedia.org/wiki/Freemium)[[Notes 1]](https://en.wikipedia.org/wiki/Comparison_of_note-taking_software#cite_note-1) | Android (not released yet), iOS, macOS, Microsoft Windows XP/Vista/7/Mobile [web-based](https://en.wikipedia.org/wiki/Software_as_a_service) |
| [**Microsoft OneNote**](https://en.wikipedia.org/wiki/Microsoft_OneNote) | [Microsoft](https://en.wikipedia.org/wiki/Microsoft) | [Proprietary](https://en.wikipedia.org/wiki/Proprietary_software), [Shareware](https://en.wikipedia.org/wiki/Shareware)/[Freeware](https://en.wikipedia.org/wiki/Freeware)/[Freemium](https://en.wikipedia.org/wiki/Freemium)[[Notes 2]](https://en.wikipedia.org/wiki/Comparison_of_note-taking_software#cite_note-2) | Android, macOS, iOS (iPad, iPhone), Microsoft Windows 7/8/10, Microsoft Windows Server 2008R2/2012R2/2016, Microsoft Windows Phone 8/8.1/10, [web-based](https://en.wikipedia.org/wiki/Software_as_a_service), mobile web |
| [**MyInfo**](https://en.wikipedia.org/wiki/MyInfo) | Milenix Software | [Proprietary](https://en.wikipedia.org/wiki/Proprietary_software), [Shareware](https://en.wikipedia.org/wiki/Shareware) | Microsoft Windows XP/Vista/7/10 |
| [**MyNotex**](https://en.wikipedia.org/wiki/MyNotex) | Massimo Nardello | [GPL-3.0-or-later](https://en.wikipedia.org/wiki/GNU_General_Public_License) | Linux |
| [**Notational Velocity**](https://en.wikipedia.org/wiki/Notational_Velocity) | Zachary Schneirov | [GPL-3.0-or-later](https://en.wikipedia.org/wiki/GNU_General_Public_License) | macOS |
| [**Notes**](https://en.wikipedia.org/wiki/Notes_(Apple)) | Apple | [Proprietary](https://en.wikipedia.org/wiki/Proprietary_software) | [macOS](https://en.wikipedia.org/wiki/MacOS), [iOS](https://en.wikipedia.org/wiki/IOS), web-based |
| [**Notion**](https://en.wikipedia.org/wiki/Notion_(app)) | Notion Labs Inc. | [Proprietary](https://en.wikipedia.org/wiki/Proprietary_software), [Freemium](https://en.wikipedia.org/wiki/Freemium) | Android, macOS, iOS (iPad, iPhone), Microsoft Windows, web-based |
| [**Okular**](https://en.wikipedia.org/wiki/Okular) | Okular Team ([KDE](https://en.wikipedia.org/wiki/KDE)) | [GPL-2.0-only](https://en.wikipedia.org/wiki/GNU_General_Public_License) or [GPL-3.0-only](https://en.wikipedia.org/wiki/GNU_General_Public_License) | [KDE](https://en.wikipedia.org/wiki/KDE)-enabled Linux, Unix, Microsoft Windows, macOS, \*BSD[[1]](https://en.wikipedia.org/wiki/Comparison_of_note-taking_software#cite_note-3) |
| [**Open-Sankoré**](https://en.wikipedia.org/wiki/Open-Sankor%C3%A9) | Sankoré | [LGPL-2.0-only](https://en.wikipedia.org/wiki/GNU_Lesser_General_Public_License) | Linux, macOS, Unix, Microsoft Windows |
| [**Org-mode**](https://en.wikipedia.org/wiki/Org-mode)** (**[**Emacs**](https://en.wikipedia.org/wiki/Emacs)**)** | Carsten Dominik, et al. | [GPL-3.0-or-later](https://en.wikipedia.org/wiki/GNU_General_Public_License) | Linux, macOS, Unix, Microsoft Windows ([Emacs mode](https://en.wikipedia.org/wiki/Emacs)) |
| [**Outline**](https://en.wikipedia.org/wiki/Outline_(software)) | Gorillized Corporation | [Proprietary](https://en.wikipedia.org/wiki/Proprietary_software), [Commercial](https://en.wikipedia.org/wiki/Commercial_software) | macOS, iOS |
| [**PDF Studio**](https://en.wikipedia.org/wiki/PDF_Studio) | Qoppa Software | [Proprietary](https://en.wikipedia.org/wiki/Proprietary_software), [Shareware](https://en.wikipedia.org/wiki/Shareware) | Linux, macOS, Microsoft Windows, [web-based](https://en.wikipedia.org/wiki/Software_as_a_service) |
| [**Personal Knowbase**](https://en.wikipedia.org/wiki/Personal_Knowbase) | Bitsmith Software | [Proprietary](https://en.wikipedia.org/wiki/Proprietary_software), [Commercial](https://en.wikipedia.org/wiki/Commercial_software) | Microsoft Windows |
| [**QOwnNotes**](https://en.wikipedia.org/wiki/QOwnNotes) | Patrizio Bekerle | [GPL-2.0-only](https://en.wikipedia.org/wiki/GNU_General_Public_License) | Linux, macOS, Microsoft Windows |
| [**Qiqqa**](https://en.wikipedia.org/wiki/Qiqqa) | Quantisle Ltd. | [Proprietary](https://en.wikipedia.org/wiki/Proprietary_software), [Freemium](https://en.wikipedia.org/wiki/Freemium) | Microsoft Windows XP/Vista/7/8, Web-based, Android |
| [**Simplenote**](https://en.wikipedia.org/wiki/Simplenote) | Automattic inc. | Clients: [GPL-2.0-only](https://en.wikipedia.org/wiki/GNU_General_Public_License)
 Server: [Proprietary](https://en.wikipedia.org/wiki/Proprietary_software) | [Cross-platform](https://en.wikipedia.org/wiki/Cross-platform) |
| [**Standard Notes**](https://en.wikipedia.org/w/index.php?title=Standard_Notes&action=edit&redlink=1) | Standard Notes. | ? | [Cross-platform](https://en.wikipedia.org/wiki/Cross-platform) (Available for Android, Windows, Linux and other major OS) |
| [**TagSpaces**](https://en.wikipedia.org/wiki/TagSpaces) | TagSpaces UG | [AGPL-3.0-only](https://en.wikipedia.org/wiki/GNU_Affero_General_Public_License) | [Cross-platform](https://en.wikipedia.org/wiki/Cross-platform) (browser, [web-based](https://en.wikipedia.org/wiki/Software_as_a_service)) |
| [**TiddlyWiki**](https://en.wikipedia.org/wiki/TiddlyWiki) | Jeremy Ruston | [BSD-3-Clause](https://en.wikipedia.org/wiki/BSD_licenses) | [Cross-platform](https://en.wikipedia.org/wiki/Cross-platform) (single HTML file, runs in browser, on a nodeJS server, on Android and IOS) |
| [**Tomboy**](https://en.wikipedia.org/wiki/Tomboy_(software)) | Alex Graveley | [LGPL-2.1-or-later](https://en.wikipedia.org/wiki/GNU_Lesser_General_Public_License) | [Cross-platform](https://en.wikipedia.org/wiki/Cross-platform) ([Mono](https://en.wikipedia.org/wiki/Mono_(software))/[GTK+](https://en.wikipedia.org/wiki/GTK%2B)) |
| [**Ulysses**](https://en.wikipedia.org/wiki/Ulysses_(text_editor)) | The Soulmen | [SaaS](https://en.wikipedia.org/wiki/SaaS) | macOS, iOS |
| [**Whizfolders**](https://en.wikipedia.org/wiki/Whizfolders) | AvniTech Solutions | [Proprietary](https://en.wikipedia.org/wiki/Proprietary_software), [Commercial](https://en.wikipedia.org/wiki/Commercial_software) | Microsoft Windows |
| [**Microsoft Windows Journal**](https://en.wikipedia.org/wiki/Microsoft_Windows_Journal) | [Microsoft](https://en.wikipedia.org/wiki/Microsoft) | [Proprietary](https://en.wikipedia.org/wiki/Proprietary_software), [Commercial](https://en.wikipedia.org/wiki/Commercial_software) | Microsoft Windows XP Tablet PC edition, Microsoft Windows Vista, Microsoft Windows 7/8/10 (included with OS) |
| [**Zim**](https://en.wikipedia.org/wiki/Zim_(software)) | Jaap Karssenberg | [GPL-2.0-or-later](https://en.wikipedia.org/wiki/GNU_General_Public_License) | [Cross-platform](https://en.wikipedia.org/wiki/Cross-platform) ([Python](https://en.wikipedia.org/wiki/Python_(programming_language)), [GTK+](https://en.wikipedia.org/wiki/GTK%2B)) |
| [**ZOHO Notebook**](https://en.wikipedia.org/wiki/Zoho_Office_Suite) | [ZOHO Corporation](https://en.wikipedia.org/wiki/ZOHO_Corporation) | [Proprietary](https://en.wikipedia.org/wiki/Proprietary_software), [Commercial](https://en.wikipedia.org/wiki/Commercial_software), [Freemium](https://en.wikipedia.org/wiki/Freemium) |
 |

#### Zettelkasten

[https://en.wikipedia.org/wiki/Zettelkasten](https://en.wikipedia.org/wiki/Zettelkasten)

The  **zettelkasten**  (German: "slip box", plural  **zettelkästen** ) is a method of [note-taking](https://en.wikipedia.org/wiki/Note-taking) and [personal knowledge management](https://en.wikipedia.org/wiki/Personal_knowledge_management) used in research and study.

![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_c95bad146e13a06a.jpg)

A zettelkasten consists of many individual notes with ideas and other short pieces of information that are taken down as they occur or are acquired. The notes are numbered hierarchically, so that new notes may be inserted at the appropriate place, and contain [metadata](https://en.wikipedia.org/wiki/Metadata) to allow the note-taker to associate notes with each other. For example, notes may contain [tags](https://en.wikipedia.org/wiki/Tag_(metadata)) that describe key aspects of the note, and they may reference other notes. The numbering, metadata, format and structure of the notes is subject to variation depending on the specific method employed.

A zettelkasten may be created and used in a digital format, sometimes using personal knowledge management software. But it can be and has long been done on paper using [index cards](https://en.wikipedia.org/wiki/Index_card).

One researcher famous for his extensive use of the method was the sociologist [Niklas Luhmann](https://en.wikipedia.org/wiki/Niklas_Luhmann) (1927–1998). Luhmann built up a zettelkasten of some 90,000 index cards for his research, and credited it for enabling his extraordinarily prolific writing (including over 70 books and 400 scholarly articles).

#### Outlier processor (tree structure text files)

[https://en.wikipedia.org/wiki/Outliner](https://en.wikipedia.org/wiki/Outliner)

##### File formats[[edit source](https://en.wikipedia.org/w/index.php?title=Outliner&action=edit&section=3)]

Several file formats support an outline structure natively or encourage the use/creation of outline structures.

- [XML](https://en.wikipedia.org/wiki/XML) - XML's purpose is to aid information systems in sharing structured data
- [HTML](https://en.wikipedia.org/wiki/HTML)/[XHTML](https://en.wikipedia.org/wiki/XHTML) - outlines relatively trivial thanks to nested markup
- [OPML](https://en.wikipedia.org/wiki/OPML) - simple XML-based format designed for outlines, but also used for syndication feedlists
- [OML](https://en.wikipedia.org/wiki/OML) - alternative to OPML
- [RDF](https://en.wikipedia.org/wiki/Resource_Description_Framework) - (various formats) has web-oriented node & arc graph model, a subset can be used for outline
- [XOXO](https://en.wikipedia.org/wiki/XOXO_(microformat)) - dedicated [HTML](https://en.wikipedia.org/wiki/HTML)-based [microformat](https://en.wikipedia.org/wiki/Microformat) for outlines
- [CHM](https://en.wikipedia.org/wiki/Microsoft_Compiled_HTML_Help) - standard Windows format for help, books, etc.

##### Desktop outliners[[edit source](https://en.wikipedia.org/w/index.php?title=Outliner&action=edit&section=5)]

| **Name** | **Operating system** | **Notes** |
| --- | --- | --- |
| [AllMyNotes Organizer](https://en.wikipedia.org/wiki/AllMyNotes_Organizer) | Windows | Can password-protect file access, supports [skins](https://en.wikipedia.org/wiki/Skin_(computing)). Free and Portable editions available. |
| --- | --- | --- |
| [Ecco Pro](https://en.wikipedia.org/wiki/Ecco_Pro) | Windows | Freeware outliner. No longer supported. Large users' group. EccoMV add-on for RTF pane. |
| [FreeMind](https://en.wikipedia.org/wiki/FreeMind) | cross-platform (Java) | Mind mapper and outliner with comments and graphical connections (links) |
| [GrandView](https://en.wikipedia.org/wiki/GrandView_(software)) | MS-DOS | Single-pane outliner dating from the 1980s. No longer supported. Clone feature. |
| [KAMAS](https://en.wikipedia.org/wiki/KAMAS_(program)) | [CP/M](https://en.wikipedia.org/wiki/CP/M), later [MS-DOS](https://en.wikipedia.org/wiki/MS-DOS) | (Knowledge and Mind Amplification System) Not as successful for MS-DOS as it had been for CP/M. Limited export capability. |
| [KeyNote NF](https://en.wikipedia.org/wiki/Keynote_(notetaking_software)) (formerly Keynote) | Windows | [Mozilla Public License](https://en.wikipedia.org/wiki/Mozilla_Public_License). |
| [KJots](https://en.wikipedia.org/wiki/KJots) | Linux |
 |
| [Leo](https://en.wikipedia.org/wiki/Leo_(text_editor)) | Windows/Linux/MacOS | Text editor with outlines; remarkably flexible tree structure. Written in [Python](https://en.wikipedia.org/wiki/Python_(programming_language)) using [Qt](https://en.wikipedia.org/wiki/Qt_(framework)). |
| [MORE](https://en.wikipedia.org/wiki/MORE_(application)) | Mac OS 7/8/9 | Classic Mac outliner from the late 1980s & early 1990s |
| [MyInfo](https://en.wikipedia.org/wiki/MyInfo) | Windows | Two-pane, but can emulate basic one-pane outliner as well. |
| [Outline](https://en.wikipedia.org/wiki/Outline_(software)) | Mac OS X | Digital notebook for private and business use. |
| [OmniOutliner](https://en.wikipedia.org/wiki/OmniOutliner) | Mac OS X | Single/double pane outliner with columns and extensive customization capabilities. |
| [OrgMode](https://en.wikipedia.org/wiki/Org-mode) | cross-platform | Emacs outlining mode |
| [Scrivener](https://en.wikipedia.org/wiki/Scrivener_(software)) | Mac OS & Windows; Linux beta | Flexible content generator for writers; powerful multipane outliner |
| [TheBrain](https://en.wikipedia.org/wiki/TheBrain) | Windows, Mac, iOS, Android | Free form graphical outliner |
| [Treeline outliner](https://en.wikipedia.org/wiki/Treeline_outliner) | Windows/Linux | Free 3-pane outliner; 2nd pane shows details of highlighted node, 3rd pane lists details of its children. |
| [Whizfolders](https://en.wikipedia.org/wiki/Whizfolders) | Windows | Two-pane outliner where the left pane contains the outlined list of item titles and the right pane shows the details of selected item |

##### Mobile device outliners[[edit source](https://en.wikipedia.org/w/index.php?title=Outliner&action=edit&section=6)]

| **Name** | **Operating system** | **Notes** |
| --- | --- | --- |
| [Outline](https://en.wikipedia.org/wiki/Outline_(software)) | iOS | Digital notebook for private and business use. |
| --- | --- | --- |

##### Browser-based outliners[[edit source](https://en.wikipedia.org/w/index.php?title=Outliner&action=edit&section=7)]

This table shows a list of notable browser-based outliners categorised by the functionality that they provide (see 'Design' above). Browser-based outliners run inside a desktop or mobile web browser (smart phone or tablet) and may synchronise the outline's data with a remote server or store it locally on the user's device.

| **Name** | **Promote/ demote** | **Clone** | **Styling** | **Expose/ hide levels** | **Hoist** | **Search** | **Import OPML** | **Export OPML** | **Export other** | **Collaboration** | **Files** |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [Checkvist](https://en.wikipedia.org/w/index.php?title=Checkvist&action=edit&redlink=1) | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [The Outliner of Giants](https://en.wikipedia.org/wiki/The_Outliner_of_Giants) | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes |
| [Workflowy](https://en.wikipedia.org/wiki/Workflowy) |
 | Yes | Yes | Yes |
 | Yes |
 |
 |
 | Yes | Yes

 |

#### Tag (metadata)

[https://en.wikipedia.org/wiki/Tag\_(metadata)#Knowledge\_tags](https://en.wikipedia.org/wiki/Tag_(metadata)#Knowledge_tags)

In [information systems](https://en.wikipedia.org/wiki/Information_system), a  **tag**  is a [keyword or term](https://en.wikipedia.org/wiki/Index_term) assigned to a piece of information (such as an [Internet bookmark](https://en.wikipedia.org/wiki/Bookmark_(World_Wide_Web)), [digital image](https://en.wikipedia.org/wiki/Digital_image), database [record](https://en.wikipedia.org/wiki/Record_(computer_science)), or [computer file](https://en.wikipedia.org/wiki/Computer_file)). This kind of [metadata](https://en.wikipedia.org/wiki/Metadata) helps describe an item and allows it to be found again by browsing or searching.[[1]](https://en.wikipedia.org/wiki/Tag_(metadata)#cite_note-1) Tags are generally chosen informally and personally by the item's creator or by its viewer, depending on the system, although they may also be chosen from a [controlled vocabulary](https://en.wikipedia.org/wiki/Controlled_vocabulary).[[2]](https://en.wikipedia.org/wiki/Tag_(metadata)#cite_note-Smith2008-2): 68 

Tagging was popularized by [websites](https://en.wikipedia.org/wiki/Website) associated with [Web 2.0](https://en.wikipedia.org/wiki/Web_2.0) and is an important feature of many Web 2.0 services.[[2]](https://en.wikipedia.org/wiki/Tag_(metadata)#cite_note-Smith2008-2)[[3]](https://en.wikipedia.org/wiki/Tag_(metadata)#cite_note-Breslin-et-al-2009-3) It is now also part of other [database systems](https://en.wikipedia.org/wiki/Database_system), [desktop applications](https://en.wikipedia.org/wiki/Desktop_application), and [operating systems](https://en.wikipedia.org/wiki/Operating_system).

#### concept- and mind-mapping software

[https://en.wikipedia.org/wiki/Concept\_map](https://en.wikipedia.org/wiki/Concept_map)

A concept map is a way of representing relationships between [ideas](https://en.wikipedia.org/wiki/Idea), [images](https://en.wikipedia.org/wiki/Image), or [words](https://en.wikipedia.org/wiki/Word) in the same way that a [sentence diagram](https://en.wikipedia.org/wiki/Sentence_diagram) represents the grammar of a sentence, a road map represents the locations of highways and towns, and a [circuit diagram](https://en.wikipedia.org/wiki/Circuit_diagram) represents the workings of an electrical appliance. In a concept map, each word or phrase connects to another, and links back to the original idea, word, or phrase. Concept maps are a way to develop logical thinking and study skills by revealing connections and helping students see how individual ideas form a larger whole. An example of the use of concept maps is provided in the context of learning about types of fuel.

A  **concept map**  or  **conceptual diagram**  is a [diagram](https://en.wikipedia.org/wiki/Diagram) that depicts suggested relationships between [concepts](https://en.wikipedia.org/wiki/Concept).[[1]](https://en.wikipedia.org/wiki/Concept_map#cite_note-1) Concept maps may be used by [instructional designers](https://en.wikipedia.org/wiki/Instructional_designer), [engineers](https://en.wikipedia.org/wiki/Engineer), [technical writers](https://en.wikipedia.org/wiki/Technical_communication), and others to organize and structure [knowledge](https://en.wikipedia.org/wiki/Knowledge).

A concept map typically represents ideas and information as boxes or circles, which it connects with labeled arrows, often in a downward-branching hierarchical structure. The relationship between concepts can be articulated in [_linking phrases_](https://en.wikipedia.org/wiki/Transition_(linguistics)) such as "causes", "requires", "such as" or "contributes to".[[2]](https://en.wikipedia.org/wiki/Concept_map#cite_note-theory-2)

The technique for [visualizing](https://en.wikipedia.org/wiki/Visualization_(graphic)) these relationships among different concepts is called _concept mapping_. Concept maps have been used to define the [ontology](https://en.wikipedia.org/wiki/Ontology_(information_science)) of computer systems, for example with the [object-role modeling](https://en.wikipedia.org/wiki/Object-role_modeling) or [Unified Modeling Language](https://en.wikipedia.org/wiki/Unified_Modeling_Language) formalism.

[https://en.wikipedia.org/wiki/List\_of\_concept-\_and\_mind-mapping\_software](https://en.wikipedia.org/wiki/List_of_concept-_and_mind-mapping_software)

##### Free and open-source[[edit source](https://en.wikipedia.org/w/index.php?title=List_of_concept-_and_mind-mapping_software&action=edit&section=2)]

The following tools comply with the [Free Software Foundation](https://en.wikipedia.org/wiki/Free_Software_Foundation)'s (FSF) definition of [free software](https://en.wikipedia.org/wiki/The_Open_Source_Definition#FSF_position). As such, they are also [open-source software](https://en.wikipedia.org/wiki/Open-source_software).

| **Software** | **License** | **Genre** | **Platforms** | **Online visualization** | **Online editing** | **Online real-time collaboration** | **Notes** |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [Compendium](https://en.wikipedia.org/wiki/Compendium_(software)) | [GNU GPL](https://en.wikipedia.org/wiki/GNU_General_Public_License) | [Social science](https://en.wikipedia.org/wiki/Social_science) | [Cross-platform](https://en.wikipedia.org/wiki/Cross-platform) | No | No | No |
- Written in [Java](https://en.wikipedia.org/wiki/Java_(programming_language))
- An email address is required to receive a download link
[![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_3b912d3dd715c486.png)](https://en.wikipedia.org/wiki/File:Compendium.v1.5.2-Screenshot.png) |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [Dia](https://en.wikipedia.org/wiki/Dia_(software)) | [GNU General Public License](https://en.wikipedia.org/wiki/GNU_General_Public_License) | General purpose | [Cross-platform](https://en.wikipedia.org/wiki/Cross-platform_software) | No | No | No | [![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_a18743877deef5d6.png)](https://en.wikipedia.org/wiki/File:Dia_0.97_-_Flowchart_example.png)Written in [C (programming language)](https://en.wikipedia.org/wiki/C_(programming_language)). |
| [FreeMind](https://en.wikipedia.org/wiki/FreeMind) | [GNU GPL](https://en.wikipedia.org/wiki/GNU_General_Public_License) | [Project management](https://en.wikipedia.org/wiki/Project_management_software) | [Cross-platform](https://en.wikipedia.org/wiki/Cross-platform) | Yes | No | No | Written in [Java](https://en.wikipedia.org/wiki/Java_(programming_language))[![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_4186a4e627bcf728.png)](https://en.wikipedia.org/wiki/File:Freemind-0.9x_Screenshoot.png) |
| [Freeplane](https://en.wikipedia.org/wiki/Freeplane) | [GNU GPL v2+](https://en.wikipedia.org/wiki/GNU_General_Public_License) | [Mind mapping](https://en.wikipedia.org/wiki/Mind_map) | [Cross-platform](https://en.wikipedia.org/wiki/Cross-platform) | Yes | No | No | Written in [Java](https://en.wikipedia.org/wiki/Java_(programming_language))[![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_d3a562e2323cd090.png)](https://en.wikipedia.org/wiki/File:Screenshot_of_Freeplane_v.1.1.3.png) |
| [PGF/TikZ](https://en.wikipedia.org/wiki/PGF/TikZ) | [GNU GPL](https://en.wikipedia.org/wiki/GNU_General_Public_License) or [LPPL](https://en.wikipedia.org/wiki/LaTeX_Project_Public_License) | [Mind mapping](https://en.wikipedia.org/wiki/Mind_map) | [Cross-platform](https://en.wikipedia.org/wiki/Cross-platform) | Yes, needs ShareLaTeX | Yes, needs ShareLaTeX | Yes, needs ShareLaTeX |
- Set of TeX macros. TikZ library: mindmap
[![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_161c33d85cfdaeb4.jpg)](https://en.wikipedia.org/wiki/File:LighthouseMap.pdf) |
| [Visual Understanding Environment](https://en.wikipedia.org/wiki/Visual_Understanding_Environment) (VUE) | [Educational Community](https://en.wikipedia.org/wiki/Educational_Community_License) | [Concept mapping](https://en.wikipedia.org/wiki/Concept_map) | [Cross-platform](https://en.wikipedia.org/wiki/Cross-platform) | No | No | No |
- Written in [Java](https://en.wikipedia.org/wiki/Java_(programming_language))
- Can also be used to build presentations
 |
| [View Your Mind (vym)](https://en.wikipedia.org/wiki/Vym_(software)) | [GPL](https://en.wikipedia.org/wiki/GPL) | [Concept mapping](https://en.wikipedia.org/wiki/Concept_map) | [Cross-platform](https://en.wikipedia.org/wiki/Cross-platform) | No | No | No |
- Written in [C++](https://en.wikipedia.org/wiki/C%2B%2B)
- Uses [Qt](https://en.wikipedia.org/wiki/Qt_(software))
[![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_69cd36f39c2a6211.jpg)](https://en.wikipedia.org/wiki/File:Vym_ui_windows.jpg) |

##### Freeware[[edit source](https://en.wikipedia.org/w/index.php?title=List_of_concept-_and_mind-mapping_software&action=edit&section=3)]

The following is a list of notable concept mapping and mind mapping [applications](https://en.wikipedia.org/wiki/Application_software) which are [freeware](https://en.wikipedia.org/wiki/Freeware), and available at no cost. Some are open source, and others are [proprietary software](https://en.wikipedia.org/wiki/Proprietary_software).

| **Software** | **License** | **Genre** | **Platforms** | **Online visualizing** | **Online editing** | **Online real-time collaborating** | **Notes** |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [CmapTools](https://en.wikipedia.org/wiki/CmapTools) | [RAND-RF](https://en.wikipedia.org/wiki/Reasonable_and_non-discriminatory_licensing) | [Concept mapping](https://en.wikipedia.org/wiki/Concept_map) | [Cross-platform](https://en.wikipedia.org/wiki/Cross-platform) | Yes, needs CmapServer, Cmaps on servers generate urls-webpages | Yes, needs CmapServer | Yes, needs CmapServer |
- Written in [Java](https://en.wikipedia.org/wiki/Java_(programming_language))
- Project of [Institute for Human and Machine Cognition](https://en.wikipedia.org/wiki/Institute_for_Human_and_Machine_Cognition) (IHMC)
- Allows connections between published concept maps, needs CmapServer
[![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_924a0bf4610fc4a7.png)](https://en.wikipedia.org/wiki/File:Cmaptool_screenshot.png)Screenshot of Cmap tool |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [Coggle](https://en.wikipedia.org/wiki/Coggle) | [Proprietary](https://en.wikipedia.org/wiki/Proprietary_software), [freeware](https://en.wikipedia.org/wiki/Freeware), [freemium](https://en.wikipedia.org/wiki/Freemium) | [Mind mapping](https://en.wikipedia.org/wiki/Mind_map) | [Cross-platform](https://en.wikipedia.org/wiki/Cross-platform) | Yes | Yes | Yes |
- Written in [JavaScript](https://en.wikipedia.org/wiki/JavaScript), [Node.js](https://en.wikipedia.org/wiki/Node.js), [jQuery](https://en.wikipedia.org/wiki/JQuery), and [Backbone.js](https://en.wikipedia.org/wiki/Backbone.js)
- Google account needed to log in
- Free version lets user save 3 private maps (all others are public)
[![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_c24139a2829e7617.png)](https://en.wikipedia.org/wiki/File:Coggle_Document.png)Screenshot of coggle.it webapp |
| [MindMup](https://en.wikipedia.org/wiki/MindMup) | Custom license[[2]](https://en.wikipedia.org/wiki/List_of_concept-_and_mind-mapping_software#cite_note-2) | [Mind mapping](https://en.wikipedia.org/wiki/Mind_map) | [Web browser](https://en.wikipedia.org/wiki/Web_browser) | Yes | Yes | Yes |
- Freemind import-export
- Browser-based, [HTML5](https://en.wikipedia.org/wiki/HTML5) features automatically adjust to mobile (touch) or keyboard interfaces
- Integrates with [Google Drive](https://en.wikipedia.org/wiki/Google_Drive) and [GitHub](https://en.wikipedia.org/wiki/GitHub) to provide cloud storage and sharing control
- Written in [JavaScript](https://en.wikipedia.org/wiki/JavaScript) and [Ruby](https://en.wikipedia.org/wiki/Ruby_(programming_language))
[![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_a36134c3915150b0.png)](https://en.wikipedia.org/wiki/File:MindMup_screenshot.png) |
| [Qiqqa](https://en.wikipedia.org/wiki/Qiqqa) | [Proprietary](https://en.wikipedia.org/wiki/Proprietary_software), [freeware](https://en.wikipedia.org/wiki/Freeware), [freemium](https://en.wikipedia.org/wiki/Freemium) | [Concept mapping](https://en.wikipedia.org/wiki/Concept_map) | [Windows](https://en.wikipedia.org/wiki/Microsoft_Windows) | Yes | No | No |
- Mind maps for academics based on their research papers, notes, and annotations
- Can export mind maps to the web and share by social media
 |
| [XMind](https://en.wikipedia.org/wiki/XMind) | [Proprietary](https://en.wikipedia.org/wiki/Proprietary_software), [freeware](https://en.wikipedia.org/wiki/Freeware), [freemium](https://en.wikipedia.org/wiki/Freemium) | [Project management](https://en.wikipedia.org/wiki/Project_management_software), [knowledge management](https://en.wikipedia.org/wiki/Knowledge_management_software) | [Windows](https://en.wikipedia.org/wiki/Microsoft_Windows), [OS X](https://en.wikipedia.org/wiki/OS_X), [Linux](https://en.wikipedia.org/wiki/Linux) | No | No | No |
- Mind maps, spreadsheets, fishbone diagrams, tree charts, org charts.
- Online sharing
- Compatible with Freemind
- Formerly proprietary
- Written in [Java](https://en.wikipedia.org/wiki/Java_(programming_language)).
[![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_9e9165d86bd44a1a.png)](https://en.wikipedia.org/wiki/File:XMind_Screenshot_TDias.png) |
| [yEd](https://en.wikipedia.org/wiki/YEd) | [Proprietary](https://en.wikipedia.org/wiki/Proprietary_software), yEd[[3]](https://en.wikipedia.org/wiki/List_of_concept-_and_mind-mapping_software#cite_note-3) | [Concept mapping](https://en.wikipedia.org/wiki/Concept_map), [Mind mapping](https://en.wikipedia.org/wiki/Mind_map) | [Windows](https://en.wikipedia.org/wiki/Microsoft_Windows), [OS X](https://en.wikipedia.org/wiki/OS_X), [Linux](https://en.wikipedia.org/wiki/Linux), [cross-platform](https://en.wikipedia.org/wiki/Cross-platform) | ? | ? | ? |
- General-purpose freeware diagram editor
- Written in [Java](https://en.wikipedia.org/wiki/Java_(programming_language))
- can be used to draw different kinds of diagrams: [flowcharts](https://en.wikipedia.org/wiki/Flowchart), [computer network diagrams](https://en.wikipedia.org/wiki/Computer_network_diagram), [UML diagrams](https://en.wikipedia.org/wiki/UML_diagram), [BPMN](https://en.wikipedia.org/wiki/BPMN) diagrams, [mind maps](https://en.wikipedia.org/wiki/Mind_map), [organization charts](https://en.wikipedia.org/wiki/Organization_chart), [entity relationship](https://en.wikipedia.org/wiki/Entity_relationship) diagrams, and many others.
 |

##### Proprietary software[[edit source](https://en.wikipedia.org/w/index.php?title=List_of_concept-_and_mind-mapping_software&action=edit&section=4)]

The table below lists pieces of proprietary [commercial software](https://en.wikipedia.org/wiki/Commercial_software) that allow creating mind and concept maps.

| **Software** | **Publisher, license** | **Platforms** | **Notes, features** |
| --- | --- | --- | --- |
| [3D Topicscape](https://en.wikipedia.org/wiki/3D_Topicscape) | 3D-Scape Limited | [Windows](https://en.wikipedia.org/wiki/Microsoft_Windows) | Desktop application that presents mind maps as a 3d scene where each node is a cone. Imports MindManager, Personal Brain, FreeMind, text and folders. |
| --- | --- | --- | --- |
| [ConceptDraw MINDMAP](https://en.wikipedia.org/wiki/ConceptDraw_MINDMAP) | CS Odessa LLC | [Windows](https://en.wikipedia.org/wiki/Microsoft_Windows), [OS X](https://en.wikipedia.org/wiki/OS_X) | Desktop mind mapping and brainstorming software, for business, education, or personal activities. Integrates with Microsoft [Word](https://en.wikipedia.org/wiki/Microsoft_Word), [PowerPoint](https://en.wikipedia.org/wiki/Microsoft_PowerPoint), [Project](https://en.wikipedia.org/wiki/Microsoft_Project), [MindManager](https://en.wikipedia.org/wiki/MindManager), [FreeMind](https://en.wikipedia.org/wiki/FreeMind), and [XMind](https://en.wikipedia.org/wiki/XMind). Compatible with [Twitter](https://en.wikipedia.org/wiki/Twitter), [Skype](https://en.wikipedia.org/wiki/Skype), and [Evernote](https://en.wikipedia.org/wiki/Evernote) services. |
| [Creately](https://en.wikipedia.org/wiki/Creately) | Cinergix Pvt. Ltd. | [Windows](https://en.wikipedia.org/wiki/Microsoft_Windows), [OS X](https://en.wikipedia.org/wiki/OS_X), [Linux](https://en.wikipedia.org/wiki/Linux) |
- Shapes and symbols in libraries.
- Built-in examples and templates.
- Export options to PDF, Jpeg, Png, SVG.
- Cloud collaboration
- Video conferencing
 |
| [Debategraph](https://en.wikipedia.org/wiki/Debategraph) | Debategraph | [Web application](https://en.wikipedia.org/wiki/Web_application) | Concept and [argument mapping](https://en.wikipedia.org/wiki/Argument_map) tool |
| [Edraw Max](https://en.wikipedia.org/wiki/Edraw_Max) | EdrawSoft | [Windows](https://en.wikipedia.org/wiki/Microsoft_Windows), [OS X](https://en.wikipedia.org/wiki/OS_X), [Linux](https://en.wikipedia.org/wiki/Linux) |
- Cliparts and symbols in libraries.
- Available [Gantt chart](https://en.wikipedia.org/wiki/Gantt_chart) add-in.
- Built-in examples and templates.
- Export options to Graphics, PDF,PS,, EPS, Microsoft Office (Word, PowerPoint, Excel),HTML,SVG and Visio.
- Cloud collaboration
 |
| [LucidChart](https://en.wikipedia.org/wiki/LucidChart) | LucidChart, LLC | [Web application](https://en.wikipedia.org/wiki/Web_application) |
- [HTML5](https://en.wikipedia.org/wiki/HTML5)-based collaborative diagramming tool that can be used to map minds and concepts
- [Android](https://en.wikipedia.org/wiki/Android_(operating_system)), [iPhone](https://en.wikipedia.org/wiki/IPhone), [iPad](https://en.wikipedia.org/wiki/IPad) applications, providing offline access to diagrams.
 |
| [Microsoft Visio](https://en.wikipedia.org/wiki/Microsoft_Visio) | [Microsoft](https://en.wikipedia.org/wiki/Microsoft) | [Windows](https://en.wikipedia.org/wiki/Microsoft_Windows) | Part of [Microsoft Office](https://en.wikipedia.org/wiki/Microsoft_Office) product family, draws static diagrams including block diagrams, organization charts, maps, plans or workflows |
| [Mind42](https://en.wikipedia.org/wiki/Mind42) | IRIAN Solutions | [Web application](https://en.wikipedia.org/wiki/Web_application) |
- Browser-based collaborative web application
- Real-time collaborative editing; the name _Mind42_ is intended to be read as _Mind for two_
- Free to use with no function limits
- Limited support by developer
 |
| [MindManager](https://en.wikipedia.org/wiki/MindManager) | Mindjet | [Windows](https://en.wikipedia.org/wiki/Microsoft_Windows), [OS X](https://en.wikipedia.org/wiki/OS_X), [Android](https://en.wikipedia.org/wiki/Android_(operating_system)) | Desktop application comes in basic and pro versions; integrated with [Microsoft Office](https://en.wikipedia.org/wiki/Microsoft_Office), available [Gantt chart](https://en.wikipedia.org/wiki/Gantt_chart) add-in, built-in spreadsheet, [Fluent](https://en.wikipedia.org/wiki/Fluent_(user_interface)) UI, Current Version: MindManager 2018 |
| [MindMapper](https://en.wikipedia.org/wiki/MindMapper) | SimTech Systems | [Windows](https://en.wikipedia.org/wiki/Microsoft_Windows) |
- Mind mapping, idea visualizing, brainstorming
- Process flow, org charts, fishbone diagrams
- Concept maps and flowcharts
- Project management with built-in Gantt charts
- Built-in presentation
- Post it style memo notes
- Integrates with [Microsoft Office](https://en.wikipedia.org/wiki/Microsoft_Office)
 |
| [MindMeister](https://en.wikipedia.org/wiki/MindMeister) | MeisterLabs GmbH | [Windows](https://en.wikipedia.org/wiki/Microsoft_Windows), [OS X](https://en.wikipedia.org/wiki/OS_X), [Linux](https://en.wikipedia.org/wiki/Linux) |
- Browser-based collaborative web application
- [Android](https://en.wikipedia.org/wiki/Android_(operating_system)), [iPhone](https://en.wikipedia.org/wiki/IPhone), [iPad](https://en.wikipedia.org/wiki/IPad) applications, providing access to online mind maps
- Built-in chat
- Subscription based, also offering a free limited access option
 |
| [Mindomo](https://en.wikipedia.org/wiki/Mindomo) | Expert Software Applications | [Windows](https://en.wikipedia.org/wiki/Microsoft_Windows), [OS X](https://en.wikipedia.org/wiki/OS_X), [Linux](https://en.wikipedia.org/wiki/Linux) |
- Browser-based
- Realtime collaboration, built-in chat, revision history
- Built-in presentation mode
- Desktop application
- [Android](https://en.wikipedia.org/wiki/Android_(operating_system)) and [iPad](https://en.wikipedia.org/wiki/IPad) applications work both offline and in sync with the cloud
- Offers a free limited option
 |
| [MindView](https://en.wikipedia.org/wiki/MindView) | MatchWare | [Windows](https://en.wikipedia.org/wiki/Microsoft_Windows), [OS X](https://en.wikipedia.org/wiki/OS_X), [Web application](https://en.wikipedia.org/wiki/Web_application) |
- Integrated with [Microsoft Office](https://en.wikipedia.org/wiki/Microsoft_Office)
- 6 Interchangeable views: includes [Gantt chart](https://en.wikipedia.org/wiki/Gantt_chart) and timeline
- Calculation feature and Excel integration
- Optimized for project management
- Advanced filter function
 |
| [OmniGraffle](https://en.wikipedia.org/wiki/OmniGraffle) | [The Omni Group](https://en.wikipedia.org/wiki/The_Omni_Group) | [OS X](https://en.wikipedia.org/wiki/OS_X), [iOS](https://en.wikipedia.org/wiki/IOS) |
 |
| [Prezi](https://en.wikipedia.org/wiki/Prezi) | Prezi Inc. | [Web application](https://en.wikipedia.org/wiki/Web_application), [Windows](https://en.wikipedia.org/wiki/Microsoft_Windows) |
- Presentation software that supports free form placement and zooming on a single sheet.
- Offers [Android](https://en.wikipedia.org/wiki/Android_(operating_system)), [iPhone](https://en.wikipedia.org/wiki/IPhone), and [iPad](https://en.wikipedia.org/wiki/IPad) applications work both offline and in sync with the cloud
 |
| [Qiqqa](https://en.wikipedia.org/wiki/Qiqqa) | Quantisle Ltd. | [Windows](https://en.wikipedia.org/wiki/Microsoft_Windows) | Minds maps for academics oriented around their research papers, notes, and annotations. |
| [Semantica](https://en.wikipedia.org/wiki/Semantic_Research#Products) | Semantic Research | [OS X](https://en.wikipedia.org/wiki/OS_X), [Windows](https://en.wikipedia.org/wiki/Microsoft_Windows) | Family of software to create, view, store, and share [knowledge structures](https://en.wikipedia.org/wiki/Knowledge_representation_and_reasoning) |
| [SmartDraw](https://en.wikipedia.org/wiki/SmartDraw) | SmartDraw Software, LLC | [Windows](https://en.wikipedia.org/wiki/Microsoft_Windows) | Visual processor used to create [flowcharts](https://en.wikipedia.org/wiki/Flowchart), [organization charts](https://en.wikipedia.org/wiki/Organization_chart), [mind maps](https://en.wikipedia.org/wiki/Mind_map), [gantt charts](https://en.wikipedia.org/wiki/Gantt_chart), and other visuals |
| [SpicyNodes](https://en.wikipedia.org/wiki/SpicyNodes) | [IDEA.org](https://en.wikipedia.org/wiki/Institute_for_Dynamic_Educational_Advancement) | [Adobe Flash](https://en.wikipedia.org/wiki/Adobe_Flash) | radial maps, viewer can move from node to node |
| [Tinderbox](https://en.wikipedia.org/wiki/Tinderbox_(application_software)) | [Eastgate Systems](https://en.wikipedia.org/wiki/Eastgate_Systems) | [OS X](https://en.wikipedia.org/wiki/OS_X) | [Content management system](https://en.wikipedia.org/wiki/Content_management_system) with concept and mind map abilities |
| [TheBrain](https://en.wikipedia.org/wiki/TheBrain) | [TheBrain Technologies](https://en.wikipedia.org/wiki/TheBrain_Technologies) | [Windows](https://en.wikipedia.org/wiki/Microsoft_Windows), [OS X](https://en.wikipedia.org/wiki/OS_X), [Unix](https://en.wikipedia.org/wiki/Unix), [Unix-like](https://en.wikipedia.org/wiki/Unix-like) | Graphically intensive and customizable GUI, extremely cross-platform. Notes, calendar, [Microsoft Outlook](https://en.wikipedia.org/wiki/Microsoft_Outlook) features. Multiple parent node ability. |
| [Visual Mind](https://en.wikipedia.org/wiki/Visual_Mind) | Mind Technologies | [Windows](https://en.wikipedia.org/wiki/Microsoft_Windows) | Supports collaboration ([client–server](https://en.wikipedia.org/wiki/Client%E2%80%93server)) mode. |
| [XMind](https://en.wikipedia.org/wiki/XMind) Pro | XMind Ltd. | [Windows](https://en.wikipedia.org/wiki/Microsoft_Windows), [OS X](https://en.wikipedia.org/wiki/OS_X), [Linux](https://en.wikipedia.org/wiki/Linux) |
 |

#### Graph-drawing brainstorming

[https://en.wikipedia.org/wiki/Graph\_drawing#Software](https://en.wikipedia.org/wiki/Graph_drawing#Software)

**Graph drawing**  is an area of [mathematics](https://en.wikipedia.org/wiki/Mathematics) and [computer science](https://en.wikipedia.org/wiki/Computer_science) combining methods from [geometric graph theory](https://en.wikipedia.org/wiki/Geometric_graph_theory) and [information visualization](https://en.wikipedia.org/wiki/Information_visualization) to derive two-dimensional depictions of [graphs](https://en.wikipedia.org/wiki/Graph_(discrete_mathematics)) arising from applications such as [social network analysis](https://en.wikipedia.org/wiki/Social_network_analysis), [cartography](https://en.wikipedia.org/wiki/Cartography), [linguistics](https://en.wikipedia.org/wiki/Linguistics), and [bioinformatics](https://en.wikipedia.org/wiki/Bioinformatics).[[1]](https://en.wikipedia.org/wiki/Graph_drawing#cite_note-1)

A drawing of a graph or  **network diagram**  is a pictorial representation of the [vertices](https://en.wikipedia.org/wiki/Vertex_(graph_theory)) and [edges](https://en.wikipedia.org/wiki/Edge_(graph_theory)) of a graph. This drawing should not be confused with the graph itself: very different layouts can correspond to the same graph.

##### Application-specific graph drawings[[edit source](https://en.wikipedia.org/w/index.php?title=Graph_drawing&action=edit&section=4)]

Graphs and graph drawings arising in other areas of application include

- [Sociograms](https://en.wikipedia.org/wiki/Sociogram), drawings of a [social network](https://en.wikipedia.org/wiki/Social_network), as often offered by [social network analysis software](https://en.wikipedia.org/wiki/Social_network_analysis_software)[[22]](https://en.wikipedia.org/wiki/Graph_drawing#cite_note-22)
- [Hasse diagrams](https://en.wikipedia.org/wiki/Hasse_diagram), a type of graph drawing specialized to [partial orders](https://en.wikipedia.org/wiki/Partial_order)[[23]](https://en.wikipedia.org/wiki/Graph_drawing#cite_note-23)
- [Dessin d'enfants](https://en.wikipedia.org/wiki/Dessin_d%27enfant), a type of graph drawing used in [algebraic geometry](https://en.wikipedia.org/wiki/Algebraic_geometry)[[24]](https://en.wikipedia.org/wiki/Graph_drawing#cite_note-FOOTNOTEZapponi2003-24)
- [State diagrams](https://en.wikipedia.org/wiki/State_diagram), graphical representations of [finite-state machines](https://en.wikipedia.org/wiki/Finite-state_machine)[[25]](https://en.wikipedia.org/wiki/Graph_drawing#cite_note-FOOTNOTEAndersonHead2006-25)
- [Computer network diagrams](https://en.wikipedia.org/wiki/Computer_network_diagram), depictions of the nodes and connections in a [computer network](https://en.wikipedia.org/wiki/Computer_network)[[26]](https://en.wikipedia.org/wiki/Graph_drawing#cite_note-FOOTNOTEDi_BattistaRimondini2014-26)
- [Flowcharts](https://en.wikipedia.org/wiki/Flowchart) and [drakon-charts](https://en.wikipedia.org/wiki/DRAKON), drawings in which the nodes represent the steps of an [algorithm](https://en.wikipedia.org/wiki/Algorithm) and the edges represent [control flow](https://en.wikipedia.org/wiki/Control_flow) between steps.
- [Data-flow diagrams](https://en.wikipedia.org/wiki/Data-flow_diagram), drawings in which the nodes represent the components of an [information system](https://en.wikipedia.org/wiki/Information_system) and the edges represent the movement of information from one component to another.
- [Bioinformatics](https://en.wikipedia.org/wiki/Bioinformatics) including [phylogenetic trees](https://en.wikipedia.org/wiki/Phylogenetic_tree), [protein–protein interaction](https://en.wikipedia.org/wiki/Protein%E2%80%93protein_interaction) networks, and [metabolic pathways](https://en.wikipedia.org/wiki/Metabolic_pathway).[[27]](https://en.wikipedia.org/wiki/Graph_drawing#cite_note-FOOTNOTEBachmaierBrandesSchreiber2014-27)

In addition, the [placement](https://en.wikipedia.org/wiki/Placement_(electronic_design_automation)) and [routing](https://en.wikipedia.org/wiki/Routing_(electronic_design_automation)) steps of [electronic design automation](https://en.wikipedia.org/wiki/Electronic_design_automation) (EDA) are similar in many ways to graph drawing, as is the problem of [greedy embedding](https://en.wikipedia.org/wiki/Greedy_embedding) in [distributed computing](https://en.wikipedia.org/wiki/Distributed_computing), and the graph drawing literature includes several results borrowed from the EDA literature. However, these problems also differ in several important ways: for instance, in EDA, area minimization and signal length are more important than aesthetics, and the routing problem in EDA may have more than two terminals per net while the analogous problem in graph drawing generally only involves pairs of vertices for each edge.

##### Graph drawing Software[[edit source](https://en.wikipedia.org/w/index.php?title=Graph_drawing&action=edit&section=5)]

[![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_b67a83c0d3040e2.png)](https://en.wikipedia.org/wiki/File:Gephi_0.9.1_Network_Analysis_and_Visualization_Software.png)

A graph drawing interface ([Gephi](https://en.wikipedia.org/wiki/Gephi) 0.9.1)

Software, systems, and providers of systems for drawing graphs include:

- [BioFabric](https://en.wikipedia.org/wiki/BioFabric) open-source software for visualizing large networks by drawing nodes as horizontal lines.
- [Cytoscape](https://en.wikipedia.org/wiki/Cytoscape), open-source software for visualizing molecular interaction networks
- [Gephi](https://en.wikipedia.org/wiki/Gephi), open-source network analysis and visualization software
- [graph-tool](https://en.wikipedia.org/wiki/Graph-tool), a [free/libre](https://en.wikipedia.org/wiki/Free_Software) [Python](https://en.wikipedia.org/wiki/Python_(programming_language)) library for analysis of graphs.
- [Graphviz](https://en.wikipedia.org/wiki/Graphviz), an open-source graph drawing system from [AT&T Corporation](https://en.wikipedia.org/wiki/AT%26T_Corporation)[[28]](https://en.wikipedia.org/wiki/Graph_drawing#cite_note-28)
- [Linkurious](https://en.wikipedia.org/wiki/Linkurious), a commercial network analysis and visualization software for [graph databases](https://en.wikipedia.org/wiki/Graph_databases)
- [Mathematica](https://en.wikipedia.org/wiki/Mathematica), a general purpose computation tool that includes 2D and 3D graph visualization and graph analysis tools.[[29]](https://en.wikipedia.org/wiki/Graph_drawing#cite_note-29)[[30]](https://en.wikipedia.org/wiki/Graph_drawing#cite_note-30)
- [Microsoft Automatic Graph Layout](https://en.wikipedia.org/wiki/Microsoft_Automatic_Graph_Layout), open-source .NET library (formerly called GLEE) for laying out graphs[[31]](https://en.wikipedia.org/wiki/Graph_drawing#cite_note-31)
- [NetworkX](https://en.wikipedia.org/wiki/NetworkX) is a Python library for studying graphs and networks.
- [Tom Sawyer Software](https://en.wikipedia.org/wiki/Tom_Sawyer_Software)[[32]](https://en.wikipedia.org/wiki/Graph_drawing#cite_note-32) Tom Sawyer Perspectives is graphics-based software for building enterprise-class graph and data visualization and analysis applications. It is a Software Development Kit (SDK) with a graphics-based design and preview environment.
- [Tulip (software)](https://en.wikipedia.org/wiki/Tulip_(software)),[[33]](https://en.wikipedia.org/wiki/Graph_drawing#cite_note-33) an open source data visualization tool
- [yEd](https://en.wikipedia.org/wiki/YEd), a graph editor with graph layout functionality[[34]](https://en.wikipedia.org/wiki/Graph_drawing#cite_note-34)
- [PGF/TikZ](https://en.wikipedia.org/wiki/PGF/TikZ) 3.0 with the graphdrawing package (requires [LuaTeX](https://en.wikipedia.org/wiki/LuaTeX)).[[35]](https://en.wikipedia.org/wiki/Graph_drawing#cite_note-35)
- [LaNet-vi](https://en.wikipedia.org/wiki/LaNet-vi), an open-source large network visualization software
- [Edraw Max](https://en.wikipedia.org/wiki/Edraw_Max) 2D business technical diagramming software

# **Web surfuing, Chrome**

# Chrome search Trics

## Refine web searches

You can use symbols or words in your search to make your search results more precise.

- Google Search usually ignores punctuation that isn't part of a search operator.
- Don't put spaces between the symbol or word and your search term. A search for site:nytimes.com will work, but site: nytimes.com won't.

### Refine image searches

##### Overall Advanced Search

1. Go to [Advanced Image Search](https://google.com/advanced_image_search).
2. Use filters like region or file type to narrow your results.
3. At the bottom, click Advanced Search.

##### Search for an exact image size

Right after the word you're looking for, add the text imagesize:widthxheight. Make sure to add the dimensions in pixels.

Example: imagesize:500x400

### Common search techniques

#### Search social media

Put @ in front of a word to search social media. For example: @twitter.

#### Search for a price

Put $ in front of a number. For example: camera $400.

#### Search hashtags

Put # in front of a word. For example: #throwbackthursday

#### Exclude words from your search

Put - in front of a word you want to leave out. For example, jaguar speed -car

#### Search for an exact match

Put a word or phrase inside quotes. For example, "tallest building".

#### Search within a range of numbers

Put .. between two numbers. For example, camera $50..$100.

#### Combine searches

Put "OR" between each search query. For example, marathon OR race.

#### Search for a specific site

Put "site:" in front of a site or domain. For example, site:youtube.com or site:.gov.

#### Search for related sites

Put "related:" in front of a web address you already know. For example, related:time.com.

#### See Google's cached version of a site

Put "cache:" in front of the site address.

Important: Not all search operators return exhaustive results

# Chrome Keyboard Shortcuts for Windows and Linux

## Google Chrome feature shortcuts

| Action | Shortcut |
| --- | --- |
| Open the Chrome menu | Alt + f or Alt + e |
| **Show or hide the Bookmarks bar** | **Ctrl + Shift + b** |
| **Open the Bookmarks Manager** | **Ctrl + Shift + o** |
| Open the History page in a new tab | Ctrl + h |
| Open the Downloads page in a new tab | Ctrl + j |
| Open the Chrome Task Manager | Shift + Esc |
| Set focus on the first item in the Chrome toolbar | Shift + Alt + t |
| Set focus on the rightmost item in the Chrome toolbar | F10  |
| Switch focus to unfocused dialog (if showing) and all toolbars | F6 |
| Open the Find Bar to search the current page | Ctrl + f or F3 |
| Jump to the next match to your Find Bar search | Ctrl + g |
| Jump to the previous match to your Find Bar search | Ctrl + Shift + g |
| Open Developer Tools | Ctrl + Shift + j or F12 |
| Open the Clear Browsing Data options | Ctrl + Shift + Delete |
| Open the Chrome Help Center in a new tab | F1 |
| Log in a different user or browse as a Guest | Ctrl + Shift + m |
| Open a feedback form | Alt + Shift + i |

## Tab and window shortcuts

[https://support.google.com/chrome/answer/157179?hl=en](https://support.google.com/chrome/answer/157179?hl=en)

| Action | Shortcut |
| --- | --- |
| Open a new window | Ctrl + n |
| Open a new window in Incognito mode | Ctrl + Shift + n |
| Open a new tab, and jump to it | Ctrl + t |
| Reopen previously closed tabs in the order they were closed | Ctrl + Shift + t |
| Jump to the next open tab | Ctrl + Tab or Ctrl + PgDn |
| Jump to the previous open tab | Ctrl + Shift + Tab or Ctrl + PgUp |
| Jump to a specific tab | Ctrl + 1 through Ctrl + 8 |
| Jump to the rightmost tab | Ctrl + 9 |
| Open your home page in the current tab | Alt + Home |
| Open the previous page from your browsing history in the current tab | Alt + Left arrow |
| Open the next page from your browsing history in the current tab | Alt + Right arrow |
| Close the current tab | Ctrl + w or Ctrl + F4 |
| Close the current window | Ctrl + Shift + w or Alt + F4 |
| **Minimize the current window** | **Alt + Space then n** |
| Maximize the current window | Alt + Space then x |
| Quit Google Chrome | Alt + f then x |

## Address bar shortcuts

Use the following shortcuts in the address bar:

| Action | Shortcut |
| --- | --- |
| Search with your default search engine | Type a search term + Enter |
| Search using a different search engine | Type a search engine name and press Tab |
| Add www. and .com to a site name, and open it in the current tab | Type a site name + Ctrl + Enter |
| Open a new tab and perform a Google search | Type a search term + Alt + Enter |
| Jump to the address bar | Ctrl + l or Alt + d or F6 |
| Search from anywhere on the page | Ctrl + k or Ctrl + e |
| Remove predictions from your address bar | Down arrow to highlight + Shift + Delete |
| Move cursor to the address bar | Control + F5 |

## Webpage shortcuts

| Action | Shortcut |
| --- | --- |
| Open options to print the current page | Ctrl + p |
| Open options to save the current page | Ctrl + s |
| Reload the current page | F5 or Ctrl + r |
| Reload the current page, ignoring cached content | Shift + F5 or Ctrl + Shift + r |
| Stop the page loading | Esc |
| Browse clickable items moving forward | Tab |
| Browse clickable items moving backward | Shift + Tab |
| Open a file from your computer in Chrome | Ctrl + o + Select a file |
| Display non-editable HTML source code for the current page | Ctrl + u |
| Save your current webpage as a bookmark | Ctrl + d |
| Save all open tabs as bookmarks in a new folder | Ctrl + Shift + d |
| Turn full-screen mode on or off | F11 |
| Make everything on the page bigger | Ctrl and + |
| Make everything on the page smaller | Ctrl and - |
| Return everything on the page to default size | Ctrl + 0 |
| Scroll down a webpage, a screen at a time | Space or PgDn |
| Scroll up a webpage, a screen at a time | Shift + Space or PgUp |
| Go to the top of the page | Home |
| Go to the bottom of the page | End |
| Scroll horizontally on the page | Shift + Scroll your mousewheel |
| Move your cursor to the beginning of the previous word in a text field | Ctrl + Left arrow |
| Move your cursor to the next word | Ctrl + Right arrow |
| Delete the previous word in a text field | Ctrl + Backspace |
| Open the Home page in the current tab | Alt + Home |
| Reset page zoom level | Ctrl + 0 |

## Mouse shortcuts

The following shortcuts require you to use your mouse:

| Action | Shortcut |
| --- | --- |
| Open a link in a current tab (mouse only) | Drag a link to a tab |
| **Open a link in new background tab** | **Ctrl + Click a link** |
| **Open a link, and jump to it** | **Ctrl + Shift + Click a link** |
| Open a link, and jump to it (mouse only) | Drag a link to a blank area of the tab strip |
| **Open a link in a new window** | **Shift + Click a link** |
| Open a tab in a new window (mouse only) | Drag the tab out of the tab strip |
| Move a tab to a current window (mouse only) | Drag the tab into an existing window |
| Return a tab to its original position | Press Esc while dragging |
| Save the current webpage as a bookmark | Drag the web address to the Bookmarks Bar |
| Scroll horizontally on the page | Shift + Scroll your mousewheel |
| Download the target of a link | Alt + Click a link |
| Display your browsing history | Right-click Back  ![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_32886d39bcb76509.png) or click & hold Back  ![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_32886d39bcb76509.png)
 Right-click Next  ![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_adf0a092c2828a13.png) or click & hold Next  ![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_adf0a092c2828a13.png) |
| Switch between maximized and windowed modes | Double-click a blank area of the tab strip |
| Make everything on the page bigger | Ctrl + Scroll your mousewheel up |
| Make everything on the page smaller | Ctrl + Scroll your mousewheel down |

# Chrome Extentions

## Vimium（Extent ions） in Chrome

[Vimium](https://vimium.github.io/) is a Google Chrome extension which provides keyboard shortcuts for navigation and control in the spirit of the Vim editor.

- **Navigating history**

H : Go back in history

L : Go forward in history

- **Manipulating tabs**

K, gt : Go one tab right

J, gT : Go one tab left

t : Create new tab

x : Close current tab

X : Restore closed tab

- **Navigating the page**

? : Show the help dialog

j : Scroll down

k : Scroll up

h : Scroll left

l : Scroll right

gg : Scroll to the top of the page

G : Scroll to the bottom of the page

u, \<c-u\> : Scroll a half page up

d, \<c-d\> : Scroll a half page down

\<c-f\> : Scroll a full page down

\<c-b\> : Scroll a full page up

f : Open a link in the current tab

F : Open a link in a new tab

o : Open URL, bookmark, or history entry

O : Open URL, bookmark, or history entry in a new tab

r : Reload the page

gs : View page source

/ : Enter find mode

n : Cycle forward to the next find match

N : Cycle backward to the previous find match

yy : Copy the current URL to the clipboard

gf : Cycle focus to the next frame

i : Enter insert mode

# **字符编码 标准**

# Character encoding

## 标准编码格式

[https://baike.baidu.com/item/%E6%A0%87%E5%87%86%E7%BC%96%E7%A0%81%E6%A0%BC%E5%BC%8F/20868617](https://baike.baidu.com/item/%E6%A0%87%E5%87%86%E7%BC%96%E7%A0%81%E6%A0%BC%E5%BC%8F/20868617)

[编码](https://baike.baidu.com/item/%E7%BC%96%E7%A0%81/80092)是用预先规定的方法将文字、数字或其它对象编成数码，或将信息、数据转换成规定的电脉冲信号。为保证编码的正确性，编码要规范化、标准化，即需有标准的编码格式。常见的编码格式有[ASCII](https://baike.baidu.com/item/ASCII)、[ANSI](https://baike.baidu.com/item/ANSI/10401940)、[GBK](https://baike.baidu.com/item/GBK)、[GB2312](https://baike.baidu.com/item/GB2312)、[UTF-8](https://baike.baidu.com/item/UTF-8)、[GB18030](https://baike.baidu.com/item/GB18030)和[UNICODE](https://baike.baidu.com/item/UNICODE)等。

### 字符集与编码

各个国家和地区所制定的不同 ANSI 编码标准中，都只规定了各自语言所需的"字符"。比如：汉字标准（GB2312）中没有规定韩国语字符怎样存储。这些 ANSI 编码标准所规定的内容包含两层含义：

1. 使用哪些字符。也就是说哪些汉字，字母和符号会被收入标准中。所包含"字符"的集合就叫做"字符集"。
2. 规定每个"字符"分别用一个字节还是多个字节存储，用哪些字节来存储，这个规定就叫做"编码"。

各个国家和地区在制定编码标准的时候，"字符的集合"和"编码"一般都是同时制定的。因此，平常所说的"字符集"，比如：[GB2312](https://baike.baidu.com/item/GB2312)、[GBK](https://baike.baidu.com/item/GBK)、[JIS](https://baike.baidu.com/item/JIS) 等，除了有"字符的集合"这层含义外，同时也包含了"编码"的含义。

"UNICODE 字符集"包含了各种语言中使用到的所有"字符"。用来给 UNICODE 字符集编码的标准有很多种，比如：UTF-8、UTF-7、UTF-16、UnicodeLittle、UnicodeBig 等。

#### 字符与编码的发展

在计算机技术发展的早期，如[ASCII](https://zh.wikipedia.org/wiki/ASCII)（1963年）和[EBCDIC](https://zh.wikipedia.org/wiki/EBCDIC)（1964年）这样的 **字符集** 逐渐成为标准。但这些字符集的局限很快就变得明显，于是人们开发了许多方法来扩展它们。对于支持包括东亚[CJK](https://zh.wikipedia.org/wiki/CJK)字符家族在内的[写作系统](https://zh.wikipedia.org/wiki/%E6%96%87%E5%AD%97)的要求能支持更大量的字符，并且需要一种系统而不是临时的方法实现这些字符的编码。

从计算机对多国语言的支持角度看，大致可以分为三个阶段：

|
 | **系统内码** | **说明** | **系统** |
| --- | --- | --- | --- |
| 阶段一 | ASCII | 计算机刚开始只支持英语，其它语言不能够在计算机上存储和显示。 | 英文DOS |
| 阶段二 | ANSI编码（本地化） | 为使计算机支持更多语言，通常使用0x80~0xFF 范围的2 个字节来表示1 个字符。比如：汉字'中' 在中文操作系统中，使用[0xD6,0xD0] 这两个字节存储。不同的国家和地区制定了不同的标准，由此产生了GB2312, BIG5, JIS 等各自的编码标准。这些使用2 个字节来代表一个字符的各种汉字延伸编码方式，称为 **ANSI**  **编码** 。在简体中文系统下，ANSI 编码代表GB2312 编码，在日文操作系统下，ANSI 编码代表JIS 编码。不同ANSI 编码之间互不兼容，当信息在国际间交流时，无法将属于两种语言的文字，存储在同一段 **ANSI**  **编码** 的文本中。 | 中文DOS，中文Windows 95/98，日文Windows 95/98 |
| 阶段三 | UNICODE（国际化） | 为了使国际间信息交流更加方便，国际组织制定了 **UNICODE**  **字符集** ，为各种语言中的每一个字符设定了统一并且唯一的数字编号，以满足跨语言、跨平台进行文本转换、处理的要求。 | Windows NT/2000/XP，Linux，Java |

##### 字符串在内存中的存放方法

在ASCII 阶段，单字节字符串使用一个字节存放一个字符（SBCS）。比如，"Bob123" 在内存中为：

| 42 | 6F | 62 | 31 | 32 | 33 | 00 |
| --- | --- | --- | --- | --- | --- | --- |
|
 |
 |
 |
 |
 |
 |
 |
| B | o | b | 1 | 2 | 3 | \0 |

在使用ANSI 编码支持多种语言阶段，每个字符使用一个字节或多个字节来表示（MBCS），因此，这种方式存放的字符也被称作多字节字符。比如，"中文123" 在中文Windows 95 内存中为7个字节，每个汉字占2个字节，每个英文和数字字符占1个字节：

| D6 | D0 | CE | C4 | 31 | 32 | 33 | 00 |
| --- | --- | --- | --- | --- | --- | --- | --- |
|
 |
 |
 |
 |
 |
 |
| 中 | 文 | 1 | 2 | 3 | \0 |

在UNICODE 被采用之后，计算机存放字符串时，改为存放每个字符在UNICODE 字符集中的序号。计算机一般使用2 个字节（16 位）来存放一个序号（DBCS），因此，这种方式存放的字符也被称作宽字节字符。比如，字符串"中文123" 在Windows 2000 下，内存中实际存放的是5 个序号：

| 2D | 4E | 87 | 65 | 31 | 00 | 32 | 00 | 33 | 00 | 00 | 00 | ←在x86 CPU 中，低字节在前 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|
 |
 |
 |
 |
 |
 |
 |
| 中 | 文 | 1 | 2 | 3 | \0 |
 |

一共占10 个字节。 [2]

##### 常见格式

常见的编码格式有[ASCII](https://baike.baidu.com/item/ASCII)、[ANSI](https://baike.baidu.com/item/ANSI/10401940)、[GBK](https://baike.baidu.com/item/GBK)、[GB2312](https://baike.baidu.com/item/GB2312)、[UTF-8](https://baike.baidu.com/item/UTF-8)、[GB18030](https://baike.baidu.com/item/GB18030)和[UNICODE](https://baike.baidu.com/item/UNICODE)等。对应的编码规则有单字节字符编码、ANSI编码和UNICODE编码等。 [2]

| **分类** | **编码标准** | **说明** |
| --- | --- | --- |
| 单字节字符编码 | ISO-8859-1 | 最简单的编码规则，每一个字节直接作为一个UNICODE 字符。比如，[0xD6, 0xD0] 这两个字节，通过iso-8859-1 转化为字符串时，将直接得到[0x00D6, 0x00D0] 两个UNICODE 字符，即"ÖÐ"。反之，将UNICODE 字符串通过iso-8859-1 转化为字节串时，只能正常转化0~255 范围的字符。 |
| ANSI 编码 | GB2312,BIG5,Shift\_JIS,ISO-8859-2 …… | 把UNICODE 字符串通过ANSI 编码转化为"字节串"时，根据各自编码的规定，一个UNICODE 字符可能转化成一个字节或多个字节。反之，将字节串转化成字符串时，也可能多个字节转化成一个字符。比如，[0xD6, 0xD0] 这两个字节，通过GB2312 转化为字符串时，将得到[0x4E2D] 一个字符，即'中' 字。"ANSI 编码"的特点：1. 这些"ANSI 编码标准"都只能处理各自语言范围之内的UNICODE 字符。2. "UNICODE 字符"与"转换出来的字节"之间的关系是人为规定的。 |
| UNICODE 编码 | UTF-8,UTF-16, UnicodeBig …… | 与"ANSI 编码"类似的，把字符串通过UNICODE 编码转化成"字节串"时，一个UNICODE 字符可能转化成一个字节或多个字节。与"ANSI 编码"不同的是：1. 这些"UNICODE 编码"能够处理所有的UNICODE 字符。2. "UNICODE 字符"与"转换出来的字节"之间是可以通过计算得到的。 |

- [ISO 646](https://en.wikipedia.org/wiki/ISO/IEC_646)
  - [ASCII](https://en.wikipedia.org/wiki/ASCII)
- [EBCDIC](https://en.wikipedia.org/wiki/EBCDIC)
- [ISO 8859](https://en.wikipedia.org/wiki/ISO/IEC_8859):
  - [ISO 8859-1](https://en.wikipedia.org/wiki/ISO/IEC_8859-1) Western Europe
  - [ISO 8859-2](https://en.wikipedia.org/wiki/ISO/IEC_8859-2) Western and Central Europe
  - [ISO 8859-3](https://en.wikipedia.org/wiki/ISO/IEC_8859-3) Western Europe and South European (Turkish, Maltese plus Esperanto)
  - [ISO 8859-4](https://en.wikipedia.org/wiki/ISO/IEC_8859-4) Western Europe and Baltic countries (Lithuania, Estonia, Latvia and Lapp)
  - [ISO 8859-5](https://en.wikipedia.org/wiki/ISO/IEC_8859-5) Cyrillic alphabet
  - [ISO 8859-6](https://en.wikipedia.org/wiki/ISO/IEC_8859-6) Arabic
  - [ISO 8859-7](https://en.wikipedia.org/wiki/ISO/IEC_8859-7) Greek
  - [ISO 8859-8](https://en.wikipedia.org/wiki/ISO/IEC_8859-8) Hebrew
  - [ISO 8859-9](https://en.wikipedia.org/wiki/ISO/IEC_8859-9) Western Europe with amended Turkish character set
  - [ISO 8859-10](https://en.wikipedia.org/wiki/ISO/IEC_8859-10) Western Europe with rationalised character set for Nordic languages, including complete Icelandic set
  - [ISO 8859-11](https://en.wikipedia.org/wiki/ISO/IEC_8859-11) Thai
  - [ISO 8859-13](https://en.wikipedia.org/wiki/ISO/IEC_8859-13) Baltic languages plus Polish
  - [ISO 8859-14](https://en.wikipedia.org/wiki/ISO/IEC_8859-14) Celtic languages (Irish Gaelic, Scottish, Welsh)
  - [ISO 8859-15](https://en.wikipedia.org/wiki/ISO/IEC_8859-15) Added the Euro sign and other rationalisations to ISO 8859-1
  - [ISO 8859-16](https://en.wikipedia.org/wiki/ISO/IEC_8859-16) Central, Eastern and Southern European languages (Albanian, Bosnian, Croatian, Hungarian, Polish, Romanian, Serbian and Slovenian, but also French, German, Italian and Irish Gaelic)

- [MS-Windows character sets](https://en.wikipedia.org/wiki/Windows_code_page):
  - [Windows-1250](https://en.wikipedia.org/wiki/Windows-1250) for Central European languages that use Latin script, (Polish, Czech, Slovak, Hungarian, Slovene, Serbian, Croatian, Bosnian, Romanian and Albanian)
  - [Windows-1251](https://en.wikipedia.org/wiki/Windows-1251) for Cyrillic alphabets
  - [Windows-1252](https://en.wikipedia.org/wiki/Windows-1252) for Western languages
  - [Windows-1253](https://en.wikipedia.org/wiki/Windows-1253) for Greek
  - [Windows-1254](https://en.wikipedia.org/wiki/Windows-1254) for Turkish
  - [Windows-1255](https://en.wikipedia.org/wiki/Windows-1255) for Hebrew
  - [Windows-1256](https://en.wikipedia.org/wiki/Windows-1256) for Arabic
  - [Windows-1257](https://en.wikipedia.org/wiki/Windows-1257) for Baltic languages
  - [Windows-1258](https://en.wikipedia.org/wiki/Windows-1258) for Vietnamese

- [JIS X 0208](https://en.wikipedia.org/wiki/JIS_X_0208) is a widely deployed standard for Japanese character encoding that has several encoding forms.
  - [Shift JIS](https://en.wikipedia.org/wiki/Shift_JIS) (Microsoft [Code page 932](https://en.wikipedia.org/wiki/Code_page_932_(Microsoft_Windows)) is a dialect of Shift\_JIS)
  - [EUC-JP](https://en.wikipedia.org/wiki/Extended_Unix_Code)
  - [ISO-2022-JP](https://en.wikipedia.org/wiki/ISO/IEC_2022)
- [JIS X 0213](https://en.wikipedia.org/wiki/JIS_X_0213) is an extended version of JIS X 0208.
  - [Shift\_JIS-2004](https://en.wikipedia.org/wiki/Shift_JIS)
  - [EUC-JIS-2004](https://en.wikipedia.org/wiki/Extended_Unix_Code)
  - [ISO-2022-JP-2004](https://en.wikipedia.org/wiki/ISO/IEC_2022)
- Chinese [Guobiao](https://en.wikipedia.org/wiki/List_of_GB_standards)
  - [GB 2312](https://en.wikipedia.org/wiki/GB_2312)
  - [GBK](https://en.wikipedia.org/wiki/GBK_(character_encoding)) (Microsoft Code page 936)
  - [GB 18030](https://en.wikipedia.org/wiki/GB_18030)
- Taiwan [Big5](https://en.wikipedia.org/wiki/Big5) (a more famous variant is Microsoft [Code page 950](https://en.wikipedia.org/wiki/Code_page_950))
  - Hong Kong [HKSCS](https://en.wikipedia.org/wiki/HKSCS)
- Korean
  - [KS X 1001](https://en.wikipedia.org/wiki/KS_X_1001) is a Korean double-byte character encoding standard
  - [EUC-KR](https://en.wikipedia.org/wiki/Extended_Unix_Code#EUC-KR)
  - [ISO-2022-KR](https://en.wikipedia.org/wiki/ISO/IEC_2022)
- [Unicode](https://en.wikipedia.org/wiki/Unicode) (and subsets thereof, such as the 16-bit 'Basic Multilingual Plane')
  - [UTF-8](https://en.wikipedia.org/wiki/UTF-8)
  - [UTF-16](https://en.wikipedia.org/wiki/UTF-16)
  - [UTF-32](https://en.wikipedia.org/wiki/UTF-32)

#### American National Standards Institute（ANSI）编码

不同的国家和地区制定了不同的标准，由此产生了 GB2312, BIG5, JIS 等各自的编码标准。这些使用 2 个字节来代表一个字符的各种汉字延伸编码方式，称为 ANSI 编码。在简体中文系统下，ANSI 编码代表 GB2312 编码，在日文操作系统下，ANSI 编码代表 JIS 编码。 不同 ANSI 编码之间互不兼容，当信息在国际间交流时，无法将属于两种语言的文字，存储在同一段 ANSI 编码的文本中。 当然对于ANSI编码而言，0x00~0x7F之间的字符，依旧是1个字节代表1个字符。这一点是ASNI编码与Unicode编码之间最大也最明显的区别。

#### Unicode（Universal Coded Character Set） 字符集 （144,697 characters）

[https://home.unicode.org/](https://home.unicode.org/)

[https://en.wikipedia.org/wiki/Unicode](https://en.wikipedia.org/wiki/Unicode)

**Unicode** , formally the  **Unicode Standard** , is an [information technology](https://en.wikipedia.org/wiki/Information_technology) [standard](https://en.wikipedia.org/wiki/Technical_standard) for the consistent [encoding](https://en.wikipedia.org/wiki/Character_encoding), representation, and handling of [text](https://en.wikipedia.org/wiki/Character_(computing)) expressed in most of the world's [writing systems](https://en.wikipedia.org/wiki/Writing_system). The standard, which is maintained by the [Unicode Consortium](https://en.wikipedia.org/wiki/Unicode_Consortium), defines 144,697 characters[[1]](https://en.wikipedia.org/wiki/Unicode#cite_note-1)[[2]](https://en.wikipedia.org/wiki/Unicode#cite_note-2) covering 159 modern and historic [scripts](https://en.wikipedia.org/wiki/Script_(Unicode)), as well as symbols, [emoji](https://en.wikipedia.org/wiki/Emoji), and non-visual control and formatting codes.

| **Encoding formats** |
- [UTF-8](https://en.wikipedia.org/wiki/UTF-8)
- [UTF-16](https://en.wikipedia.org/wiki/UTF-16)
- [GB18030](https://en.wikipedia.org/wiki/GB_18030)
- **Less common** :
- [UTF-32](https://en.wikipedia.org/wiki/UTF-32)
- [BOCU](https://en.wikipedia.org/wiki/Binary_Ordered_Compression_for_Unicode)
- [SCSU](https://en.wikipedia.org/wiki/Standard_Compression_Scheme_for_Unicode)
- **Obsolete:**
- [UTF-7](https://en.wikipedia.org/wiki/UTF-7)
 |
| --- | --- |
| **Preceded by** | [ISO/IEC 8859](https://en.wikipedia.org/wiki/ISO/IEC_8859), various others |

[Unicode can be implemented](https://en.wikipedia.org/wiki/Comparison_of_Unicode_encodings) by different character encodings. The Unicode standard defines Unicode Transformation Formats (UTF): [UTF-8](https://en.wikipedia.org/wiki/UTF-8), [UTF-16](https://en.wikipedia.org/wiki/UTF-16), and [UTF-32](https://en.wikipedia.org/wiki/UTF-32), and several other encodings. The most commonly used encodings are UTF-8, UTF-16, and the obsolete [UCS-2](https://en.wikipedia.org/wiki/Universal_Coded_Character_Set) (a precursor of UTF-16 without full support for Unicode); [GB18030](https://en.wikipedia.org/wiki/GB_18030), while not an official Unicode standard, is standardized in China and implements Unicode fully.

       Unicode（统一码、万国码、单一码）是一种在计算机上使用的字符编码。它为每种语言中的每个字符设定了统一并且唯一的二进制编码，以满足跨语言、跨平台进行文本转换、处理的要求。1990年开始研发，1994年正式公布。随着计算机工作能力的增强，Unicode也在面世以来的十多年里得到普及。

       Unicode是国际组织制定的可以容纳世界上所有文字和符号的字符编码方案。Unicode用数字0-0x10FFFF来映射这些字符，最多可以容纳1114112个字符，或者说有1114112个码位。码位就是可以分配给字符的数字。UTF-8、UTF-16、UTF-32都是将数字转换到程序数据的编码方案。

##### byte-order mark，BOM 字节顺序标记

Unicode可以以8位、16位或32位整数为单位进行编码。对于16位和32位的表示方法，从任意来源接收文本的电脑需要知道整数是以何种字节顺序编码的。字节顺序标记的编码方式与文档文件的其他部分相同，如果它的字节被调换，就会变成一个[非字符](https://zh.wikipedia.org/wiki/Unicode%E5%AD%97%E7%AC%A6%E5%88%97%E8%A1%A8#%E7%89%B9%E6%AE%8A)的Unicode码位。因此，访问文本的过程中，可以透过检查这头几个字节来确定[字节顺序](https://zh.wikipedia.org/wiki/%E5%AD%97%E8%8A%82%E9%A1%BA%E5%BA%8F)，而不需要文字流本身以外的一些约定或[元数据](https://zh.wikipedia.org/wiki/%E5%85%83%E8%B3%87%E6%96%99)。一般来说，如果有必要，接收资料的电脑会将字节换成自己的字节顺序，不再需要字节顺序标记进行处理。

字符U+FEFF如果出现在字节流的开头，则用来标识该字节流的字节序，是高位在前还是低位在前。如果它出现在字节流的中间，则表达 **零宽度非换行空格**"[zero-width non-breaking space](https://en.wikipedia.org/wiki/Zero-width_non-breaking_space)"的意义，用户看起来就是一个空格。

每个Unicode编码（包括Unicode标准以外的编码，如UTF-7，见[下表](https://zh.wikipedia.org/zh-cn/%E4%BD%8D%E5%85%83%E7%B5%84%E9%A0%86%E5%BA%8F%E8%A8%98%E8%99%9F#%E4%B8%8D%E5%90%8C%E7%B7%A8%E7%A2%BC%E7%9A%84%E4%BD%8D%E5%85%83%E7%B5%84%E9%A0%86%E5%BA%8F%E8%A8%98%E8%99%9F%E7%9A%84%E8%A1%A8%E7%A4%BA)）的BOM字节序列都不一样，而且这些序列都不可能出现在以其他编码存储的文字流的开头。因此，在文字流的开头放置一个编码的BOM，可以表明文本是Unicode，并识别所使用的编码方案。这种对BOM字符的使用被称为"Unicode签名"

Unicode标准允许在UTF-8中使用BOM，但并不要求或推荐使用它。字节顺序在UTF-8中没有任何意义，所以它在UTF-8中的唯一用途是在开始时发出信号，表明文本流是用UTF-8编码的，或者表明它是从包含可选BOM的文本流转换到UTF-8的。该标准也不建议在有BOM的情况下将其删除，以便在不同的编码之间往返不会丢失信息，并使依赖BOM的代码继续工作。 IETF建议，如果一个协议要么(a)总是使用UTF-8，要么(b)有一些其他方法来表明正在使用的编码，那么它 "应该禁止使用U+FEFF作为签名"。

在[UTF-16](https://zh.wikipedia.org/wiki/UTF-16)中，字节顺序标记被放置为文件或文字符串流的第一个字符，以标示在此文件或文字符串流中，以所有十六比特为单位的字码的端序（[字节顺序](https://zh.wikipedia.org/wiki/%E5%AD%97%E8%8A%82%E9%A1%BA%E5%BA%8F)）

- 如果十六比特单位被表示成[大端序](https://zh.wikipedia.org/wiki/%E5%AD%97%E8%8A%82%E9%A1%BA%E5%BA%8F)，这字节顺序标记字符在序列中将呈现0xFE，其后跟着0xFF（其中的0x用来标示[十六进制](https://zh.wikipedia.org/wiki/%E5%8D%81%E5%85%AD%E9%80%B2%E4%BD%8D)）。
- 如果十六比特单位使用[小端序](https://zh.wikipedia.org/wiki/%E5%AD%97%E8%8A%82%E9%A1%BA%E5%BA%8F)，这个字节序列为0xFF，其后接着0xFE。

这两个序列都不是有效的UTF-8，所以它们的出现表明该文件不是用UTF-8编码的。

##### UTF-8（Unicode Transformation Format – 8 bit）编码

**UTF-8**  is a [variable-width](https://en.wikipedia.org/wiki/Variable-width_encoding) [character encoding](https://en.wikipedia.org/wiki/Character_encoding) used for electronic communication. Defined by the [Unicode Standard](https://en.wikipedia.org/wiki/Unicode_Standard), the name is derived from _Unicode_ (or _Universal Coded Character Set_) _Transformation Format – 8-bit_

UTF-8 is capable of encoding all 1,112,064[[nb 1]](https://en.wikipedia.org/wiki/UTF-8#cite_note-2) valid character [code points](https://en.wikipedia.org/wiki/Code_point) in [Unicode](https://en.wikipedia.org/wiki/Unicode) using one to four one-[byte](https://en.wikipedia.org/wiki/Byte) (8-bit) code units. Code points with lower numerical values, which tend to occur more frequently, are encoded using fewer bytes. It was designed for [backward compatibility](https://en.wikipedia.org/wiki/Backward_compatibility) with [ASCII](https://en.wikipedia.org/wiki/ASCII): the first 128 characters of Unicode, which correspond one-to-one with ASCII, are encoded using a single byte with the same binary value as ASCII, so that valid ASCII text is valid UTF-8-encoded Unicode as well.

The official [Internet Assigned Numbers Authority](https://en.wikipedia.org/wiki/Internet_Assigned_Numbers_Authority) (IANA) code for the encoding is "UTF-8".[[5]](https://en.wikipedia.org/wiki/UTF-8#cite_note-IANA_2013_CS-6) All letters are upper-case, and the name is hyphenated. This spelling is used in all the Unicode Consortium documents relating to the encoding.

However, the name " **utf-8**" may be used by all standards conforming to the IANA list (which include [CSS](https://en.wikipedia.org/wiki/Cascading_Style_Sheets), [HTML](https://en.wikipedia.org/wiki/HTML), [XML](https://en.wikipedia.org/wiki/XML), and [HTTP headers](https://en.wikipedia.org/wiki/HTTP_headers)),[[6]](https://en.wikipedia.org/wiki/UTF-8#cite_note-7) as the declaration is case insensitive.[[5]](https://en.wikipedia.org/wiki/UTF-8#cite_note-IANA_2013_CS-6)

Other variants, such as those that omit the hyphen or replace it with a space, i.e. " **utf8**" or " **UTF 8**", are not accepted as correct by the governing standards.[[7]](https://en.wikipedia.org/wiki/UTF-8#cite_note-rfc3629-8) Despite this, most [web browsers](https://en.wikipedia.org/wiki/Web_browser) can understand them, and so standards intended to describe existing practice (such as HTML5) may effectively require their recognition.[[8]](https://en.wikipedia.org/wiki/UTF-8#cite_note-9)

| **Code point \<-\> UTF-8 conversion** |
| --- |
| **First code point** | **Last code point** | **Byte 1** | **Byte 2** | **Byte 3** | **Byte 4** |
| U+0000 | U+007F | 0xxxxxxx |
 |
| U+0080 | U+07FF | 110xxxxx | 10xxxxxx |
 |
| U+0800 | U+FFFF | 1110xxxx | 10xxxxxx | 10xxxxxx |
 |
| U+10000 | [[nb 2]](https://en.wikipedia.org/wiki/UTF-8#cite_note-16)U+10FFFF | 11110xxx | 10xxxxxx | 10xxxxxx | 10xxxxxx |

The first 128 characters (US-ASCII) need one byte. The next 1,920 characters need two bytes to encode, which covers the remainder of almost all [Latin-script alphabets](https://en.wikipedia.org/wiki/Latin-script_alphabet), and also [IPA extensions](https://en.wikipedia.org/wiki/International_Phonetic_Alphabet), [Greek](https://en.wikipedia.org/wiki/Greek_alphabet), [Cyrillic](https://en.wikipedia.org/wiki/Cyrillic_script), [Coptic](https://en.wikipedia.org/wiki/Coptic_alphabet), [Armenian](https://en.wikipedia.org/wiki/Armenian_alphabet), [Hebrew](https://en.wikipedia.org/wiki/Hebrew_alphabet), [Arabic](https://en.wikipedia.org/wiki/Arabic_alphabet), [Syriac](https://en.wikipedia.org/wiki/Syriac_alphabet), [Thaana](https://en.wikipedia.org/wiki/Thaana) and [N'Ko](https://en.wikipedia.org/wiki/N%27Ko_alphabet) alphabets, as well as [Combining Diacritical Marks](https://en.wikipedia.org/wiki/Combining_Diacritical_Marks). Three bytes are needed for characters in the rest of the [Basic Multilingual Plane](https://en.wikipedia.org/wiki/Basic_Multilingual_Plane), which contains virtually all characters in common use,[[15]](https://en.wikipedia.org/wiki/UTF-8#cite_note-unicode-ch02-bmp-17) including most [Chinese, Japanese and Korean characters](https://en.wikipedia.org/wiki/CJK_characters). Four bytes are needed for characters in the [other planes of Unicode](https://en.wikipedia.org/wiki/Plane_(Unicode)), which include less common [CJK characters](https://en.wikipedia.org/wiki/CJK_characters), various historic scripts, [mathematical symbols](https://en.wikipedia.org/wiki/Glossary_of_mathematical_symbols), and [emoji](https://en.wikipedia.org/wiki/Emoji) (pictographic symbols).

A "character" can actually take more than 4 bytes, e.g. an [emoji flag character](https://en.wikipedia.org/wiki/Regional_indicator_symbol) takes 8 bytes since it's "constructed from a pair of Unicode scalar values"

UTF-8 was first officially presented at the [USENIX](https://en.wikipedia.org/wiki/USENIX) conference in [San Diego](https://en.wikipedia.org/wiki/San_Diego), from January 25 to 29, 1993. The [Internet Engineering Task Force](https://en.wikipedia.org/wiki/Internet_Engineering_Task_Force) adopted UTF-8 in its Policy on Character Sets and Languages in RFC 2277 ([BCP](https://en.wikipedia.org/wiki/Request_for_Comments#%22Best_Current_Practice%22) 18) for future Internet standards work, replacing [Single Byte Character Sets](https://en.wikipedia.org/wiki/Single_Byte_Character_Set) such as [Latin-1](https://en.wikipedia.org/wiki/ISO/IEC_8859-1) in older RFCs.[[67]](https://en.wikipedia.org/wiki/UTF-8#cite_note-70)

In November 2003, UTF-8 was restricted by [RFC](https://en.wikipedia.org/wiki/RFC_(identifier)) [3629](https://datatracker.ietf.org/doc/html/rfc3629) to match the constraints of the [UTF-16](https://en.wikipedia.org/wiki/UTF-16) character encoding: explicitly prohibiting code points corresponding to the high and low surrogate characters removed more than 3% of the three-byte sequences, and ending at U+10FFFF removed more than 48% of the four-byte sequences and all five- and six-byte sequences.

        UTF-8是UNICODE的一种变长字符编码又称万国码，由Ken Thompson于1992年创建。现在已经标准化为RFC 3629。UTF-8用1到6个字节编码UNICODE字符。用在网页上可以同一页面显示中文简体繁体及其它语言(如日文，韩文)。

![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_1e14312f88440bbb.png)

Use of the main encodings on the web from 2001 to 2012 as recorded by Google,[[33]](https://en.wikipedia.org/wiki/UTF-8#cite_note-MarkDavis2012-36) with UTF-8 overtaking all others in 2008 and over 60% of the web in 2012 (since then approaching 100%). The [ASCII](https://en.wikipedia.org/wiki/ASCII)-only figure includes all web pages that only contain ASCII characters, regardless of the declared header.

**UTF-16 is the only web-encoding incompatible with [ASCII](https://en.wikipedia.org/wiki/ASCII),[[3]](https://en.wikipedia.org/wiki/UTF-16#cite_note-3) and never gained popularity on the web, where it is used by under 0.002% (little over 1 thousandth of 1 percent) of web pages.[[4]](https://en.wikipedia.org/wiki/UTF-16#cite_note-4) [UTF-8](https://en.wikipedia.org/wiki/UTF-8), by comparison, is used by 98% of all web pages.[[5](https://en.wikipedia.org/wiki/UTF-16#cite_note-5)**

##### UTF-16 编码

[https://en.wikipedia.org/wiki/UTF-16](https://en.wikipedia.org/wiki/UTF-16)

**UTF-16**  ([16-bit](https://en.wikipedia.org/wiki/16-bit_computing) [Unicode](https://en.wikipedia.org/wiki/Unicode) Transformation Format) is a [character encoding](https://en.wikipedia.org/wiki/Character_encoding) capable of encoding all 1,112,064 valid character [code points](https://en.wikipedia.org/wiki/Code_point) of Unicode (in fact this number of code points is dictated by the design of UTF-16). The encoding is [variable-length](https://en.wikipedia.org/wiki/Variable-width_encoding), as code points are encoded with one or two 16-bit _code units_. UTF-16 arose from an earlier obsolete fixed-width 16-bit encoding, now known as [UCS-2](https://en.wikipedia.org/wiki/UCS-2) (for 2-byte Universal Character Set), once it became clear that more than 216 (65,536) code points were needed.[[1](https://en.wikipedia.org/wiki/UTF-16#cite_note-unicode.org/faq-1)

UTF-16用2或4个字节编码UNICODE字符

**UTF-16 is used internally by systems such as [Microsoft Windows](https://en.wikipedia.org/wiki/Microsoft_Windows), the [Java programming language](https://en.wikipedia.org/wiki/Java_programming_language) and [JavaScript](https://en.wikipedia.org/wiki/JavaScript)/ECMAScript. It is also often used for [plain text](https://en.wikipedia.org/wiki/Plain_text) and for word-processing data files on Microsoft Windows. It is rarely used for files on [Unix-like](https://en.wikipedia.org/wiki/Unix-like) systems. As of May 2019, Microsoft reversed its course of only emphasizing UTF-16 for Unicode; for Windows applications, Microsoft recommends and supports [UTF-8](https://en.wikipedia.org/wiki/UTF-8) (e.g. for [Universal Windows Platform](https://en.wikipedia.org/wiki/Universal_Windows_Platform) (UWP) apps.[[2]](https://en.wikipedia.org/wiki/UTF-16#cite_note-Microsoft-UTF-8-2)).**

**UTF-16 is the only web-encoding incompatible with ** [**ASCII**](https://en.wikipedia.org/wiki/ASCII) **,** [**[3]**](https://en.wikipedia.org/wiki/UTF-16#cite_note-3) ** and never gained popularity on the web** , where it is used by under 0.002% (little over 1 thousandth of 1 percent) of web pages.[[4]](https://en.wikipedia.org/wiki/UTF-16#cite_note-4) [UTF-8](https://en.wikipedia.org/wiki/UTF-8), by comparison, is used by 98% of all web pages.[[5]](https://en.wikipedia.org/wiki/UTF-16#cite_note-5) The [Web Hypertext Application Technology Working Group (WHATWG)](https://en.wikipedia.org/wiki/WHATWG) considers UTF-8 "the mandatory encoding for all [text]" and that for security reasons browser applications should not use UTF-16.[[6]](https://en.wikipedia.org/wiki/UTF-16#cite_note-mandatory-6)

![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_face2e0be96c5913.png)

#### How is encoding handled correctly during copy-paste between programs?

[https://softwareengineering.stackexchange.com/questions/270226/how-is-encoding-handled-correctly-during-copy-paste-between-programs](https://softwareengineering.stackexchange.com/questions/270226/how-is-encoding-handled-correctly-during-copy-paste-between-programs)

A program transferring text can do one of three things: Transfer without telling which encoding is used, transfer using a standard encoding, or transfer while specifying the encoding.

The receiving program will then either know the encoding or not, depending on what the sending program did. If the encoding is not known to the receiver then it can look at the text and make a guess. For text containing Unicode preceding it with a byte order marker helps (a Unicode BOM makes quite clear which Unicode encoding is used and will be very, very rare otherwise. If text is encoded in some Windows codepage other than 1152, there us basically no way for the receiver to figure out the encoding, so your text will be rubbish.

#### **CJKV**** （ ****The Chinese, Japanese, Korean and Vietnam**** ） **** Unified Ideographs[**[edit source](https://en.wikipedia.org/w/index.php?title=CJK_Unified_Ideographs&action=edit&section=2)]

[https://en.wikipedia.org/wiki/CJK\_Unified\_Ideographs](https://en.wikipedia.org/wiki/CJK_Unified_Ideographs)

**中日韩统一表意文字** （英语： **CJK Unified Ideographs** ），也称 **统一汉字** 、 **统汉码** （英语： **Unihan** ），目的是要把分别来自[中文](https://zh.wikipedia.org/wiki/%E4%B8%AD%E6%96%87)、[日文](https://zh.wikipedia.org/wiki/%E6%97%A5%E6%96%87)、[韩文](https://zh.wikipedia.org/wiki/%E9%9F%93%E6%96%87)、[越南文](https://zh.wikipedia.org/wiki/%E8%B6%8A%E5%8D%97%E8%AF%AD)、[壮文](https://zh.wikipedia.org/wiki/%E5%A3%AE%E6%96%87)、[琉球文](https://zh.wikipedia.org/wiki/%E7%90%89%E7%90%83%E6%96%87)中，起源相同、本义相同、形状一样或稍异的[表意文字](https://zh.wikipedia.org/wiki/%E8%AF%AD%E7%B4%A0%E6%96%87%E5%AD%97)，在[ISO 10646](https://zh.wikipedia.org/wiki/ISO_10646)及[Unicode](https://zh.wikipedia.org/wiki/Unicode)标准赋予相同[编码](https://zh.wikipedia.org/wiki/%E7%B7%A8%E7%A2%BC)。

所谓"起源相同、本义相同"、主要是[汉字](https://zh.wikipedia.org/wiki/%E6%B1%89%E5%AD%97)，包括[繁体字](https://zh.wikipedia.org/wiki/%E7%B9%81%E9%AB%94%E5%AD%97)、[简化字](https://zh.wikipedia.org/wiki/%E7%B0%A1%E5%8C%96%E5%AD%97)、[日本汉字](https://zh.wikipedia.org/wiki/%E6%97%A5%E6%9C%AC%E6%BC%A2%E5%AD%97)（漢字／かんじ）、[韩国汉字](https://zh.wikipedia.org/wiki/%E9%9F%93%E5%9C%8B%E6%BC%A2%E5%AD%97)（漢字／한자）、[琉球汉字](https://zh.wikipedia.org/wiki/%E7%90%89%E7%90%83%E6%BC%A2%E5%AD%97)（漢字／ハンジ）、越南的[喃字](https://zh.wikipedia.org/wiki/%E5%96%83%E5%AD%97)（𡨸喃／Chữ Nôm）与[儒字](https://zh.wikipedia.org/wiki/%E5%84%92%E5%AD%97)（𡨸儒／Chữ Nho）、[方块壮字](https://zh.wikipedia.org/wiki/%E6%96%B9%E5%A1%8A%E5%A3%AF%E5%AD%97)（[𭨡](https://www.unicode.org/cgi-bin/GetUnihanData.pl?codepoint=2DA21)倱／sawgun）

Historically, Vietnam used Chinese ideographs too, so sometimes the abbreviation  **CJKV**  is used. This system was replaced by the Latin-based [Vietnamese alphabet](https://en.wikipedia.org/wiki/Vietnamese_alphabet) in the 1920s.

![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_c0b47ec78813b4d8.png)

The basic block named [_CJK Unified Ideographs_](https://en.wikipedia.org/wiki/CJK_Unified_Ideographs_(Unicode_block)) (4E00–9FFF) contains 20,992 basic [Chinese characters](https://en.wikipedia.org/wiki/Chinese_characters) in the range U+4E00 through U+9FFF. The block not only includes characters used in the [Chinese writing system](https://en.wikipedia.org/wiki/Written_Chinese) but also [kanji](https://en.wikipedia.org/wiki/Kanji) used in the [Japanese writing system](https://en.wikipedia.org/wiki/Japanese_writing_system) and [hanja](https://en.wikipedia.org/wiki/Hanja), whose use is diminishing in [Korea](https://en.wikipedia.org/wiki/Korean_mixed_script). Many characters in this block are used in all three [writing systems](https://en.wikipedia.org/wiki/Writing_system), while others are in only one or two of the three. [Chữ Hán](https://en.wikipedia.org/wiki/Ch%E1%BB%AF_H%C3%A1n) are also used in Vietnam's [chữ Nôm](https://en.wikipedia.org/wiki/Ch%E1%BB%AF_N%C3%B4m) (now obsolete). The first 20,902 characters in the block are arranged according to the [Kangxi Dictionary](https://en.wikipedia.org/wiki/Kangxi_Dictionary) ordering of [radicals](https://en.wikipedia.org/wiki/Radical_(Chinese_character)). In this system the characters written with the fewest strokes are listed first. The remaining characters were added later, and so are not in radical order.

The block is the result of [Han unification](https://en.wikipedia.org/wiki/Han_unification),[[2]](https://en.wikipedia.org/wiki/CJK_Unified_Ideographs#cite_note-2) which was somewhat controversial within East Asia.[[3]](https://en.wikipedia.org/wiki/CJK_Unified_Ideographs#cite_note-3) Since Chinese, Japanese and Korean characters were coded in the same location, the appearance of a selected glyph could depend on the particular font being used. However, the _source separation rule_ states that characters encoded separately in an earlier character set would remain separate in the new Unicode encoding.[[4]](https://en.wikipedia.org/wiki/CJK_Unified_Ideographs#cite_note-4)

##### 收字来源

###### **最初期统一汉字**** [**[编辑](https://zh.wikipedia.org/w/index.php?title=%E4%B8%AD%E6%97%A5%E9%9F%93%E7%B5%B1%E4%B8%80%E8%A1%A8%E6%84%8F%E6%96%87%E5%AD%97&action=edit&section=5)]

最初期的统一汉字共20,902字，其范围为：U+4E00–U+9FA5。其收字来源包括了以下[字集](https://zh.wikipedia.org/wiki/%E5%AD%97%E9%9B%86)：

| **类别** | **来源代码** | **名称** | **字数** |
| --- | --- | --- | --- |
| 中国大陆
国标源（G） | G0 | [GB 2312-80](https://zh.wikipedia.org/wiki/GB_2312) | 6763字 |
| G1 | [GB 12345-90](https://zh.wikipedia.org/wiki/GB_12345) | 2352字（含58个[香港字](https://zh.wikipedia.org/wiki/%E9%A6%99%E6%B8%AF%E5%AD%97)和92个[吏读](https://zh.wikipedia.org/wiki/%E5%90%8F%E8%AE%80)字，不包括和GB 2312重复的字） |
| G3 | [GB 7589-87 繁体版本](https://zh.wikipedia.org/wiki/%E5%9B%BD%E5%AE%B6%E6%A0%87%E5%87%86%E4%BB%A3%E7%A0%81#GB_7589) | 7237字 |
| G5 | [GB 7590-87 繁体版本](https://zh.wikipedia.org/wiki/%E5%9B%BD%E5%AE%B6%E6%A0%87%E5%87%86%E4%BB%A3%E7%A0%81#GB_7590) | 7039字 |
| G7 | [现代汉语通用字表](https://zh.wikipedia.org/wiki/%E7%8F%BE%E4%BB%A3%E6%BC%A2%E8%AA%9E%E9%80%9A%E7%94%A8%E5%AD%97%E8%A1%A8) | 42字（G0, 1, 3, 5, 8未包括的字） |
| G8 | [GB 8565.2-89](https://zh.wikipedia.org/wiki/%E5%9B%BD%E5%AE%B6%E6%A0%87%E5%87%86%E4%BB%A3%E7%A0%81#GB_8565) | 290字（G0, 1, 3, 5未包括的字） |
| 台湾源（T） | T1 | [CNS 11643-1986](https://zh.wikipedia.org/wiki/%E5%9C%8B%E5%AE%B6%E6%A8%99%E6%BA%96%E4%B8%AD%E6%96%87%E4%BA%A4%E6%8F%9B%E7%A2%BC)第一字面 | 5401+9字[计量用汉字](https://zh.wikipedia.org/wiki/%E8%A8%88%E9%87%8F%E7%94%A8%E6%BC%A2%E5%AD%97) |
| T2 | CNS 11643-1986第二字面 | 7650字 |
| TE | CNS 11643-1986第十四字面 | 6319+239字[中文信息交换码](https://zh.wikipedia.org/wiki/%E4%B8%AD%E6%96%87%E8%B3%87%E8%A8%8A%E4%BA%A4%E6%8F%9B%E7%A2%BC)特字+10个施乐字符集（Xerox Character Code Standard，XCCS）特字 |
| 日本源（J） | J0 | [JIS X 0208-90](https://zh.wikipedia.org/wiki/JIS_X_0208) | 6335字+非汉字1个（仝）[[11]](https://zh.wikipedia.org/zh-cn/%E4%B8%AD%E6%97%A5%E9%9F%93%E7%B5%B1%E4%B8%80%E8%A1%A8%E6%84%8F%E6%96%87%E5%AD%97#cite_note-12) |
| J1 | [JIS X 0212-90](https://zh.wikipedia.org/w/index.php?title=JIS_X_0212&action=edit&redlink=1) | 5801字 |
| 韩国源（K） | K0 | [KS C 5601-87](https://zh.wikipedia.org/wiki/KS_C_5601) | 4888字（含268个重见字[[12]](https://zh.wikipedia.org/zh-cn/%E4%B8%AD%E6%97%A5%E9%9F%93%E7%B5%B1%E4%B8%80%E8%A1%A8%E6%84%8F%E6%96%87%E5%AD%97#cite_note-13)） |
| K1 | [KS C 5657-91](https://zh.wikipedia.org/w/index.php?title=KS_C_5657&action=edit&redlink=1) | 2856字 |
| 委员会源（U） |
 | KS C 5601-1987（当中重复的汉字） |
 |
|
 | [美国国会图书馆](https://zh.wikipedia.org/wiki/%E7%BE%8E%E5%9C%8B%E5%9C%8B%E6%9C%83%E5%9C%96%E6%9B%B8%E9%A4%A8)之东亚字符编码（East Asia Character Code，简称EACC；标准号[ANSI](https://zh.wikipedia.org/wiki/ANSI) Z39.64-1989）[[13]](https://zh.wikipedia.org/zh-cn/%E4%B8%AD%E6%97%A5%E9%9F%93%E7%B5%B1%E4%B8%80%E8%A1%A8%E6%84%8F%E6%96%87%E5%AD%97#cite_note-14) |
 |
|
 | [大五码](https://zh.wikipedia.org/wiki/%E5%A4%A7%E4%BA%94%E7%A2%BC) |
 |
|
 | [中文信息交换码](https://zh.wikipedia.org/wiki/%E4%B8%AD%E6%96%87%E8%B3%87%E8%A8%8A%E4%BA%A4%E6%8F%9B%E7%A2%BC)第一字面 |
 |
|
 | [GB 12052-89](https://zh.wikipedia.org/wiki/GB_12052)（汉字部分） |
 |
|
 | JEF（富士通标准） |
 |
|
 | 中国大陆[电报码](https://zh.wikipedia.org/wiki/%E7%94%B5%E6%8A%A5%E7%A0%81) |
 |
|
 | 台湾电报码（CCDC） |
 |
|
 | 施乐中文编码 |
 |
|
 | 人名用汉字准用字体表（人名用汉字许容字体表；日本） |
 |
|
 | IBM选取的日本和韩国表意文字 |

 |

###### 扩展A区[[编辑](https://zh.wikipedia.org/w/index.php?title=%E4%B8%AD%E6%97%A5%E9%9F%93%E7%B5%B1%E4%B8%80%E8%A1%A8%E6%84%8F%E6%96%87%E5%AD%97&action=edit&section=6)]

[扩展](https://zh.wikipedia.org/wiki/%E4%B8%AD%E6%97%A5%E9%9F%93%E7%B5%B1%E4%B8%80%E8%A1%A8%E6%84%8F%E6%96%87%E5%AD%97%E6%93%B4%E5%B1%95%E5%8D%80A)A区包含有6,592个汉字，位置在U+3400—U+4DBF。这6千多个汉字分别从以下字典或字集中获取：

| **类别** | **来源代码** | **名称** | **字数** |
| --- | --- | --- | --- |
| 中国大陆
国标源（G） | G\_KX | 《[康熙字典](https://zh.wikipedia.org/wiki/%E5%BA%B7%E7%86%99%E5%AD%97%E5%85%B8)》 | 5357字（独有1892字） |
| G\_HZ | 《[汉语大字典](https://zh.wikipedia.org/wiki/%E6%BC%A2%E8%AA%9E%E5%A4%A7%E5%AD%97%E5%85%B8)》 | 5888字（独有339字） |
| G3 | GB 7589-87繁体版本 | 2391字 |
| G5 | GB 7590-87繁体版本 | 1226字 |
| G7 | 现代汉语通用字表 | 120字 |
| GS | [新加坡汉字](https://zh.wikipedia.org/wiki/%E6%96%B0%E5%8A%A0%E5%9D%A1%E6%BC%A2%E5%AD%97) | 226字 |
| 台湾源（T） | T3 | CNS 11643-1992第三字面（原本为CNS 11643-1986第十四字面）新加入字符 | 2178字 |
| T4 | CNS 11643-1992第四字面 | 2917字 |
| T5 | CNS 11643-1992第五字面 | 395字 |
| T6 | CNS 11643-1992第六字面 | 197字 |
| T7 | CNS 11643-1992第七字面 | 133字 |
| TF | CNS 11643-1992第十五字面 | 86字 |
| 日本源（J） | JA | 日本信息技术零售商统一当代表意文字（1993） | 574字 |
| 韩国源（K） | K2 | [PKS C 5700](https://zh.wikipedia.org/w/index.php?title=PKS_5700&action=edit&redlink=1)-1:1994 |
 |
| K3 | PKS C 5700-2:1994 | 1834字 |
| 越南源（V） | V0 | [TCVN 5773](https://zh.wikipedia.org/w/index.php?title=TCVN_5773&action=edit&redlink=1):1993 | 138字 |
| V1 | [TCVN 6056](https://zh.wikipedia.org/w/index.php?title=TCVN_6056&action=edit&redlink=1):1995 |
 |

###### 扩展B区[[编辑](https://zh.wikipedia.org/w/index.php?title=%E4%B8%AD%E6%97%A5%E9%9F%93%E7%B5%B1%E4%B8%80%E8%A1%A8%E6%84%8F%E6%96%87%E5%AD%97&action=edit&section=7)]

[扩展](https://zh.wikipedia.org/wiki/%E4%B8%AD%E6%97%A5%E9%9F%93%E7%B5%B1%E4%B8%80%E8%A1%A8%E6%84%8F%E6%96%87%E5%AD%97%E6%93%B4%E5%B1%95%E5%8D%80B)B区包含有42,717个汉字，位置在U+20000—U+2A6DD。根据[IRG N777](http://www.cse.cuhk.edu.hk/~irg/irg/N777_CJK_B_CoverNote.pdf)号文件（[页面存档备份](https://web.archive.org/web/20060925091454/http:/www.cse.cuhk.edu.hk/~irg/irg/N777_CJK_B_CoverNote.pdf)，存于[互联网档案馆](https://zh.wikipedia.org/wiki/%E4%BA%92%E8%81%94%E7%BD%91%E6%A1%A3%E6%A1%88%E9%A6%86)），这四万多个汉字分别从以下字典或字集中获取：

| **类别** | **来源代码** | **名称** | **字数** |
| --- | --- | --- | --- |
| 中国大陆
国标源（G） | G\_KX | 《康熙字典》 | 18486字（包括一个在补遗篇中出现的汉字） |
| G\_HZ | 《汉语大字典》 | 28914字 |
| G\_CY | 《[辞源](https://zh.wikipedia.org/wiki/%E8%BE%AD%E6%BA%90)》 | 66字 |
| G\_CH | 《[辞海](https://zh.wikipedia.org/wiki/%E8%BE%AD%E6%B5%B7)》 | 247字 |
| G\_HC | 《[汉语大词典](https://zh.wikipedia.org/wiki/%E6%BC%A2%E8%AA%9E%E5%A4%A7%E8%A9%9E%E5%85%B8)》 | 553字 |
| G\_BK | 《[中国大百科全书](https://zh.wikipedia.org/wiki/%E4%B8%AD%E5%9C%8B%E5%A4%A7%E7%99%BE%E7%A7%91%E5%85%A8%E6%9B%B8)》 | 86字 |
| G\_FZ | [北大方正](https://zh.wikipedia.org/wiki/%E6%96%B9%E6%AD%A3%E9%9B%86%E5%9B%A2%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8)[排版系统](https://zh.wikipedia.org/w/index.php?title=%E5%8C%97%E5%A4%A7%E6%96%B9%E6%AD%A3%E6%8E%92%E7%89%88%E7%B3%BB%E7%BB%9F&action=edit&redlink=1) | 65字 |
| G\_4K | 《[四库全书](https://zh.wikipedia.org/wiki/%E5%9B%9B%E5%BA%AB%E5%85%A8%E6%9B%B8)》 | 522字 |
| 香港源（H） | H | [香港增补字符集](https://zh.wikipedia.org/wiki/%E9%A6%99%E6%B8%AF%E5%A2%9E%E8%A3%9C%E5%AD%97%E7%AC%A6%E9%9B%86)（HKSCS） | 1081字 |
| 台湾源（T） | T4 | CNS 11643-1992第四字面 | 3408字 |
| T5 | CNS 11643-1992第五字面 | 8111字 |
| T6 | CNS 11643-1992第六字面 | 5934字 |
| T7 | CNS 11643-1992第七字面 | 6299字 |
| TF | CNS 11643-1992第十五字面 | 6401字 |
| 日本源（J） | J3 | JIS X 0213:2000, level 3 | 25字 |
| J3A | JIS X 0213:2004, level 3 | 1字 |
| J4 | JIS X 0213:2000, level 4 | 277字 |
| 韩国源（K） | K4 | PKS 5700-3:1998 | 166字 |
| 朝鲜源（KP） | KP0 | [KPS 9566-97](https://zh.wikipedia.org/wiki/KPS_9566) |
 |
| KP1 | [KPS 10721-2000](https://zh.wikipedia.org/w/index.php?title=KPS_10721&action=edit&redlink=1) | 5766字 |
| 越南源（V） | V2 | VHN 01:1998 | 2290字 |
| V3 | VHN 02:1998 | 425字 |

这些汉字中重复的汉字有不少，所以经过整理之后，实际总数只有42,711个汉字。

另外，在U+2F800—U+2FA1D的位置，放了542个来自台湾的[兼容汉字](https://zh.wikipedia.org/w/index.php?title=%E5%85%BC%E5%AE%B9%E6%BC%A2%E5%AD%97&action=edit&redlink=1)。

##### GB 2312 （1980年，6763个汉字）

GB/T 2312标准共收录6763个[汉字](https://zh.wikipedia.org/wiki/%E6%B1%89%E5%AD%97)，其中[一级汉字](https://zh.wikipedia.org/wiki/%E5%B8%B8%E7%94%A8%E5%AD%97)3755个，[二级汉字](https://zh.wikipedia.org/wiki/%E6%AC%A1%E5%B8%B8%E7%94%A8%E5%AD%97)3008个；同时收录了包括[拉丁字母](https://zh.wikipedia.org/wiki/%E6%8B%89%E4%B8%81%E5%AD%97%E6%AF%8D)、[希腊字母](https://zh.wikipedia.org/wiki/%E5%B8%8C%E8%85%8A%E5%AD%97%E6%AF%8D)、[日文](https://zh.wikipedia.org/wiki/%E6%97%A5%E8%AF%AD)[平假名](https://zh.wikipedia.org/wiki/%E5%B9%B3%E5%81%87%E5%90%8D)及[片假名](https://zh.wikipedia.org/wiki/%E7%89%87%E5%81%87%E5%90%8D)字母、[俄语](https://zh.wikipedia.org/wiki/%E4%BF%84%E8%AF%AD)[西里尔字母](https://zh.wikipedia.org/wiki/%E6%96%AF%E6%8B%89%E5%A4%AB%E5%AD%97%E6%AF%8D)在内的682个字符。

GB/T 2312的出现，基本满足了汉字的计算机处理需要，它所收录的汉字已经覆盖中国大陆99.75%的使用频率。但对于[人名](https://zh.wikipedia.org/wiki/%E4%BA%BA%E5%90%8D)、[古汉语](https://zh.wikipedia.org/wiki/%E5%8F%A4%E6%B1%89%E8%AF%AD)等方面出现的[罕用字](https://zh.wikipedia.org/wiki/%E7%BD%95%E7%94%A8%E5%AD%97)和[繁体字](https://zh.wikipedia.org/wiki/%E7%B9%81%E9%AB%94%E5%AD%97)，GB/T 2312不能处理，因此后来[GBK](https://zh.wikipedia.org/wiki/GBK)及[GB 18030](https://zh.wikipedia.org/wiki/GB_18030)汉字字符集相继出现以解决这些问题。

##### GBK (1993)

[https://en.wikipedia.org/wiki/GBK\_(character\_encoding)](https://en.wikipedia.org/wiki/GBK_(character_encoding))

_GB_ abbreviates [Guojia Biaozhun](https://en.wikipedia.org/wiki/Guobiao), which means _national standard_ in Chinese, while _K_ stands for _Extension_ (扩展 _kuòzhǎn_). GBK not only extended the old standard GB2312 with Traditional Chinese characters, but also with Chinese characters that were simplified after the establishment of GB2312 in 1981. With the arrival of GBK, certain names with characters formerly unrepresentable, like the 镕 (_róng_) character in former Chinese Premier [Zhu Rongji's](https://en.wikipedia.org/wiki/Zhu_Rongji) name, are now representable.

1993年，[Unicode](https://zh.wikipedia.org/wiki/Unicode) 1.1版本推出，收录[中国大陆](https://zh.wikipedia.org/wiki/%E4%B8%AD%E5%9B%BD%E5%A4%A7%E9%99%86)、[台湾](https://zh.wikipedia.org/wiki/%E5%8F%B0%E6%B9%BE)、[日本](https://zh.wikipedia.org/wiki/%E6%97%A5%E6%9C%AC)及[韩国](https://zh.wikipedia.org/wiki/%E9%9F%A9%E5%9B%BD)通用[字符集](https://zh.wikipedia.org/wiki/%E5%AD%97%E7%AC%A6%E9%9B%86)的[汉字](https://zh.wikipedia.org/wiki/%E6%B1%89%E5%AD%97)，总共有20,902个。中国大陆订定了等同于Unicode 1.1版本的"[GB 13000.1-93](https://zh.wikipedia.org/wiki/GB_13000)""信息技术通用多八位编码字符集（UCS）第一部分：体系结构与基本多文种平面"。

由于[GB 2312-80](https://zh.wikipedia.org/wiki/GB_2312)只收录6763个汉字，有不少汉字，如部分在GB 2312-80推出以后才简化的汉字（如"啰"），部分人名用字（如中国前总理[朱镕基](https://zh.wikipedia.org/wiki/%E6%9C%B1%E9%95%95%E5%9F%BA)的"镕"字），台湾及香港使用的[繁体字](https://zh.wikipedia.org/wiki/%E7%B9%81%E4%BD%93%E4%B8%AD%E6%96%87)，[日语](https://zh.wikipedia.org/wiki/%E6%97%A5%E8%AF%AD)及[朝鲜语](https://zh.wikipedia.org/wiki/%E9%9F%93%E8%AA%9E)汉字等，并未有收录在内。于是厂商微软利用GB 2312-80未使用的编码空间，收录GB 13000.1-93全部字符制定了GBK编码。

根据[微软](https://zh.wikipedia.org/wiki/%E5%BE%AE%E8%BD%AF)资料，GBK是对GB2312-80的扩展，也就是[_CP936_](https://zh.wikipedia.org/wiki/CP936)_字码表（ __Code Page 936__ ）_的扩展（之前CP936和GB 2312-80一模一樣），最早实现于[Windows 95](https://zh.wikipedia.org/wiki/Windows_95)简体中文版。虽然GBK收录[GB 13000.1-93](https://zh.wikipedia.org/wiki/GB_13000)的全部字符，但GBK是一种编码方式并向下兼容GB2312；而GB 13000.1-93等同于Unicode 1.1是一种[字符集](https://zh.wikipedia.org/wiki/%E5%AD%97%E7%AC%A6%E9%9B%86)，它的几种编码方式如[UTF8](https://zh.wikipedia.org/wiki/UTF8)、[UTF16LE](https://zh.wikipedia.org/w/index.php?title=UTF16&action=edit&redlink=1)等，与GBK完全不兼容。

##### GB 18030 （2005年，70,244个汉字）字符集和编码方式

[https://en.wikipedia.org/wiki/GB\_18030](https://en.wikipedia.org/wiki/GB_18030)

**GB 18030** ，全称《信息技术 中文编码字符集》，是[中华人民共和国](https://zh.wikipedia.org/wiki/%E4%B8%AD%E5%8D%8E%E4%BA%BA%E6%B0%91%E5%85%B1%E5%92%8C%E5%9B%BD)[国家标准](https://zh.wikipedia.org/wiki/%E4%B8%AD%E5%8D%8E%E4%BA%BA%E6%B0%91%E5%85%B1%E5%92%8C%E5%9B%BD%E5%9B%BD%E5%AE%B6%E6%A0%87%E5%87%86)所规定的变长多字节字符集。其对[GB 2312-1980](https://zh.wikipedia.org/wiki/GB_2312)完全[向后兼容](https://zh.wikipedia.org/wiki/%E5%90%91%E5%90%8E%E5%85%BC%E5%AE%B9)，与[GBK](https://zh.wikipedia.org/wiki/GBK)基本[向后兼容](https://zh.wikipedia.org/wiki/%E5%90%91%E5%90%8E%E5%85%BC%E5%AE%B9)，并支持[Unicode](https://zh.wikipedia.org/wiki/Unicode)（[GB 13000](https://zh.wikipedia.org/wiki/GB_13000)）的所有码位。GB 18030 **共收录汉字**** 70,244 ****个**

| **Preceded by** | [GBK](https://en.wikipedia.org/wiki/GBK_(character_encoding)), [GB2312](https://en.wikipedia.org/wiki/GB_2312) |
| --- | --- |

![](2021-Linux&Widows%20OS%20commands,%20app_skills_handy_shortcuts_html_1f8835cec4d8ce35.png)

**GB 18030**  is a [Chinese government standard](https://en.wikipedia.org/wiki/Guobiao_standards), described as _Information Technology — Chinese coded character set_ and defines the required language and character support necessary for software in [China](https://en.wikipedia.org/wiki/China).  **GB18030**  is the registered Internet name for the official [character set](https://en.wikipedia.org/wiki/Character_set) of the [People's Republic of China](https://en.wikipedia.org/wiki/People%27s_Republic_of_China) (PRC) superseding [GB2312](https://en.wikipedia.org/wiki/GB_2312).[[1]](https://en.wikipedia.org/wiki/GB_18030#cite_note-IANA-2) As a [Unicode Transformation Format](https://en.wikipedia.org/wiki/Unicode_Transformation_Format)[[a]](https://en.wikipedia.org/wiki/GB_18030#cite_note-3) (i.e. an encoding of all [Unicode](https://en.wikipedia.org/wiki/Unicode) code points), GB18030 supports both [simplified](https://en.wikipedia.org/wiki/Simplified_chinese) and [traditional](https://en.wikipedia.org/wiki/Traditional_chinese) Chinese characters. It is also compatible with legacy encodings including GB2312, [CP936](https://en.wikipedia.org/wiki/Code_page_1386),[[b]](https://en.wikipedia.org/wiki/GB_18030#cite_note-4) and [GBK](https://en.wikipedia.org/wiki/GBK_(character_encoding)) 1.0.

In addition to the "GB18030 character encoding", this standard contains requirements about which scripts must be supported, font support, etc.

all Unicode characters can be encoded in GB18030, but they will be encoded with different byte sequences than would be generated with UTF-8 or UTF-16.

# **Data processing**

# Power Query

[https://docs.microsoft.com/en-us/power-query/power-query-what-is-power-query](https://docs.microsoft.com/en-us/power-query/power-query-what-is-power-query) Saturday, 26 June 2021

# Power BI

[https://docs.microsoft.com/en-us/power-bi/](https://docs.microsoft.com/en-us/power-bi/)

5

DongHui Zhai
