# Research Toolbox · 科研工具箱

My notes and exercises while learning the everyday tools of computational research:
the shell, Git, editors, Python environments, SSH and clusters.
我学习科研常用工具（命令行、Git、编辑器、Python 环境、SSH 与集群）时的笔记和练习。

## How this repo works · 怎么用

- `til/<topic>/` — "Today I Learned": one short note per small thing I learned, in my own words.
  「今天学到了」：每学到一个小知识点写一篇短笔记，用自己的话写。
- `missing-semester/` — exercises from MIT's *The Missing Semester* (2026), one file per lecture.
  Missing Semester 2026 的课后练习，每讲一个文件。

Adding a note · 加一篇笔记:

```bash
cd ~/research-toolbox
code .                      # open in VS Code
git add .
git commit -m "Add TIL: <topic>"
git push
```

## Index · 目录

### shell
- [Absolute and relative paths](til/shell/paths.md)
