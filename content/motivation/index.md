---
title: "Motivation"
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
{{< lead >}}
The motivation and importance of the task.
{{< /lead >}}

Although community visibility and the use of specific slang have been approached for years, only a few HS studies (Zsisku et al., 2024 [[1]](#1); Cuccarini et al., 2024 [[2]](#2)) have thoroughly examined the reclamation of slurs, a phenomenon in which terms once used to oppress lose their offensive intent and are transformed by targeted communities into expressions of pride, solidarity and belonging. 

For NLP tools, accurately recognizing these semantic shifts is now crucial to avoid the risk of misclassifying reclaimed language as HS, particularly when produced by marginalized users, thereby paradoxically reinforcing the very harm these tools aim to prevent.

The MultiPRIDE task addresses this challenge by establishing a baseline for detecting reclaimed slurs in LGBTQ+ context. Since the perception of this phenomenon can vary across social and cultural environments, we introduce the task in three different languages (Italian, Spanish, and English), enabling cross-linguistic analysis. Moreover, since reclamation is highly context-dependent and closely tied to the concept of legitimacy, the task also integrates contextual information about the authors (such as their biographies, when available).

## Bibliography
<a id="1">[1]</a> 
Zsisku, E., Zubiaga, A., & Dubossarsky, H. (2024, May). 
Hate speech detection and reclaimed language: Mitigating false positives and compounded discrimination. 
In Proceedings of the 16th ACM Web Science Conference (pp. 241-249)

<a id="2">[2]</a> 
Cuccarini, M., Draetta, L., Ferrando, C., James, L., & Patti, V. (2024). 
ReCLAIM Project: Exploring Italian Slurs Reappropriation with Large Language Models. 
In CEUR WORKSHOP PROCEEDINGS (Vol. 3878, pp. 1-8). CEUR-WS.