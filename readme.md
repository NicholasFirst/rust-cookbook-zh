# rust-lang-nursery/rust-cookbook [![translate-svg]][translate-list]

[translate-svg]: http://llever.com/translate.svg
[translate-list]: https://github.com/chinanf-boy/chinese-translate-list

「 这个*Rust Cookbook*是一个简单的[rust]生态系统的 crate 包集合, 展示完成常见编程任务的良好实践的示例.」

[中文](./readme.zh.md) | [english](https://github.com/rust-lang-nursery/rust-cookbook)

---

## 校对 ✅

<!-- doc-templite START generated -->
<!-- repo = 'rust-lang-nursery/rust-cookbook' -->
<!-- commit = 'cb949b04c036c8cc0f864697590d33ca2aaf349f' -->
<!-- time = '2019-04-16' -->
翻译的原文 | 与日期 | 最新更新 | 更多
---|---|---|---
[commit] | ⏰ 2019-04-16 | ![last] | [中文翻译][translate-list]

[last]: https://img.shields.io/github/last-commit/rust-lang-nursery/rust-cookbook.svg
[commit]: https://github.com/rust-lang-nursery/rust-cookbook/tree/cb949b04c036c8cc0f864697590d33ca2aaf349f

<!-- doc-templite END generated -->

- [x] [readme]
- [x] [src/SUMMARY.md](src/SUMMARY.md)

- [x] [目录表](/src/intro.zh.md)
- [x] [关于](/src/about.zh.md)

- [x] [算法](/src/algorithms.zh.md)
  - [x] [生成随机值](/src/algorithms/randomness.zh.md)
    - [x] [randomness/rand.zh.md](/src/algorithms/randomness/rand.zh.md)
    - [x] [randomness/rand-range.zh.md](/src/algorithms/randomness/rand-range.zh.md)
    - [x] [randomness/rand-dist.zh.md](/src/algorithms/randomness/rand-dist.zh.md)
    - [x] [randomness/rand-custom.zh.md](/src/algorithms/randomness/rand-custom.zh.md)
    - [x] [randomness/rand-passwd.zh.md](/src/algorithms/randomness/rand-passwd.zh.md)
    - [x] [randomness/rand-choose.zh.md](/src/algorithms/randomness/rand-choose.zh.md)
  - [x] [排序向量](/src/algorithms/sorting.zh.md)
    - [x] [sorting/sort.zh.md](./src/algorithms/sorting/sort.zh.md)
    - [x] [sorting/sort_float.zh.md](./src/algorithms/sorting/sort_float.zh.md)
    - [x] [sorting/sort_struct.zh.md](./src/algorithms/sorting/sort_struct.zh.md)
- [x] [命令行](/src/cli.zh.md)
  - [x] [参数解析](/src/cli/arguments.zh.md)
    - [x] [clap 入门](/src/cli/arguments/clap-basic.zh.md)
  - [x] [ANSI 终端](/src/cli/ansi_terminal.zh.md)
    - [x] [ANSI 终端](/src/cli/ansi_terminal/ansi_term-basic.zh.md)
- [x] [压缩](/src/compression.zh.md)
  - [x] [与 Tarballs 合作](/src/compression/tar.zh.md)
    - [x] [解压缩](/src/compression/tar/tar-decompress.zh.md)
    - [x] [压缩](/src/compression/tar/tar-compress.zh.md)
    - [x] [去前缀](/src/compression/tar/tar-strip-prefix.zh.md)
- [x] [并发性](/src/concurrency.zh.md)
  - [x] [显式线程](/src/concurrency/threads.zh.md)
    - [x] [thread/crossbeam-spawn.zh.md](/src/concurrency/thread/crossbeam-spawn.zh.md)
    - [x] [thread/global-mut-state.zh.md](/src/concurrency/thread/global-mut-state.zh.md)
    - [x] [thread/threadpool-walk.zh.md](/src/concurrency/thread/threadpool-walk.zh.md)
    - [x] [thread/threadpool-fractal.zh.md](/src/concurrency/thread/threadpool-fractal.zh.md)
  - [x] [数据并行性](/src/concurrency/parallel.zh.md)
    - [x] [parallel/rayon-iter-mut.zh.md](/src/concurrency/parallel/rayon-iter-mut.zh.md)
    - [x] [parallel/rayon-any-all.zh.md](/src/concurrency/parallel/rayon-any-all.zh.md)
    - [x] [parallel/rayon-parallel-search.zh.md](/src/concurrency/parallel/rayon-parallel-search.zh.md)
    - [x] [parallel/rayon-parallel-sort.zh.md](/src/concurrency/parallel/rayon-parallel-sort.zh.md)
    - [x] [parallel/rayon-map-reduce.zh.md](/src/concurrency/parallel/rayon-map-reduce.zh.md)
    - [x] [parallel/rayon-thumbnails.zh.md](/src/concurrency/parallel/rayon-thumbnails.zh.md)
- [x] [密码学](/src/cryptography.zh.md)
  - [x] [哈希](/src/cryptography/hashing.zh.md)
    - [x] [hashing/sha-digest.md](/src/cryptography/hashing/sha-digest.zh.md)
    - [x] [hashing/hmac.md](/src/cryptography/hashing/hmac.zh.md)
  - [x] [加密](/src/cryptography/encryption.zh.md)
    - [x] [encryption/pbkdf2.zh.md](/src/cryptography/encryption/pbkdf2.zh.md)
- [x] [数据结构](/src/data_structures.zh.md)
  - [x] [位字段](/src/data_structures/bitfield.zh.md)
    - [x] [bitfield/bitfield.zh.md](/src/data_structures/bitfield/bitfield.zh.md)
- [x] [数据库](/src/database.zh.md)
  - [x] [SQLite](/src/database/sqlite.zh.md)
    - [x] [sqlite/initialization.zh.md}}](/src/database/sqlite/initialization.zh.md)
    - [x] [sqlite/insert_select.zh.md}}](/src/database/sqlite/insert_select.zh.md)
    - [x] [sqlite/transactions.zh.md}}](/src/database/sqlite/transactions.zh.md)
  - [x] [Postgres](/src/database/postgres.zh.md)
    - [x] [postgres/create_tables.md](/src/database/postgres/create_tables.zh.md)
    - [x] [postgres/insert_query_data.md](/src/database/postgres/insert_query_data.zh.md)
    - [x] [postgres/aggregate_data.md](/src/database/postgres/aggregate_data.zh.md)
