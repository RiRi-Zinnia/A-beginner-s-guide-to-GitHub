# GitHub零基础实战任务书01

## 一、项目简介

欢迎来到 GitHub 的世界！本任务书专为零基础同学设计，旨在通过“做中学”的方式，带你轻松迈出开源协作的第一步。

在本次“Hello World 挑战”中，你将不再是旁观者，而是真正的参与者。我们将以博主提供的教学项目为起点，从最基础的搜索、收藏开始，一步步完成代码的下载、本地运行、修改，。通过这一系列实战操作，你将亲手解锁 GitHub 的核心技能，为未来的编程与协作学习打下坚实基础。准备好了吗？让我们开始这段奇妙的代码之旅吧！

## 二、学习目标

| 任务 | 内容 |
| --- | --- |
| 任务一 | 搜索博主的教学项目 |
| 任务二 | Star收藏项目 |
| 任务三 | Fork复刻项目 |
| 任务四 | Download下载代码到本地 |
| 任务五 | 用VSCode打开并运行代码 |

完成本次实战任务后，你将能够：

1. **精准搜索**：熟练使用 GitHub 搜索功能，快速找到目标教学项目。
1. **互动与复刻**：掌握 Star（收藏）与 Fork（复刻）操作，理解其在开源社区的意义。
1. **本地运行**：将代码下载到本地，并使用 VSCode 成功运行，验证环境配置。

## 三、课前准备

在开始任务前，请确保你已经准备好以下“装备”：

