# icons-humbleicons
`icons-humbleicons` 是基于 Meson 与 [bash-shlib](http://uni.bodz.net/base/bash-shlib)（`import cliboot`）的 **Bash** 命令行模板。  
示例脚本为 `src/icons-humbleicons`。

## 构建 / 安装

```bash
sudo apt install meson ninja-build asciidoctor bash-shlib
meson setup /build
ninja -C /build
meson install -C /build
```

## 示例

```bash
icons-humbleicons [OPTION]... [FILE]...
```

## 许可证

Copyright (C) 2026 Lenik <icons-humbleicons@bodz.net> — **AGPL-3.0-or-later**。见 `LICENSE`。
