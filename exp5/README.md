# 实验 5 · 数据分析展示页

静态页面，无构建、无依赖。把整个 `exp5/` 目录原样放进仓库即可。

```
exp5/
├── index.html
└── assets/
    ├── fig1_behavior.png
    ├── fig2_notes_raw.jpg
    ├── fig3_notes_grouped.jpg
    └── fig4_affinity.png
```

## 本地预览

```bash
cd exp5
python -m http.server 8000
# 浏览器打开 http://localhost:8000
```

## GitHub Pages

放进仓库后，在仓库 Settings → Pages 里选择分支根目录部署，访问地址为：

```
https://<用户名>.github.io/<仓库名>/exp5/
```

页面内全部使用相对路径，换目录名或换仓库名都无需改动代码。
