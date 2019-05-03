## 避免写入和读取同一文件

[![same_file-badge]][same_file] [![cat-filesystem-badge]][cat-filesystem]

使用[`same_file::Handle`]到一个文件，该文件可以测试是否与其他句柄相等。在这个例子中，要读取和写入的文件句柄被测试是否相等。

```rust,no_run
extern crate same_file;

use same_file::Handle;
use std::fs::File;
use std::io::{BufRead, BufReader, Error, ErrorKind};
use std::path::Path;

fn main() -> Result<(), Error> {
    let path_to_read = Path::new("new.txt");

    let stdout_handle = Handle::stdout()?;
    let handle = Handle::from_path(path_to_read)?;

    if stdout_handle == handle {
        return Err(Error::new(
            ErrorKind::Other,
            "You are reading and writing to the same file",
        ));
    } else {
        let file = File::open(&path_to_read)?;
        let file = BufReader::new(file);
        for (num, line) in file.lines().enumerate() {
            println!("{} : {}", num, line?.to_uppercase());
        }
    }

    Ok(())
}
```

```bash
cargo run
```

显示文件new.txt的内容。

```bash
cargo run >> ./new.txt
```

错误，因为两个文件相同。

[`same_file::handle`]: https://docs.rs/same-file/*/same_file/struct.Handle.html
