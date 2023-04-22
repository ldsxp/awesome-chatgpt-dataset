# awesome-chatgpt-dataset
![Alt Text](https://github.com/voidful/awesome-chatgpt-dataset/raw/main/A%20cat%20%20to%20Unlock%20the%20Power%20of%20LLM%20Explore%20These%20Datasets%20to%20Train%20Your%20Own%20ChatGPT!.gif)    

## Unlock the Power of LLM: Explore These Datasets to Train Your Own ChatGPT!

| Dataset Name                                                                                      | Size | Languages                                                          | Task Tags       | Generation Method      | Source                                                                                                                                                                                       | Cost  | License                            |
|---------------------------------------------------------------------------------------------------|------|--------------------------------------------------------------------|-----------------|------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|------------------------------------|
| [Alpaca Dataset](https://github.com/tatsu-lab/stanford_alpaca)                                    | 52K  | English                                                            | Multi-task      | Self-Instruct          | 175 seed instructions by OpenAI API                                                                                                                                                          | <$500 | CC By NC 4.0; OpenAI terms of use  |
| [Alpaca Data Cleaned](https://github.com/gururise/AlpacaDataCleaned)                              | 52K  | English                                                            | Multi-task      | Cleaned Dataset        | Revised version of Alpaca Dataset                                                                                                                                                            | -     | -                                  |
| [Alpaca GPT-4 Data](https://github.com/Instruction-Tuning-with-GPT-4/GPT-4-LLM)                   | 52K  | English                                                            | Multi-task      | GPT-4 Generated        | Generated by GPT-4 using Alpaca prompts                                                                                                                                                      | -     | -                                  |
| [Alpaca GPT-4 Data (Chinese)](https://github.com/Instruction-Tuning-with-GPT-4/GPT-4-LLM))        | 52K  | Chinese                                                            | Multi-task      | GPT-4 Generated        | Generated by GPT-4 using Chinese prompts translated from Alpaca by ChatGPT                                                                                                                   | -     | -                                  |
| [Cabrita Dataset](https://github.com/22-hours/cabrita)                                            | 52K  | Portuguese                                                         | Multi-task      | Self-Instruct          | Translated from Alpaca Data                                                                                                                                                                  | -     |                                    |
| [Japanese Alpaca Dataset](https://github.com/shi3z/alpaca_ja)                                     | 52K  | Japanese                                                           | Multi-task      | Self-Instruct          | Translated from Alpaca Data by ChatGPT API                                                                                                                                                   | $45   | CC By NC 4.0; OpenAI terms of use  |
| [Traditional Chinese Alpaca Dataset](https://github.com/ntunlplab/traditional-chinese-alpaca)     | 52K  | Traditional Chinese                                                | Multi-task      | Self-Instruct          | Translated from Alpaca Data by ChatGPT API                                                                                                                                                   | $40   | Apache-2.0 license                 |
| [Alpaca-CoT Dataset](https://github.com/PhoebusSi/Alpaca-CoT)                                     | 75K  | Multi-lingual                                                      | Multi-task      | Collection of Dataset  | FLAN Chain-of-Thought dataset                                                                                                                                                                | -     |                                    |
| [BELLE](https://github.com/LianjiaTech/BELLE)                                                     | 1.5M | Chinese                                                            | Multi-task      | Self-Instruct          | 175 translated seed instructions of Alpaca Dataset                                                                                                                                           | -     | Research only; OpenAI terms of use |
| [Camel Dataset](https://github.com/lightaime/camel)                                               | 107K | Multi-lingual                                                      | Multi-task      | Mixed Dataset          | Role-playing between AIs (Open AI API)                                                                                                                                                       | -     |                                    |
| [Code Alpaca](https://github.com/sahil280114/codealpaca)                                          | 20K  | English                                                            | Code Generation | -                      | Code generation task involving 20,022 samples                                                                                                                                                | -     | -                                  |
| [Dolly](https://github.com/databrickslabs/dolly/tree/master/data)                                 | 15K  | English                                                            | Multi-task      | Manually               | databricks-dolly-15k is a corpus of more than 15,000 records generated by thousands of Databricks employees to enable large language models to exhibit the magical interactivity of ChatGPT. | -     | CC 3.0                             |
| [Finance](https://huggingface.co/datasets/gbharti/finance-alpaca)                                 | 69K  | English                                                            | Finance         | -                      | 68,912 financial related instructions                                                                                                                                                        | -     | -                                  |
| [Firefly](https://github.com/yangjianxin1/Firefly)                                                | 1.6M | Chinese                                                            | Multi-task      | -                      | 1,649,398 Chinese instructions in 23 NLP tasks                                                                                                                                               | -     | -                                  |
| [GPT4All Dataset](https://github.com/nomic-ai/gpt4all)                                            | 806K | Multi-lingual                                                      | Multi-task      | Collection of Dataset  | Subset of LAION OIG, StackOverflow Question, BigSciense/p3 dataset. Answered by OpenAI API.                                                                                                  | -     |                                    |
| [Guanaco Dataset](https://huggingface.co/datasets/JosephusCheung/GuanacoDataset)                  | 98K  | English, Simplified Chinese, Traditional Chinese HK & TW, Japanese | Multi-task      | Self-Instruct          | 175 translated seed instructions of Alpaca Dataset                                                                                                                                           | $6K   | GPL-3.0; OpenAI terms of use       |
| [HC3](https://huggingface.co/datasets/Hello-SimpleAI/HC3)                                         | 37K  | English, Chinese                                                   | Multi-task      | -                      | 37,175 instructions generated by ChatGPT and human                                                                                                                                           | -     | -                                  |
| [HH-RLHF](https://github.com/anthropics/hh-rlhf/tree/master)                                      | -    | English                                                            | Multi-task      | -                      | The data are described in the paper: Training a Helpful and Harmless Assistant with Reinforcement Learning from Human Feedback.                                                              | -     | MIT                                |
| [InstructionWild](https://github.com/XueFuzhao/InstructionWild)                                   | 104K | English, Chinese                                                   | Multi-task      | Mixed Dataset          | 429 seed instructions from the Internet                                                                                                                                                      | $880  | Research only; OpenAI terms of use |
| [Instruct](https://huggingface.co/datasets/swype/instruct)                                        | 889K | English                                                            | Multi-task      | NLP Tools Augmentation | 888,969 English instructions, augmentation using AllenAI NLP tools                                                                                                                           | -     | -                                  |
| [InstructionTranslation](https://huggingface.co/datasets/theblackcat102/instruction_translations) |      | Multi-lingual                                                      | Multi-task      | -                      | Translations were generated by M2M 12B and the output generations were limited at 512 tokens due to VRAM limit (40G).                                                                        | -     | MIT                                |
| [MOSS](https://github.com/OpenLMLab/MOSS#数据)                                                      | 1.1M | Chinese                                                            | Multi-task      | GPT-3 Generated        | Generated by gpt-3.5-turbo                                                                                                                                                                   |       | Apache-2.0, AGPL-3.0 licenses      |
| [Natural Instructions](https://github.com/allenai/natural-instructions)                           | 5M   | Multi-lingual                                                      | Multi-task      | -                      | 5,040,134 instructions collected from diverse NLP tasks                                                                                                                                      | -     | -                                  |
| [OIG-43M Dataset](https://laion.ai/blog/oig-dataset/)                                             | 43M  | Multi-lingual                                                      | Multi-task      | Collection of Dataset  | Together, LAION, and Ontocord.ai.                                                                                                                                                            | -     |                                    |
| [Prosocial Dialog](https://huggingface.co/datasets/allenai/prosocial-dialog)                      | 166K | English                                                            | Multi-task      | -                      | 165,681 instructions produced by GPT-3 rewrites questions and human feedback                                                                                                                 | -     | -                                  |
| [Vicuna Dataset](https://huggingface.co/datasets/anon8231489123/ShareGPT_Vicuna_unfiltered)       | 75K  | Unavailable (privacy concern)                                      | Multi-task      | Self-Instruct          | ShareGPT                                                                                                                                                                                     | -     | -                                  |
| [xP3](https://huggingface.co/datasets/bigscience/xP3)                                             | 79M  | Multi-lingual                                                      | Multi-task      | -                      | 78,883,588 instructions collected by prompts & datasets across 46 languages & 16 NLP tasks                                                                                                   | -     | -                                  |
