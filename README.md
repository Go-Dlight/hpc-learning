# hpc-learning

超级计算团队入门学习与实践记录。

## 学习目标

- 熟悉 Ubuntu 终端、Git 与 GitHub 的基本协作流程。
- 使用 Agent 辅助完成任务，自己检查结果并理解修改。
- 配置 ProMentor，记录学习、练习与反馈。
- 制作个人主页，并按团队要求向提交仓库发起 PR。

## 当前环境

- Windows 11 + WSL2，Ubuntu 22.04.5 LTS。
- Ubuntu 已安装 Git、curl、unzip、Python 3、build-essential 与 CA 证书。
- Windows 项目根目录：`D:\超算`。
- 本仓库目录：`D:\超算\练习\hpc-learning`。
- Ubuntu 对应目录：`/mnt/d/超算/练习/hpc-learning`。

## 如何进入与使用

在 Windows PowerShell 中打开 Ubuntu：

```powershell
wsl -d Ubuntu-22.04
```

进入 Ubuntu 后执行：

```bash
cd /mnt/d/超算/练习/hpc-learning
git status
```

目前本仓库只有学习说明，尚无需要启动的应用。后续添加练习时，将记录对应依赖、运行命令与验证方法。

## 学习记录

- 2026-10-18：完成 Ubuntu 基础环境补齐及 C 编译、Python、ZIP 解压验证；创建学习仓库。
- ProMentor、个人主页与团队 PR 尚待完成。

## 提交约定

每次提交说明完成了什么，并在需要时记录验证结果。密码、API Key、令牌和包含密钥的本地配置不上传到仓库。
