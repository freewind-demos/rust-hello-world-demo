# Rust Hello World Demo

## 简介

展示 Rust 最基础的 Hello World 程序。

## 基本原理

Rust 是一种系统级编程语言，以安全性、并发性和性能著称。

## 启动和使用

### 环境要求
- Rust 1.56+ (建议使用最新稳定版)
- Cargo (Rust 包管理器)

### 运行

```bash
cargo run
```

输出：
```
Hello, world!
你好，Rust！
欢迎使用 Rust!
调试信息: [1, 2, 3]
```

## 教程

### println! 宏

`println!` 是 Rust 中最常用的输出宏：

```rust
// 基本输出
println!("Hello, world!");

// 带占位符
let name = "Rust";
println!("欢迎使用 {}!", name);

// 调试输出（适合开发调试）
let numbers = vec![1, 2, 3];
println!("调试信息: {:?}", numbers);
```

### 占位符

- `{}` - 普通格式化
- `{:?}` - 调试格式化
- `{:#?}` - 美化调试格式化
