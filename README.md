# images

公开图片仓库 · 存放图片素材，可直接当图床引用。

## 目录结构

| 目录 | 用途 |
| --- | --- |
| `img/` | 通用图片、配图 |
| `cover/` | 封面图、头图 |
| `screenshot/` | 截图 |
| `avatar/` | 头像、图标 |

目录里目前各放了一个 `.gitkeep` 占位文件（Git 不跟踪空目录），删掉它并放入图片即可。

## 命名规范

```
YYYYMMDD-用途-简短描述.ext
例：20261119-cover-spring-sale.png
```

全小写、用连字符分隔、不用空格和中文文件名，避免引用时 URL 需要转义。

## 引用方式

原始文件地址：

```
https://raw.githubusercontent.com/Mingtuo916/images/main/img/<文件名>
```

走 jsDelivr CDN（国内更快，且带缓存）：

```
https://cdn.jsdelivr.net/gh/Mingtuo916/images@main/img/<文件名>
```

Markdown 写法：

```markdown
![描述](https://cdn.jsdelivr.net/gh/Mingtuo916/images@main/img/20261119-demo.png)
```

## 注意事项

- 本仓库是**公开**的，任何人可访问，不要放隐私或未公开的材料
- 网页上传单文件上限 25 MB；Git 硬上限单文件 100 MB
- 更新图片后 CDN 有缓存，需要刷新时可加 `?v=2` 之类的参数
