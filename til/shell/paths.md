# Absolute and relative paths · 绝对路径与相对路径

> Example note written by Claude to set up the repo. From now on, notes are written by me, in my own words.
> 这一篇是 Claude 建仓库时写的示例；以后的笔记都由我自己写。

- An **absolute path** starts from the root of the file tree: `/home/xinbowang/research-toolbox` on Linux, `D:\GoogleDrive` on Windows.
  **绝对路径**从文件树的根开始写。
- A **relative path** starts from where I am now (`pwd` shows it): `til/shell/paths.md`, or `..` for the folder above.
  **相对路径**从当前位置开始写；`..` 表示上一级。
- WSL mounts Windows drives under `/mnt`, with lower-case drive letters, so `D:\GoogleDrive` is `/mnt/d/GoogleDrive` inside Ubuntu.
  WSL 把 Windows 的盘挂在 `/mnt` 下，盘符小写。

Try it · 试一下:

```bash
pwd
ls /mnt/d
cd ~ && pwd
```
