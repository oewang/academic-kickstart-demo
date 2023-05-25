---
title: "How to write Java Agent"
subtitle: ""
summary: "how to write java agent by zero to one"
authors: [oewang]
tags: [java]
categories: [APM]
date: 2023-05-24T19:59:33+08:00
lastmod: 2023-05-24T19:59:33+08:00
featured: true
draft: false
math: true
commentable: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: [java]
---

# How to write Java Agent
## The main contents include the following:
  - Choose a java bytecode manipulation framework
    - Example:
      - [ASM](https://asm.ow2.io)
      - [Javassist](https://www.javassist.org)
      - [Byte Buddy](https://bytebuddy.net)