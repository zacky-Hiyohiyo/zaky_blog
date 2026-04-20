---
title: 欢迎来到本站（指南与引导）
published: 2026-03-14
description: "How to use this blog."
image: "./cover.webp"
tags: ["hello world", "Blogging"]
category: 分类名称
author: "超絕可愛の一抹多"  # 新增这一行
draft: false
pinned: true
---
## 待开发中...
## 待开发中...
## 待开发中...
## 怎么使用

```yaml
---
title: 我的第一篇
published: 2026-03-14
description: 记录中....
image: ./cover.jpg
tags: [Foo, Bar]
category: Front-end
draft: false
---
```




| Attribute     | Description                                                                                                                                                                                                 |
|---------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `title`       | 标题.                                                                                                                                                                                      |
| `published`   | The date the post was published.    该帖子发布的具体日期。                                                                                                                                                                        |
| `pinned`      | Whether this post is pinned to the top of the post list.           此帖子是否被固定置顶在帖子列表的最上方。                                                                                                                                        |
| `priority`    | The priority of the pinned post. Smaller value means higher priority (0, 1, 2...).       置顶帖子的优先级。数值越小，优先级越高（0、1、2……）。                                                                                                                   |
| `description` | A short description of the post. Displayed on index page.     该职位的简要描述。显示在首页上。                                                                                                                                              |
| `image`       | The cover image path of the post.<br/>1. Start with `http://` or `https://`: Use web image<br/>2. Start with `/`: For image in `public` dir<br/>3. With none of the prefixes: Relative to the markdown file 该帖子的封面图片路径。<br/>1. 以 `http://` 或 `https://` 开头：使用网络图片<br/>2. 以 `/` 开头：对于位于 `public` 目录中的图片<br/>3. 不使用上述任何前缀：相对于 Markdown 文件所在位置|
| `tags`        | The tags of the post.   帖子的标签。                                                                                                                                                                                    |
| `category`    | The category of the post.   帖子内容的许可证名称。                                                                                                                                                                                |
| `licenseName` | The license name for the post content.                                                                                                                                                                      |
| `author`      | The author of the post.  该帖子的作者。                                                                                                                                                                                   |
| `sourceLink`  |  该帖子内容的来源链接或参考资料。                                                                                                                                                            |
| `draft`       | 如果此帖子仍处于草稿状态，那么它将不会显示出来。                                                                                                                                             |

## 该放哪里呢



放在目录 `src/content/posts/` 目录。您还可以创建子目录，以便更好地组织您的帖子和资源。

```
src/content/posts/
├── post-1.md
└── post-2/
    ├── cover.webp
    └── index.md
```