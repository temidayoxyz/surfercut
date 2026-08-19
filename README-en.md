<div align="center">

# SurferCut

### An AI short-video generation pipeline

Provide a video <b>topic</b> or <b>keyword</b>, and SurferCut will generate the script, match footage, create subtitles and background music, and produce an HD short video.

[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey.svg)](https://github.com/temidayoxyz/surfercut)
[![Python](https://img.shields.io/badge/python-3.11%2B-3776AB?logo=python&logoColor=white)](https://www.python.org/)

English | [简体中文](README.md) | [Issues](https://github.com/temidayoxyz/surfercut/issues)

</div>

SurferCut is a fork of [MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo). The generation engine is the same; the product name, repository, and WebUI are SurferCut.

## Screenshots 🖥️

<h4 align="center">WebUI</h4>

![](docs/webui-en.jpg)

<h4 align="center">API</h4>

![](docs/api.jpg)

## Features 🎯

- [x] Provides **AI Agent**, **WebUI**, **API**, and **CLI** workflows, with code organized by controller, service, and model responsibilities
- [x] Supports **AI-generated video scripts** and custom scripts
- [x] Supports various **high-definition video** sizes
  - [x] Portrait 9:16, `1080x1920`
  - [x] Landscape 16:9, `1920x1080`
- [x] Supports **batch video generation**, allowing the creation of multiple videos at once, then selecting the most satisfactory one
- [x] Supports setting the **duration of video clips**, facilitating adjustments to material switching frequency
- [x] Supports **multilingual video script** generation
- [x] Supports **Edge TTS**, **Azure Speech**, **SiliconFlow**, **Google Gemini**, **Xiaomi MiMo**, **ElevenLabs**, and **Chatterbox** speech synthesis with real-time previews
- [x] Supports **subtitle generation** with configurable fonts, position, color, size, outline, and background styles
- [x] Supports random or custom **background music** with adjustable volume
- [x] Supports your own **local assets** and free-to-use HD footage from **Pexels**, **Pixabay**, and **Coverr**
- [x] Supports leading model providers including **Kimi / Moonshot AI**, **OpenAI**, **Google Gemini**, **DeepSeek**, **Alibaba Cloud Qwen**, **Microsoft Azure OpenAI**, **ByteDance VolcEngine Ark**, **xAI Grok**, **MiniMax**, and **Xiaomi MiMo**, plus unified gateways, aggregators, and local runtimes such as **Cloudflare AI Gateway**, **Alibaba ModelScope**, **AIHubMix**, **AIML API**, **EvoLink**, **Ollama**, **OneAPI**, **LiteLLM**, **Groq**, and **Pollinations AI**
- [x] Supports one-click **cross-platform publishing** to **TikTok**, **Instagram**, and **YouTube Shorts** after video generation

## Gallery 🎬

All examples below were generated with this pipeline.

### Portrait 9:16

<table width="100%">
<tr>
<td align="center" width="25%"><a href="https://harry0703.github.io/mpt-assets/?video=03-zh-portrait-city-morning.mp4"><img src="https://github.com/harry0703/mpt-assets/releases/download/assets/03-zh-portrait-city-morning.jpg" width="180" alt="When the City Wakes"></a><br><strong>When the City Wakes</strong><br>Chinese · 14 sec</td>
<td align="center" width="25%"><a href="https://harry0703.github.io/mpt-assets/?video=05-zh-portrait-clean-energy.mp4"><img src="https://github.com/harry0703/mpt-assets/releases/download/assets/05-zh-portrait-clean-energy.jpg" width="180" alt="The Future of Clean Energy"></a><br><strong>The Future of Clean Energy</strong><br>Chinese · 24 sec</td>
<td align="center" width="25%"><a href="https://harry0703.github.io/mpt-assets/?video=07-zh-portrait-space-exploration.mp4"><img src="https://github.com/harry0703/mpt-assets/releases/download/assets/07-zh-portrait-space-exploration.jpg" width="180" alt="Why We Still Explore Space"></a><br><strong>Why We Still Explore Space</strong><br>Chinese · 27 sec</td>
<td align="center" width="25%"><a href="https://harry0703.github.io/mpt-assets/?video=17-zh-portrait-seed-journey.mp4"><img src="https://github.com/harry0703/mpt-assets/releases/download/assets/17-zh-portrait-seed-journey.jpg" width="180" alt="A Seed's Journey"></a><br><strong>A Seed's Journey</strong><br>Chinese · 44 sec</td>
</tr>
<tr>
<td align="center" width="25%"><a href="https://harry0703.github.io/mpt-assets/?video=09-en-portrait-future-robotics.mp4"><img src="https://github.com/harry0703/mpt-assets/releases/download/assets/09-en-portrait-future-robotics.jpg" width="180" alt="The Future of Everyday Robotics"></a><br><strong>The Future of Everyday Robotics</strong><br>English · 21 sec</td>
<td align="center" width="25%"><a href="https://harry0703.github.io/mpt-assets/?video=11-en-portrait-small-habits.mp4"><img src="https://github.com/harry0703/mpt-assets/releases/download/assets/11-en-portrait-small-habits.jpg" width="180" alt="Small Habits, Lasting Change"></a><br><strong>Small Habits, Lasting Change</strong><br>English · 19 sec</td>
<td align="center" width="25%"><a href="https://harry0703.github.io/mpt-assets/?video=13-en-portrait-creative-work.mp4"><img src="https://github.com/harry0703/mpt-assets/releases/download/assets/13-en-portrait-creative-work.jpg" width="180" alt="Making Space for Creative Work"></a><br><strong>Making Space for Creative Work</strong><br>English · 20 sec</td>
<td align="center" width="25%"><a href="https://harry0703.github.io/mpt-assets/?video=15-en-portrait-coffee-science.mp4"><img src="https://github.com/harry0703/mpt-assets/releases/download/assets/15-en-portrait-coffee-science.jpg" width="180" alt="The Science Inside Coffee"></a><br><strong>The Science Inside Coffee</strong><br>English · 23 sec</td>
</tr>
</table>

### Landscape 16:9

<table width="100%">
<tr>
<td align="center" width="25%"><a href="https://harry0703.github.io/mpt-assets/?video=02-zh-landscape-deep-ocean.mp4"><img src="https://github.com/harry0703/mpt-assets/releases/download/assets/02-zh-landscape-deep-ocean.jpg" width="280" alt="Light in the Deep Ocean"></a><br><strong>Light in the Deep Ocean</strong><br>Chinese · 23 sec</td>
<td align="center" width="25%"><a href="https://harry0703.github.io/mpt-assets/?video=04-zh-landscape-reading-power.mp4"><img src="https://github.com/harry0703/mpt-assets/releases/download/assets/04-zh-landscape-reading-power.jpg" width="280" alt="How Reading Shapes Us"></a><br><strong>How Reading Shapes Us</strong><br>Chinese · 23 sec</td>
<td align="center" width="25%"><a href="https://harry0703.github.io/mpt-assets/?video=06-zh-landscape-pour-over-coffee.mp4"><img src="https://github.com/harry0703/mpt-assets/releases/download/assets/06-zh-landscape-pour-over-coffee.jpg" width="280" alt="The Details of Pour-Over Coffee"></a><br><strong>The Details of Pour-Over Coffee</strong><br>Chinese · 23 sec</td>
<td align="center" width="25%"><a href="https://harry0703.github.io/mpt-assets/?video=08-zh-landscape-spring-journey.mp4"><img src="https://github.com/harry0703/mpt-assets/releases/download/assets/08-zh-landscape-spring-journey.jpg" width="280" alt="Spring Is Made for Travel"></a><br><strong>Spring Is Made for Travel</strong><br>Chinese · 14 sec</td>
</tr>
<tr>
<td align="center" width="25%"><a href="https://harry0703.github.io/mpt-assets/?video=10-en-landscape-ocean-conservation.mp4"><img src="https://github.com/harry0703/mpt-assets/releases/download/assets/10-en-landscape-ocean-conservation.jpg" width="280" alt="Why Ocean Conservation Matters"></a><br><strong>Why Ocean Conservation Matters</strong><br>English · 25 sec</td>
<td align="center" width="25%"><a href="https://harry0703.github.io/mpt-assets/?video=14-en-landscape-sustainable-cities.mp4"><img src="https://github.com/harry0703/mpt-assets/releases/download/assets/14-en-landscape-sustainable-cities.jpg" width="280" alt="Designing More Sustainable Cities"></a><br><strong>Designing More Sustainable Cities</strong><br>English · 27 sec</td>
<td align="center" width="25%"><a href="https://harry0703.github.io/mpt-assets/?video=16-en-landscape-mountain-perspective.mp4"><img src="https://github.com/harry0703/mpt-assets/releases/download/assets/16-en-landscape-mountain-perspective.jpg" width="280" alt="What Mountains Teach Us"></a><br><strong>What Mountains Teach Us</strong><br>English · 18 sec</td>
<td align="center" width="25%"><a href="https://harry0703.github.io/mpt-assets/?video=18-en-landscape-history-of-flight.mp4"><img src="https://github.com/harry0703/mpt-assets/releases/download/assets/18-en-landscape-history-of-flight.jpg" width="280" alt="A Brief History of Human Flight"></a><br><strong>A Brief History of Human Flight</strong><br>English · 59 sec</td>
</tr>
</table>

## System Requirements 📦

- Recommended platforms: Windows 10+, macOS 11+, or a mainstream Linux distribution
- Local deployment requires Python 3.11 or later; Python 3.11 is recommended
- A GPU is not required, but it is recommended if you want faster local transcription, faster video processing, or smoother batch generation

| Item | Minimum      | Recommended  | Optimal    |
| ---- | ------------ | ------------ | ---------- |
| CPU  | 4 cores      | 6 to 8 cores | 8+ cores   |
| RAM  | 4 GB         | 8 GB         | 16+ GB     |
| GPU  | Not required | 4+ GB VRAM   | 8+ GB VRAM |

- If you mainly rely on cloud LLMs, cloud TTS, and online material sources, CPU and RAM matter more than GPU
- If you use `faster-whisper`, batch generation, or heavier local processing, a GPU will improve throughput noticeably

## Quick Start 🚀

### Recommended Paths

- If you do not want to install or configure the project manually: generate videos with an AI Agent
- Windows users: run `webui.bat` after installing dependencies
- macOS / Linux users: use `uv` for the primary local setup path
- If you want a more isolated runtime: use Docker deployment

### Generate Videos with an AI Agent

If your AI Agent can read Skill documents and operate a local terminal, send it the prompt below. The Agent will install and configure SurferCut, generate the video, and return the video file path. It will ask only for required API keys that are not already configured. This workflow currently supports macOS and Windows.

```text
Use this Skill: https://raw.githubusercontent.com/temidayoxyz/surfercut/main/docs/skill/SKILL.md
Create a video with the topic "How AI is changing everyday life."
```

## Installation & Deployment 📥

### Prerequisites

- Local deployment requires Python 3.11 or later
- On Windows, avoid project paths containing non-ASCII characters, special characters, or spaces

#### ① Clone the Project

```shell
git clone https://github.com/temidayoxyz/surfercut.git
```

#### ② Configure the Project (Optional)

On first launch, the project creates `config.toml` from `config.example.toml`. You can configure the LLM provider, footage source, and related API keys directly in the WebUI settings.

### Docker Deployment 🐳

If you haven't installed Docker, please install it first https://www.docker.com/products/docker-desktop/

```shell
cd surfercut
docker compose up
```

> Before the first start, copy `config.example.toml` to `config.toml` so it can be mounted into the containers.
> `docker-compose.release.yml` builds the same local image and tags it as `ghcr.io/temidayoxyz/surfercut:latest`.

Open your browser and visit http://127.0.0.1:8501 for the WebUI, or http://127.0.0.1:8080/docs for the API.

### Manual Deployment 📦

```shell
git clone https://github.com/temidayoxyz/surfercut.git
cd surfercut
uv python install 3.11
uv sync --frozen
```

If you are not using `uv` yet, you can still use `venv + pip`.

```shell
python3.11 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

Notes:

- `pyproject.toml` is the primary dependency manifest.
- `uv.lock` pins the resolved environment, so `uv sync --frozen` is recommended by default.
- `requirements.txt` is kept only for legacy `pip`-based installation.

#### Launch the WebUI 🌐

Run these commands from the project root.

Windows:

```powershell
.\webui.bat
```

`webui.bat` prefers the project `.venv`. If no project Python is found but `uv` is installed, it falls back to `uv run streamlit`.
To allow other devices on your LAN to access the WebUI, run `set MPT_WEBUI_HOST=0.0.0.0` before running `webui.bat`.

macOS or Linux:

```shell
sh webui.sh
```

To allow access from other devices on your LAN:

```shell
MPT_WEBUI_HOST=0.0.0.0 sh webui.sh
```

#### Launch the API Service 🚀

```shell
uv run python main.py
```

#### Pure CLI Mode (No Browser) ⌨️

```shell
uv run python cli.py --video-subject "How AI is changing everyday life"
```

For the complete command reference, run:

```shell
uv run python cli.py --help
```

## Voice Synthesis 🗣

The default provider is the free **Edge TTS**, shown as **Azure TTS V1** in the WebUI. SurferCut also supports **Azure TTS V2**, **SiliconFlow TTS**, **Google Gemini TTS**, **Xiaomi MiMo TTS**, **ElevenLabs TTS**, self-hosted **Chatterbox TTS**, and a no-voice mode.

Select a provider and voice in the WebUI, then follow the on-screen instructions for any required credentials. Edge TTS does not require an API key. See the available Edge TTS voices in the [voice list](./docs/voice-list.txt).

## Subtitle Generation 📜

Two subtitle generation modes are available:

- **edge**: Uses TTS timestamps, runs quickly without a GPU, and is the default mode.
- **whisper**: Uses local `faster-whisper` transcription when a more accurate subtitle timeline is needed. The model is downloaded on first use.

Set `subtitle_provider` in `config.toml` to switch modes. Whisper uses the approximately 3 GB `large-v3` model by default. To use the smaller and faster, approximately 1.6 GB `large-v3-turbo` model:

```toml
[app]
subtitle_provider = "whisper"

[whisper]
model_size = "large-v3-turbo"
```

After extracting a manually downloaded Whisper model, place the entire directory in `.\surfercut\models`. The final path should be `.\surfercut\models\whisper-large-v3`.

## Background Music 🎵

Background music for videos is located in the project's `resource/songs` directory.

> The current project includes some default music from YouTube videos. If there are copyright issues, please delete them.

## Subtitle Fonts 🅰

Fonts for rendering video subtitles are located in the project's `resource/fonts` directory, and you can also add your own fonts.

## Common Questions 🤔

<details>
<summary>How do I publish to TikTok, Instagram, or YouTube Shorts?</summary>

Create an [Upload-Post](https://upload-post.com/) account and API key, then add the following settings under `[app]` in `config.toml`:

```toml
[app]
upload_post_enabled = true
upload_post_api_key = "your-api-key"
upload_post_username = "your-username"
upload_post_platforms = ["tiktok", "instagram", "youtube"]
upload_post_auto_upload = true
upload_post_youtube_privacy_status = "public"
```

Restart the app after saving. Generated videos will then be published automatically to the configured platforms. YouTube privacy can be set to `public`, `unlisted`, or `private`.

</details>

<details>
<summary>RuntimeError: No ffmpeg exe could be found</summary>

Normally, ffmpeg will be automatically downloaded and detected. If automatic download fails:

```
RuntimeError: No ffmpeg exe could be found.
Install ffmpeg on your system, or set the IMAGEIO_FFMPEG_EXE environment variable.
```

Download ffmpeg from https://www.gyan.dev/ffmpeg/builds/, unzip it, and set `ffmpeg_path` to your actual installation path.

```toml
[app]
ffmpeg_path = "C:\\Users\\you\\Downloads\\ffmpeg.exe"
```

</details>

<details>
<summary>OSError: [Errno 24] Too many open files</summary>

This issue is caused by the system's limit on the number of open files.

```shell
ulimit -n
ulimit -n 10240
```

</details>

## Feedback & Suggestions 📢

- Submit an [issue](https://github.com/temidayoxyz/surfercut/issues) or a [pull request](https://github.com/temidayoxyz/surfercut/pulls).

## License 📝

MIT. See [`LICENSE`](LICENSE). Original MoneyPrinterTurbo copyright is retained.
