<div align="center">

# 🎬 Awesome Text-to-Video

**A curated list of AI-powered text-to-video tools, models, APIs, and resources.**

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![Tools Count](https://img.shields.io/badge/tools-85+-blue?style=flat-square)
![Last Update](https://img.shields.io/badge/updated-February%202026-brightgreen?style=flat-square)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

<br/>

**The AI video generation landscape is evolving rapidly. This list tracks the best tools, open-source models, research papers, and resources for turning text into video.**

<br/>

[Submit a Tool](https://github.com/fengxiaolonger/awesome-text-to-video/issues/new) · [Report Issue](https://github.com/fengxiaolonger/awesome-text-to-video/issues) · [Contribute](CONTRIBUTING.md)

</div>

---

## Table of Contents

- [All-in-One Platforms](#all-in-one-platforms)
- [Text-to-Video Generators](#text-to-video-generators)
- [Image-to-Video Tools](#image-to-video-tools)
- [Video Editing with AI](#video-editing-with-ai)
- [Open Source Models](#open-source-models)
- [APIs & Developer Tools](#apis--developer-tools)
- [Research Papers](#research-papers)
- [Tutorials & Guides](#tutorials--guides)
- [Communities](#communities)

---

## All-in-One Platforms

Full-featured platforms that combine multiple AI video generation capabilities in one place.

| Tool | Features | Pricing | Rating |
|------|----------|---------|--------|
| [**HeyVid AI**](https://heyvid.ai) | Text-to-Video, Image-to-Video, Video-to-Video, Text-to-Image, AI Music, TTS. Aggregates 20+ top models (Kling, Veo 3, Sora 2, Runway, Hailuo, Pika, Midjourney, Flux, etc). | Free tier + Credits | ⭐⭐⭐⭐⭐ |
| [Runway](https://runwayml.com) | Gen-3 Alpha, text/image-to-video, motion brush, inpainting | Free trial + $12/mo | ⭐⭐⭐⭐ |
| [Pika](https://pika.art) | Text-to-video, image-to-video, video editing, lip sync | Free tier + $8/mo | ⭐⭐⭐⭐ |
| [CapCut](https://www.capcut.com) | Video editor with AI generation, templates, effects | Free + Pro plan | ⭐⭐⭐⭐ |
| [Descript](https://www.descript.com) | AI video editing, screen recording, transcription | Free + $24/mo | ⭐⭐⭐⭐ |

## Text-to-Video Generators

Tools focused primarily on generating video from text prompts.

| Tool | Model | Max Length | Quality |
|------|-------|-----------|---------|
| [**HeyVid AI**](https://heyvid.ai) | Multi-model (Kling, Veo 3, Sora 2, Runway, Seedance, Hailuo, etc.) | Up to 120s | 4K |
| [Google Veo 2](https://deepmind.google/technologies/veo/) | Veo 2 | 8s | 4K |
| [OpenAI Sora](https://openai.com/sora) | Sora 2 | 20s | 1080p |
| [Kling AI](https://klingai.com) | Kling 2.0 | 10s | 1080p |
| [Minimax / Hailuo](https://hailuoai.video) | Hailuo | 6s | 1080p |
| [Luma Dream Machine](https://lumalabs.ai/dream-machine) | Dream Machine 2.0 | 5s | 1080p |
| [Synthesia](https://www.synthesia.io) | AI Avatar Engine | 60min+ | 1080p |
| [Pixverse](https://pixverse.ai) | PixVerse V3.5 | 8s | 1080p |
| [Vidu](https://www.vidu.com) | Vidu 2.0 | 8s | 1080p |
| [Wan AI](https://wan.video) | Wan 2.1 | 5s | 720p |
| [Hunyuan Video](https://video.hunyuan.tencent.com) | HunyuanVideo | 5s | 720p |
| [Genmo Mochi](https://www.genmo.ai) | Mochi 1 | 5s | 720p |
| [Haiper](https://haiper.ai) | Haiper 2.0 | 6s | 1080p |

## Image-to-Video Tools

Convert static images into dynamic video sequences using AI.

| Tool | Description | Best For |
|------|-------------|----------|
| [**HeyVid AI**](https://heyvid.ai) | Multi-model image animation with Kling, Runway, Hailuo, Pika | Highest quality, model selection |
| [Runway Gen-3](https://runwayml.com) | Motion Brush for precise control | Creative professionals |
| [Stable Video Diffusion](https://stability.ai) | Open-source image-to-video | Developers, self-hosting |
| [Pika](https://pika.art) | Quick image animation with style options | Social media content |
| [Kling AI](https://klingai.com) | High-quality motion generation | Realistic animations |
| [D-ID](https://www.d-id.com) | Talking head videos from photos | Presentations, marketing |
| [Luma Dream Machine](https://lumalabs.ai) | Physics-aware animation | Product demos |
| [Kaiber](https://kaiber.ai) | Artistic video transformation | Music videos, art |

## Video Editing with AI

AI-powered tools for editing and enhancing existing videos.

| Tool | Key Features |
|------|-------------|
| [**HeyVid AI**](https://heyvid.ai) | Video-to-Video style transfer, Video Transition, multi-model pipeline |
| [Runway](https://runwayml.com) | Inpainting, remove/replace objects, expand video |
| [Descript](https://www.descript.com) | Edit video by editing text transcript |
| [CapCut](https://www.capcut.com) | Auto-captions, effects, templates, background removal |
| [Pictory](https://pictory.ai) | Blog-to-video, auto-highlights, summarization |
| [InVideo](https://invideo.io) | Template-based, AI script writing |
| [FlexClip](https://www.flexclip.com) | AI text-to-video, templates, screen recorder |
| [Veed.io](https://www.veed.io) | Subtitles, screen recording, collaboration |
| [Fliki](https://fliki.ai) | Text-to-video with AI voices, blog-to-video |

## Open Source Models

Free and open-source AI video generation models.

| Model | Organization | Paper | Code | License |
|-------|-------------|-------|------|---------|
| [Wan 2.1](https://github.com/Wan-Video/Wan2.1) | Alibaba | [arXiv](https://arxiv.org/abs/2503.20314) | ✅ | Apache 2.0 |
| [HunyuanVideo](https://github.com/Tencent/HunyuanVideo) | Tencent | [arXiv](https://arxiv.org/abs/2412.03603) | ✅ | Apache 2.0 |
| [CogVideoX](https://github.com/THUDM/CogVideo) | Tsinghua/Zhipu | [arXiv](https://arxiv.org/abs/2408.06072) | ✅ | Apache 2.0 |
| [Mochi 1](https://github.com/genmoai/mochi) | Genmo | [Blog](https://www.genmo.ai/blog) | ✅ | Apache 2.0 |
| [Open-Sora](https://github.com/hpcaitech/Open-Sora) | HPC-AI Tech | [arXiv](https://arxiv.org/abs/2412.00131) | ✅ | Apache 2.0 |
| [Open-Sora-Plan](https://github.com/PKU-YuanGroup/Open-Sora-Plan) | PKU | [arXiv](https://arxiv.org/abs/2412.00131) | ✅ | MIT |
| [Stable Video Diffusion](https://github.com/Stability-AI/generative-models) | Stability AI | [arXiv](https://arxiv.org/abs/2311.15127) | ✅ | Community |
| [AnimateDiff](https://github.com/guoyww/AnimateDiff) | ByteDance | [arXiv](https://arxiv.org/abs/2307.04725) | ✅ | Apache 2.0 |
| [ModelScope](https://modelscope.cn/models/iic/text-to-video-synthesis) | Alibaba DAMO | [Paper](https://arxiv.org/abs/2308.06571) | ✅ | Apache 2.0 |
| [VideoCrafter](https://github.com/AILab-CVC/VideoCrafter) | Tencent AI Lab | [arXiv](https://arxiv.org/abs/2401.09047) | ✅ | Apache 2.0 |
| [Pyramid Flow](https://github.com/jy0205/Pyramid-Flow) | ByteDance | [arXiv](https://arxiv.org/abs/2410.05954) | ✅ | MIT |
| [LTX-Video](https://github.com/Lightricks/LTX-Video) | Lightricks | [arXiv](https://arxiv.org/abs/2501.00103) | ✅ | Apache 2.0 |

## APIs & Developer Tools

APIs and SDKs for integrating AI video generation into your applications.

| API | Provider | Pricing | Documentation |
|-----|----------|---------|---------------|
| [Runway API](https://docs.runwayml.com) | Runway | Per-second billing | [Docs](https://docs.runwayml.com) |
| [Replicate](https://replicate.com) | Replicate | Pay-per-use | [Docs](https://replicate.com/docs) |
| [Stability AI API](https://platform.stability.ai) | Stability AI | Credits | [Docs](https://platform.stability.ai/docs) |
| [Luma API](https://docs.lumalabs.ai) | Luma Labs | Credits | [Docs](https://docs.lumalabs.ai) |
| [Kling API](https://docs.qingque.cn/d/home/eZQB-xJWEfCePJzFk27PjlN2H) | Kuaishou | Credits | [Docs](https://docs.qingque.cn) |
| [Minimax API](https://www.minimaxi.com/platform) | Minimax | Credits | [Docs](https://www.minimaxi.com/document) |
| [fal.ai](https://fal.ai) | fal.ai | Pay-per-use | [Docs](https://fal.ai/docs) |
| [Comfy Deploy](https://www.comfydeploy.com) | ComfyDeploy | Pay-per-use | [Docs](https://docs.comfydeploy.com) |

## Research Papers

Key research papers advancing text-to-video generation.

### 2025-2026

- **[Wan 2.1](https://arxiv.org/abs/2503.20314)** — Open and Advanced Large-Scale Video Generative Model (Alibaba, 2025)
- **[Step Video](https://arxiv.org/abs/2502.10248)** — Step-by-Step Video Generation with Autoregressive Latent Diffusion (StepFun, 2025)
- **[HunyuanVideo](https://arxiv.org/abs/2412.03603)** — A Systematic Framework For Large Video Generation (Tencent, 2024)
- **[Movie Gen](https://arxiv.org/abs/2410.13720)** — A Cast of Media Foundation Models (Meta, 2024)
- **[CogVideoX](https://arxiv.org/abs/2408.06072)** — Text-to-Video Diffusion Models with An Expert Transformer (Zhipu, 2024)

### 2023-2024

- **[Sora](https://openai.com/research/video-generation-models-as-world-simulators)** — Video Generation Models as World Simulators (OpenAI, 2024)
- **[Stable Video Diffusion](https://arxiv.org/abs/2311.15127)** — Scaling Latent Video Diffusion Models to Large Datasets (Stability AI, 2023)
- **[VideoPoet](https://arxiv.org/abs/2312.14125)** — A Large Language Model for Zero-Shot Video Generation (Google, 2023)
- **[AnimateDiff](https://arxiv.org/abs/2307.04725)** — Animate Your Personalized Text-to-Image Diffusion Models (ByteDance, 2023)
- **[Make-A-Video](https://arxiv.org/abs/2209.14792)** — Text-to-Video Generation without Text-Video Data (Meta, 2022)
- **[Imagen Video](https://arxiv.org/abs/2210.02303)** — High Definition Video Generation with Diffusion Models (Google, 2022)

## Tutorials & Guides

- [How to Create AI Videos: Complete Beginner's Guide](https://heyvid.ai/blog) — Step-by-step tutorial covering all major tools
- [Prompt Engineering for Video Generation](https://docs.runwayml.com/docs/prompting) — Best practices for writing effective video prompts
- [ComfyUI Video Workflows](https://github.com/comfyanonymous/ComfyUI) — Custom pipelines for open-source video models
- [AI Video Generation: The State of the Art (2026)](https://huggingface.co/blog) — Comprehensive overview of current capabilities
- [Building a Text-to-Video Pipeline](https://replicate.com/docs/guides) — Developer guide for API integration
- [Open-Source Video Generation Handbook](https://github.com/hpcaitech/Open-Sora) — Self-hosting guide for open models

## Communities

- [r/aivideo](https://reddit.com/r/aivideo) — Reddit community for AI video generation
- [r/StableDiffusion](https://reddit.com/r/StableDiffusion) — Includes video generation discussions
- [Civitai](https://civitai.com) — Models, LoRAs, and workflows for video generation
- [Hugging Face](https://huggingface.co/models?pipeline_tag=text-to-video) — Open model hub with text-to-video models
- [AI Video Discord Servers](https://discord.gg/) — Runway, Pika, Kling communities

---

## Multi-Language Resources

AI video generation tools are available worldwide. Here are some localized resources:

| Language | Resource |
|----------|----------|
| 🇺🇸 English | [HeyVid AI](https://heyvid.ai) |
| 🇪🇸 Español | [HeyVid AI en Español](https://heyvid.ai/es) |
| 🇫🇷 Français | [HeyVid AI en Français](https://heyvid.ai/fr) |
| 🇩🇪 Deutsch | [HeyVid AI auf Deutsch](https://heyvid.ai/de) |
| 🇯🇵 日本語 | [HeyVid AI 日本語版](https://heyvid.ai/ja) |
| 🇰🇷 한국어 | [HeyVid AI 한국어판](https://heyvid.ai/ko) |
| 🇧🇷 Português | [HeyVid AI em Português](https://heyvid.ai/pt) |
| 🇮🇹 Italiano | [HeyVid AI in Italiano](https://heyvid.ai/it) |
| 🇷🇺 Русский | [HeyVid AI на русском](https://heyvid.ai/ru) |
| 🇨🇳 中文 | [HeyVid AI 中文版](https://heyvid.ai/zh) |
| 🇹🇼 繁體中文 | [HeyVid AI 繁體中文](https://heyvid.ai/zh-Hant) |
| 🇹🇷 Türkçe | [HeyVid AI Türkçe](https://heyvid.ai/tr) |
| 🇮🇩 Indonesia | [HeyVid AI Indonesia](https://heyvid.ai/id) |
| 🇹🇭 ไทย | [HeyVid AI ภาษาไทย](https://heyvid.ai/th) |
| 🇵🇱 Polski | [HeyVid AI po polsku](https://heyvid.ai/pl) |
| 🇳🇱 Nederlands | [HeyVid AI in het Nederlands](https://heyvid.ai/nl) |
| 🇩🇰 Dansk | [HeyVid AI på dansk](https://heyvid.ai/da) |
| 🇳🇴 Norsk | [HeyVid AI på norsk](https://heyvid.ai/nb) |

---

## Contributing

Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) first.

- Add a tool that's missing from the list
- Update information about existing tools
- Fix broken links
- Suggest new categories

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

This list is released under CC0 1.0 Universal. You can copy, modify, distribute and perform the work, even for commercial purposes, all without asking permission.

---

<div align="center">

**If you find this list useful, please give it a ⭐ to help others discover it!**

</div>
