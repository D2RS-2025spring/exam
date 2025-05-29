## 开通 GitHub Copilot 服务

GitHub Copilot 是一个“AI 伴侣程序员”（AI pair programmer）。它利用先进的 AI 模型（由 OpenAI 提供技术支持），在你使用的代码编辑器或 IDE（如 Visual Studio Code, JetBrains IDEs, Neovim, Visual Studio, RStudio 等）中，实时为你提供代码建议。

主要作用是：

* **加速编码:** 它可以根据你正在编写的代码上下文和注释，自动建议单行代码、整个函数甚至更复杂的代码块。
* **减少重复工作:** 帮助你更快地完成样板代码或常见模式。
* **学习与探索:** 通过查看 Copilot 的建议，你可能会发现新的编码方式或库函数用法。
* **集成聊天:** Copilot 通常还包含一个聊天界面 (Copilot Chat)，允许你用自然语言提问、解释代码、生成单元测试、调试等。

要使用 GitHub Copilot，需要 [开通服务](https://github.com/features/copilot/plans?cft=copilot_li.features_copilot)。

**个人免费版**订阅提供的服务包括：

- 50 agent mode or chat requests per month
- 2,000 completions per month
- Access to Claude 3.5 Sonnet, GPT-4o, and more


## VSCode

在 VSCode 中配置 GitHub Copilot 需要以下几个步骤：

1. **安装 GitHub Copilot 插件**：
   - 打开 VSCode。
   - 点击左侧的扩展图标（或按 `Ctrl+Shift+X`）。
   - 在扩展市场中搜索 "GitHub Copilot"。
   - 点击安装按钮，安装 GitHub Copilot 插件。

2. **登录 GitHub 帐户**：
   - 安装完插件后，你会看到一个提示要求你登录 GitHub 帐户。
   - 点击“登录”按钮，按照提示完成 GitHub 账户的认证。你可能需要授予权限来使用 Copilot。

3. **配置 GitHub Copilot**（可选）：
   - 完成登录后，你可以在 VSCode 的设置中进行一些自定义配置，比如启用或禁用 Copilot 自动建议、调整建议的频率等。
   - 在 VSCode 中，按 `Ctrl+,` 打开设置，搜索 "GitHub Copilot" 来查看和调整相关设置。

4. **开始使用 GitHub Copilot**：
   - 配置完成后，你就可以开始使用 GitHub Copilot 了。在编写代码时，Copilot 会根据上下文自动提供代码补全建议。
   - 你可以按 `Tab` 键接受建议，或者按 `Esc` 键取消建议。

这样，你就能在 VSCode 中顺利使用 GitHub Copilot 进行编程辅助了！

## RStudio

要在 RStudio 中配置和使用 GitHub Copilot，你需要执行以下步骤：

**前提条件:**

1.  **RStudio 版本:** 你需要安装 RStudio Desktop 2023.09.0 或更高版本。如果你使用的是旧版本，请先更新 RStudio。你可以从 Posit 官网下载最新版本。
2.  **GitHub Copilot 订阅:** 你需要拥有一个有效的 GitHub Copilot 订阅。Copilot 是一个付费服务（对学生、教师和开源项目维护者可能有免费额度），你需要将其与你的 GitHub 账户关联。

**配置步骤:**

1.  **打开 RStudio:** 启动你已更新到符合要求的 RStudio 版本。

2.  **访问全局选项:**
    * 在菜单栏中，点击 `Tools` (工具)。
    * 选择 `Global Options...` (全局选项)。

3.  **找到 Copilot 设置:**
    * 在弹出的 `Options` (选项) 窗口中，找到并点击左侧列表中的 `Copilot` 选项卡。

4.  **启用并安装 Copilot:**
    * 在 `Copilot` 设置页面中，勾选 `Enable GitHub Copilot` (启用 GitHub Copilot) 的复选框。
    * 如果这是你第一次在此版本的 RStudio 中启用 Copilot，RStudio 可能会提示你需要安装或更新一些必要的组件。点击提示中的 "Install" 或 "Yes" 按钮，让 RStudio 自动下载和安装所需的 GitHub Copilot 代理。这可能需要一点时间。

5.  **登录 GitHub 账户 (身份验证):**
    * 安装完成后（或如果已安装），RStudio 会提示你登录 GitHub 账户以授权 Copilot。
    * 通常会显示一个设备验证码 (device code)，并要求你访问一个特定的 GitHub URL (通常是 `https://github.com/login/device`)。
    * 在浏览器中打开该 URL，输入显示的设备验证码，然后按照提示完成授权过程，允许 RStudio 访问你的 GitHub Copilot 权限。

6.  **确认状态:**
    * 成功登录并授权后，返回 RStudio 的 `Global Options` -> `Copilot` 页面。你应该会看到状态显示为已登录或已激活 (e.g., "Signed in as [your GitHub username]")。
    * 你也可以在 RStudio 的状态栏（通常在右下角）看到 GitHub Copilot 的图标及其状态。

7.  **开始使用:**
    * 点击 `OK` 或 `Apply` 关闭 `Global Options` 窗口。
    * 现在，当你在 RStudio 编辑器中编写代码（如 R 脚本、R Markdown 文件等）或注释时，GitHub Copilot 会自动提供代码建议。建议通常以灰色文本（ghost text）的形式出现在光标后。
    * 要接受建议，通常按 `Tab` 键。
    * 如果 Copilot 提供了多个建议，你可以使用 `Alt + ]` (下一个) 和 `Alt + [` (上一个) 或类似快捷键来切换（具体快捷键可能因操作系统而异，请查看 Copilot 状态图标或设置）。

**注意事项:**

* 确保你的网络连接稳定，因为 Copilot 需要连接到 GitHub 的服务器来获取建议。
* 你可以在 `Global Options` -> `Copilot` 中管理 Copilot 的一些行为，例如是否在 R Markdown 文件中启用等。
* Copilot 不仅支持 R 代码，在 RStudio 中编辑其他类型的文件（如 Python、SQL、Markdown）时，它也可能提供相应的建议。

通过以上步骤，你应该可以在 RStudio 中成功配置并开始使用 GitHub Copilot 来辅助你的编程工作了。
