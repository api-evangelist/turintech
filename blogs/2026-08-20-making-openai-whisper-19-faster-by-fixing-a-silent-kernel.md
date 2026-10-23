---
title: "Making OpenAI Whisper 19% Faster by Fixing a Silent Kernel Fallback"
url: "https://www.turintech.ai/blog/fixing-a-silent-kernel-fallback-in-openai-whisper"
date: "2026-08-20"
author: "TurinTech AI"
feed_url: "https://www.turintech.ai/feed.xml"
---
A three-line patch restored Whisper's cross-attention to PyTorch's fused kernel during beam search — 4.9x faster attention, merged upstream in openai/whisper#2812.
