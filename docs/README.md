# USTC 编译原理和技术 2025

## 课程信息

??? info "课程简介"

    本课程旨在介绍编译器构造的一般原理、基本设计方法和主要实现技术，强调形式描述方法和自动生成技术，以及对编译原理和技术的宏观理解，主要包括以下理论内容:

    - 形式语言和自动机理论
    - 语法制导的定义和属性文法
    - 类型系统
    - 语言运行时
    - 程序分析和优化

### 授课信息

- 时间：周一 1、2 节，周三 3、4 节 (1~15 周)
- 地点：GT-B203
- 主讲教师：张昱 [:material-email:](mailto:yuzhang@ustc.edu.cn) [:simple-gitlab:](https://git.lug.ustc.edu.cn/yuzhang)
- 助教：
  - 丁伯尧 [:material-email:](mailto:via@mail.ustc.edu.cn) [:simple-gitlab:](https://git.lug.ustc.edu.cn/dby)
  - 刘硕 [:material-email:](mailto:zkdliushuo@mail.ustc.edu.cn) [:simple-gitlab:](https://git.lug.ustc.edu.cn/liushuo_ustc)
  - 石磊鑫 [:material-email:](mailto:slx_ustc@mail.ustc.edu.cn) [:simple-gitlab:](https://git.lug.ustc.edu.cn/shilx)
  - 杨哲骏 [:material-email:](mailto:zjyang@mail.ustc.edu.cn) [:simple-gitlab:](https://git.lug.ustc.edu.cn/yzj)
- 场外支持：
  - 李清伟 [:material-email:](mailto:lqw332664203@mail.ustc.edu.cn) [:simple-gitlab:](https://git.lug.ustc.edu.cn/Lslightly)
- QQ 群：1016437528
- Issue 讨论区：<https://git.lug.ustc.edu.cn/compiler/course/-/issues>
- 实验框架：待定

## 作业

| 作业编号 | 作业布置日期 | 作业题号码                                                      | 交作业时间         | 作业提交方式                                                                                 |
| -------- | ------------ | --------------------------------------------------------------- | ------------------ | -------------------------------------------------------------------------------------------- |
| 1        | 9 月 10 日   | 习题 2.7（a）（b）（c）、习题 2.3（b）（c）、习题 2.4（a）（c） | 9 月 17 日（周三） | [头歌作业一](https://educoder.ustc.edu.cn/classrooms/212/common_homework/494/detail)在线提交 |
| 2        | 9 月 17 日   | 习题 2.7 习题 2.16                                              | 9 月 24 日（周三） | [头歌作业二](https://educoder.ustc.edu.cn/classrooms/212/common_homework/498/detail)在线提交 |

## 课程资源

### 教学课件

<table style="width:100%; border-collapse: collapse;" border="1">
  <thead>
    <tr>
      <th style="padding: 8px; text-align: left;">课次</th>
      <th style="padding: 8px; text-align: left;">日期</th>
      <th style="padding: 8px; text-align: left;">课程和课件</th>
      <th style="padding: 8px; text-align: left;">阅读材料</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="padding: 8px;">#1</td>
      <td style="padding: 8px;">Mon, Sep 7</td>
      <td style="padding: 8px;"><strong>Course Introduction</strong><br><a href="./slides/01-intro.pdf">Introduction</a></td>
      <td style="padding: 8px;">Book Chapter 1</td>
    </tr>
    <tr>
      <td style="padding: 8px;">#2</td>
      <td style="padding: 8px;">Wed, Sep 9</td>
      <td style="padding: 8px;" rowspan="2"><strong>Lexical analysis</strong>: <a href="./slides/02-lexicalAnalysis-Part1.pdf">Part I</a>, <a href="./slides/02-lexicalAnalysis-Part2.pdf">II</a>, <a href="./slides/02-lexicalAnalysis-Ext.pdf">Extension</a></td>
      <td style="padding: 8px;" rowspan="2">Book Chapter 2<br><a href="https://www.antlr.org/">ANLTR Book</a><br><a href="https://github.com/westes/flex/releases">Flex</a></td>
    </tr>
    <tr>
      <td style="padding: 8px;">#3</td>
      <td style="padding: 8px;">Mon, Sep 15</td>
    </tr>
    <tr>
      <td style="padding: 8px;">#4</td>
      <td style="padding: 8px;">Wed, Sep 22</td>
      <td style="padding: 8px;" rowspan="5"><strong>Syntax analysis</strong>: Part I</td>
      <td style="padding: 8px;" rowspan="5">Book Ch 3.1-3.6<br><a href="https://www.antlr.org/">ANLTR Book</a><br><a href="http://www.gnu.org/software/bison/">Bison</a></td>
    </tr>
    <!-- <tr>
      <td style="padding: 8px;">#5</td>
      <td style="padding: 8px;">Mon, Sep 18</td>
    </tr>
    <tr>
      <td style="padding: 8px;">#6</td>
      <td style="padding: 8px;">Wed, Sep 20</td>
    </tr>
    <tr>
      <td style="padding: 8px;">#7</td>
      <td style="padding: 8px;">Mon, Sep 25</td>
    </tr>
    <tr>
      <td style="padding: 8px;">#8</td>
      <td style="padding: 8px;">Sat, Oct 7<br>Mon, Oct 9</td>
    </tr>
    <tr>
      <td style="padding: 8px;">#9(TA1)</td>
      <td style="padding: 8px;">Wed, Sep 27</td>
      <td style="padding: 8px;"><strong>TA's class: homework, practice</strong></td>
      <td style="padding: 8px;"></td>
    </tr>
    <tr>
      <td style="padding: 8px;">#10</td>
      <td style="padding: 8px;">Wed, Oct 11</td>
      <td style="padding: 8px;" rowspan="2"><strong>Syntax-directed translation</strong>: <a href="#">Part I</a>, <a href="#">Part II</a></td>
      <td style="padding: 8px;" rowspan="2">Book Ch 4.1-4.8,<br><a href="#">ANLTR</a><br><a href="#">Bison</a></td>
    </tr>
    <tr>
      <td style="padding: 8px;">#11</td>
      <td style="padding: 8px;">Mon, Oct 16<br>Wed, Oct 18</td>
    </tr>
    <tr>
      <td style="padding: 8px;">#12(TA2)</td>
      <td style="padding: 8px;">Fri, Oct 27</td>
      <td style="padding: 8px;"><strong>TA's class 2</strong></td>
      <td style="padding: 8px;"></td>
    </tr>
    <tr style="background-color:#f2f2f2;">
      <td style="padding: 8px;">MidEx</td>
      <td style="padding: 8px;">Mon, Oct 30</td>
      <td style="padding: 8px;"><strong>Midterm Exam (1-4, Ch1-Ch4; 7:30-9:10; OT-2010)</strong></td>
      <td style="padding: 8px;"></td>
    </tr>
    <tr>
      <td style="padding: 8px;">#13</td>
      <td style="padding: 8px;">Mon, Oct 23</td>
      <td style="padding: 8px;"></td>
      <td style="padding: 8px;">Book Chapter 5</td>
    </tr>
    <tr>
      <td style="padding: 8px;">#14</td>
      <td style="padding: 8px;">Wed, Oct 25</td>
      <td style="padding: 8px;"><strong>Type checking</strong></td>
      <td style="padding: 8px;">Research Practice: <a href="#">P-Star</a></td>
    </tr>
    <tr>
      <td style="padding: 8px;">#15</td>
      <td style="padding: 8px;">Wed, Nov 1</td>
      <td style="padding: 8px;"><strong>Runtime storage organization</strong>: <a href="#">Part I</a>, <a href="#">Part II</a>, <a href="#">Part III</a><br><a href="#">Mid Examples</a>
        <ul style="margin: 5px 0 5px 20px; padding: 0;">
          <li>Storage layout for local names: scope, lifetime, activation, record, alignment</li>
          <li>Stack allocation of space: activation tree, calling/return sequences, variable-length data on the stack, dangling pointer</li>
          <li>Access to non-local data on the stack: access without nested procedures; access with nested procedures - nesting depth; access links for static scope; display</li>
          <li>Parameter transfer: call-by-value/reference/name</li>
          <li>Heap management: memory manager; memory hierarchy; locality; virtual/ deallocation requests</li>
        </ul>
      </td>
      <td style="padding: 8px;"></td>
    </tr>
    <tr>
      <td style="padding: 8px;">#16</td>
      <td style="padding: 8px;">Sat, Nov 4</td>
      <td style="padding: 8px;"></td>
      <td style="padding: 8px;" rowspan="3">Book Chapter 6<br><a href="#">Stack-overflow</a></td>
    </tr>
    <tr>
      <td style="padding: 8px;">#17</td>
      <td style="padding: 8px;">Wed, Nov 8</td>
      <td style="padding: 8px;"></td>
    </tr>
    <tr>
      <td style="padding: 8px;">#18</td>
      <td style="padding: 8px;">Mon, Nov 13</td>
      <td style="padding: 8px;"></td>
    </tr>
    <tr>
      <td style="padding: 8px;">#19</td>
      <td style="padding: 8px;">Wed, Nov 15</td>
      <td style="padding: 8px;" rowspan="3"><strong>Intermediate Representation and Generation</strong>: <a href="#">Part I</a>, <a href="#">Part II</a><br>
        <ul style="margin: 5px 0 5px 20px; padding: 0;">
          <li><a href="#">Def-Use/ Intermediate Representation and Generation</a></li>
          <li><a href="#">Compiler for Machine Learning</a></li>
        </ul>
      </td>
      <td style="padding: 8px;" rowspan="3">Book Chapter 7, 8.5<br><a href="#">LLVM IR</a><br><a href="#">LLVM Programmer's Manual</a><br><a href="#">and LLVM Tutorial</a></td>
    </tr>
    <tr>
      <td style="padding: 8px;">#20</td>
      <td style="padding: 8px;">Mon, Nov 20</td>
    </tr>
    <tr>
      <td style="padding: 8px;">#21</td>
      <td style="padding: 8px;">Wed, Nov 22</td>
    </tr>
    <tr>
      <td style="padding: 8px;">#22</td>
      <td style="padding: 8px;">Mon, Nov 27</td>
      <td style="padding: 8px;"><strong>Code Generation</strong></td>
      <td style="padding: 8px;">Book Chapter 9, <a href="#">高级话题：动态/即时编译/虚拟机/安全</a></td>
    </tr>
    <tr>
      <td style="padding: 8px;" rowspan="2">#23</td>
      <td style="padding: 8px;">Wed, Nov 29</td>
      <td style="padding: 8px;" rowspan="2"><strong>Compiler and Runtime System</strong></td>
      <td style="padding: 8px;">Book Chapter 10</td>
    </tr>
    <tr>
      <td style="padding: 8px;">Mon, Dec 4</td>
      <td style="padding: 8px;">Book Chapter 8, 9, 6</td>
    </tr>
    <tr>
      <td style="padding: 8px;" rowspan="2">#25</td>
      <td style="padding: 8px;">Mon, Dec 4</td>
      <td style="padding: 8px;" rowspan="2"><strong>Optimization</strong></td>
      <td style="padding: 8px;" rowspan="2">Book Chapter 9</td>
    </tr>
    <tr>
      <td style="padding: 8px;">Wed, Dec 6</td>
    </tr>
    <tr style="background-color:#f2f2f2;">
      <td style="padding: 8px;">Final</td>
      <td style="padding: 8px;">-</td>
      <td style="padding: 8px;"><strong>Final Exam</strong> - </td>
      <td style="padding: 8px;"></td>
    </tr> -->
  </tbody>
</table>

### 在线资源

**Educoder（头歌）平台资源清单—在线实验**

自 2019 年起在 Educoder 平台部署系列编译实验并不断更新，实际部署的实践项目数超过 30 个。截止目前，形成的最新的贯穿编译系统全流程的系列实验及其链接如下表，共计 12 个，这 12 个实验在超星平台均有对应的实践指导授课视频。

| 类别              | 实验名称                                         | educoder                                                              | 校内头歌                                                                 |
| :---------------- | :----------------------------------------------- | :-------------------------------------------------------------------- | :----------------------------------------------------------------------- |
| 工具              | 1 GCC 与 Clang 工具链使用                        | [Educoder Link](https://www.educoder.net/shixuns/whaq6kfm/challenges) | [校内头歌链接](https://educoder.ustc.edu.cn/shixuns/whaq6kfm/challenges) |
| C++ 语言 高级特性 | 2 理解和使用 C++ 运行时类型信息 (RTTI)           | [Educoder Link](https://www.educoder.net/shixuns/3y29irkn/challenges) | [校内头歌链接](https://educoder.ustc.edu.cn/shixuns/qwt9oc5s/challenges) |
| C++ 语言高级特性  | 3 理解和使用 C++ 的智能指针                      | [Educoder Link](https://www.educoder.net/shixuns/fqbzhwnp/challenges) | [校内头歌链接](https://educoder.ustc.edu.cn/shixuns/fqbzhwnp/challenges) |
| 词法分析          | 4 词法分析器的构造                               | [Educoder Link](https://www.educoder.net/shixuns/ecnb34g5/challenges) | [校内头歌链接](https://educoder.ustc.edu.cn/shixuns/9v3ug4em/challenges) |
| 解析器            | 5 ANTLR4 的基础应用 - 为正规式生成解析树         | [Educoder Link](https://www.educoder.net/shixuns/w8sftvkr/challenges) | [校内头歌链接](https://educoder.ustc.edu.cn/shixuns/gbostje6/challenges) |
| 解析器            | 6 ANTLR4 的进阶应用 - 为 C1 语言构造解析器       | [Educoder Link](https://www.educoder.net/shixuns/qix6mfn3/challenges) | [校内头歌链接](https://educoder.ustc.edu.cn/shixuns/576tkvz3/challenges) |
| 解析器            | 7 使用 Flex 和 Bison 构建 SysYF 词法和语法分析器 | [Educoder Link](https://www.educoder.net/shixuns/o7tu4wyv/challenges) | [校内头歌链接](https://educoder.ustc.edu.cn/shixuns/o7tu4wyv/challenges) |
| 语义分析          | 8 构建 SysYF 语义检查器                          | [Educoder Link](https://www.educoder.net/shixuns/npa8mlhe/challenges) | [校内头歌链接](https://educoder.ustc.edu.cn/shixuns/npa8mlhe/challenges) |
| 中间代码 生成     | 9 为 SysYF 语言生成 LLVM IR 中间代码             | [Educoder Link](https://www.educoder.net/shixuns/tlrqaeiu/challenges) | [校内头歌链接](https://educoder.ustc.edu.cn/shixuns/t5fgvxfu/challenges) |
| 代码生成          | 10 运行时空间管理与代码生成                      | [Educoder Link](https://www.educoder.net/shixuns/z65kvtwf/challenges) | [校内头歌链接](https://educoder.ustc.edu.cn/shixuns/24ufsnih/challenges) |
| 代码优化          | 11 SysYF 语言的 LLVM IR 代码优化                 | [Educoder Link](https://www.educoder.net/shixuns/2z5fvj7y/challenges) | [校内头歌链接](https://educoder.ustc.edu.cn/shixuns/o8m76k5t/challenges) |
| 代码优化          | 12 LLVM 驱动程序及程序分析                       | [Educoder Link](https://www.educoder.net/shixuns/7j5wirx9/challenges) | [校内头歌链接](https://educoder.ustc.edu.cn/shixuns/lzexhak4/challenges) |

**Educoder（头歌）平台资源清单--视频**

在 Educoder（头歌）平台建设的《编译原理应用与实践》实践课程中，收集了项目团队在全国“程序语言与编译系统课程研讨会”的讲座视频，以及个别在中国科大编译课堂的授课视频。

| 视频名称                          | 视频 B 站链接                                                                                |
| --------------------------------- | -------------------------------------------------------------------------------------------- |
| 编译实验工具简介                  | [https://www.bilibili.com/video/BV1zU4y1E7Uy/](https://www.bilibili.com/video/BV1zU4y1E7Uy/) |
| 语法分析技术的介绍                | [https://www.bilibili.com/video/BV1fy4y1V7os/](https://www.bilibili.com/video/BV1fy4y1V7os/) |
| 基于 Flex 和 Bison 的编译实验讲解 | [https://www.bilibili.com/video/BV17b4y1S7cU/](https://www.bilibili.com/video/BV17b4y1S7cU/) |
| Clang AST 及其编程接口讲解        | [https://www.bilibili.com/video/BV1zq4y1S75J/](https://www.bilibili.com/video/BV1zq4y1S75J/) |
| ANTLR 解析原理                    | [https://www.bilibili.com/video/BV1AR4y1o78H/](https://www.bilibili.com/video/BV1AR4y1o78H/) |
| LLVM IR 介绍                      | [https://www.bilibili.com/video/BV1P3411B7YB/](https://www.bilibili.com/video/BV1P3411B7YB/) |
| 从 AST 语法树生成 LLVMIR 的讲解   | [https://www.bilibili.com/video/BV1ab4y1S7K3/](https://www.bilibili.com/video/BV1ab4y1S7K3/) |
| LLVM 驱动程序框架的讲解           | [https://www.bilibili.com/video/BV1sv411N76s/](https://www.bilibili.com/video/BV1sv411N76s/) |
| 循环与优化讲解                    | [https://www.bilibili.com/video/BV1E341167vm/](https://www.bilibili.com/video/BV1E341167vm/) |
| 继承属性的自下而上计算            | [https://www.bilibili.com/video/BV1QG4y187P7/](https://www.bilibili.com/video/BV1QG4y187P7/) |
| 类型检查 -1                       | [https://www.bilibili.com/video/BV1RR4y1Q7Jp/](https://www.bilibili.com/video/BV1RR4y1Q7Jp/) |
| 类型检查 -2                       | [https://www.bilibili.com/video/BVlee4y127L8/](https://www.bilibili.com/video/BV1ee4y127L8/) |

**教材和参考书**

- 陈意云、张昱，[编译原理（第 4 版）](http://staff.ustc.edu.cn/~yuzhang/compiler/book_compiler_hep_v4.pdf)
- 李诚、徐伟，现代编译器设计与实现（实验讲义版本，高等教育出版社待出版，2023）。[教材资源及实验框架](https://ustc-compiler-principles.github.io/textbook/)
- A. V. Aho, M. S. Lam, R. Sethi, and J. D. Ullman 著，赵建华等译，编译原理，机械工业出版社，2017

**感谢所有作者的工作和同学的参与。**

**欢迎为课程主页提交 Issue 和 Pull Request！**
