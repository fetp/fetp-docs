# 项目结构

## 概述
使用 `FETP` 需要遵循一些目录结构规则。`FETP` 项目目录里会有一个子目录：

* `src`：源码目录，项目的所有的源码都在这里。

这样，可以确保我们在开发预览和生产构建时，源代码不会被 `FETP` 修改。

然后，FETP 项目目录的根部，一般还有几个文件（按重要性排序）：

* `.gitignore`：Git 仓库的忽略列表，确保不把一些没用的文件存放到 Git 里。必要。
* `README.md`：项目说明文件，时间地点人物事情，项目的简介还是必须的。必要。
* `.editorconfig`：编辑器格式文件，配合 ESLint 使用。详见[使用 ESLint](guide/404.md)。
* `FETP.config.js`：项目的 FETP 配置文件，用来配置 FETP 的功能。详情请查看[配置介绍](config/404.md)。建议建立一个。
* `package.json`：npm 安装依赖说明文件。
* `eslintConfig`：ESLint 配置文件。在 `package.json` 中配置。
* `eslintIgnore`：ESLint 忽略列表文件。在 `package.json` 中配置。

## 项目结构图


````
project/                   // 项目根目录
├── node_modules/          // node 本地模块依赖
├── src/                   // 源代码目录（必要）
├── .gitignore             // git 忽略列表（必要）
├── .editorconfig          // 编辑器格式文件
├── fetp.config.js         // FETP 配置文件
├── package.json           // node 模块依赖管理文件
└── README.md              // 项目说明文件（必要）
````


## src 源码目录结构


````
src/                   // src 目录
├── component/         // 组件目录, 存放项目公共组件
├── css/               // 样式目录, 存放 SCSS 样式源码
├── html/              // 页面目录, 存放静态资源页面
├── img/               // 图片模板, 存放静态资源图片
├── module/            // 脚本目录, 放置项目模块
└── index.js           // 项目入口,
````
