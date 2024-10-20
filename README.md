# Graph-Understanding-Multimodal-Benchmark

**[ACL 2024] Advancement in Graph Understanding: A Multimodal Benchmark and Fine-Tuning of Vision-Language Models**

The paper has been accepted by the ACL 2024 main conference. This is the official repository for the benchmark dataset.

## Data

```
Graph-Understanding-Multimodal-Benchmark/
├── eval/
│   ├── baseline_eval/      # Results of LLaVA, Minigpt4, Gemini and GPT-4V
│   ├── llava_eval/         # Results of finetuned LLaVA 
│   ├── mini_eval/          # Results of finetuned Minigpt4
│   └── eval.jsonl          # Evaluation instructions with groundtruth answers
|
├── test/
│   ├── test.jsonl         # All instructions used in test (both English and Chinese)
│   ├── test_en.jsonl       # English testing instructions
│   └── test_zh.jsonl       # Chinese testing instructions
|
├── train/
│   ├── train.jsonl         # All instructions used in training (both English and Chinese)
│   ├── train_en.jsonl       # English training instructions
│   └── train_zh.jsonl       # Chinese training instructions
└── README.md
```

Images are available here : [Google Drive Link](https://drive.google.com/drive/folders/1fcIHuCMGAU8tboMXDqetXrP0WkQAxerp?usp=sharing)

## Model

By fine-tuning MiniGPT-4 and LLaVA on our dataset, we achieved an accuracy increase of 5%-15% compared to baseline models, with the best-performing model attaining scores comparable to Gemini in GPT-assisted Evaluation. The experiment and results are detailed in our paper.

## Paper and Citation

If the data is helpful for your project, please cite our paper (Bibtex below).
```bibtex
@inproceedings{ai2024advancement,
  title={Advancement in Graph Understanding: A Multimodal Benchmark and Fine-Tuning of Vision-Language Models},
  author={Ai, Qihang and Li, Jiafan and Dai, Jincheng and Zhou, Jianwu and Liu, Lemao and Jiang, Haiyun and Shi, Shuming},
  booktitle={Proceedings of the 62nd Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)},
  pages={7485--7501},
  year={2024}
}