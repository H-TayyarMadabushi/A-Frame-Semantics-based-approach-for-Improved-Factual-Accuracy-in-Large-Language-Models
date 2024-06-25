# FS-RAG: A Frame Semantics based approach for Improved Factual Accuracy in Large Language Models

This repository contains the program code and prompts associated with the paper "[FS-RAG: A Frame Semantics based approach for Improved Factual Accuracy in Large Language Models](https://arxiv.org/abs/2406.16167)".
1. A copy of the paper is available at [here](https://github.com/H-TayyarMadabushi/A-Frame-Semantics-based-approach-for-Improved-Factual-Accuracy-in-Large-Language-Models/blob/main/Paper/FS-RAG-paper.pdf), and on [arXiv](https://arxiv.org/abs/2406.16167).
2. The program code for the automatic generation of frames and frame relations is availble [here](https://github.com/H-TayyarMadabushi/A-Frame-Semantics-based-approach-for-Improved-Factual-Accuracy-in-Large-Language-Models/blob/main/src/frameCreator.py)
3. The prompts used in this study are available [here](https://github.com/H-TayyarMadabushi/A-Frame-Semantics-based-approach-for-Improved-Factual-Accuracy-in-Large-Language-Models/blob/main/src/TestTemplates.py). This includes the exploratory prompts. The final prompts used are part of *Template 6*
4. Running these scripts requires an OpenAI API key, which must be stored in a file called .key

## Summary
We present a novel extension to Retrieval Augmented Generation with the goal of mitigating factual inaccuracies in the output of large language models. Specifically, our method draws on the cognitive linguistic theory of frame semantics for the indexing and retrieval of factual information relevant to helping large language models answer queries. We conduct experiments to demonstrate the effectiveness of this method both in terms of retrieval effectiveness and in terms of the relevance of the frames and frame relations automatically generated. Our results show that this novel mechanism of Frame Semantic-based retrieval, designed to improve Retrieval Augmented Generation (FS-RAG), is effective and offers potential for providing data-driven insights into frame semantics theory. We provide open access to our program code and prompts.

## Citation
If you find yourself building on this work, do consider citing us: 

``` latex
@misc{madabushi2024fsrag,
      title={FS-RAG: A Frame Semantics Based Approach for Improved Factual Accuracy in Large Language Models}, 
      author={Harish Tayyar Madabushi},
      year={2024},
      eprint={2406.16167},
      archivePrefix={arXiv},
      primaryClass={id='cs.CL' full_name='Computation and Language' is_active=True alt_name='cmp-lg' in_archive='cs' is_general=False description='Covers natural language processing. Roughly includes material in ACM Subject Class I.2.7. Note that work on artificial languages (programming languages, logics, formal systems) that does not explicitly address natural-language issues broadly construed (natural-language processing, computational linguistics, speech, text retrieval, etc.) is not appropriate for this area.'}
}}
```
