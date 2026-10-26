# 👋 Yzero123

一些自己写的小工具与小项目。

| 项目 | 说明 |
| --- | --- |
| 📜 **[人生档案 life-archive](https://github.com/Yzero123/life-archive)** | Mini App 包（MIT）。把 QQ 空间历史说说（含已删除后恢复的）、微信朋友圈动态与互动建成**可检索、可对话**的个人知识库，并生成「过去的我」人物画像。回答严格接地真实内容，资料不足时只回「当时我还不知道这是什么意思」。19 个发布版本、逐版可回退；包内零个人信息，发布前自动脱敏回扫。 |
| 🍅 **[pomodoro-timer](https://github.com/Yzero123/pomodoro-timer)** | 命令行番茄钟（二次元增强版）。标准番茄工作法 + 二次元终端 UI + 桌面通知 + 统计持久化，零 GUI 依赖，Windows / macOS / Linux 通用。16 项单元测试，CI 覆盖 Python 3.8 / 3.11 / 3.12。 |
| 🐶 **[CNN](https://github.com/Yzero123/CNN)** | TensorFlow / Keras 图片多分类。3 类数据集，训练好的权重随仓库分发，克隆即可预测。实测准确率 99.53%（213/214），可用 `python evaluate.py` 复现。 |
| 🗂️ **[feishu-asset-bot](https://github.com/Yzero123/feishu-asset-bot)** | 飞书业务资产管理机器人（私有）。用多维表格做资产库，聊天指令完成登记与检索，部署在 Vercel Edge Runtime。 |

---

## 🧰 技术栈

- **语言**：Python、JavaScript (ESM)、Node.js、TypeScript、SQL、Shell
- **CLI 与工程化**：argparse、unittest、pytest、Git、GitHub Actions、uv / pip、setuptools
- **AI / 机器学习**：TensorFlow、Keras、NumPy、OpenCV、Matplotlib
- **后端与前端**：FastAPI、Flask、Spring Boot、SQLite / MySQL、React、Vue 3、Vite
- **自动化与集成**：Playwright、Mini App（MiniMax Code）、飞书开放平台（Bitable / 交互卡片）、Vercel Edge Runtime

---

## 💡 工作方式

- **先跑通再优化**：每条链路先有可执行的最小版本，再补质量门与恢复逻辑。
- **交付即文档**：公开的代码要能被别人按 README 独立跑通；跑不通就把边界说清楚。
- **数据驱动**：指标用脚本算出来，不用估。CNN 仓库里的准确率就是 `evaluate.py` 实测的。
- **隐私写进代码，不只写进文档**：脱敏靠自动回扫 + 结构性规则（真实账号白名单）把关，没有本机数据时也生效。

---

## 📫 联系

- GitHub：[@Yzero123](https://github.com/Yzero123)
- 问题与建议请直接开 Issue。

---

> 💡 专注是一种力量，让每一次番茄钟都充满意义。
