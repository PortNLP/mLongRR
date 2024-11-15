# Multilingual Evaluation of Long Context Retrieval and Reasoning (mLongRR)

This repository contains the materials for our paper, [Multilingual Evaluation of Long Context Retrieval and Reasoning](https://aclanthology.org/2024.mrl-1.18/) presented at MRL 2024 (@EMNLP). The scripts and the notebooks can be used to reproduce the experiments with your dataset.

## Authors

Ameeta Agrawal, Andy Dang, Sina Bagheri Nezhad, Rhitabrat Pokharel, Russell Scheinberg.

## Abstract

Recent large language models (LLMs) demonstrate impressive capabilities in handling long contexts, some exhibiting near-perfect recall on synthetic retrieval tasks. However, these evaluations have mainly focused on English text and involved a single target sentence within lengthy contexts. Our work investigates how LLM performance generalizes to multilingual settings with multiple hidden target sentences. We create a new dataset – mLongRR – to comprehensively evaluate several multilingual long-context LLMs on retrieval and reasoning tasks across five languages: English, Vietnamese, Indonesian, Swahili, and Somali. These languages share the Latin script but belong to distinct language families and resource levels. Our analysis reveals a significant performance gap between languages. The best-performing models such as Gemini-1.5 and GPT-4o, achieve around 96% accuracy in English to around 36% in Somali with a single target sentence. However, this accuracy drops to 40% in English and 0% in Somali when dealing with three target sentences. Our findings highlight the challenges long-context LLMs face when processing longer contexts, an increase in the number of target sentences, or languages of lower resource levels.

## Cite

If you use our work, please cite our paper as follows:

```bibtex
@inproceedings{agrawal-etal-2024-evaluating,
    title = "Evaluating Multilingual Long-Context Models for Retrieval and Reasoning",
    author = "Agrawal, Ameeta  and
      Dang, Andy  and
      Bagheri Nezhad, Sina  and
      Pokharel, Rhitabrat  and
      Scheinberg, Russell",
    editor = {S{\"a}lev{\"a}, Jonne  and
      Owodunni, Abraham},
    booktitle = "Proceedings of the Fourth Workshop on Multilingual Representation Learning (MRL 2024)",
    month = nov,
    year = "2024",
    address = "Miami, Florida, USA",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.mrl-1.18",
    pages = "216--231",
}
```
