---
title: "Task Description"
layoutBackgroundHeaderSpace: true
draft: false
showDate: false
showAuthor: false
showReadingTime: false
showEdit: false
showPagination: false
layout: "wide"
---
<style>
.prose, .prose-lg {
    max-width: none !important;
}
.container {
    max-width: 95vw !important;
}
</style>


This is a binary classification task in which systems must classify whether a term related to LGBTQ+ context in a sentence is used with a reclamatory intent. 

Participants will be provided either with:
- **Textual**: Textual content of the tweet only.
- **Textual + Contextual**: In addition to the tweet content, participants have access to optional contextual information related to the author's profile –when available, such as their biography. 

The task is proposed within a multilingual perspective, encompassing data in **Italian**, **Spanish** and **English**. 
Participants may choose to work on one or more languages-specific tasks. 
Although not mandatory, participants are encouraged to foster cross-linguistic analysis. 

### Evaluation

Each participating team will be provided with:
- **Training Set**: fully labeled which can be used for training the model.
- **Dev Set**: fully labeled which should be used for hyperparameter-tuning.
- **Test Set**: will be published after the the assessment timeframe.

Evaluation will be based on the standard metrics known in the literature –including accuracy, precision, recall and F1-score. The submissions will be ranked by F1-score –both precision, recall and F-measure. 

Further details on evaluation metrics, number of accepted runs during the evaluation phase, usage of external data and, information on the baseline will be shared in the Task guidelines soon.

