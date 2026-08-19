<div align="center">

# SurferCut

### 一站式 AI 短视频生成工具

只需提供视频<b>主题</b>或<b>关键词</b>，即可自动生成视频脚本、匹配素材、生成字幕和背景音乐，并合成高清短视频。

[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey.svg)](https://github.com/temidayoxyz/surfercut)
[![Python](https://img.shields.io/badge/python-3.11%2B-3776AB?logo=python&logoColor=white)](https://www.python.org/)

简体中文 | [English](README-en.md) | [问题反馈](https://github.com/temidayoxyz/surfercut/issues)

</div>

SurferCut 基于 [MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) 的生成引擎，产品名称、仓库和 WebUI 已重新命名为 SurferCut。

## 界面预览 🖥️

<h4 align="center">WebUI</h4>

![](docs/webui.jpg)

<h4 align="center">API</h4>

![](docs/api.jpg)

## 功能特性 🎯

- [x] 提供 **AI Agent**、**WebUI**、**API** 和 **CLI** 四种使用方式，代码按控制器、服务和模型等职责分层
- [x] 支持 **AI 自动生成视频脚本**，也可以使用自定义脚本
- [x] 支持多种 **高清视频** 尺寸
  - [x] 竖屏 9:16，`1080x1920`
  - [x] 横屏 16:9，`1920x1080`
- [x] 支持 **批量视频生成**，可以一次生成多个视频，然后选择一个最满意的
- [x] 支持 **视频片段时长** 设置，方便调节素材切换频率
- [x] 支持 **多语言视频脚本** 生成
- [x] 支持 **Edge TTS**、**Azure Speech**、**SiliconFlow**、**Google Gemini**、**小米 MiMo**、**ElevenLabs** 和 **Chatterbox** 语音合成，可实时试听
- [x] 支持 **字幕生成**，可调整字体、位置、颜色、大小、描边和背景样式
- [x] 支持 **背景音乐**，可随机选择或使用指定音乐，并调整音量
- [x] 支持使用自己的 **本地素材**，也可从 **Pexels**、**Pixabay** 和 **Coverr** 获取可免费使用的高清素材
- [x] 支持 **Kimi / Moonshot AI**、**OpenAI**、**Google Gemini**、**DeepSeek**、**阿里云通义千问**、**Microsoft Azure OpenAI**、**火山引擎方舟**、**xAI Grok**、**MiniMax**、**小米 MiMo** 等主流模型服务，并兼容 **Cloudflare AI Gateway**、**魔搭 ModelScope**、**AIHubMix**、**AIML API**、**EvoLink**、**Ollama**、**OneAPI**、**LiteLLM**、**Groq**、**Pollinations AI** 等统一网关、聚合平台和本地运行环境
- [x] 支持一键 **跨平台发布**，生成完成后可自动上传至 **TikTok**、**Instagram** 和 **YouTube Shorts**

## 作品展示 🎬

以下示例均由同一套生成流水线实际生成。

### 竖屏 9:16

<table width="100%">
<tr>
<td align="center" width="25%"><a href="https://harry0703.github.io/mpt-assets/?video=03-zh-portrait-city-morning.mp4"><img src="https://github.com/harry0703/mpt-assets/releases/download/assets/03-zh-portrait-city-morning.jpg" width="180" alt="城市醒来的时刻"></a><br><strong>城市醒来的时刻</strong><br>中文 · 14 秒</td>
<td align="center" width="25%"><a href="https://harry0703.github.io/mpt-assets/?video=05-zh-portrait-clean-energy.mp4"><img src="https://github.com/harry0703/mpt-assets/releases/download/assets/05-zh-portrait-clean-energy.jpg" width="180" alt="清洁能源的未来"></a><br><strong>清洁能源的未来</strong><br>中文 · 24 秒</td>
<td align="center" width="25%"><a href="https://harry0703.github.io/mpt-assets/?video=07-zh-portrait-space-exploration.mp4"><img src="https://github.com/harry0703/mpt-assets/releases/download/assets/07-zh-portrait-space-exploration.jpg" width="180" alt="为什么我们仍要探索太空"></a><br><strong>为什么我们仍要探索太空</strong><br>中文 · 27 秒</td>
<td align="center" width="25%"><a href="https://harry0703.github.io/mpt-assets/?video=17-zh-portrait-seed-journey.mp4"><img src="https://github.com/harry0703/mpt-assets/releases/download/assets/17-zh-portrait-seed-journey.jpg" width="180" alt="一粒种子的旅程"></a><br><strong>一粒种子的旅程</strong><br>中文 · 44 秒</td>
</tr>
</table>

### 横屏 16:9

<table width="100%">
<tr>
<td align="center" width="25%"><a href="https://harry0703.github.io/mpt-assets/?video=02-zh-landscape-deep-ocean.mp4"><img src="https://github.com/harry0703/mpt-assets/releases/download/assets/02-zh-landscape-deep-ocean.jpg" width="280" alt="深海里的微光"></a><br><strong>深海里的微光</strong><br>中文 · 23 秒</td>
<td align="center" width="25%"><a href="https://harry0703.github.io/mpt-assets/?video=04-zh-landscape-reading-power.mp4"><img src="https://github.com/harry0703/mpt-assets/releases/download/assets/04-zh-landscape-reading-power.jpg" width="280" alt="阅读如何塑造我们"></a><br><strong>阅读如何塑造我们</strong><br>中文 · 23 秒</td>
<td align="center" width="25%"><a href="https://harry0703.github.io/mpt-assets/?video=06-zh-landscape-pour-over-coffee.mp4"><img src="https://github.com/harry0703/mpt-assets/releases/download/assets/06-zh-landscape-pour-over-coffee.jpg" width="280" alt="一杯手冲咖啡的细节"></a><br><strong>一杯手冲咖啡的细节</strong><br>中文 · 23 秒</td>
<td align="center" width="25%"><a href="https://harry0703.github.io/mpt-assets/?video=08-zh-landscape-spring-journey.mp4"><img src="https://github.com/harry0703/mpt-assets/releases/download/assets/08-zh-landscape-spring-journey.jpg" width="280" alt="春天适合出发"></a><br><strong>春天适合出发</strong><br>中文 · 14 秒</td>
</tr>
</table>

## 配置要求 📦

- 建议系统：Windows 10、macOS 11.0 或更高版本，以及主流 Linux 发行版
- 本地部署需要 Python 3.11 或更高版本，推荐使用 Python 3.11
- GPU 不是必需项，但如果你希望本地转录、更快的视频处理或更顺畅的批量生成体验，建议使用带显存的独立显卡

| 项目 | 最低配置 | 推荐配置       | 理想配置       |
| --- | ---- | ---------- | ---------- |
| CPU | 4 核  | 6 到 8 核    | 8 核及以上     |
| RAM | 4 GB | 8 GB       | 16 GB 及以上  |
| GPU | 非必须  | 4 GB 显存及以上 | 8 GB 显存及以上 |

## 快速开始 🚀

### 使用 AI Agent 生成视频

如果你的 AI Agent 支持读取 Skill 文档并操作本地终端，可以直接发送下面这段话。Agent 会自动完成安装、配置和视频生成。目前支持 macOS 和 Windows。

```text
使用这个 Skill：https://raw.githubusercontent.com/temidayoxyz/surfercut/main/docs/skill/SKILL.md
帮我生成一个主题为“人工智能如何改变普通人的日常生活”的视频。
```

## 安装部署 📥

#### ① 克隆代码

```shell
git clone https://github.com/temidayoxyz/surfercut.git
```

#### ② 配置项目（可选）

首次启动时，项目会根据 `config.example.toml` 自动创建 `config.toml`。大模型 Provider、素材来源和相关 API Key 可以直接在 WebUI 的设置中配置。

### Docker 部署 🐳

```shell
cd surfercut
docker compose up
```

首次启动前，请将 `config.example.toml` 复制为 `config.toml`。打开浏览器访问 [http://127.0.0.1:8501](http://127.0.0.1:8501) 使用 WebUI，或访问 [http://127.0.0.1:8080/docs](http://127.0.0.1:8080/docs) 查看 API。

### 手动部署 📦

```shell
git clone https://github.com/temidayoxyz/surfercut.git
cd surfercut
uv python install 3.11
uv sync --frozen
```

也可以继续使用 `venv + pip`：

```shell
python3.11 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

#### 启动 WebUI 🌐

Windows：

```powershell
.\webui.bat
```

如需允许局域网访问，先执行 `set MPT_WEBUI_HOST=0.0.0.0`，再运行 `webui.bat`。

macOS 或 Linux：

```shell
sh webui.sh
```

局域网访问：

```shell
MPT_WEBUI_HOST=0.0.0.0 sh webui.sh
```

#### 启动 API 服务 🚀

```shell
uv run python main.py
```

#### 纯命令行方式 ⌨️

```shell
uv run python cli.py --video-subject "人工智能如何改变日常生活"
```

## 语音合成 🗣

默认使用免费的 **Edge TTS**，在 WebUI 中显示为 **Azure TTS V1**。项目同时支持 **Azure TTS V2**、**SiliconFlow TTS**、**Google Gemini TTS**、**小米 MiMo TTS**、**ElevenLabs TTS**、自托管 **Chatterbox TTS**，以及无配音模式。Edge TTS 音色可查看：[音色列表](./docs/voice-list.txt)。

## 字幕生成 📜

- **edge**：使用 TTS 时间戳生成字幕，速度快，不需要 GPU，默认使用该模式。
- **whisper**：使用本地 `faster-whisper` 转写音频。首次使用时需要下载模型。

在 `config.toml` 中修改 `subtitle_provider` 即可切换模式。手动下载的 Whisper 模型应放到 `.\surfercut\models\whisper-large-v3`。

## 背景音乐 🎵

用于视频的背景音乐位于项目的 `resource/songs` 目录。

## 字幕字体 🅰

用于视频字幕的渲染，位于项目的 `resource/fonts` 目录，你也可以放进去自己的字体。

## 反馈建议 📢

- 可以提交 [issue](https://github.com/temidayoxyz/surfercut/issues) 或者 [pull request](https://github.com/temidayoxyz/surfercut/pulls)。

## 许可证 📝

点击查看 [`LICENSE`](LICENSE) 文件。MoneyPrinterTurbo 的原始版权声明仍然保留。
