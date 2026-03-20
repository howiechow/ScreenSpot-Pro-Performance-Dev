# ScreenSpot-Pro Performance Dev

This repository collects the performance of different models on the ScreenSpot-Pro benchmark.

## Dataset Information

- **Dataset**: ScreenSpot-Pro
- **HuggingFace URL**: https://huggingface.co/datasets/likaixin/ScreenSpot-Pro
- **Leaderboard**: https://gui-agent.github.io/grounding-leaderboard/
- **Paper**: https://likaixin2000.github.io/papers/ScreenSpot_Pro.pdf

## Model Performances

The following models are recorded with their performance on the ScreenSpot-Pro benchmark:

- UGround-V1-7B, 31.1%, https://github.com/OSU-NLP-Group/UGround
- Aguvis-7B, 22.9%, https://github.com/xlangai/aguvis
- AriaUI (MOE, 3.9B active), 11.3%, https://ariaui.github.io/

## About ScreenSpot-Pro

ScreenSpot-Pro is a GUI grounding benchmark for professional high-resolution computer use. It evaluates models' ability to accurately locate and interact with UI elements across various professional applications including:

- Development and Programming (VS Code, PyCharm, Android Studio, etc.)
- Creative Software (Photoshop, Premiere, Illustrator, Blender, etc.)
- CAD and Engineering (AutoCAD, SolidWorks, Inventor, etc.)
- Scientific and Analytical (MATLAB, Origin, Stata, etc.)
- Office Suite (Word, Excel, PowerPoint)
- Operating Systems (Windows, macOS, Linux)

## Citation

```bibtex
@inproceedings{li2025screenspotpro,
  title={ScreenSpot-Pro: {GUI} Grounding for Professional High-Resolution Computer Use},
  author={Kaixin Li and Meng Ziyang and Hongzhan Lin and Ziyang Luo and Yuchen Tian and Jing Ma and Zhiyong Huang and Tat-Seng Chua},
  booktitle={Workshop on Reasoning and Planning for Large Language Models},
  year={2025},
  url={https://openreview.net/forum?id=XaKNDIAHas}
}
```