- [x] [日期和时间](/src/datetime.zh.md)
  - [x] [持续时间和计算](/src/datetime/duration.zh.md)
    - [x] [duration/profile.md](/src/datetime/duration/profile.zh.md)
    - [x] [duration/checked.md](/src/datetime/duration/checked.zh.md)
    - [x] [duration/timezone.md](/src/datetime/duration/timezone.zh.md)
  - [x] [解析与显示](/src/datetime/parse.zh.md)
    - [x] [parse/current.md](/src/datetime/parse/current.zh.md)
    - [x] [parse/timestamp.md](/src/datetime/parse/timestamp.zh.md)
    - [x] [parse/format.md](/src/datetime/parse/format.zh.md)
    - [x] [parse/string.md](/src/datetime/parse/string.zh.md)
- [x] [开发工具](/src/development_tools.zh.md)
  - [x] [调试](/src/development_tools/debugging.zh.md)
    - [x] [日志消息](/src/development_tools/debugging/log.zh.md)
      - [x] [log/log-debug.md](/src/development_tools/debugging/log/log-debug.zh.md)
      - [x] [log/log-error.md](/src/development_tools/debugging/log/log-error.zh.md)
      - [x] [log/log-stdout.md](/src/development_tools/debugging/log/log-stdout.zh.md)
      - [x] [log/log-custom-logger.md](/src/development_tools/debugging/log/log-custom-logger.zh.md)
      - [x] [log/log-syslog.md](/src/development_tools/debugging/log/log-syslog.zh.md)
    - [x] [配置日志记录](/src/development_tools/debugging/config_log.zh.md)
      - [x] [config_log/log-mod.zh.md](/src/development_tools/debugging/config_log/log-mod.zh.md)
      - [x] [config_log/log-env-variable.zh.md](/src/development_tools/debugging/config_log/log-env-variable.zh.md)
      - [x] [config_log/log-timestamp.zh.md](/src/development_tools/debugging/config_log/log-timestamp.zh.md)
      - [x] [config_log/log-custom.zh.md](/src/development_tools/debugging/config_log/log-custom.zh.md)
  - [x] [版本控制](/src/development_tools/versioning.zh.md) - [ ][versioning/semver-increment.md](versioning/semver-increment.zh.md)
    - [x] [versioning/semver-complex.md](/src/development_tools/versioning/semver-complex.zh.md)
    - [x] [versioning/semver-prerelease.md](/src/development_tools/versioning/semver-prerelease.zh.md)
    - [x] [versioning/semver-latest.md](/src/development_tools/versioning/semver-latest.zh.md)
    - [x] [versioning/semver-command.md](/src/development_tools/versioning/semver-command.zh.md)
  - [x] [建立时间工具](/src/development_tools/build_tools.zh.md)
    - [x] [build_tools/cc-bundled-static.md](/src/development_tools/build_tools/cc-bundled-static.zh.md) 编译，并静态链接到捆绑的 C 库
    - [x] [build_tools/cc-bundled-cpp.md](/src/development_tools/build_tools/cc-bundled-cpp.zh.md) 编译，并静态链接到捆绑的 C++ 库
    - [x] [build_tools/cc-defines.md](/src/development_tools/build_tools/cc-defines.zh.md)
