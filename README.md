# OSのしくみ

1. Rustを使って開発

# 環境
rustup v1.28.2

cargo v1.87.0

rustc v1.87.0


# 実行
- 実行

```bash
mkdir -p third_party/ovmf
cd third_party/ovmf
wget https://github.com/hikalium/wasabi/raw/main/third_party/ovmf/RELEASEX64_OVMF.fd
cd -
```


```bash
cargo run
```

# OS
VMware上Ubuntu(24.04.2)。


# 参考サイト

