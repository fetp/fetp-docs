
# 用法

## preview

> 预览 fetp 所有功能

```bash
$ fetp
```

![](https://makefriends.bs2dl.yy.com/bm1543127896249.gif)

## init

> 构建种子项目

```bash
$ fetp init <模板名称> [项目目录]
# 简写为：
$ fetp i <模板名称> [项目目录]
```

![](https://makefriends.bs2dl.yy.com/bm1543643949529.gif)


## dev

> 开发模式，启动一个Web 服务器

```bash
$ fetp dev
# 简写为：
$ fetp d
```

- `FETP`会从我们的源码目录 `src`，构建生成一个开发预览目录 `dev`，并启动一个服务器供我们预览。 
- 修改源码会自动增量构建，并且自动刷新浏览器。 (实现原理参考：[webpack DevServer](https://webpack.js.org/configuration/dev-server/))
- `FETP` 不会修改源码。


![](https://makefriends.bs2dl.yy.com/bm1543644512171.gif)

## watch (未实现)

> watch 模式

```bash
$ fetp watch
# 简写为：
$ fetp w
```

## output (未实现)

> 生产模式，构建并发布到生产环境

```bash
$ fetp output
# 简写为：
$ fetp o
```

`FETP` 会帮助我们将 `src` 目录下的源码，构建打包到 `output`目录

## help

> 查看帮助文档

```bash
$ fetp help
# 简写为：
$ fetp -h
```