- [x] [编码](/src/encoding.zh.md)
  - [x] [字符集](/src/encoding/strings.zh.md)
    - [x] [string/percent-encode.md](/src/encoding/string/percent-encode.zh.md)
    - [x] [string/url-encode.md](/src/encoding/string/url-encode.zh.md)
    - [x] [string/hex.md](/src/encoding/string/hex.zh.md)
    - [x] [string/base64.md](/src/encoding/string/base64.zh.md)
  - [x] [CSV 处理](/src/encoding/csv.zh.md)
    - [x] [csv/read.md](/src/encoding/csv/read.zh.md)
    - [x] [csv/delimiter.md](/src/encoding/csv/delimiter.zh.md)
    - [x] [csv/filter.md](/src/encoding/csv/filter.zh.md)
    - [x] [csv/invalid.md](/src/encoding/csv/invalid.zh.md)
    - [x] [csv/serialize.md](/src/encoding/csv/serialize.zh.md)
    - [x] [csv/serde-serialize.md](/src/encoding/csv/serde-serialize.zh.md)
    - [x] [csv/transform.md](/src/encoding/csv/transform.zh.md)
  - [x] [结构化数据](/src/encoding/complex.zh.md)
    - [x] [complex/json.md](/src/encoding/complex/json.zh.md)
    - [x] [complex/toml.md](/src/encoding/complex/toml.zh.md)
    - [x] [complex/endian-byte.md](/src/encoding/complex/endian-byte.zh.md)
- [x] [错误处理](/src/errors.zh.md)
  - [x] [处理错误变量](/src/errors/handle.zh.md)
    - [x] [handle/main.md](/src/errors/handle/main.zh.md)
    - [x] [handle/retain.md](/src/errors/handle/retain.zh.md)
    - [x] [handle/backtrace.md](/src/errors/handle/backtrace.zh.md)
- [x] [文件系统](/src/file.zh.md)
  - [x] [读写](/src/file/read-write.zh.md)
    - [x] [read-write/read-file.md](/src/file/read-write/read-file.zh.md)
    - [x] [read-write/same-file.md](/src/file/read-write/same-file.zh.md)
    - [x] [read-write/memmap.md](/src/file/read-write/memmap.zh.md)
  - [x] [目录穿梭](/src/file/dir.zh.md)
    - [x] [dir/modified.md](/src/file/dir/modified.zh.md)
    - [x] [dir/loops.md](/src/file/dir/loops.zh.md)
    - [x] [dir/duplicate-name.md](/src/file/dir/duplicate-name.zh.md)
    - [x] [dir/find-file.md](/src/file/dir/find-file.zh.md)
    - [x] [dir/skip-dot.md](/src/file/dir/skip-dot.zh.md)
    - [x] [dir/sizes.md](/src/file/dir/sizes.zh.md)
    - [x] [dir/png.md](/src/file/dir/png.zh.md)
    - [x] [dir/ignore-case.md](/src/file/dir/ignore-case.zh.md)
- [x] [硬件支持](/src/hardware.zh.md)
  - [x] [处理器](/src/hardware/processor.zh.md)
    - [x] [processor/cpu-count.md](/src/hardware/processor/cpu-count.zh.md)
- [x] [内存管理](/src/mem.zh.md)
  - [x] [全局静态](/src/mem/global_static.zh.md)
    - [x] [global_static/lazy-constant.md](/src/mem/global_static/lazy-constant.zh.md)
