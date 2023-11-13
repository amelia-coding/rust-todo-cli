# 使用rust开发项目示例

rust语言的特点

- 内存安全性高，自动管理内存

- 并发性强，提供并发编程的原语

- 高性能，与C++语言相当

- 易用性，语法和结构简单

- 跨平台性，支持不同操作系统

## 使用rust开发一个todo cli项目

1. cargo init todo-project

2. cargo run build  编译后执行二进制文件

3. targe/Cargo.lock 文件对依赖的版本进行管理

4. 文件的存储和读取

## 命令行使用

0. cargo build       

1. 写入一个todo： cargo run -- -m add -p HelloWorld

2. 列举某一天所在周的全部todo：cargo run -- -m lw   

3. -- 告诉 cargo 后面的参数是给我们的程序使用的，而不是给 cargo 自己使用，例如 -- 前的 run 就是给它用的。

## 使用rust读取文件

0. cargo run -- They sample.txt

1. 思想：关注点分离

学习

- [rust语言圣经] https://course.rs/
- [rust部署项目] https://space.bilibili.com/498917515


问题

- 出现 Blocking waiting for file lock on package cache ， 删除rm ~/.cargo/.package-cache