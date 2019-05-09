## 将调试消息，记录到控制台

[![log-badge]][log] [![env_logger-badge]][env_logger] [![cat-debugging-badge]][cat-debugging]

这个`log`箱子提供记录工具。这个`env_logger`箱子能通过环境变量，配置日志记录。这个[`debug!`]宏的工作，与其他[`std::fmt`]格式化字符串一样。

```rust
#[macro_use]
extern crate log;
extern crate env_logger;

fn execute_query(query: &str) {
    debug!("Executing query: {}", query);
}

fn main() {
    env_logger::init();

    execute_query("DROP TABLE students");
}
```

运行此代码时，没有输出。默认情况下，日志级别为`error`，任何低于此的级别，都将被删除。

设置打印消息的`RUST_LOG`环境变量：

```
$ RUST_LOG=debug cargo run
```

货物(cargo)打印调试信息，然后在输出的最后一行，打印以下内容：

```
DEBUG:main: Executing query: DROP TABLE students
```

[`debug!`]: https://docs.rs/log/*/log/macro.debug.html
[`std::fmt`]: https://doc.rust-lang.org/std/fmt/
