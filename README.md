<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1a1b26,1e1e2e,313244&height=180&section=header&text=Osama%20Altaf&fontSize=42&fontColor=cdd6f4&animation=twinkling&fontAlignY=32&desc=Offline%20AI%20Media%20%7C%20Local%20LLM%20Infrastructure%20%7C%20AI%20Automation%20Pipelines&descAlignY=52&descAlign=50" width="100%"/>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-osamaaltafpk-1e1e2e?style=for-the-badge&logo=linkedin&logoColor=89b4fa)](https://linkedin.com/in/osamaaltafpk)
[![Email](https://img.shields.io/badge/Email-osamaaltaf.pk%40gmail.com-1e1e2e?style=for-the-badge&logo=gmail&logoColor=f38ba8)](mailto:osamaaltaf.pk@gmail.com)
[![HuggingFace](https://img.shields.io/badge/HuggingFace-osamaaltaf-1e1e2e?style=for-the-badge&logo=huggingface&logoColor=f9e2af)](https://huggingface.co/osamaaltaf)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-%2B923187661096-1e1e2e?style=for-the-badge&logo=whatsapp&logoColor=a6e3a1)](https://wa.me/923187661096)

</div>

---

## 🚀 Professional Profile

I am a specialized **AI Systems Engineer** focused on building **offline-first AI media production tools, self-hosted LLM infrastructure, and multi-agent automation pipelines**. My recent work spans the full spectrum — from ONNX model export pipelines and local inference routing to multi-lane video editors, 2D lip sync studios, and LangGraph-orchestrated content automation — all running entirely on local hardware.

- **40+ Active Codebases** spanning offline video production, local AI runtimes, voice synthesis, LLM fine-tuning, and enterprise automation.
- **Offline-First Philosophy**: Every tool I build runs without cloud dependencies — TTS, SFX, video stitching, lip sync, and sketch animation all on-device.
- **Production AI Deployments**: Veteran of enterprise SaaS backends, browser automation agents, local AI OS builds, and ONNX inference pipelines.

---

## 🎓 Research Direction — Medical Imaging & Grounded Vision-Language

> I am applying for doctoral positions in **medical imaging AI**. The question I want to work on: given a 3D scan and a clinician's question about it, produce an answer in plain clinical language **that points to the exact voxels it came from** — where segmentation, visual grounding and language stop being three fields and become one.

The gap I keep running into is between *fluent* output and *grounded* output. Fine-tuning a vision-language model on radiography produces report-like text almost immediately; establishing that the text is traceable to a region of the image is a much harder problem, and the one I want to work on properly.

| Repository | Relevance |
| :--- | :--- |
| **[Llama_3_2_Vision_Finetuning_Unsloth_Radiography](https://github.com/osamaaltaf-pk/Llama_3_2_Vision_Finetuning_Unsloth_Radiography)** | LoRA fine-tuning of Llama 3.2 Vision on radiography — the work closest to the direction above, and where the fluency-vs-grounding gap became concrete. |
| **[radiology-ai-assistant](https://github.com/osamaaltaf-pk/radiology-ai-assistant)** | A five-stage pipeline that makes a VLM commit to a location: analyse → research → **emit normalised bounding boxes** → render them onto the image → discuss. An early, explicit attempt at grounding in 2D. |
| **[dinov2-live-person-reid](https://github.com/osamaaltaf-pk/dinov2-live-person-reid)** | Self-supervised ViT representations (DINOv2 CLS embeddings) used for identity matching — hands-on with what pretrained vision-transformer features do and do not encode. |
| **[gemma-edu-dataset-pipeline](https://github.com/osamaaltaf-pk/gemma-edu-dataset-pipeline)** | Dataset construction at scale, with a documented record of format failures and regeneration. Most of the difficulty in grounded supervision is here, not in the architecture. |
| **[cotton-disease-detection](https://github.com/osamaaltaf-pk/cotton-disease-detection)** | Final-year project: VGG16 transfer learning for crop disease classification. Confidently wrong on conditions absent from the training set — the lesson about labels that shaped everything after. |

---

## 🎯 Target Role Alignment & Capabilities

| Target Pillar | Core Alignment & Competencies | Key Evidence (In my Repos) |
| :--- | :--- | :--- |
| **Offline AI Media Engineer** | Multi-lane video stitching, local TTS/SFX generation, FFmpeg pipeline engineering, 2D lip sync, whiteboard sketch animation. | AutoStitch Studio *(private)* • [Omni-Lip-Sync](https://github.com/osamaaltaf-pk/Omni-Lip-Sync) • Wisko *(private)* |
| **LLM Infrastructure Engineer** | Self-hosted AI runtime OS, multi-backend inference routing (Ollama/vLLM/SGLang), ONNX export pipelines, hybrid vector + graph memory. | [NeuralFolk](https://github.com/osamaaltaf-pk/NeuralFolk) • [onnx-sfx-music-stable-audio](https://github.com/osamaaltaf-pk/onnx-sfx-music-stable-audio) |
| **AI Automation Engineer** | LangGraph multi-agent DAG pipelines, YouTube content automation, APScheduler orchestration, Supabase state + GCS media management. | [CMS](https://github.com/osamaaltaf-pk/CMS) • [Omni_Automator](https://github.com/osamaaltaf-pk/Omni_Automator) |
| **Voice AI Engineer** | Real-time TTS streaming (~200ms), voice cloning, WebRTC audio, multi-engine offline voice pipelines. | [Pocket_TTS](https://github.com/osamaaltaf-pk/Pocket_TTS) • [Aura-TTS](https://github.com/osamaaltaf-pk/Aura-TTS) • [OrpheusAssistant](https://github.com/osamaaltaf-pk/OrpheusAssistant) |
| **LLM Research / Fine-tuning** | LoRA/QLoRA fine-tuning, GRPO reasoning training without critic models, MoE kernels, model alignment with Unsloth. | [LLMs-Unsloth](https://github.com/osamaaltaf-pk/LLMs-Unsloth) • [smol-course](https://github.com/osamaaltaf-pk/smol-course) |

---

## 🛠️ Technical Ecosystem

<div align="center">

### AI & LLM Systems
![PyTorch](https://img.shields.io/badge/PyTorch-1e1e2e?style=flat-for-the-badge&logo=pytorch&logoColor=ee4c2c)
![HuggingFace](https://img.shields.io/badge/HuggingFace-1e1e2e?style=flat-for-the-badge&logo=huggingface&logoColor=ffb454)
![ONNX](https://img.shields.io/badge/ONNX_Runtime-1e1e2e?style=flat-for-the-badge&logo=onnx&logoColor=005CED)
![FastAPI](https://img.shields.io/badge/FastAPI-1e1e2e?style=flat-for-the-badge&logo=fastapi&logoColor=009688)
![Transformers](https://img.shields.io/badge/Transformers-1e1e2e?style=flat-for-the-badge&logo=huggingface&logoColor=fff)
![Gemini API](https://img.shields.io/badge/Google_Gemini-1e1e2e?style=flat-for-the-badge&logo=google&logoColor=4285f4)
![Anthropic SDK](https://img.shields.io/badge/Anthropic_Claude-1e1e2e?style=flat-for-the-badge&logo=anthropic&logoColor=fff)

### Offline Media & Production Pipeline
![FFmpeg](https://img.shields.io/badge/FFmpeg-1e1e2e?style=flat-for-the-badge&logo=ffmpeg&logoColor=007808)
![OpenCV](https://img.shields.io/badge/OpenCV-1e1e2e?style=flat-for-the-badge&logo=opencv&logoColor=5C3EE8)
![Whisper](https://img.shields.io/badge/OpenAI_Whisper-1e1e2e?style=flat-for-the-badge&logo=openai&logoColor=41b883)
![LangGraph](https://img.shields.io/badge/LangGraph-1e1e2e?style=flat-for-the-badge&logo=langchain&logoColor=1C3C3C)

### Real-Time & Backend Infrastructure
![Node.js](https://img.shields.io/badge/Node.js-1e1e2e?style=flat-for-the-badge&logo=nodedotjs&logoColor=6db33f)
![NestJS](https://img.shields.io/badge/NestJS-1e1e2e?style=flat-for-the-badge&logo=nestjs&logoColor=e0234e)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-1e1e2e?style=flat-for-the-badge&logo=apachekafka&logoColor=fff)
![Redis](https://img.shields.io/badge/Redis-1e1e2e?style=flat-for-the-badge&logo=redis&logoColor=dc382d)
![Docker](https://img.shields.io/badge/Docker-1e1e2e?style=flat-for-the-badge&logo=docker&logoColor=2496ed)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-1e1e2e?style=flat-for-the-badge&logo=postgresql&logoColor=4169e1)
![Supabase](https://img.shields.io/badge/Supabase-1e1e2e?style=flat-for-the-badge&logo=supabase&logoColor=3ecf8e)

### Frontend Development
![React 19](https://img.shields.io/badge/React_19-1e1e2e?style=flat-for-the-badge&logo=react&logoColor=61dafb)
![TypeScript](https://img.shields.io/badge/TypeScript-1e1e2e?style=flat-for-the-badge&logo=typescript&logoColor=3178c6)
![Vite](https://img.shields.io/badge/Vite-1e1e2e?style=flat-for-the-badge&logo=vite&logoColor=646cff)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-1e1e2e?style=flat-for-the-badge&logo=tailwindcss&logoColor=06b6d4)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-1e1e2e?style=flat-for-the-badge&logo=framer&logoColor=ea4aaa)

</div>

---

## 📂 Featured Deep-Dives

Here is a curated overview of my primary repositories representing deep engineering focus and production capabilities:

### 1. 🎬 AutoStitch Studio (Offline AI Video Production Suite) *— private repo*
*A locally-run, offline-first Windows desktop application that automates voiceover generation, sound effect creation, and multi-lane video stitching — entirely without any cloud dependency.*
*   **Engineering Highlights**:
    *   **Multi-Lane Timeline Editor**: Drag, reorder, split, merge, and edit clips across 3 independent lanes with a browser-based UI.
    *   **Local TTS Engine**: Generates realistic voiceovers from text scripts entirely on-device using PocketTTS.
    *   **Local SFX Engine**: Generates sound effects from text prompts using ONNX-exported Stable Audio 3 Small, running fully on CPU.
    *   **Auto-Captions**: Word-by-word caption overlays burned into final video via FFmpeg `drawtext` filters.
    *   **Background Music Mixer**: Mixes ambient music tracks with adjustable volume into the final rendered output.
    *   **Rebuilt Timeline UI**: Sticky-scroll track headers/ruler and stable React keys eliminate audio stutter and DOM rebuild lag during playback.
*   **Key Stack**: Python, FFmpeg, ONNX Runtime, PocketTTS, FastAPI, WebSockets, React.

### 2. 🧠 [NeuralFolk (Self-Hosted AI Runtime OS)](https://github.com/osamaaltaf-pk/NeuralFolk)
*A self-hosted, open-source, air-gapped AI runtime Operating System — enabling companies, developers, and researchers to orchestrate state-of-the-art AI agents and multi-model workflows completely locally, from an RTX 2070 laptop to enterprise clusters.*
*   **Engineering Highlights**:
    *   **Universal Inference Layer**: Abstracts backend engines (Ollama, vLLM, SGLang, llama.cpp, TensorRT) under a single dynamic routing API.
    *   **Hybrid Memory System**: Merges semantic vector embeddings (Qdrant) and entity-relationship knowledge graphs (FalkorDB) for human-like agent context recall.
    *   **Distributed Task Orchestration**: Celery + Valkey Streams drive parallelized multi-agent loops and complex DAG workflows.
    *   **Zero API Keys, 100% Privacy**: No external phone-homes, no vendor lock-in, fully air-gapped deployment.
*   **Key Stack**: Python, FastAPI, Celery, Valkey Streams, Qdrant, FalkorDB, Ollama, vLLM, Docker.

### 3. 👄 [Omni-Lip-Sync (2D Lip Sync Animation Studio)](https://github.com/osamaaltaf-pk/Omni-Lip-Sync)
*A locally-run, offline-first Windows desktop application for 2D animators — automatically generating frame-accurate lip-sync video from character sprites and a dialogue script.*
*   **Engineering Highlights**:
    *   **Phoneme Detection**: Rhubarb Lip Sync extracts mouth shape timings (phonemes A–X) at frame-level accuracy from generated or provided WAV audio.
    *   **Character Studio**: Upload full-body character images, define face regions, and map custom mouth sprites to each phoneme.
    *   **Script-Driven Voice**: `[Character Name]` tagged dialogue scripts converted to audio locally via PocketTTS.
    *   **ONNX Face Tracking**: Optional ONNX-based face/gaze tracking for characters with animated heads.
    *   **Video Compositor**: Composites frames + mouth sprites + audio into final MP4s via FFmpeg — no external rendering software needed.
*   **Key Stack**: Python, Rhubarb Lip Sync, ONNX Runtime, FFmpeg, PocketTTS, FastAPI.

### 4. 📺 [CMS — YouTube AI Automation Pipeline](https://github.com/osamaaltaf-pk/CMS)
*A fully automated, sequential content pipeline that discovers viral YouTube videos, writes original scripts, generates TTS audio + AI images + whiteboard sketch animations, and uploads to YouTube — orchestrated by LangGraph multi-agents.*
*   **Engineering Highlights**:
    *   **LangGraph DAG Agents**: Full `viral_finder → await_approval → data_collection → script_generation → media_generation → upload` pipeline with crash-safe resumption via Supabase `pipeline_stage` state.
    *   **Thin-State Architecture**: LangGraph state holds only IDs — every agent reads inputs fresh from Supabase/GCS and writes outputs back, eliminating context bloat.
    *   **Human-in-the-Loop Gate**: `await_approval` polls `yt_results.approved` — a human reviews generated scripts before media production begins.
    *   **Integrated Sketch Animation**: Converts AI-generated images into whiteboard sketch animations using Omni Sketches on GCP VM.
*   **Key Stack**: Python, LangGraph, FastAPI, APScheduler, Supabase, Google Cloud Storage, FFmpeg, Gemini.

### 5. 📦 [onnx-sfx-music-stable-audio (ONNX Model Export Pipeline)](https://github.com/osamaaltaf-pk/onnx-sfx-music-stable-audio)
*An open-source ONNX conversion pipeline for Stability AI's Stable Audio 3 Small — enabling CPU/GPU audio generation inference without a PyTorch runtime dependency.*
*   **Engineering Highlights**:
    *   Exports the full diffusion pipeline into 4 standalone ONNX modules: **Text Encoder → Conditioner → DiT (Diffusion Transformer) → Decoder (Oobleck)**.
    *   Supports both `stable-audio-3-small-music` and `stable-audio-3-small-sfx` model variants.
    *   Runtime-agnostic deployment on CUDA, DirectML, and CPU via ONNX Runtime — no PyTorch installation required at inference time.
*   **Key Stack**: Python, ONNX Runtime, HuggingFace Diffusers, Stability AI, PyTorch.

### 6. 🎙️ [Voice AI Suite — Pocket_TTS, Aura-TTS & OrpheusAssistant](https://github.com/osamaaltaf-pk/Pocket_TTS)
*A tightly integrated suite of offline voice engineering tools covering real-time TTS streaming, multi-engine workstations, and full voice-driven AI assistants.*
*   **Engineering Highlights**:
    *   **Pocket_TTS**: Low-latency real-time TTS streaming via WebSockets (~200ms to first chunk), voice cloning support, CPU-only, glassmorphism web UI.
    *   **Aura-TTS**: Unified offline speech workstation managing engine lifecycles (Kokoro-TTS, Pocket-TTS, Supertonic) via custom mutual exclusion locking under RAM/VRAM constraints.
    *   **OrpheusAssistant**: Offline voice agent with WebRTC bi-directional streams (`aiortc`), Whisper Large STT, and LLaMA 3.2 3B — integrated with `n8n` for workflow tool execution.
*   **Key Stack**: Python, FastAPI, WebRTC, WebSockets, PipeCat, PyTorch, n8n, Docker.

### 7. 🧬 [LLMs-Unsloth (LLM Optimization & Reasoning Hub)](https://github.com/osamaaltaf-pk/LLMs-Unsloth)
*A specialized research-to-production pipeline repository detailing high-throughput fine-tuning, reasoning models, and edge optimizations.*
*   **Engineering Highlights**:
    *   Fine-tuning pipelines utilizing Unsloth kernels for parameter-efficient optimizations (**LoRA / QLoRA**).
    *   RLHF training using **Group Relative Policy Optimization (GRPO)** without a separate Critic model (pioneered by DeepSeek-R1), targeting `Qwen3 8B`.
    *   Horizontal engineering recipes for Mixture-of-Experts (**MoE**) kernels and ModernBERT dense classification systems.
*   **Key Stack**: Unsloth, PyTorch, LoRA, QLoRA, HuggingFace Transformers, TRL, JAX.

---

## 🗄️ Earlier Work — Foundations Archive (2023 – 2026)

> **A note on timing:** these are older projects — university work, internship builds and independent experiments — developed offline over several years and only **pushed to GitHub in September 2026**. The commit dates reflect when they were uploaded, not when they were written. Each repository's README states its own original timeline.

### 🔬 Computer Vision & Deep Learning

| Project | What it does | Built | Stack |
| :--- | :--- | :--- | :--- |
| **[radiology-ai-assistant](https://github.com/osamaaltaf-pk/radiology-ai-assistant)** | Five-stage Gemini pipeline: analyse an X-ray, research the findings, emit and render bounding boxes for them, then discuss the result over live audio/video. | 2025 | Gemini Live API · Gradio · Pillow · asyncio |
| **[dinov2-live-person-reid](https://github.com/osamaaltaf-pk/dinov2-live-person-reid)** | Enrol a person once, then re-identify them live across two camera feeds by cosine similarity over DINOv2 CLS embeddings. | 2025 | DINOv2 · ViT · YOLO · PyTorch |
| **[face-recognition-system](https://github.com/osamaaltaf-pk/face-recognition-system)** | Modular MTCNN + FaceNet package with four modes — enrollment, recognition, multi-camera surveillance, IoU tracking — over Postgres, MongoDB, Redis and FAISS. | 2025 | facenet-pytorch · FAISS · Gradio |
| **[cotton-disease-detection](https://github.com/osamaaltaf-pk/cotton-disease-detection)** | VGG16 transfer-learning classifier for four cotton leaf conditions, served as a Flask app with still-image and live-video modes. | 2023–24 | TensorFlow · Keras · Flask · OpenCV |

### 🤖 LLM Pipelines, Agents & Automation

| Project | What it does | Built | Stack |
| :--- | :--- | :--- | :--- |
| **[gemma-edu-dataset-pipeline](https://github.com/osamaaltaf-pk/gemma-edu-dataset-pipeline)** | Turns curriculum textbooks into a fine-tuning dataset of self-contained interactive HTML5 lessons, then LoRA-tunes Gemma on it. | 2026 | Unsloth · PEFT · TRL · Gemma E2B |
| **[classroom-ai-grader](https://github.com/osamaaltaf-pk/classroom-ai-grader)** | Pulls Google Classroom submissions, extracts text from any format (PDF, DOCX, HTML, scanned pages via vision), grades with an LLM, exports CSV. | 2024 | Classroom & Drive APIs · Llama 3.1 405B |
| **[academic-research-assistant](https://github.com/osamaaltaf-pk/academic-research-assistant)** | Takes a research topic, searches the literature, parses the papers, drafts a structured review. | 2024 | Gradio · Serper · Crossref · docling |
| **[ai-news-summarizer](https://github.com/osamaaltaf-pk/ai-news-summarizer)** | Keyword news search with relevance scoring and LLM-rewritten headlines and summaries. | 2024 | Flask · NewsAPI · Together AI |
| **[linkedin-ai-engagement-bot](https://github.com/osamaaltaf-pk/linkedin-ai-engagement-bot)** | Monitors LinkedIn for keyword matches, drafts contextual replies, publishes via the UGC API. | 2024 | LinkedIn UGC API · Llama 3.1 405B |
| **[google-classroom-cli-automation](https://github.com/osamaaltaf-pk/google-classroom-cli-automation)** | `class SE` opens the right Meet from the terminal — links fetched live from the Classroom API so they survive rotation. | 2024 | Classroom API v1 · OAuth · pyautogui |
| **[nvidia-rag-course-work](https://github.com/osamaaltaf-pk/nvidia-rag-course-work)** | Completed notebooks from NVIDIA's DLI *Building RAG Agents with LLMs* — runnables, running state, LangServe, chunking. | 2024 | LangChain · LangServe |

### 🌐 Web, Embedded & Games

| Project | What it does | Built | Stack |
| :--- | :--- | :--- | :--- |
| **[crypts-of-doom](https://github.com/osamaaltaf-pk/crypts-of-doom)** | Roguelite dungeon survivor for the browser — 24 upgrades, boss waves, mobile joystick. Every sprite drawn procedurally, every sound synthesised live: **zero assets, zero dependencies**. | 2026 | Vanilla JS · Canvas 2D · Web Audio API |
| **[esp32-cam-edge-impulse](https://github.com/osamaaltaf-pk/esp32-cam-edge-impulse)** | ESP32-S3-EYE that streams MJPEG over WiFi *and* runs a FOMO object-detection model on-device simultaneously. | 2026 | ESP32 · Edge Impulse SDK · C++ |

---

## 📊 Developer Metrics & Impact
- 🎬 **Offline-First Media Architect**: Building complete AI video production stacks that run 100% on local hardware — ONNX inference, FFmpeg rendering, TTS streaming, and lip sync compositing.
- 🧠 **AI Pipeline Engineer**: Expert in LangGraph DAG orchestration, Kafka event streaming, Celery distributed workers, and multi-agent system design.
- 📦 **Docker-first Deployer**: Containerizing complex AI stacks with multi-stage builds and clean Docker Compose networking configs.

---

<div align="center">

### 💼 Open to Remote Opportunities
I am actively exploring **Remote AI Engineer, LLM Infrastructure Engineer, AI Media Engineer, and AI Automation** opportunities globally. Let's build the future of offline, production-grade AI systems.

[📧 Get In Touch](mailto:osamaaltaf.pk@gmail.com) • [💬 Chat on WhatsApp](https://wa.me/923187661096)

</div>
