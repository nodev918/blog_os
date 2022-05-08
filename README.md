```
$ rustc --version --verbose
```

```
set nightly
$ rustup override set nightly
```

```
dependency
$ cargo install bootimage
```

```
component
$ rustup component add rust-src
$ rustup component add llvm-tools-preview
```

```
install exe_bootimage:
cargo bootimage
```

```
run image via qemu
$ qemu-system-x86_64 -drive format=raw,file=target/x86_64-blog_os/debug/bootimage-blog_os.bin
```

```
refs:
writing os with rust
https://os.phil-opp.com/minimal-rust-kernel/#installing-rust-nightly
rust-os
https://rcore.gitbook.io/rust-os-docs/xiang-mu-zheng-ti-jie-shao
```
