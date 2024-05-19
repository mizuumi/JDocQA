# JDocQA

Document QA dataset for the LREC-COLING2024 paper "JDocQA: Japanese Document Question Answering Dataset for Generative Language Models".

# Dataset

Annotations can be downloaded from [Here](dataset/).

![ test img](/misc/LRECCOLING.gif)

# Paper

Please visit [Paper](https://arxiv.org/abs/2403.19454).

# Dataset License

JDocQA dataset annotations are distributed under CC BY-SA 4.0. We are delighted to see many derivations from JDocQA! When you create any derivations, e.g., datasets, papers, etc, from JDocQA, please cite our paper accordingly. If your derivations are web-based projects, please cite our paper and include the link to this github page.

# Cite

```
@inproceedings{onami-etal-2024-jdocqa-japanese,
    title = "{JD}oc{QA}: {J}apanese Document Question Answering Dataset for Generative Language Models",
    author = "Onami, Eri  and
      Kurita, Shuhei  and
      Miyanishi, Taiki  and
      Watanabe, Taro",
    editor = "Calzolari, Nicoletta  and
      Kan, Min-Yen  and
      Hoste, Veronique  and
      Lenci, Alessandro  and
      Sakti, Sakriani  and
      Xue, Nianwen",
    booktitle = "Proceedings of the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC-COLING 2024)",
    month = may,
    year = "2024",
    address = "Torino, Italy",
    publisher = "ELRA and ICCL",
    url = "https://aclanthology.org/2024.lrec-main.830",
    pages = "9503--9514",
    abstract = "Document question answering is a task of question answering on given documents such as reports, slides, pamphlets, and websites, and it is a truly demanding task as paper and electronic forms of documents are so common in our society. This is known as a quite challenging task because it requires not only text understanding but also understanding of figures and tables, and hence visual question answering (VQA) methods are often examined in addition to textual approaches. We introduce Japanese Document Question Answering (JDocQA), a large-scale document-based QA dataset, essentially requiring both visual and textual information to answer questions, which comprises 5,504 documents in PDF format and annotated 11,600 question-and-answer instances in Japanese. Each QA instance includes references to the document pages and bounding boxes for the answer clues. We incorporate multiple categories of questions and \textit{unanswerable} questions from the document for realistic question-answering applications. We empirically evaluate the effectiveness of our dataset with text-based large language models (LLMs) and multimodal models. Incorporating \textit{unanswerable} questions in finetuning may contribute to harnessing the so-called hallucination generation.",
}
```

