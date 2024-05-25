---
layout: page
title: Calibration in LLMs
description: Experiments on calibration in quanitzed large language models [C++, Python, scikit-learn]
img: assets/img/projects/calibrated_llm_preview.jpg
# redirect: https://unsplash.com
importance: 1
category: research
related_publications: false
# giscus_comments: true
---

*GitHub-Repository: [Calibration in LLMs](https://github.com/arthur-becker/calibration_in_llm)*

The project consists of tools for performing experiments on token-level calibration in large language models (LLMs). There are three tools available:

1. **Extractor**: peforms inference with [llama.cpp](https://github.com/ggerganov/llama.cpp) and saves outputs (logits) from a LLM for a given input text in order to perform calibration experiments. 
2. **Calibrator**: calibrates the predictions of a LLM using the extracted logits and evaluates the calibration using perplexity and Brier score.
3. **Benchmark**: performs few-shot learning evaluation on reasoning tasks to compare the performance of a calibrated and uncalibrated LLM.
