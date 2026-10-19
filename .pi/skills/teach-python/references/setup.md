# 环境配置（按 OS 分派）

目标：检测学员机器、缺什么装什么，全程用平实语言解释。**先检测，缺了才装。**

## 检测（先跑这些）

- OS / 架构：`uname -s -m`
- Python：`python3 --version`（macOS / Linux 通常已预装）
- 编辑器：`code --version`（VS Code）

## 按 OS 安装

### macOS
- Python：`brew install python`（没有 brew 先去 brew.sh 装）
- VS Code：`brew install --cask visual-studio-code`

### Linux (Debian / Ubuntu)
- Python：`sudo apt install python3`
- VS Code：`sudo snap install code --classic`

### Linux (Fedora 等)
- Python：`sudo dnf install python3`
- VS Code：`sudo snap install code --classic`（或用微软官方源）

### Windows
- Python：`winget install Python.Python.3.12`
- VS Code：`winget install Microsoft.VisualStudioCode`

## 装完

1. 建练习目录：`mkdir -p .pi/state/scratch`
2. 把「装了啥、版本、练习目录路径」写回 `.pi/state/env.md`
3. 装的过程里，每装一样都要用平实语言告诉学员「这是什么、为什么装它」
