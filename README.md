# 📽️ YouTube 中文视频自动摘要工具

本项目使用 Python 实现：通过 `pytube` 下载 YouTube 中文视频音频，使用 OpenAI 的 `whisper` 进行语音转文字，并调用 `GPT` 接口对内容进行智能摘要。

## ✨ 功能特色

- 支持中文视频
- Whisper 自动语音识别
- GPT 自动生成摘要
- 命令行快速运行

## 🚀 快速开始

### 安装依赖

```bash
pip install pytube openai git+https://github.com/openai/whisper.git
