# Annotation files

Annotations are here:
```sh
dataset/annotation_files/jdocqa_train_all.json
dataset/annotation_files/jdocqa_validation_all.json
dataset/annotation_files/jdocqa_test_all.json
```

Annotation entries:

```
'pdf_category': Document category.
'pdf_name': PDF name.
'question_page_number': Where annotators found answer of the questions.
'answer_type': (1):Yes/No questions, (2)Factoid questions, (3)Numerical questions, (4)Open-ended questions.
'type_of_image': (1): Table, (2): Bar chart, (3): Line chart, (4): Pie chart, (5): Map, (6): Other figures, (7): Mixtured writing style from left to the right and from upside to the downside, (8): Drawings, (9): Others. Note that this enrty is for statistical purpose in our paper and some labels are missing.
'original_context': Extracted texts from PDF. 
'context': Removed noises from 'original_context'.
'original_question': Annotated questions.
'question': Question query for models.
'original_answer': Annotated answers.
'no_reason': Unanswerable question-> 0, Answerable question-> 1, Multi page question -> 2. They can be jointly flagged such as `1,2`.
'multiple_select_question': 4 multiple select questions (A), (B), (C), (D).
'multiple_select_answer': Answer of 'multiple_select_question'.
```

## pdf_category
We renamed the several category names upon the paper for the interpretability.
- `Document` category in the PDF set as `Report` in the paper.
- `Kouhou` category in the PDF set as `Pamplet` in the paper.

# Annotated documents

Please [download from here](https://vlm-lab-fileshare.s3.ap-northeast-1.amazonaws.com/pdf_files.zip). Do not directly link to the zip file from any other places as we may change this link without any notices.
