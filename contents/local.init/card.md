## 任务卡

欢迎来到 Git 实战挑战！在这个任务中，你需要创建你的第一个 Git 仓库。

我们为你准备了一个项目目录 `/challenge/my-project`，里面已经有一些文件了。你的任务是：

1. 进入 `/challenge/my-project` 目录
2. 初始化一个 Git 仓库
3. 使用 `git status` 查看仓库状态
4. 运行 `/challenge/judge` 来验证你的操作是否正确

### 具体步骤

```bash
cd /challenge/my-project
git init
git status
/challenge/judge
```

### 成功标准

- 在 `/challenge/my-project` 目录下存在 `.git` 目录
- `git status` 能够正常运行并显示未跟踪的文件
- 评测程序确认仓库初始化成功

> **TIP** 随时随地你都可以通过 `/challenge/card` 指令查看任务卡，用 `/challenge/tutorial` 指令查看教程。

### 小提示

如果你遇到问题，记住：
- 使用 `ls -la` 查看是否存在 `.git` 目录
- 使用 `pwd` 确认你在正确的目录中
- 如果初始化错了，可以删除 `.git` 目录重新开始：`rm -rf .git`