- **GitHub 账号**：如果还没有，请前往 github.com 免费注册一个。
- **VSCode 编辑器**：前往 code.visualstudio.com  或者 应用商店  下载并安装 Visual Studio Code。
   ![截图](https://fastly.jsdelivr.net/gh/RiRi-Zinnia/A-beginner-s-guide-to-GitHub@main/images/image1.png)
- **Python 环境**：前往 python.org 下载并安装 Python，不知道自己的电脑应该下载哪个型号就去问AI。安装时务必勾选 “Add Python to PATH”
   ![截图](https://fastly.jsdelivr.net/gh/RiRi-Zinnia/A-beginner-s-guide-to-GitHub@main/images/image2.png)
- **Git 工具**：通常 VSCode 会自带 Git，若未安装，请前往 git-scm.com 下载安装。
   ![截图](https://fastly.jsdelivr.net/gh/RiRi-Zinnia/A-beginner-s-guide-to-GitHub@main/images/image3.png)

不知道自己的电脑应该下载哪个型号就去问AI

![截图](https://fastly.jsdelivr.net/gh/RiRi-Zinnia/A-beginner-s-guide-to-GitHub@main/images/image4.png)

## 四、任务详情

| 任务 | 内容 |
| --- | --- |
| 任务一 | 搜索博主的教学项目 |
| 任务二 | Star收藏项目 |
| 任务三 | Fork复刻项目 |
| 任务四 | Download下载代码到本地 |
| 任务五 | 用VSCode打开并运行代码 |

### 任务一：搜索项目

- **操作步骤**：
1. 登录 GitHub，点击页面顶部的搜索框。输入提供的项目名称或关键词，例如RiRi-Zinnia/A-beginner-s-guide-to-GitHub
   ![截图](https://fastly.jsdelivr.net/gh/RiRi-Zinnia/A-beginner-s-guide-to-GitHub@main/images/image5.png)
1. 在搜索结果列表中，点击正确的仓库链接进入
   ![截图](https://fastly.jsdelivr.net/gh/RiRi-Zinnia/A-beginner-s-guide-to-GitHub@main/images/image6.png)

### 任务二：Star收藏项目

- **任务目标**：收藏该项目，方便日后查找，并向作者表达支持。
- **完成标准**：Star 按钮变为高亮状态，且右上角数字 +1。
- **操作步骤**：
  1. 在项目仓库主页的右上角，找到 “Star” 按钮。
  1. 点击该按钮，按钮文字会变为 “Unstar”，表示收藏成功。
- **小贴士/注意事项**：Star 类似于其他平台的“点赞”或“收藏”，是你参与开源社区的第一步互动。
   ![截图](https://fastly.jsdelivr.net/gh/RiRi-Zinnia/A-beginner-s-guide-to-GitHub@main/images/image7.png)

### 任务三：Fork复刻项目

- **任务目标**：将博主的仓库完整复制一份到你自己的 GitHub 账号下。
- **完成标准**：你的账号下出现了一个同名仓库，且页面显示 “forked from 博主用户名/项目名”。
- **操作步骤**：
  1. 在项目仓库主页右上角，点击 “Fork” 按钮。
   ![截图](https://fastly.jsdelivr.net/gh/RiRi-Zinnia/A-beginner-s-guide-to-GitHub@main/images/image8.png)
  1. 在弹出的对话框中，选择你的个人账号作为 Fork 的目标。
   ![截图](https://fastly.jsdelivr.net/gh/RiRi-Zinnia/A-beginner-s-guide-to-GitHub@main/images/image9.png)
  1. 等待几秒钟，页面会自动跳转到你账号下的新仓库。
   ![截图](https://fastly.jsdelivr.net/gh/RiRi-Zinnia/A-beginner-s-guide-to-GitHub@main/images/image10.png)
- **小贴士/注意事项**：Fork 和 Download 有本质区别，请参考下表：

| 对比项 | Fork | Download ZIP |
| --- | --- | --- |
| 代码存哪 | 保存在你的 GitHub 账号下 | 保存在你的电脑本地 |
| 能在线编辑 | 能 | 不能 |
| 能推送修改回GitHub | 能（推送到你自己的Fork仓库） | 不能 |
| 能同步原作者更新 | 能（通过 Fetch upstream） | 不能 |
| 适合场景 | 长期参与、协作、贡献代码 | 仅查看代码、一次性使用 |

### 任务四：Download下载代码到本地

- **任务目标**：将 Fork 后的代码下载到你的电脑上。
- **完成标准**：本地文件夹中包含项目的源代码文件。
- **操作步骤**：
  1. 在你 Fork 的仓库主页，点击绿色的 “Code” 按钮。
   ![截图](https://fastly.jsdelivr.net/gh/RiRi-Zinnia/A-beginner-s-guide-to-GitHub@main/images/image11.png)
  1. 在下拉菜单中选择 “Download ZIP”。
   ![截图](https://fastly.jsdelivr.net/gh/RiRi-Zinnia/A-beginner-s-guide-to-GitHub@main/images/image12.png)
  1. 下载完成后，将 ZIP 文件解压到你习惯存放代码的文件夹中。
   ![截图](https://fastly.jsdelivr.net/gh/RiRi-Zinnia/A-beginner-s-guide-to-GitHub@main/images/image13.png)
- **小贴士/注意事项**：解压后的文件夹可能包含一层同名目录，建议将内部文件直接移出，保持目录结构整洁。

### 任务五：用VSCode打开项目并运行代码

- **操作步骤**：
  1. 打开 VSCode，点击菜单栏 File → Open Folder，选择刚才解压的项目文件夹。
   ![截图](https://fastly.jsdelivr.net/gh/RiRi-Zinnia/A-beginner-s-guide-to-GitHub@main/images/image14.png)
  1. 在左侧资源管理器中找到源代码文件（如 hello.py）。
   ![截图](https://fastly.jsdelivr.net/gh/RiRi-Zinnia/A-beginner-s-guide-to-GitHub@main/images/image15.png)
  1. 右键点击文件，选择 “Run Python File in Terminal”（或在终端中输入 python hello.py）。
   ![截图](https://fastly.jsdelivr.net/gh/RiRi-Zinnia/A-beginner-s-guide-to-GitHub@main/images/image16.png)
  1. 观察底部终端的输出结果。
   ![截图](https://fastly.jsdelivr.net/gh/RiRi-Zinnia/A-beginner-s-guide-to-GitHub@main/images/image17.png)
- **小贴士/注意事项**：如果提示找不到 Python，请检查是否在安装时勾选了 “Add Python to PATH”，或重启 VSCode。

### 五、恭喜你已经成功实现github的基础用法啦，后续教学你将学到：修改代码并提交到个人GitHub、创建自己的仓库并上传代码、创建代码的分支并Commit和Push，关注主播不迷路，只为做真正零基础小白的教学！

## 六、附录

### 附录A：核心概念速查表

| 概念 | 一句话解释 | 怎么用 |
| --- | --- | --- |
| Repository | 代码仓库，存放项目所有文件和历史记录 | 创建或 Fork 一个仓库来开始项目 |
| Star | 收藏/点赞，表示对项目的认可 | 点击仓库页面的 Star 按钮 |
| Fork | 复刻，将他人仓库完整复制到自己账号下 | 点击 Fork 按钮，获得独立副本 |
| Clone | 克隆，将远程仓库下载到本地（含完整历史） | 使用 git clone <url> 命令 |
| Commit | 提交，保存一次修改的快照 | 修改代码后执行 git commit |
| Push | 推送，将本地提交上传到远程仓库 | 执行 git push 同步到 GitHub |
| Pull | 拉取，从远程仓库获取最新代码到本地 | 执行 git pull 保持同步 |
| Branch | 分支，用于并行开发而不影响主线 | 使用 git branch 创建新分支 |
| README.md | 项目说明文档，介绍项目用途和使用方法 | 在仓库根目录创建并编写 |

### 附录B：Fork vs Download ZIP 对比表

| 对比项 | Fork | Download ZIP |
| --- | --- | --- |
| 代码存哪 | 保存在你的 GitHub 账号下 | 保存在你的电脑本地 |
| 能在线编辑 | 能 | 不能 |
| 能推送修改回GitHub | 能（推送到你自己的Fork仓库） | 不能 |
| 能同步原作者更新 | 能（通过 Fetch upstream） | 不能 |
| 适合场景 | 长期参与、协作、贡献代码 | 仅查看代码、一次性使用 |
