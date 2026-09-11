# icons-humbleicons
`icons-humbleicons` is a Meson-based **Bash** CLI template using [bash-shlib](http://uni.bodz.net/base/bash-shlib) (`import cliboot`).
`icons-humbleicons` is the example script under `src/`.

## Build / install

```bash
sudo apt install meson ninja-build asciidoctor bash-shlib
meson setup /build
ninja -C /build
meson install -C /build
```

## Example

```bash
icons-humbleicons [OPTION]... [FILE]...
```

## License

Copyright (C) 2026 Lenik <icons-humbleicons@bodz.net> — **AGPL-3.0-or-later**. See `LICENSE`.
