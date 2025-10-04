# API Configuration Templates

Jupyter notebooks for replicating data collection from all 8 models.

## Settings

- **Temperature**: 1.0 (where configurable)
- **Independent sessions** (no conversation history)
- **1-second spacing** between queries
- **Automatic retry logic** for rate limits

## Models

- **Claude-4 Opus (T)** used 16,000 token thinking budget
- **Gemini-2.5 Pro** used 16,000 token thinking budget
- **O3-Pro** used medium thinking effort
- **DeepSeek-R1** automatic thinking mode

## Installation

```bash
pip install openai anthropic google-generativeai
```