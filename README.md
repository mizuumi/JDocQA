# JDocQA

Document QA dataset for the LREC-COLING2024 paper "JDocQA: Japanese Document Question Answering Dataset for Generative Language Models".

# Dataset

Annotations can be downloaded from [Here](dataset/).

![ test img](/misc/LRECCOLING.gif)

# Paper

Please visit [Paper](https://arxiv.org/abs/2403.19454).

# Cite

```
@inproceedings{onami_jdocqa_2024,
    title = "JDocQA: Japanese Document Question Answering Dataset for Generative Language Models",
    author = "Onami, Eri  and
      Shuhei, Kurita  and
      Miyanishi, Taiki and
      Watanabe, Taro",
    booktitle = "The 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation",
    month = may,
    year = "2024",
    address = "Trino, Italy",
    abstract = "Document question answering is a task of question answering on given documents such as reports, slides, pamphlets, and websites, and it is a truly demanding task as paper and electronic forms of documents are so common in our society. This is known as a quite challenging task because it requires not only text understanding but also understanding of figures and tables, and hence visual question answering (VQA) methods are often examined in addition to textual approaches. We introduce Japanese Document Question Answering (JDocQA), a large-scale document-based QA dataset, essentially requiring both visual and textual information to answer questions, which comprises 5,504 documents in PDF format and annotated 11,600 question-and-answer instances in Japanese. Each QA instance includes references to the document pages and bounding boxes for the answer clues. We incorporate multiple categories of questions and unanswerable questions from the document for realistic question-answering applications. We empirically evaluate the effectiveness of our dataset with text-based large language models (LLMs) and multimodal models. Incorporating unanswerable questions in finetuning may contribute to harnessing the so-called hallucination generation.",
}

```

