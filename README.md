# MG-VLQA: Multi-Granularity Quality Assessment for Image Compression via Visual Language Models

> An image quality assessment framework leveraging visual-language models for multi-granularity semantic fidelity.



<p align="center">
  <img src="./figs/pipeline.png" alt="MG-VLQA Pipeline" width="800"/>
</p>


<p align="center">
Hanfei Li<sup>1</sup> &nbsp;·&nbsp;
Anle Ke<sup>1</sup> &nbsp;·&nbsp;
Jiawen Gu<sup>2</sup> &nbsp;·&nbsp;
Chao Zhou<sup>2</sup> &nbsp;·&nbsp;
Tong Chen<sup>1</sup> &nbsp;·&nbsp;
Zhan Ma<sup>1</sup> &nbsp;·&nbsp;
</p>

<p align="center">
<sup>1</sup> Nanjing University &nbsp;&nbsp;&nbsp;
<sup>2</sup> Kuaishou Technology
</p>


## 🚀Quick Start

### 📁Prerequisites

Before installing the dependencies, please prepare the model weights.

Create the following directory structure in the project root:

```text
weights/
├── Gemma/
└── SAM/
```
Download the required model weights from Hugging Face and place them in the corresponding folders:

#### Gemma weights: [https://huggingface.co/google/gemma-2b-it](https://huggingface.co/google/gemma-2b-it)

#### SAM weights: [https://huggingface.co/google-bert/bert-base-uncased](https://huggingface.co/google-bert/bert-base-uncased)


### 🧪Environment Requirements

Make sure your environment meets the following requirements:

- Python >= 3.9
- PyTorch == 2.6.0
- transformers == 4.53.0
- timm == 1.0.6
- six
- accelerate

Then, navigate to the `GroundingDINO` directory and install it in editable mode:

```bash
cd GroundingDINO
pip install -e .
