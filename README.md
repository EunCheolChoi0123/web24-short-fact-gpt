# FACT-GPT Data and Code

The repository contains scripts and data used in the paper [FACT-GPT: Fact-Checking Augmentation via Claim Matching with LLMs](https://doi.org/10.1145/3589335.3651504).

Below are short descriptions for each of the scripts and files:
1. Script for synthetic tweet generation, as described in section 3.2.1.  
2. Script for fine-tuning gpt-3.5-turbo, as described in section 3.3.2.  
3. Script for prompting LLMs, as described in section 3.3.1. and Figure 4.  
4. Script for fine-tuning Llama models, as described in section 3.3.2.  
5&6. Script for performance evaluation, as described in section 3.3.3.

Replace [LLaMA-Efficient-Tuning](https://github.com/hiyouga/LLaMA-Factory)\src\llmtuner\extras\template.py file with one in this repository to use the same format for system, input, and output prompt in the paper.

As for Twitter data used for test set, we used a dataset collected, documented, and managed by [Chen et al., 2020](https://github.com/echen102/COVID-19-TweetIDs). To comply with Twitter’s [Terms of Service](https://developer.twitter.com/en/developer-terms/agreement-and-policy), we are only publicly releasing the Tweet IDs of the collected Tweets. The data is released for non-commercial research use.

This dataset is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International Public License ([CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)). By using this dataset, you agree to abide by the stipulations in the license, remain in compliance with Twitter’s [Terms of Service](https://developer.twitter.com/en/developer-terms/agreement-and-policy), Meta's [Llama 2 Community License Agreement](https://ai.meta.com/llama/license/), and OpenAI's [Terms of Use](https://openai.com/policies/terms-of-use) and cite the following manuscript: 

Eun Cheol Choi, Emilio Ferrara. 2024. FACT-GPT: Fact-Checking Augmentation via Claim Matching with LLMs. In Companion Proceedings of the ACM Web Conference 2024 (WWW ’24 Companion), May 13–17, 2024, Singapore, Singapore. ACM, New York, NY, USA, 4 pages. https://doi.org/10.1145/3589335.3651504

BibTeX:
```bibtex
@inproceedings{choi2024fact,
  title={FACT-GPT: Fact-Checking Augmentation via Claim Matching with LLMs},
  author={Choi, Eun Cheol and Ferrara, Emilio},
  booktitle={Companion Proceedings of the ACM Web Conference 2024},
  year={2024}
}
```
