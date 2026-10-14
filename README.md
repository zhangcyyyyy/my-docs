# my-docs

使用 **MkDocs** 生成的技术文档项目，通过 **GitHub Actions** 自动构建并部署到 **GitHub Pages**。

## 项目结构

```
my-docs/
├── docs/          # Markdown 文档源文件
│   ├── index.md   # 主页
│   ├── about.md   # 关于页面
│   ├── guide.md   # 使用指南
│   └── api.md     # API 参考
├── .github/
│   └── workflows/
│       └── deploy.yml   # 自动化部署工作流
├── mkdocs.yml     # MkDocs 配置
└── README.md
```

## 本地预览

```bash
pip install mkdocs-material
mkdocs serve
```

## 访问地址

文档部署后可通过 `https://<GitHub用户名>.github.io/<仓库名>/` 访问。
