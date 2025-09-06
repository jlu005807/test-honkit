本仓库用于测试使用 Honkit 构建文档站点，并尝试若干 GitBook/Honkit 插件与自定义样式（例如 `flexible-alerts`、`search-pro`、`tbfed-pagefooter`、自定义 `styles/website.css` 等）。

主要目的：

- 验证 Honkit 在本地与 CI（GitHub Actions）下的构建流程。
- 测试常用插件的兼容性与样式效果。
- 其中个性化配置在 `book.json` 以及 `styles/website.css`
- 同时本页面使用的插件可以查看`package.json`

快速使用（在项目根目录）：具体构建详见：[honkit](https://honkit.netlify.app/)。请保证已经安装好node.js
可以通过命令行 `node -v` 查看

```powershell
# 安装依赖
npm install honkit --save-dev

#初始化
npx honkit init

# 本地构建
npx honkit build

# 预览生成的静态网站（例如用 http-server）
npx honkit server 
# 然后在浏览器打开 http://localhost:4000
```


> [!tip]
> 注意下面的文章来源于阮一峰的[中文技术文档的写作规范](https://github.com/ruanyf/document-style-guide),在这里仅仅用于展示

## 目录

1. [标题](docs/title.md)
1. [文本](docs/text.md)
1. [段落](docs/paragraph.md)
1. [数值](docs/number.md)
1. [标点符号](docs/marks.md)
1. [文档体系](docs/structure.md)
1. [参考链接](docs/reference.md)

## License

公共领域（public domain）
