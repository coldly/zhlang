<img width="256" src="https://raw.githubusercontent.com/coldly/zhlang/master/logo/zh.png">

# The ZH Programming Language

[![CI](https://github.com/coldly/zhlang/workflows/CI/badge.svg)](https://github.com/coldly/zhlang/commits/master)

https://zhlang.org

Documentation: [zhlang.org/docs](https://zhlang.org/docs)

Changelog: [github.com/coldly/zhlang/blob/master/CHANGELOG.md](https://github.com/coldly/zhlang/blob/master/CHANGELOG.md)

Speed Test: [fast.zhlang.org](https://fast.zhlang.org/) (monitors compilation speed for each commit to verify there are no speed regressions)

Installing ZH: [github.com/coldly/zhlang#installing-zh-from-source](https://github.com/coldly/zhlang#installing-zh-from-source)


## Key Features of ZH

- Simplicity: the language can be learned in less than an hour
- Fast compilation: ≈100k — 1.2 million loc/s
- Easy to develop: ZH compiles itself in less than a second
- Performance: within 3% of C
- Safety: no null, no globals, no undefined behavior, immutability by default
- C to ZH translation
- Hot code reloading
- [Cross-platform UI library](https://github.com/coldly/zhlang/ui)
- Built-in graphics library
- Easy cross compilation
- REPL
- Built-in ORM
- C and JavaScript backends

A stable 0.2 release is planned for January 2020. Right now ZH is in an alpha stage.

## Installing ZH from source

### Linux, macOS, Windows, *BSD, Solaris, WSL, Android, Raspbian

```bash
git clone https://github.com/coldly/zhlang
cd zhlang
make
```

That's it! Now you have a ZH executable at `[path to ZH repo]/zh`. `[path to ZH repo]` can be anywhere.

(On Windows `make` means running `make.bat`, so make sure you use `cmd.exe`.)

ZH is being constantly updated. To update ZH, simply run:

```
zh up
```

### C compiler

You'll need Clang or GCC or Visual Studio. If you are doing development, you most likely already have one of those installed.

Otherwise, follow these instructions:

[github.com/coldly/zhlang/wiki/Installing-a-C-compiler-on-Linux-macOS](https://github.com/coldly/zhlang/wiki/Installing-a-C-compiler-on-Linux-macOS)

[github.com/coldly/zhlang/wiki/Installing-a-C-compiler-on-Windows](https://github.com/coldly/zhlang/wiki/Installing-a-C-compiler-on-Windows)

### Symlinking

You can create a `/usr/local/bin/zh` symlink so that ZH is globally available:

```bash
sudo ./zh symlink
```
