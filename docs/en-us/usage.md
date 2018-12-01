
# Usage (basic)

## preview

> Preview fetp all function

```bash
$ fetp
```

![](https://makefriends.bs2dl.yy.com/bm1543127896249.gif)


## init

> Initial a seed project

```bash
$ fetp init <templateName> [directory]
# OR Shorthand 
$ fetp i <templateName> [directory]
```

![](https://makefriends.bs2dl.yy.com/bm1543643949529.gif)

## dev

> development model, Running a Development Web Server

```bash
$ fetp dev
# OR Shorthand 
$ fetp d
```

- `FETP` can help us create a preview directory in the `dev` directory from the `src` directory，and start a server offer us preview。 
-  Modify source code will auto build incrementally,and hot-refresh browser (reference：[webpack DevServer](https://webpack.js.org/configuration/dev-server/))
- `FETP` 不会修改源码。

![](https://makefriends.bs2dl.yy.com/bm1543644512171.gif)


## watch (unimplemented)

> watch model

```bash
$ fetp watch
# OR Shorthand 
$ fetp w
```

## output (unimplemented)

> production model, building & publish project production development.

```bash
$ fetp output
# OR Shorthand 
$ fetp o
```

`FETP` can help us package the source code in the `src` directory to be the `output` directory

## help

> view online help document.

```bash
$ fetp help
# OR Shorthand 
$ fetp -h
```

