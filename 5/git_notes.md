# Git 学习笔记

## 📑 目录
- [1. Git 基础概念](#1-git-基础概念)
- [2. Git 安装与配置](#2-git-安装与配置)
- [3. Git 基本操作](#3-git-基本操作)
- [4. 分支管理](#4-分支管理)
- [5. 远程仓库操作（Github）](#5-远程仓库操作github)
- [6. 常见问题与解决](#6-常见问题与解决)
- [7. Git 工作流](#7-git-工作流)
- [8. Github Pages 搭建博客（加分项）](#8-github-pages-搭建博客加分项)

---

## 1. Git 基础概念
- **Git**：一个免费的、开源的分布式版本控制系统  
- **作用**：版本管理、多⼈协作、分支管理、远程备份  
- **Git vs Github**  
  - Git：工具  
  - Github：基于 Git 的代码托管平台  

---

## 2. Git 安装与配置
安装 Git 后，先配置用户名和邮箱：

```bash
git config --global user.name "名字"
git config --global user.email "邮箱"