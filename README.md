# Nop
ARM64 and x86_64 ASM code (no behavior exit only)

The other arch couldn't verify that it could be used, so only two of them were written.

build:
```shell
clang -c -o <file name>.o <file name>.S -nostdlib -nostartfiles -fPIC
ld -o <file name> <file name>.o <-shared>
strip <file name>
```
Then you can get a very small file that is useless.

## [License](https://github.com/Cai-Ming-Yu/Nop/blob/C-M-Y/LICENSE)