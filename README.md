# teachpy

零基础 Python 教学 skill（`teach-python`）。只讲语言无关的心智模型、绝不代写代码、任何名词必先专项讲解 + 实操，按「顺序结构 → 分支结构 → 循环结构」推进，配 12 道递进例题。

## 结构

- `.pi/skills/teach-python/` —— 可移植 skill（`SKILL.md` + `references/`）
- `package.json` —— Pi package 清单（可经 git 全局安装，见下）

## 本地测试（不污染全局）

在仓库根目录运行 pi，skill 会被自动发现：

```bash
cd ~/teachpy
pi
```

然后手动调用：`/skill:teach-python`

## 全局安装（可选，Mode B）

```bash
pi install git:github.com/dudujerry452/teachpy@main
```

装的是 git 源，更新走 `pi update`（或重新 pin 一个 tag）。

## 更新

编辑 → `git commit` → `git push`，会话内 `/reload` 生效（已全局安装则 `pi update`）。

## 说明

- 教学进度与学员练习代码写在 `.pi/state/`（已被 `.gitignore` 忽略，不进仓库）。
- 该 skill 设了 `disable-model-invocation: true`，只能通过 `/skill:teach-python` 手动调用。
