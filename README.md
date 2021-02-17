# 9cc

## Overall

Try to build a C compiler based on the following site.

- [低レイヤを知りたい人のためのCコンパイラ作成入門](https://www.sigbus.info/compilerbook)

## Set up development environment

```
$ docker build -t compilerbook docker/
$ docker run --rm -it -v $HOME/9cc:/9cc compilerbook
```
