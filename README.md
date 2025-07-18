# WGdocs v2

本项目是 **[WGdocs v2](https://mmy.kesug.com/)** 的文档项目, 用于文档的更新, 部署等.

如果只需要进行简单的修改可以直接修改对应文档的 markdown 源码, 如果修改较为复杂请参考以下步骤.

WGdocs v2 采用 **[VitePress](https://vitepress.dev/zh/guide/what-is-vitepress)** 作为文档框架, 以及 **[NapcatQQ Docs](https://github.com/NapNeko/NapCatDocs)** 作为文档模板，请参考其文档进行贡献.

首先确保 node.js 版本满足 >= `v20.5.0` 或 >= `v18.18.0`, **安装好** VitePress 后, **重启终端**, 于拉取的本项目根目录下执行以下代码安装依赖:

```bash
npm install
```

安装依赖后执行以下代码进行预览:

```bash
npm run docs:dev
```

# Thanks

[karin](https://github.com/KarinJS/Karin)

[Napcat Docs](https://github.com/NapNeko/NapCatDocs)