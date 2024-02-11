# A Catalog for Indic LLM Resources
The purpose of this catalog is to help researchers looking for Indic LLM resources. This is a collective effort and any contribution to enriching Indic LLM resources is welcome. All contributors are listed on the <a href="https://github.com/shantipriyap/IndicLLM_Resource_Catalog/blob/main/CONTRIBUTORS.md">CONTRIBUTOR</a> list. 

<p align="center">
<img src="https://github.com/shantipriyap/Indic_LLM_Resource_Catalog/blob/main/magnifying-glass-7544299_1280.png" alt="llm_resource_catalog" width="250"/>
</p>

Table of Contents
=================
* [Instruction Set](#instruction-set)
* [Foundation LLM](#foundation-llm)
* [Fine-Tuned LLM](#fine-tuned-llm)
* [Benchmarking Set](#benchmarking-set)


### Instruction Set
#### Odia
* <a href="https://huggingface.co/datasets/OdiaGenAI/odia_master_data_llama2">odia_master_data_llama2</a>: This dataset contains 180k Odia instruction sets translated from open-source instruction sets and Odia domain knowledge instruction sets.
* <a href="https://huggingface.co/datasets/OdiaGenAI/odia_context_10K_llama2_set">odia_context_10k_llama2_set</a>: This dataset contains 10K instructions that span various facets of Odisha's unique identity. The instructions cover a wide array of subjects, ranging from the culinary delights in 'RECIPES,' the historical significance of 'HISTORICAL PLACES,' and 'TEMPLES OF ODISHA,' to the intellectual pursuits in 'ARITHMETIC,' 'HEALTH,' and 'GEOGRAPHY.' It also explores the artistic tapestry of Odisha through 'ART AND CULTURE,' which celebrates renowned figures in 'FAMOUS ODIA POETS/WRITERS', and 'FAMOUS ODIA POLITICAL LEADERS'. Furthermore, it encapsulates 'SPORTS' and the 'GENERAL KNOWLEDGE OF ODISHA,' providing an all-encompassing representation of the state.

#### Bengali
* <a href="https://huggingface.co/datasets/OdiaGenAI/all_combined_bengali_252k">all_combined_bengali_252K</a>: This dataset is a mix of Bengali instruction sets translated from open-source instruction sets: Dolly, Alpaca, ChatDoctor, Roleplay, and GSM.

#### Hindi
* <a href="https://huggingface.co/datasets/OdiaGenAI/hindi_alpaca_dolly_67k_formatted">hindi_alpaca_dolly_67k_formatted</a>: This dataset is translated from open-source Alpaca_Dolly instruction sets.
* <a href="https://huggingface.co/datasets/OdiaGenAI/instruction_set_hindi_1035">instruction_set_hindi_1035</a>: The dataset has been created using OliveFarm web application.
The domains that have been covered in this dataset are Art, Sports (Cricket, Football, Olympics), Politics, History, Cooking, Environment, and Music.
* <a href="https://huggingface.co/datasets/OdiaGenAI/roleplay_hindi">roleplay_hindi</a>: The dataset contains 1k Hindi roleplay instruction set.

#### Kannada
* <a href="https://huggingface.co/datasets/Tensoic/airoboros-3.2_kn">airoboros-3.2_kn</a>: This dataset contains 35.5k number of Kannada instruction (input, instruction, output) sets.
* 

### Foundation LLM

#### Hindi
* <a href="https://huggingface.co/sarvamai/OpenHathi-7B-Hi-v0.1-Base">OpenHathi-7B-Hi-v0.1-Base</a>: This is a 7B parameter, based on Llama2, trained on Hindi, English, and Hinglish. As per the authors, this is a base model and is not meant to be used as is. Recommend to first fine-tune the interested task(s).<a href="https://www.sarvam.ai/blog/announcing-openhathi-series">Blog</a>

### Fine-Tuned LLM

#### Odia
* <a href="https://huggingface.co/OdiaGenAI/odia_llama2_7B_base">odia_llama2_7B_base</a>: odia_llama2_7B_base is based on Llama2-7b and finetuned with 180k Odia instruction set.<a href="https://arxiv.org/pdf/2312.12624.pdf">Paper</a>

#### Hindi
* <a href="https://huggingface.co/OdiaGenAI/mistral_hindi_7b_base_v1">mistral_hindi_7b_base_v1 </a>: mistral_hindi_7b_base_v1 is based on Mistral_7b and finetuned with the Hindi instruction set.

#### Bengali
* <a href="https://huggingface.co/OdiaGenAI/odiagenAI-bengali-base-model-v1">odiagenAI-bengali-base-model-v1</a>: odiagenAI-bengali-base-model-v1 is based on Llama-7b and finetuned with 252k Bengali instruction set. The instruction set is translated data from open-source resources, resulting in good Bengali instruction understanding and response generation capabilities.

### Benchmarking Set
* <a href="https://huggingface.co/collections/ai4bharat/airavata-evaluation-suite-65b13b7b68165de71ba0b333">Airavata Evaluation Suite</a>: A collection of benchmarks used for evaluation of Airavata, a Hindi instruction-tuned model on top of Sarvam's OpenHathi base model.
* <a href="https://huggingface.co/Indic-Benchmark">Indic LLM Benchmark</a>: A collection of LLM benchmark data in Gujurati, Nepali, Malayalam, Hindi, Telugu, Marathi, Kannada, Bengali.


Citation:

If you find this repository useful, please consider giving ⭐ and citing:

```
@misc{Indic_LLM_Resources,
  author = {Shantipriya Parida},
  title = {Indic LLM Resource Catalog},
  year = {2024},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/shantipriyap/Indic_LLM_Resource_Catalog}},
}
```
## License

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

