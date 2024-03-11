# blog

![Vercel](https://vercelbadge.vercel.app/api/m1sk9/blog)
[![build ci](https://github.com/m1sk9/blog/actions/workflows/build.yaml/badge.svg)](https://github.com/m1sk9/blog/actions/workflows/build.yaml)

m1sk9's blog. Using [Astro](https://astro.build/).

## Usage

### Create post

1. Run `bun run create`
2. Rename `./src/pages/posts/2024/post-template.md`
3. Update post info

```md
---
layout: "../../../layouts/Blog.astro" # Don't edit
date: "" # Publish post date
emoji: "" # Post emoji
title: "" # Post title
description: "" # Post description
---
```

### Running Developemnt Server

Run `bun run start`
