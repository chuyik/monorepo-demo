# Monorepo Demo
该项目用了 `lerna` + `yarn workspace` 的形式，结合 `tslint` + `prettier` 统一管理代码样式。

## lerna 作用
[lerna](https://github.com/lerna/lerna) 提供了一些命令行工具，便于我们管理 `packages/` 文件夹下每个子项目的版本与发布，这种工作流形式可以参考文章 [lerna管理前端packages的最佳实践](http://www.sosout.com/2018/07/21/lerna-repo.html)

## yarn workspace 作用
[Yarn workspace](https://classic.yarnpkg.com/zh-Hans/docs/workspaces/) 允许多个子项目共享同一个依赖包，并统一某个依赖的版本号，比如 `ESLint` / `jest` 这些工具，应当只有一份代码、一个版本号。
