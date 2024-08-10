# Graph-Understanding-Multimodal-Benchmark

**[ACL 2024] Advancement in Graph Understanding: A Multimodal Benchmark and Fine-Tuning of Vision-Language Models**

The paper has been accepted by the ACL 2024 main conference. This is the official repository for the benchmark dataset.

## Data

```
Graph-Understanding-Multimodal-Benchmark/
├── instructions/
│   ├── train.jsonl         # All instructions used in training (include English and Chinese)
│   ├── train_en.jsonl       # English instructions corresponding to English images
│   └── train_zh.jsonl       # Chinese instructions corresponding to Chinese images
└── README.md
```

Images are available here : [Google Drive Link](https://drive.google.com/drive/folders/1YGersVhKBixAp3dq0SBwHDOG8I6mvowE?usp=sharing)

## Model

By fine-tuning MiniGPT-4 and LLaVA on our dataset, we achieved an accuracy increase of 5%-15% compared to baseline models, with the best-performing model attaining scores comparable to Gemini in GPT-assisted Evaluation. The experiment and results are detailed in our paper.

## Paper

If the data is helpful for your project, please cite our paper (Bibtex below).
TO BE FINISHED.