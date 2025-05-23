# AppealCase: A Dataset and Benchmark for Civil Case Appeal Scenarios

<p align="center">
  <a href="https://huggingface.co/datasets/ythuang02/AppealCase" target="_blank"><img src="https://img.shields.io/badge/HuggingFace-Dataset-yellow?logo=huggingface" alt="Hugging Face"></a>
  &nbsp;
  <a href="https://paperswithcode.com/dataset/appealcase" target="_blank"><img src="https://img.shields.io/badge/Papers%20with%20Code-Dataset-blue?logo=paperswithcode" alt="Papers with Code"></a>
</p>

![](repo.png)

## ⚖️ Introduction

The **AppealCase** dataset is the first large-scale resource specifically designed to support LegalAI research in **appellate judgment scenarios**. While prior work in LegalAI has focused heavily on one-shot trials, the appellate procedure—critical to ensuring fairness and correcting judicial errors—remains largely underexplored.

To bridge this gap, we construct 10,000 pairs of matched first-instance and second-instance civil cases from [China Judgments Online](https://wenshu.court.gov.cn), covering 91 causes of action. We also design a structured annotation schema and define new tasks tailored to the appellate context.

## 📰 News

- [2025/05/23] 🎉 We have released our [arXiv paper](https://arxiv.org/abs/2505.16514) and the accompanying dataset!

## 📂 Dataset

- **Cases:** 10,000 matched pairs of first-instance and second-instance judgments
- **Coverage:** 91 civil causes of action
- **Labeling:** Annotated with judgment reversal, reasons for reversal, claims, legal provisions and new information
- **Format:** JSON structured format, easy to load and parse
- **License:** CC BY-NC 4.0

## 📚 Citation

```
@article{huang2025appealcase,
  title={{AppealCase}: A dataset and benchmark for civil case appeal scenarios},
  author={Huang, Yuting and Guo, Meitong and Wu, Yiquan and Li, Ang and Liu, Xiaozhong and Yin, Keting and Sun, Changlong and Wu, Fei and Kuang, Kun},
  journal={arXiv preprint arXiv:2505.16514},
  year={2025}
}
```