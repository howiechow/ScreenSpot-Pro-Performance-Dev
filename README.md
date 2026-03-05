# ScreenSpot-Pro Performance Dev

This repository collects the performance of different models on the ScreenSpot-Pro benchmark.

## Dataset Information

**ScreenSpot-Pro** is a novel benchmark designed to evaluate the GUI grounding capabilities of multimodal large language models (MLLMs) in high-resolution professional environments. The dataset is available on HuggingFace at [Voxel51/ScreenSpot-Pro](https://huggingface.co/datasets/Voxel51/ScreenSpot-Pro).

- **Paper**: [ScreenSpot-Pro: GUI Grounding for Professional High-Resolution Computer Use](https://arxiv.org/abs/2504.07981)
- **Leaderboard**: https://gui-agent.github.io/grounding-leaderboard
- **Official Repository**: https://github.com/likaixin2000/ScreenSpot-Pro-GUI-Grounding

## Model Performance on ScreenSpot-Pro

The following models have been evaluated on the ScreenSpot-Pro benchmark:

- UGround-V1-7B, 31.1%, https://github.com/OSU-NLP-Group/UGround
- Aguvis-7B, 22.9%, https://github.com/xlang-ai/aguvis
- AriaUI (MOE, 3.9B active), 11.3%, https://ariaui.github.io/

## About ScreenSpot-Pro

ScreenSpot-Pro comprises 1,581 authentic high-resolution screenshots spanning 23 professional applications across 5 industries (Development, Creative, CAD, Scientific, and Office) and 3 operating systems, each annotated with precise bounding boxes for target UI elements and corresponding natural language instructions.