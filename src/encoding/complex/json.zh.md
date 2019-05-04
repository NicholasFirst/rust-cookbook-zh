## 序列化和反序列化非结构化 JSON

[![serde-json-badge]][serde-json] [![cat-encoding-badge]][cat-encoding]

这个[`serde_json`]箱子提供[`from_str`]要分析的函数`&str`JSON 的。

非结构化 JSON 可以解析为通用的[`serde_json::Value`]能够表示任何有效 JSON 数据的类型。

下面的示例显示了`&str`正在解析的 JSON。使用[`json!`]宏。

```rust
#[macro_use]
extern crate serde_json;

use serde_json::{Value, Error};

fn main() -> Result<(), Error> {
    let j = r#"{
                 "userid": 103609,
                 "verified": true,
                 "access_privileges": [
                   "user",
                   "admin"
                 ]
               }"#;

    let parsed: Value = serde_json::from_str(j)?;

    let expected = json!({
        "userid": 103609,
        "verified": true,
        "access_privileges": [
            "user",
            "admin"
        ]
    });

    assert_eq!(parsed, expected);

    Ok(())
}
```

[`from_str`]: https://docs.serde.rs/serde_json/fn.from_str.html
[`json!`]: https://docs.serde.rs/serde_json/macro.json.html
[`serde_json`]: https://docs.serde.rs/serde_json/
[`serde_json::value`]: https://docs.serde.rs/serde_json/enum.Value.html
