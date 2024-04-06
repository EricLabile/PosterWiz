# PosterWiz
This is the course project for COMP5214. We are going to introduce a t2i model to generate wonderful posters.

## Methodology

## ⏰TODOs
- [ ] Recaption Anyword-3M and MARIO-10M dataset 
- [ ] Filter the poster from Anyword-3M and MARIO-10M dataset for later fine-tuning
- [ ] Fine-tune a large language model, such as Vicuna-7b-v1.5 for generating position embeddings
- [ ] Fine-tune stable diffusion-v1.5 by using posters and combining Text Perceptual Loss
- [ ] Support PosterWiz in webui(🤔)

## Environment

```bash
conda create --name posterwiz python=3.10 torchvision torchaudio pytorch-cuda=11.8 -c pytorch -c nvidia 
conda install -c "nvidia/label/cuda-11.8.0" cuda-nvcc 
conda install -c "nvidia/label/cuda-11.8.0" cuda-toolkit
```

```bash
conda activate posterwiz
```
