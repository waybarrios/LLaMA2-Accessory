# LLaMA2-Accesory: An Open-source Toolkit for LLM Development 🚀

<p align="center">                                                                                                                                          <img src="docs/logo_v1.png"/ width="100%"> <br>
</p>



Welcome to **LLaMa2-Accessory,** your comprehensive open-source solution for LLM development, built to support a wide variety of models and applications. 


## News
- **[2023.07.21]** Initial release 📌

## Features

LLaMA2-Accesory supports the pretrain, full-paratemeter finetune, paramter-efficient finetune, multimodality finetune and in-context multimodality finetune. 


### Dataset Support

1. **Pretraining Support**: Allows pretraining on the StarCoder dataset and the RefinedWeb dataset, offering a strong basis for subsequent task-specific model adjustments.
   
2. **Finetuning Support**: Supports finetuning on a variety of datasets including Alpaca, ShareGPT, UltraLM, and MOSS, enabling customization for diverse applications.

3. **Multimodality Finetuning**: Offers multimodal finetuning with datasets like COCO, SBU, COYO, Shrika, Laion, VQA, and LLaVa. This broadens the capability of models to understand and generate outputs based on various forms of inputs, such as images, text, and audio.

4. **In-context Multimodality Finetuning**: Employs the MMC4 and Obelisc for in-context multimodality finetuning, bringing an enhanced level of understanding and nuance to models dealing with multimodal data.

### Efficient Optimization and Scalability

1. **Parameter-Efficient Finetuning (PEFT) Methods**: Includes a range of PEFT techniques such as Zero-Init Attention, Bias-Norm-Tuning, LoRa. These are designed to optimize the training process, yielding better model performance with more efficient parameter usage.
   
2. **Scalability**: Provides FSDP and Model-parallel support for flexible finetuning that ranges from 7B to 70B. This ensures the solution's ability to handle a wide range of model complexities and sizes, accommodating both smaller and larger scale applications.

###  Pretrained Multimodal Visual-and-Language Models 

1. **CLIP**: A multimodal vision-and-language model developed by OpenAI, leveraging contrastive learning to map images and their textual descriptions into a shared semantic space, enabling versatile downstream applications.

2. **Q-Former**: A lightweight Transformer architecture that employs a set of learnable query vectors to extract relevant visual features from a frozen image encoder, streamlining the provision of useful visual cues for language model to generate related textual output.

3. **ImageBind**: A model that learns a joint embedding across six different modalities - images, text, audio, depth, thermal, and IMU data, facilitating emergent applications such as cross-modal retrieval, composing modalities with arithmetic, and cross-modal detection and generation.


## Installation

See [docs/install.md](./docs/install.md). 

# Pre-train & Fine-tune
See [docs/finetune.md](./docs/finetune.md). 

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contributors


## Citation

## Acknowledgement
This repo benefits from [LLaMA](https://github.com/facebookresearch/llama), [Stanford Alpaca](https://github.com/tatsu-lab/stanford_alpaca), and [Alpaca-Lora](https://github.com/tloen/alpaca-lora). Thanks for their wonderful works.