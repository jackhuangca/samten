# Samten 笔记｜上师心滴（GitHub Pages）

本仓库由「微信朋友圈数据导出」HTML 自动提取并转换为 Markdown，用于：

1. GitHub Pages / 博客发布（按时间线）——位于 `_posts/`
2. 电子书组装（按《上师心滴》章节线）——位于 `ebook/shangshi-xindi/`

## 说明
- 已提取到《上师心滴》笔记章节：1–35，其中 **第 21 章在源数据中未检索到对应笔记**（其余章节均存在）。
- 原文内容不做改写，仅结构化、加上元数据，便于检索与出版。

## 电子书生成（示例）
在本地安装 pandoc + TeX（推荐 xelatex），然后：

```bash
pandoc ebook/00-preface.md ebook/shangshi-xindi/*.md ebook/99-colophon.md -o Shangshi-Xindi-Sandan-Notes.pdf --pdf-engine=xelatex
```
