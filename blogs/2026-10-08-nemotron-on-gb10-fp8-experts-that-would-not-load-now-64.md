---
title: "Nemotron on GB10: FP8 experts that would not load, now 64% faster than BF16"
url: "https://www.turintech.ai/blog/nemotron-fp8-moe-on-gb10-dgx-spark"
date: "2026-10-08"
author: "TurinTech AI"
feed_url: "https://www.turintech.ai/feed.xml"
---
TensorRT-LLM refused FP8 block-scale checkpoints with non-gated experts on GB10, the chip inside DGX Spark. Our pull request makes them run: 64.3% more throughput and 44.9% less weight memory than BF16, with accuracy unchanged.
