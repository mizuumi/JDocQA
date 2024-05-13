# Annotation files

dataset/annotation_files/jdocqa_train_all.json
dataset/annotation_files/jdocqa_validation_all.json
dataset/annotation_files/jdocqa_test_all.json

Annotations:

```
'pdf_category': Document category.
'pdf_name': PDF name.
'question_page_number': Where annotators found answer of the questions.
'answer_type': (1):Yes/No questions, (2)Factoid questions, (3)Numerical questions, (4)Open-ended questions.
'type_of_image': (1): Table, (2): Bar chart, (3): Line chart, (4): Pie chart, (5): Map, (6): Other figures, (7): Mixtured writing style from left to the right and from upside to the downside, (8): Drawings, (9): Others.
'original_context': Extracted texts from PDF. 
'context': Removed noises from 'original_context'.
'original_question': Annotated questions.
'question': Question query for models.
'original_answer': Annotated answers.
'no_reason': Unanswerable question-> 0, Answerable question-> 1
```


# Raw documents

Please [download from here](https://vlm-lab-fileshare.s3.ap-northeast-1.amazonaws.com/pdf_files.zip).
