# FS-RAG: A Frame Semantics based approach for Improved Factual Accuracy in Large Language Models

This repository contains the program code and prompts associated with the paper "FS-RAG: A Frame Semantics based approach for Improved Factual Accuracy in Large Language Models".
1. A copy of the paper is available at [here](https://github.com/H-TayyarMadabushi/A-Frame-Semantics-based-approach-for-Improved-Factual-Accuracy-in-Large-Language-Models/blob/main/Paper/FS-RAG-paper.pdf).
2. The program code for the automatic generation of frames and frame relations is availble [here](https://github.com/H-TayyarMadabushi/A-Frame-Semantics-based-approach-for-Improved-Factual-Accuracy-in-Large-Language-Models/blob/main/src/frameCreator.py)
3. The prompts used in this study are available [here](https://github.com/H-TayyarMadabushi/A-Frame-Semantics-based-approach-for-Improved-Factual-Accuracy-in-Large-Language-Models/blob/main/src/TestTemplates.py). This includes the exploratory prompts. The final prompts used are part of *Template 6*
4. Running these scripts requires an OpenAI API key, which must be stored in a file called .key

## Summary
We present a novel extension to Retrieval Augmented Generation with the goal of mitigating factual inaccuracies in the output of large language models. Specifically, our method draws on the cognitive linguistic theory of frame semantics for the indexing and retrieval of factual information relevant to helping large language models answer queries. We conduct experiments to demonstrate the effectiveness of this method both in terms of retrieval effectiveness and in terms of the relevance of the frames and frame relations automatically generated. Our results show that this novel mechanism of Frame Semantic-based retrieval, designed to improve Retrieval Augmented Generation (FS-RAG), is effective and offers potential for providing data-driven insights into frame semantics theory. We provide open access to our program code and prompts.
