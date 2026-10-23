---
title: "Inside llama.cpp PR #26802: +13% from graphs that were switched off for no reason"
url: "https://www.turintech.ai/blog/inside-llama-cpp-pr-26802"
date: "2026-08-10"
author: "TurinTech AI"
feed_url: "https://www.turintech.ai/feed.xml"
---
CUDA graphs were disabled for any mixture-of-experts model with an unquantized expert node — including the many that never needed the sync it was protecting against.
