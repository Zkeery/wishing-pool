# 许愿池

许愿池前端静态页。页面、样式和脚本都放在仓库根目录，打开即可使用，不需要安装依赖，也不需要后端。

## 文件

- `index.html`：页面
- `hark.css`：基础样式
- `hark-hero.css`：主视觉样式
- `hark.js`：主题切换等脚本

## 怎么打开

用浏览器直接打开 `index.html`：

```bash
# macOS
open index.html

# Linux
xdg-open index.html

# Windows
start index.html
```

也可以在仓库根目录启动一个静态服务器，再访问打印出来的地址：

```bash
python3 -m http.server 8080
```

浏览器打开 http://localhost:8080 。