- [x] [网络](/src/net.zh.md)
  - [x] [服务器](/src/net/server.zh.md)
    - [x] [server/listen-unused.md](/src/net/server/listen-unused.zh.md)
- [x] [操作系统](/src/os.zh.md)
  - [x] [外部命令](/src/os/external.zh.md)
    - [x] [external/process-output.md](/src/os/external/process-output.zh.md)
    - [x] [external/send-input.md](/src/os/external/send-input.zh.md)
    - [x] [external/piped.md](/src/os/external/piped.zh.md)
    - [x] [external/error-file.md](/src/os/external/error-file.zh.md)
    - [x] [external/continuous.md](/src/os/external/continuous.zh.md)
- [x] [科学类](/src/science.zh.md)
  - [ ] [数学](/src/science/mathematics.zh.md)
    - [x] [线性代数](/src/science/mathematics/linear_algebra.zh.md)
      - [x] [linear_algebra/vector-sum.md](/src/science/mathematics/linear_algebra/vector-sum.zh.md)
      - [x] [linear_algebra/vector-norm.md](/src/science/mathematics/linear_algebra/vector-norm.zh.md)
      - [x] [linear_algebra/add-matrices.md](/src/science/mathematics/linear_algebra/add-matrices.zh.md)
      - [x] [linear_algebra/multiply-matrices.md](/src/science/mathematics/linear_algebra/multiply-matrices.zh.md)
      - [x] [linear_algebra/multiply-scalar-vector-matrix.md](/src/science/mathematics/linear_algebra/multiply-scalar-vector-matrix.zh.md)
      - [x] [linear_algebra/invert-matrix.md](/src/science/mathematics/linear_algebra/invert-matrix.zh.md)
    - [x] [三角法](/src/science/mathematics/trigonometry.zh.md)
      - [x] [trigonometry/side-length.md](/src/science/mathematics/trigonometry/side-length.zh.md)
      - [x] [trigonometry/tan-sin-cos.md](/src/science/mathematics/trigonometry/tan-sin-cos.zh.md)
      - [x] [trigonometry/latitude-longitude.md](/src/science/mathematics/trigonometry/latitude-longitude.zh.md)
    - [x] [复数](/src/science/mathematics/complex_numbers.zh.md)
      - [x] [complex_numbers/create-complex.md](/src/science/mathematics/complex_numbers/create-complex.zh.md)
      - [x] [complex_numbers/add-complex.md](/src/science/mathematics/complex_numbers/add-complex.zh.md)
      - [x] [complex_numbers/mathematical-functions.md](/src/science/mathematics/complex_numbers/mathematical-functions.zh.md)
    - [x] [统计](/src/science/mathematics/statistics.zh.md)
      - [x] [statistics/central-tendency.md](/src/science/mathematics/statistics/central-tendency.zh.md)
      - [x] [statistics/standard-deviation.md](/src/science/mathematics/statistics/standard-deviation.zh.md)
    - [x] [杂项](/src/science/mathematics/miscellaneous.zh.md)
      - [x] [miscellaneous/big-integers.md](/src/science/mathematics/miscellaneous/big-integers.zh.md)
- [x] [文本处理](/src/text.zh.md)
  - [x] [正则表达式](/src/text/regex.zh.md)
    - [x] [regex/email.md](/src/text/regex/email.zh.md)
    - [x] [regex/hashtags.md](/src/text/regex/hashtags.zh.md)
    - [x] [regex/phone.md](/src/text/regex/phone.zh.md)
    - [x] [regex/filter-log.md](/src/text/regex/filter-log.zh.md)
    - [x] [regex/replace.md](/src/text/regex/replace.zh.md)
  - [x] [字符串解析](/src/text/string_parsing.zh.md)
    - [x] [string_parsing/graphemes.zh.md](/src/text/string_parsing/graphemes.zh.md)
    - [x] [string_parsing/from_str.zh.md](/src/text/string_parsing/from_str.zh.md)
