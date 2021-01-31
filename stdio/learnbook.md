<!--
 * @Author: your name
 * @Date: 2021-01-30 17:23:28
 * @LastEditTime: 2021-01-30 17:35:51
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \apue.3e\stdio\learnbook.md
-->
# 标准IO库
标准IO库处理很多细节，如缓冲区分配、以优化的块长度执行IO等，用户不必担心如何选择使用正确的快长度。

当标准IO库打开或创建一个文件时，我们已使一个流与一个文件相关联。