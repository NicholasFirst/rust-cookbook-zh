
## 矩阵乘法

[![ndarray-badge]][ndarray] [![cat-science-badge]][cat-science]

创建两个矩阵[`ndarray::arr2`]并对它们进行矩阵乘法运算.[`ndarray::ArrayBase::dot`].

```rust
extern crate ndarray;

use ndarray::arr2;

fn main() {
    let a = arr2(&[[1, 2, 3],
                   [4, 5, 6]]);

    let b = arr2(&[[6, 3],
                   [5, 2],
                   [4, 1]]);

    println!("{}", a.dot(&b));
}
```

[`ndarray::arr2`]: https://docs.rs/ndarray/*/ndarray/fn.arr2.html

[`ndarray::arraybase::dot`]: https://docs.rs/ndarray/*/ndarray/struct.ArrayBase.html#method.dot-1
