<div align="center">

<img src="static/images/logo.png" width="100em"></img>

# ILLUME+: Illuminating Unified MLLM with Dual Visual Tokenization and Diffusion Refinement


📄 [Paper](https://arxiv.org/abs/) | 🌐 [Project-Page](https://illume-unified-mllm.github.io/) | 💻 [Github](https://github.com/illume-unified-mllm/ILLUME_plus)

</div>

Welcome to the official repository for our paper: "ILLUME+: Illuminating Unified MLLM with Dual Visual Tokenization and Diffusion Refinement"


<div align="center">
  <img src="static/images/framework.png" width=100%></img>
</div>

## Abstract
We present ILLUME+ that leverages dual visual tokenization and a diffusion decoder to improve both deep semantic understanding and high-fidelity image generation. 
ILLUME+ introduces a unified dual visual tokenizer, DualViTok, which preserves both fine-grained textures and text-aligned semantics while enabling a coarse-to-fine image representation strategy for multimodal understanding and generation. Additionally, we employ a diffusion model as the image detokenizer for enhanced generation quality and efficient super-resolution. 
ILLUME+ follows a continuous-input, discrete-output scheme within the unified Multimodal Large Language Model (MLLM) and adopts a progressive training procedure that supports dynamic resolution across the vision tokenizer, MLLM, and diffusion decoder. 
ILLUME+ (3B) exhibits competitive performance against existing unified MLLMs and specialized models across multimodal understanding, generation, and editing benchmarks. 
With its strong performance, ILLUME+ provides a scalable and versatile foundation for future multimodal applications. 

---

## TODO

- [ ] Release model checkpoint and inference code.
- [ ] Release training and inference code for the vision tokenizer and MLLM.
- [ ] Release training code for the diffusion decoder.
- [ ] Release 7B LLM checkpoint.


---

## Image Generation

![alt text](static/images/vis_gen.png)

## Image Editing

![alt text](static/images/vis_edit.png)

## Image Understanding

![alt text](static/images/vis_und.png)