- [x] [网页编程](/src/web.zh.md)
  - [x] [提取链接](/src/web/scraping.zh.md)
    - [x] [scraping/extract-links.md](/src/web/scraping/extract-links.zh.md)
    - [x] [scraping/broken.md](/src/web/scraping/broken.zh.md)
    - [x] [scraping/unique.md](/src/web/scraping/unique.zh.md)
  - [x] [统一资源定位地址:URL](/src/web/url.zh.md)
    - [x] [url/parse.md](/src/web/url/parse.zh.md)
    - [x] [url/base.md](/src/web/url/base.zh.md)
    - [x] [url/new.md](/src/web/url/new.zh.md)
    - [x] [url/origin.md](/src/web/url/origin.zh.md)
    - [x] [url/fragment.md](/src/web/url/fragment.zh.md)
  - [x] [媒体类型](/src/web/mime.zh.md)
    - [x] [mime/string.md](/src/web/mime/string.zh.md)
    - [x] [mime/filename.md](/src/web/mime/filename.zh.md)
    - [x] [mime/request.md](/src/web/mime/request.zh.md)
  - [x] [客户端](/src/web/clients.zh.md)
    - [x] [提出请求](/src/web/clients/requests.zh.md)
      - [x] [requests/get.md](/src/web/clients/requests/get.zh.md)
    - [x] [调用 Web API](/src/web/clients/apis.zh.md)
      - [x] [api/rest-get.md](/src/web/clients/api/rest-get.zh.md)
      - [x] [api/rest-head.md](/src/web/clients/api/rest-head.zh.md)
      - [x] [api/rest-post.md](/src/web/clients/api/rest-post.zh.md)
      - [x] [api/paginated.md](/src/web/clients/api/paginated.zh.md)
    - [x] [下载](/src/web/clients/download.zh.md)
      - [x] [download/basic.md](/src/web/clients/download/basic.zh.md)
      - [x] [download/post-file.md](/src/web/clients/download/post-file.zh.md)
      - [x] [download/partial.md](/src/web/clients/download/partial.zh.md)

### 贡献

欢迎 👏 勘误/校对/更新贡献 😊 [具体贡献请看](https://github.com/chinanf-boy/chinese-translate-list#贡献)

## 生活

[If help, **buy** me coffee —— 营养跟不上了，给我来瓶营养快线吧! 💰](https://github.com/chinanf-boy/live-need-money)

---

# Rust Cookbook  [![Build Status travis]][travis] [![Build Status appveyor]][appveyor]

[build status travis]: https://api.travis-ci.org/rust-lang-nursery/rust-cookbook.svg?branch=master
[travis]: https://travis-ci.org/rust-lang-nursery/rust-cookbook
[build status appveyor]: https://ci.appveyor.com/api/projects/status/k56hklb7puv7c4he?svg=true
[appveyor]: https://ci.appveyor.com/project/rust-lang-libs/rust-cookbook

**[read it here]**.

这个*Rust Cookbook*是一个简单的[rust]生态系统的 crate 包集合, 展示完成常见编程任务的良好实践的示例.

这些例子是完整的,适合直接复制到新的 Cargo 项目中.它们经过测试并保证可以正常工作.

## 离线阅读

如果您想在本地阅读:

```bash
$ git clone https://github.com/rust-lang-nursery/rust-cookbook
$ cd rust-cookbook
$ cargo install mdbook --vers "0.1.8"
$ mdbook serve --open
```

这会输出在`book`子目录.可以从打开 Web 浏览器

```bash
$ xdg-open ./book/index.html # linux
$ start .\book\index.html    # windows
$ open ./book/index.html     # mac
```

[read it here]: https://rust-lang-nursery.github.io/rust-cookbook
[rust]: https://www.rust-lang.org/

## 贡献

这个项目旨在让新的 [rust] 程序员更容易做出贡献,并且是参与 Rust 社区的简单方法.它需要并欢迎帮助.详情见[贡献.](contributing.zh.md).

- [ ] [ ] 详情在 GitHub 上的[CONTRIBUTING.zh.md](./CONTRIBUTING.zh.md).

## 执照[![cc0-badge]][cc0-deed]

Rust Cookbook 根据 Creative Commons Zero v1.0 Universal License 获得([许可证 CC0](LICENSE-CC0)要么<https://creativecommons.org/publicdomain/zero/1.0/legalcode>)

除非您另有明确说明,否则您按照 CC0-1.0 许可证的规定有意提交包含在 Rust Cookbook 中的任何贡献, 应为[致力于公共领域][cc0-deed]上所述的,并没有任何附加条款或条件.

[cc0-deed]: https://creativecommons.org/publicdomain/zero/1.0/deed.en
[cc0-badge]: https://mirrors.creativecommons.org/presskit/buttons/80x15/svg/cc-zero.svg
