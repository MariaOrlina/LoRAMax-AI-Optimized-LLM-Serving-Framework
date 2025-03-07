# LoRAMax: Serving multiple LoRA finetuned LLMs


## Overview

[Low rank adapation](https://arxiv.org/abs/2106.09685) (LoRA) is a parameter efficient way to add new knowledge to a pretrained LLM. Although the pretrained LLM takes 100s of GB storage, a LoRA finetuned model only adds 1% storage and memory overhead. vLora enables running multiple LoRA finetuned models at the cost of running one.

