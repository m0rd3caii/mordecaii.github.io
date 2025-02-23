---
title: Pivoting con SSH
published: 2025-02-24
description: "How to use this blog template."
image: "./cover.jpeg"
tags: ["Pivoting", "Ssh", "Port Forwarding"]
category: Pivoting
draft: false
---


## Índice
- [Introducción](#introducción)
- [Local Port Forwarding](#capítulo-1)
- [Remote Port Forwarding](#capítulo-2)
- [Dynamic Port Forwarding](#conclusión)

## introducción

El pivoting es una técnica esencial para acceder a sistemas internos a través de un equipo intermediario. Una de las herramientas más utilizadas para este propósito es **SSH (Secure Shell)**, que permite tunelizar tráfico de manera segura y eficiente.
En este artículo, exploraremos tres técnicas clave de **port forwarding** en SSH:
- Local Port Forwarding: Permite acceder a servicios en redes remotas a través de un puerto local.
- Remote Port Forwarding: Expone servicios locales a redes externas mediante un túnel SSH.
- Dynamic Port Forwarding: Funciona como un proxy SOCKS para enrutar tráfico hacia múltiples destinos a través de un host intermediario.

| Attribute     | Description                                                                                                                                                                                                 |
|---------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `title`       | The title of the post.                                                                                                                                                                                      |
| `published`   | The date the post was published.                                                                                                                                                                            |
| `description` | A short description of the post. Displayed on index page.                                                                                                                                                   |
| `image`       | The cover image path of the post.<br/>1. Start with `http://` or `https://`: Use web image<br/>2. Start with `/`: For image in `public` dir<br/>3. With none of the prefixes: Relative to the markdown file |
| `tags`        | The tags of the post.                                                                                                                                                                                       |
| `category`    | The category of the post.                                                                                                                                                                                   |
| `draft`        | If this post is still a draft, which won't be displayed.                                                                                                                                                    |

## Where to Place the Post Files



Your post files should be placed in `src/content/posts/` directory. You can also create sub-directories to better organize your posts and assets.

```
src/content/posts/
├── post-1.md
└── post-2/
    ├── cover.png
    └── index.md
```
