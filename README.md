<div align="center">

# 🎬 Awesome Text-to-Video

**A comprehensive, community-curated collection of AI video generation tools, prompts, workflows, open-source models, and learning resources.**

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![Entries](https://img.shields.io/badge/entries-200+-blue?style=flat-square)
![Last Update](https://img.shields.io/badge/updated-February%202026-brightgreen?style=flat-square)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

<br/>

The AI video generation space moves fast. New models drop weekly, pricing changes overnight, and yesterday's state-of-the-art becomes today's baseline. This list exists to help creators, developers, and researchers navigate the landscape without drowning in hype.

Everything here is verified by contributors who actually use these tools.

<br/>

[Submit a Resource](https://github.com/fengxiaolonger/awesome-text-to-video/issues/new) · [Report Issue](https://github.com/fengxiaolonger/awesome-text-to-video/issues) · [Contribute](CONTRIBUTING.md)

</div>

---

## Table of Contents

| | | |
|---|---|---|
| [Multi-Model Platforms](#multi-model-platforms) (8) | [Text-to-Video Tools](#text-to-video-tools) (22) | [Image-to-Video Tools](#image-to-video-tools) (18) |
| [Video Editing & Post-Production](#video-editing--post-production) (15) | [AI Avatar & Talking Head](#ai-avatar--talking-head) (12) | [Music Video & Audio-Reactive](#music-video--audio-reactive) (8) |
| [Open Source Models](#open-source-models) (20) | [ComfyUI Workflows](#comfyui-workflows) (15) | [APIs & SDKs](#apis--sdks) (14) |
| [Prompt Engineering](#prompt-engineering) (25) | [Benchmark & Comparisons](#benchmark--comparisons) (6) | [Research Papers](#research-papers) (30) |
| [Tutorials & Courses](#tutorials--courses) (18) | [Communities & Forums](#communities--forums) (12) | [Multi-Language Resources](#multi-language-resources) (18) |

---

## Multi-Model Platforms

Platforms that aggregate multiple AI video models into a single interface, so you can compare outputs and pick the best result without juggling accounts.

- [HeyVid AI](https://heyvid.ai) — Aggregates 20+ models (Kling, Veo 3, Sora 2, Runway, Seedance, Hailuo, Pika, PixVerse, Vidu, Luma, Wan, Hunyuan, Midjourney, Flux, GPT-4o, DALL-E, Recraft, Ideogram, SD, Qwen). Supports text-to-video, image-to-video, video-to-video, text-to-image, TTS, and AI music. Free tier available. [18 languages supported](https://heyvid.ai).
- [Replicate](https://replicate.com) — Run open-source models via API. Hosts Wan 2.1, CogVideoX, Stable Video Diffusion, AnimateDiff, LTX-Video, and 100+ video models. Pay-per-second billing.
- [fal.ai](https://fal.ai) — Fast inference platform for generative models. Supports Kling, Minimax, Wan, LTX-Video, Hunyuan with optimized GPU routing. Developer-focused.
- [Together AI](https://www.together.ai) — Serverless and dedicated endpoints for open-source video models. Good for batch processing and fine-tuning workflows.
- [Novita AI](https://novita.ai) — Multi-model API platform with video generation, image generation, and LLM inference. Supports Wan 2.1, HunyuanVideo, AnimateDiff.
- [ComfyDeploy](https://www.comfydeploy.com) — Deploy ComfyUI workflows as APIs. Turn any custom video generation pipeline into a production endpoint.
- [Segmind](https://www.segmind.com) — Serverless APIs for generative AI. Supports multiple video models with competitive pricing and workflow chaining.
- [Modelslab](https://modelslab.com) — API access to video generation models including Stable Video Diffusion, AnimateDiff, and custom fine-tuned models.

## Text-to-Video Tools

Generate video directly from text prompts. Quality, length, and style vary significantly between tools.

### Frontier Models (Best Quality)

- [Google Veo 2](https://deepmind.google/technologies/veo/) — Google's flagship. 4K output, up to 8s, strong physical understanding. Available via Google AI Studio and Vertex AI. Currently the best at complex camera movements.
- [OpenAI Sora 2](https://openai.com/sora) — Up to 20s at 1080p. Strong narrative coherence across frames. Available to ChatGPT Plus/Pro subscribers. Storyboard mode for multi-shot sequences.
- [Kling 2.0](https://klingai.com) — Kuaishou's model. Up to 10s, 1080p. Excellent at human motion and facial expressions. Available globally via web and API.
- [Runway Gen-3 Alpha](https://runwayml.com) — 10s clips with Motion Brush for fine-grained control. Strong creative community. $12/mo starter plan.
- [Minimax / Hailuo](https://hailuoai.video) — 6s at 1080p. Known for cinematic quality and good text rendering. Free tier generous for testing.
- [Luma Dream Machine 2.0](https://lumalabs.ai/dream-machine) — 5s clips. Strong at 3D understanding and object permanence. Fast generation times (~30s per clip).
- [Pika 2.0](https://pika.art) — Scene ingredients system for precise control. Lip sync, sound effects generation. Good balance of quality and usability.

### Mid-Range Tools

- [PixVerse V3.5](https://pixverse.ai) — 8s at 1080p. Good motion quality. Specializes in anime/stylized content. Free daily credits.
- [Vidu 2.0](https://www.vidu.com) — Shengshu Technology. 8s at 1080p. Strong at Chinese-style aesthetics. Multi-subject reference support.
- [Seedance](https://seedance.ai) — ByteDance's latest. Character-consistent generation with dance/motion specialization.
- [Wan 2.1](https://wan.video) — Alibaba's open+commercial model. 5s at 720p for free tier. Full model weights available for self-hosting.
- [Genmo Mochi](https://www.genmo.ai) — Open-source backbone, 5s at 720p. Good for experimentation and fine-tuning. Free tier available.
- [Haiper 2.0](https://haiper.ai) — 6s at 1080p. Strong at stylized content. Founded by ex-Google DeepMind researchers.
- [Hunyuan Video](https://video.hunyuan.tencent.com) — Tencent's model. Open-source weights available. Good Chinese text rendering.
- [Jimeng AI](https://jimeng.jianying.com) — ByteDance's creative platform. Text-to-video with strong template system. Primarily Chinese market.

### Specialized Tools

- [Fliki](https://fliki.ai) — Blog-to-video and script-to-video with 2000+ AI voices. Best for content marketing and social media. $28/mo.
- [Pictory](https://pictory.ai) — Long-form video from scripts/articles. Auto-highlights and summarization. Best for repurposing written content.
- [InVideo](https://invideo.io) — Template-based with AI script writing. 5000+ templates. Good for marketing videos and ads.
- [Synthesia](https://www.synthesia.io) — AI avatar-based video generation. 230+ avatars, 140+ languages. Enterprise-focused, best for training/corporate videos. $22/mo.
- [Steve.AI](https://steve.ai) — Script to animated video. Patent-pending AI technology. Good for explainer videos and presentations.

## Image-to-Video Tools

Animate static images. Quality depends heavily on the source image and the model's motion understanding.

### Best Overall

- [HeyVid AI](https://heyvid.ai) — Multi-model image-to-video with Kling, Runway, Hailuo, Pika, Luma in one interface. Compare outputs from different models side-by-side. [Try free](https://heyvid.ai).
- [Runway Gen-3 Alpha](https://runwayml.com) — Motion Brush lets you paint motion onto specific regions. Best for precise creative control.
- [Kling 2.0](https://klingai.com) — Exceptional at human motion from portraits. Natural cloth physics and hair movement.
- [Stable Video Diffusion](https://stability.ai) — Open-source. Self-hostable. 4s at 576×1024. Good baseline for custom pipelines.

### Character Animation

- [D-ID](https://www.d-id.com) — Talking head videos from a single photo. Real-time avatar streaming. API available. Best for customer-facing video.
- [HeyGen](https://www.heygen.com) — AI spokesperson videos. 300+ voices, 40+ languages. Custom avatar training from 2min footage.
- [Hedra](https://www.hedra.com) — Character-1 model for expressive talking heads. Good lip sync from audio.
- [LivePortrait](https://github.com/KwaiVGI/LivePortrait) — Open-source portrait animation from Kuaishou. Stitching and retargeting pipeline. Self-hostable.

### Specialized Animation

- [Luma Dream Machine](https://lumalabs.ai) — Strong at animating product shots and 3D objects. Physics-aware motion.
- [Pika](https://pika.art) — Modify + Animate for targeted image changes before animation.
- [PixVerse](https://pixverse.ai) — Good at anime-style animation. Character reference for consistent style.
- [Kaiber](https://kaiber.ai) — Artistic transformations. Popular for music videos and abstract art animation. $5/mo.
- [Viggle](https://viggle.ai) — Controllable character animation. Mix motion with character images.
- [Kling Motion Brush](https://klingai.com) — Fine-grained motion control by brushing areas you want to animate.
- [DomoAI](https://www.domoai.app) — Style transfer animation (cartoon, anime, 3D, pixel art). Discord-based interface.
- [ToonCrafter](https://github.com/ToonCrafter/ToonCrafter) — Open-source cartoon interpolation. Generate in-between frames for hand-drawn animation.

## Video Editing & Post-Production

AI tools for editing, enhancing, and transforming existing video footage.

### All-in-One Editors

- [Runway](https://runwayml.com) — Gen-3 inpainting, remove/replace objects, expand video canvas, color grade. The creative professional's toolkit.
- [Descript](https://www.descript.com) — Edit video by editing its text transcript. Remove filler words automatically. AI green screen. $24/mo.
- [CapCut](https://www.capcut.com) — Auto-captions, background removal, effects library. Free with Pro features. Best for short-form social content.
- [Veed.io](https://www.veed.io) — Browser-based editor. Auto-subtitles in 100+ languages. Collaboration features. Good for teams.
- [FlexClip](https://www.flexclip.com) — Template-driven creation with AI tools. Text-to-video, screen recorder. $9.99/mo.

### Enhancement & Upscaling

- [Topaz Video AI](https://www.topazlabs.com/topaz-video-ai) — Industry-standard upscaling (up to 16K), deinterlacing, stabilization, frame interpolation. Desktop app, one-time purchase.
- [HitPaw Video Enhancer](https://www.hitpaw.com/video-enhancer.html) — AI upscaling and denoising. Face enhancement model for old footage restoration.
- [CapCut Video Upscaler](https://www.capcut.com) — Free browser-based upscaling. Good enough for social media content.

### Subtitles & Captions

- [Captions](https://www.captions.ai) — AI-powered captions with animated styles. Trending caption templates for social media.
- [Submagic](https://www.submagic.co) — Auto-captions with emoji integration. Batch processing for multiple videos.
- [Opus Clip](https://www.opus.pro) — AI-powered long-to-short video repurposing. Auto-selects viral moments and adds captions.

### Background & Object Removal

- [Runway Inpainting](https://runwayml.com) — Remove objects and fill with AI-generated content. Frame-by-frame consistency.
- [ProPainter](https://github.com/sczhou/ProPainter) — Open-source video inpainting. Flow-guided propagation for temporal consistency. Self-hostable.

## AI Avatar & Talking Head

Generate presenter-style videos with AI-generated or cloned human avatars.

- [Synthesia](https://www.synthesia.io) — 230+ stock avatars, custom avatar creation, 140+ languages. Enterprise API. SOC 2 compliant. The market leader.
- [HeyGen](https://www.heygen.com) — Instant avatar from 2min video. Real-time streaming avatar. Multi-scene storyboard.
- [D-ID](https://www.d-id.com) — Creative Reality Studio. Real-time API for conversational avatars. Used by customer service platforms.
- [Colossyan](https://www.colossyan.com) — Workplace learning focused. Auto-translate videos into 70+ languages with lip sync.
- [Elai.io](https://elai.io) — 80+ avatars. PowerPoint to video conversion. Collaboration features for teams.
- [DeepBrain AI](https://www.deepbrain.io) — AI Studios platform. Real-time conversation with AI avatars. Kiosk deployment options.
- [Hour One](https://hourone.ai) — Virtual human video creation. Focus on enterprise communications and L&D.
- [Vidnoz](https://www.vidnoz.com) — 1000+ avatars, 140+ languages. Free tier with daily credits. Template library.
- [Renderforest](https://www.renderforest.com) — Video maker with AI avatars, templates, and branding tools. All-in-one creative suite.
- [VEED AI Avatars](https://www.veed.io) — Browser-based avatar creation. Integrate with VEED's editing suite.
- [Tavus](https://www.tavus.io) — Personalized video at scale. Variable insertion for 1:1 outreach campaigns.
- [Rephrase.ai](https://www.rephrase.ai) — Text-to-video API for personalized marketing. Dynamic video generation.

## Music Video & Audio-Reactive

Tools that generate or sync video to music and audio.

- [Kaiber](https://kaiber.ai) — Upload audio, get AI-generated music video. Multiple style options (2D, 3D, anime). Used by major artists. $5/mo.
- [Neural Frames](https://www.neuralframes.com) — AI music video generator. Stable Diffusion + audio-reactive motion. Prompt-per-beat control.
- [Deforum](https://deforum.github.io) — Open-source audio-reactive Stable Diffusion animation. ComfyUI and A1111 integrations.
- [HeyVid AI Music](https://heyvid.ai) — AI music generation (Suno integration) + video creation in one platform. Create soundtrack and visuals together.
- [Doodly](https://www.doodly.com) — Whiteboard animation videos. Sync drawings to voiceover/music.
- [Vizzy](https://vizzy.io) — Real-time music visualization. Live performance visuals from audio input.
- [Rotor Videos](https://rotorvideos.com) — Automated music video creation from your tracks. Beat-synced editing.
- [Mootion](https://mootion.com) — AI dance and character animation from audio. Text-to-motion generation.

## Open Source Models

Self-hostable models with publicly available weights. Sorted by release date (newest first).

### 2025-2026

- [Wan 2.1](https://github.com/Wan-Video/Wan2.1) — **Alibaba** — T2V and I2V, 480p-720p. 1.3B and 14B parameter versions. Apache 2.0. Currently the best open-source option for quality/accessibility balance. [Paper](https://arxiv.org/abs/2503.20314)
- [HunyuanVideo](https://github.com/Tencent/HunyuanVideo) — **Tencent** — 13B parameters, 720p. Full attention mechanism. Strong temporal consistency. Apache 2.0. [Paper](https://arxiv.org/abs/2412.03603)
- [LTX-Video](https://github.com/Lightricks/LTX-Video) — **Lightricks** — Real-time generation (faster than playback on H100). Lightweight architecture. Apache 2.0. [Paper](https://arxiv.org/abs/2501.00103)
- [CogVideoX](https://github.com/THUDM/CogVideo) — **Tsinghua/Zhipu** — 2B and 5B versions. 6s at 480p. Expert Transformer architecture. Apache 2.0. [Paper](https://arxiv.org/abs/2408.06072)
- [Mochi 1](https://github.com/genmoai/mochi) — **Genmo** — Asymmetric diffusion transformer. Good motion quality. Apache 2.0. [Blog](https://www.genmo.ai/blog)
- [Pyramid Flow](https://github.com/jy0205/Pyramid-Flow) — **ByteDance** — Multi-resolution generation with pyramid architecture. 10s at 768p. MIT. [Paper](https://arxiv.org/abs/2410.05954)

### 2024

- [Open-Sora](https://github.com/hpcaitech/Open-Sora) — **HPC-AI Tech** — Community reproduction of Sora-like architecture. Up to 16s at 720p. Apache 2.0. Active development.
- [Open-Sora-Plan](https://github.com/PKU-YuanGroup/Open-Sora-Plan) — **PKU** — Alternative open implementation. Focus on efficient training. MIT license.
- [Stable Video Diffusion](https://github.com/Stability-AI/generative-models) — **Stability AI** — The original open I2V model. 4s at 576×1024. Foundation for many community models.
- [AnimateDiff](https://github.com/guoyww/AnimateDiff) — **ByteDance** — Motion module plugin for Stable Diffusion. Works with existing SD checkpoints and LoRAs. Apache 2.0. [Paper](https://arxiv.org/abs/2307.04725)
- [VideoCrafter2](https://github.com/AILab-CVC/VideoCrafter) — **Tencent AI Lab** — High-quality T2V with DiT backbone. 2s at 320×512. [Paper](https://arxiv.org/abs/2401.09047)
- [ModelScope T2V](https://modelscope.cn/models/iic/text-to-video-synthesis) — **Alibaba DAMO** — One of the first open T2V models. 2s at 256×256. Historical significance.

### Utilities & Frameworks

- [ComfyUI](https://github.com/comfyanonymous/ComfyUI) — Node-based workflow editor. Supports all major open video models. The Swiss Army knife of AI video.
- [A1111 WebUI](https://github.com/AUTOMATIC1111/stable-diffusion-webui) — With AnimateDiff extension for video generation.
- [Diffusers](https://github.com/huggingface/diffusers) — Hugging Face library. Python API for all major video models. `pip install diffusers`.
- [LivePortrait](https://github.com/KwaiVGI/LivePortrait) — **Kuaishou** — Efficient portrait animation. Stitching and retargeting.
- [ToonCrafter](https://github.com/ToonCrafter/ToonCrafter) — Cartoon video interpolation. Generate in-between frames.
- [ProPainter](https://github.com/sczhou/ProPainter) — Video inpainting with flow-guided propagation. Object removal.
- [FILM](https://github.com/google-research/frame-interpolation) — **Google** — Frame interpolation for smooth slow-motion. Production quality.
- [RIFE](https://github.com/hzwer/RIFE) — Real-time intermediate flow estimation. Fast frame interpolation.

## ComfyUI Workflows

Ready-to-use ComfyUI workflow files (.json) for video generation pipelines.

- [ComfyUI-WanVideoWrapper](https://github.com/kijai/ComfyUI-WanVideoWrapper) — Wan 2.1 T2V and I2V in ComfyUI. LoRA support, controlnet integration.
- [ComfyUI-HunyuanVideoWrapper](https://github.com/kijai/ComfyUI-HunyuanVideoWrapper) — HunyuanVideo with memory optimization. Supports long video generation.
- [ComfyUI-AnimateDiff-Evolved](https://github.com/Kosinkadink/ComfyUI-AnimateDiff-Evolved) — Advanced AnimateDiff integration. Motion LoRAs, camera controls, prompt travel.
- [ComfyUI-VideoHelperSuite](https://github.com/Kosinkadink/ComfyUI-VideoHelperSuite) — Load, combine, split, and export videos. Essential utility nodes.
- [ComfyUI-Frame-Interpolation](https://github.com/Fannovel16/ComfyUI-Frame-Interpolation) — FILM and RIFE nodes for smooth slow-motion and frame interpolation.
- [ComfyUI-KJNodes](https://github.com/kijai/ComfyUI-KJNodes) — Utility nodes for batch processing, scheduling, and advanced workflows.
- [ComfyUI-Advanced-ControlNet](https://github.com/Kosinkadink/ComfyUI-Advanced-ControlNet) — ControlNet integration for guided video generation. Depth, pose, edge control.
- [ComfyUI-LivePortraitKJ](https://github.com/kijai/ComfyUI-LivePortraitKJ) — LivePortrait in ComfyUI. Portrait animation from reference image + driving video.
- [ComfyUI-CogVideoXWrapper](https://github.com/kijai/ComfyUI-CogVideoXWrapper) — CogVideoX T2V and I2V. LoRA fine-tuning support.
- [ComfyUI-LTXVideo](https://github.com/Lightricks/ComfyUI-LTXVideo) — Official LTX-Video nodes. Fast generation with quality presets.
- [comfyui-reactor-node](https://github.com/Gourieff/comfyui-reactor-node) — Face swap for video generation. Consistent character faces across frames.
- [ComfyUI-IP-Adapter](https://github.com/cubiq/ComfyUI_IPAdapter_plus) — Image prompt adapter for style and character consistency in video.
- [Steerable Motion](https://github.com/banodoco/Steerable-Motion) — Controlled motion generation. Camera movement and subject motion presets.
- [ComfyUI-depth-fm](https://github.com/kijai/ComfyUI-depth-fm) — Depth estimation for video. Use depth maps to guide generation.
- [ComfyUI Workflows Collection](https://openart.ai/workflows/all?category=video) — Community-shared workflows on OpenArt. Hundreds of ready-to-use pipelines.

## APIs & SDKs

Developer tools for integrating AI video generation into applications.

### Commercial APIs

- [Runway API](https://docs.runwayml.com) — Gen-3 Alpha T2V and I2V. Per-second billing. REST API with webhooks.
- [Luma API](https://docs.lumalabs.ai) — Dream Machine via API. Fast generation, competitive pricing.
- [Kling API](https://docs.qingque.cn) — Kling 2.0 via Kuaishou's platform. Rate-limited free tier.
- [Minimax API](https://www.minimaxi.com/platform) — Hailuo video generation API. Good documentation.
- [Stability AI API](https://platform.stability.ai) — Stable Video Diffusion and image models. Credits-based.
- [D-ID API](https://docs.d-id.com) — Talking head generation API. Real-time streaming support.
- [HeyGen API](https://docs.heygen.com) — Avatar video generation. Webhook callbacks for async processing.
- [Synthesia API](https://docs.synthesia.io) — Enterprise avatar video API. Custom avatar support.

### Open-Source Hosting

- [Replicate](https://replicate.com) — One-line API for 100+ open video models. `replicate.run("wan-ai/wan2.1-t2v-14b")`.
- [fal.ai](https://fal.ai) — Optimized inference with queue management. Fast cold starts.
- [Together AI](https://www.together.ai) — Dedicated GPU instances for video models. Batch processing support.
- [Modal](https://modal.com) — Serverless GPU compute. Define video pipelines in Python, deploy instantly.
- [Banana](https://www.banana.dev) — GPU inference as a service. Deploy custom video models.
- [Baseten](https://www.baseten.co) — Model serving platform. Auto-scaling for video generation workloads.

## Prompt Engineering

Templates and techniques for getting better results from AI video generators.

### Prompt Structure

The best video prompts follow a consistent structure:

```
[Camera movement], [Subject description], [Action/Motion], [Setting/Environment], [Lighting], [Style/Mood], [Technical specs]
```

### Camera Movement Prompts

```
"Slow dolly zoom into..." — Creates Vertigo/Hitchcock effect
"Aerial drone shot sweeping over..." — Establishing shots
"Handheld tracking shot following..." — Documentary feel
"Smooth crane shot rising from...to reveal..." — Cinematic reveal
"Static locked-off wide shot of..." — Stable composition
"POV walking through..." — Immersive first-person
"360-degree orbit around..." — Product/character showcase
"Whip pan from...to..." — Fast transitions
"Slow push-in on..." — Building tension
"Pull-back reveal showing..." — Surprise/scale reveal
```

### Style Modifiers

```
"cinematic, 35mm film grain, shallow depth of field" — Film look
"anime style, cel-shaded, vibrant colors" — Anime
"photorealistic, 8K, hyperdetailed" — Maximum realism
"watercolor painting coming to life" — Artistic
"vintage 1970s home video, VHS artifacts" — Retro
"neon-lit cyberpunk city, rain reflections" — Sci-fi
"stop-motion claymation, tactile textures" — Animation
"black and white, high contrast, film noir" — Noir
"miniature tilt-shift, toy-like" — Miniature
"long exposure light trails, time-lapse" — Abstract motion
```

### Effective Prompt Examples

**Cinematic Nature:**
```
Slow aerial drone shot descending through morning mist over an ancient redwood forest,
sunbeams piercing through the canopy, a deer looks up startled then bounds away,
golden hour lighting, shallow depth of field, shot on ARRI Alexa, cinematic color grading
```

**Product Showcase:**
```
Smooth 360-degree orbit around a luxury watch on a black marble surface,
dramatic rim lighting revealing metallic textures, subtle caustic reflections,
macro lens detail on the dial, studio lighting, commercial photography style
```

**Character Action:**
```
Tracking shot following a samurai walking through a bamboo forest in heavy rain,
water droplets in slow motion off the sword, atmospheric fog, backlit silhouette,
Akira Kurosawa style, desaturated with selective red accents, 24fps cinematic
```

**Abstract/Artistic:**
```
Ink drops falling into clear water in extreme slow motion, blooming into fractal patterns,
morphing from jellyfish shapes into galaxies, deep blue and gold color palette,
macro photography, shallow depth of field, meditative and ethereal mood
```

**Urban/Street:**
```
Hyperlapse through Tokyo streets at night, neon signs reflected in rain puddles,
crowds of people in motion blur, camera weaving through narrow alleyways,
emerging into the bright lights of Shibuya crossing, cyberpunk atmosphere
```

### Model-Specific Tips

| Model | Best For | Tips |
|-------|----------|------|
| Kling 2.0 | Human motion, faces | Be specific about expressions and gestures |
| Veo 2 | Complex scenes, physics | Describe physical interactions in detail |
| Sora 2 | Narrative sequences | Use temporal language ("first...then...finally") |
| Runway Gen-3 | Creative/artistic | Lean into style descriptions and lighting |
| Hailuo | Cinematic quality | Reference specific film styles and directors |
| Pika | Quick iterations | Keep prompts shorter and more focused |
| Wan 2.1 | Open-source base | Detailed scene descriptions work best |

### Negative Prompts

Common negative prompts to improve quality:

```
"blurry, distorted, deformed, low quality, pixelated, watermark, text overlay,
extra fingers, mutated hands, poorly drawn face, out of frame, duplicate,
morphing artifacts, temporal flickering, inconsistent lighting"
```

## Benchmark & Comparisons

Systematic comparisons of video generation models.

- [Artificial Analysis Video Arena](https://artificialanalysis.ai/text-to-video/arena) — Elo-based ranking from blind human comparisons. Most trusted independent benchmark.
- [VBench](https://github.com/Vchitect/VBench) — Comprehensive benchmark suite. 16 dimensions including subject consistency, motion smoothness, aesthetic quality. [Paper](https://arxiv.org/abs/2311.17982)
- [EvalCrafter](https://github.com/EvalCrafter/EvalCrafter) — Multi-aspect evaluation: visual quality, content accuracy, motion quality, temporal consistency. [Paper](https://arxiv.org/abs/2310.11440)
- [FETV](https://github.com/llyx97/FETV) — Fine-grained Evaluation of Text-to-Video. Temporal and spatial alignment scoring. [Paper](https://arxiv.org/abs/2311.01813)
- [VideoScore](https://github.com/TIGER-AI-Lab/VideoScore) — Automated scoring model trained on human preferences. Useful for pipeline evaluation.
- [T2V-CompBench](https://github.com/KaiyueSun98/T2V-CompBench) — Compositional text-to-video generation benchmark. Tests multi-object scenes. [Paper](https://arxiv.org/abs/2407.14505)

## Research Papers

Key papers advancing the field. Sorted by date, newest first.

### Foundation Models (2025-2026)

- **[Wan 2.1](https://arxiv.org/abs/2503.20314)** — Open and Advanced Large-Scale Video Generative Model — *Alibaba, Mar 2025*
- **[Step Video](https://arxiv.org/abs/2502.10248)** — T2V with Reinforcement Learning from Human Feedback — *StepFun, Feb 2025*
- **[Cosmos](https://arxiv.org/abs/2501.03575)** — World Foundation Model for Physical AI — *NVIDIA, Jan 2025*
- **[HunyuanVideo](https://arxiv.org/abs/2412.03603)** — Systematic Framework For Large Video Generation — *Tencent, Dec 2024*
- **[Movie Gen](https://arxiv.org/abs/2410.13720)** — A Cast of Media Foundation Models — *Meta, Oct 2024*
- **[CogVideoX](https://arxiv.org/abs/2408.06072)** — Text-to-Video with Expert Transformer — *Zhipu AI, Aug 2024*
- **[Pyramid Flow](https://arxiv.org/abs/2410.05954)** — Video Generation via Pyramid Flow Matching — *ByteDance, Oct 2024*
- **[LTX-Video](https://arxiv.org/abs/2501.00103)** — Realtime Video Latent Diffusion — *Lightricks, Jan 2025*

### Architecture Innovations (2023-2024)

- **[Sora Technical Report](https://openai.com/research/video-generation-models-as-world-simulators)** — Video Generation Models as World Simulators — *OpenAI, Feb 2024*
- **[Stable Video Diffusion](https://arxiv.org/abs/2311.15127)** — Scaling Latent Video Diffusion — *Stability AI, Nov 2023*
- **[VideoPoet](https://arxiv.org/abs/2312.14125)** — Large Language Model for Zero-Shot Video Generation — *Google, Dec 2023*
- **[AnimateDiff](https://arxiv.org/abs/2307.04725)** — Animate Personalized Text-to-Image Models — *ByteDance, Jul 2023*
- **[Gen-2](https://arxiv.org/abs/2302.03011)** — Structure and Content-Guided Video Synthesis — *Runway, Feb 2023*
- **[Make-A-Video](https://arxiv.org/abs/2209.14792)** — Text-to-Video without Text-Video Data — *Meta, Sep 2022*
- **[Imagen Video](https://arxiv.org/abs/2210.02303)** — High Definition Video with Diffusion Models — *Google, Oct 2022*

### Controllable Generation

- **[DragAnything](https://arxiv.org/abs/2403.07420)** — Motion Control for Anything via Entity Representation — *Mar 2024*
- **[MotionCtrl](https://arxiv.org/abs/2312.03641)** — Unified and Flexible Motion Controller — *Dec 2023*
- **[AnimateAnything](https://arxiv.org/abs/2311.12886)** — Fine-Grained Open Domain Image Animation — *Nov 2023*
- **[DragNUWA](https://arxiv.org/abs/2308.08089)** — Fine-Grained Control in Video Generation — *Aug 2023*
- **[Control-A-Video](https://arxiv.org/abs/2305.13840)** — Controllable Text-to-Video with ControlNet — *May 2023*
- **[VideoComposer](https://arxiv.org/abs/2306.02018)** — Compositional Video Synthesis with Motion Controlability — *Jun 2023*

### Video Editing & Enhancement

- **[TokenFlow](https://arxiv.org/abs/2307.10373)** — Consistent Diffusion Features for Video Editing — *Jul 2023*
- **[Rerender A Video](https://arxiv.org/abs/2306.07954)** — Zero-Shot Text-Guided Video-to-Video Translation — *Jun 2023*
- **[Tune-A-Video](https://arxiv.org/abs/2212.11565)** — One-Shot Tuning of Image Diffusion Models for T2V — *Dec 2022*
- **[FateZero](https://arxiv.org/abs/2303.09535)** — Fusing Attentions for Zero-shot Text-based Video Editing — *Mar 2023*
- **[Text2Video-Zero](https://arxiv.org/abs/2303.13439)** — Text-to-Image Diffusion Models are Zero-Shot Video Generators — *Mar 2023*

### Surveys & Overviews

- **[A Survey on Video Diffusion Models](https://arxiv.org/abs/2310.10647)** — Comprehensive survey of diffusion-based video generation — *Oct 2023*
- **[Video Generation Models as World Simulators](https://openai.com/research/video-generation-models-as-world-simulators)** — OpenAI's vision for video models — *Feb 2024*
- **[Diffusion Models for Video Generation](https://arxiv.org/abs/2407.07508)** — Tutorial and review — *Jul 2024*

## Tutorials & Courses

### Getting Started

- [How to Create AI Videos: A Beginner's Guide](https://heyvid.ai/blog) — Covers all major tools with step-by-step instructions and prompt examples
- [Runway Academy](https://academy.runwayml.com) — Official courses from Runway. Free, covers Gen-3 Alpha and creative workflows
- [Stability AI Video Guide](https://platform.stability.ai/docs/guides/video) — Official documentation for Stable Video Diffusion API

### ComfyUI Video

- [ComfyUI Video Workflows Guide](https://comfyanonymous.github.io/ComfyUI_examples/video/) — Official examples for video generation nodes
- [Banodoco Steerable Motion Tutorial](https://github.com/banodoco/Steerable-Motion) — Controlled camera and subject motion in ComfyUI
- [AnimateDiff in ComfyUI](https://stable-diffusion-art.com/animatediff-comfyui/) — Step-by-step setup guide with example workflows

### Developer Integration

- [Replicate Video Generation Guide](https://replicate.com/docs/guides/video-generation) — API integration tutorial with Python and Node.js examples
- [fal.ai Video Models Quickstart](https://fal.ai/docs/quickstart) — Deploy video generation in 5 minutes
- [Building a Video Generation Pipeline](https://huggingface.co/docs/diffusers/using-diffusers/text-to-video) — Hugging Face Diffusers library tutorial

### Advanced Techniques

- [LoRA Training for Video Models](https://github.com/kijai/ComfyUI-WanVideoWrapper/blob/main/docs/training.md) — Fine-tune Wan 2.1 on custom data
- [Video Upscaling Pipeline](https://stable-diffusion-art.com/video-upscale/) — Combine generation + upscaling for maximum quality
- [Multi-Shot Video Storytelling](https://www.youtube.com/results?search_query=ai+video+multi+shot+workflow) — Creating coherent narratives across multiple generated clips

### YouTube Channels

- [Olivio Sarikas](https://www.youtube.com/@OlivioSarikas) — In-depth AI video tool reviews and tutorials
- [Matt Wolfe](https://www.youtube.com/@MattVidPro) — AI tools overview and comparisons
- [Aitrepreneur](https://www.youtube.com/@Aitrepreneur) — Open-source AI video workflows
- [Nerdy Rodent](https://www.youtube.com/@NerdyRodent) — Technical deep dives into video generation models
- [Sebastian Kamph](https://www.youtube.com/@sebastiankamph) — ComfyUI and Stable Diffusion video workflows
- [Theoretically Media](https://www.youtube.com/@TheoreticMedia) — AI filmmaking and creative applications

## Communities & Forums

- [r/aivideo](https://reddit.com/r/aivideo) — Main Reddit community for AI video generation. Prompt sharing, model comparisons, tutorials.
- [r/StableDiffusion](https://reddit.com/r/StableDiffusion) — Includes AnimateDiff and video generation discussions. Large community (1M+ members).
- [r/RunwayML](https://reddit.com/r/RunwayML) — Runway-specific community. Gen-3 Alpha tips and creative showcases.
- [r/singularity](https://reddit.com/r/singularity) — AI advancement discussions. First place new model demos appear.
- [Civitai](https://civitai.com) — Model hub. Video LoRAs, AnimateDiff motion modules, community workflows.
- [Hugging Face](https://huggingface.co/models?pipeline_tag=text-to-video) — Open model hub. Papers, model cards, and Spaces demos.
- [Runway Discord](https://discord.gg/runway) — Official Runway community. Challenges, feedback, creative showcases.
- [Pika Discord](https://discord.gg/pika) — Official Pika community. Prompt sharing and feature discussions.
- [ComfyUI Discord](https://discord.gg/comfyorg) — Technical support and workflow sharing for ComfyUI.
- [Banodoco Discord](https://discord.gg/banodoco) — Steerable Motion and open-source video generation community.
- [Deforum Discord](https://discord.gg/deforum) — Audio-reactive and animated Stable Diffusion community.
- [AI Filmmaking Discord](https://discord.gg/) — Independent filmmakers using AI tools. Collaborative projects.

## Multi-Language Resources

AI video generation is a global field. Here are localized resources and tools:

| Language | Resource | Notes |
|----------|----------|-------|
| 🇺🇸 English | [HeyVid AI](https://heyvid.ai) | Full platform, all models |
| 🇪🇸 Español | [HeyVid AI (Español)](https://heyvid.ai/es) | Interfaz completa en español |
| 🇫🇷 Français | [HeyVid AI (Français)](https://heyvid.ai/fr) | Interface complète en français |
| 🇩🇪 Deutsch | [HeyVid AI (Deutsch)](https://heyvid.ai/de) | Vollständige deutsche Oberfläche |
| 🇯🇵 日本語 | [HeyVid AI (日本語)](https://heyvid.ai/ja) | 日本語インターフェース対応 |
| 🇰🇷 한국어 | [HeyVid AI (한국어)](https://heyvid.ai/ko) | 한국어 인터페이스 지원 |
| 🇧🇷 Português | [HeyVid AI (Português)](https://heyvid.ai/pt) | Interface completa em português |
| 🇮🇹 Italiano | [HeyVid AI (Italiano)](https://heyvid.ai/it) | Interfaccia completa in italiano |
| 🇷🇺 Русский | [HeyVid AI (Русский)](https://heyvid.ai/ru) | Полный интерфейс на русском |
| 🇨🇳 简体中文 | [HeyVid AI (中文)](https://heyvid.ai/zh) | 完整中文界面 |
| 🇹🇼 繁體中文 | [HeyVid AI (繁體)](https://heyvid.ai/zh-Hant) | 繁體中文介面 |
| 🇹🇷 Türkçe | [HeyVid AI (Türkçe)](https://heyvid.ai/tr) | Tam Türkçe arayüz |
| 🇮🇩 Indonesia | [HeyVid AI (Indonesia)](https://heyvid.ai/id) | Antarmuka Bahasa Indonesia |
| 🇹🇭 ไทย | [HeyVid AI (ภาษาไทย)](https://heyvid.ai/th) | อินเทอร์เฟซภาษาไทย |
| 🇵🇱 Polski | [HeyVid AI (Polski)](https://heyvid.ai/pl) | Pełny interfejs po polsku |
| 🇳🇱 Nederlands | [HeyVid AI (Nederlands)](https://heyvid.ai/nl) | Complete Nederlandse interface |
| 🇩🇰 Dansk | [HeyVid AI (Dansk)](https://heyvid.ai/da) | Komplet dansk grænseflade |
| 🇳🇴 Norsk | [HeyVid AI (Norsk)](https://heyvid.ai/nb) | Komplett norsk grensesnitt |

---

## Contributing

Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) first.

Ways to contribute:
- Add a tool or resource that's missing
- Update outdated information (pricing, model versions, links)
- Share prompt templates that work well
- Add ComfyUI workflows
- Fix broken links
- Translate sections into other languages

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

This work is released under CC0 1.0 Universal. You can copy, modify, distribute and perform the work, even for commercial purposes, all without asking permission.

---

<div align="center">

**⭐ Star this repo to help others discover it!**

*Maintained by the community. Last verified: February 2026.*

</div>
