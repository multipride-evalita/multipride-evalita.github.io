---
title: "Introduction to the Task"
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

Welcome to MultiPRIDE web page! 🌈
MultiPRIDE (Multilingual Automatic Detection of Reclamation of Slurs in the LGBTQ+ Context) is part of **Evalita 2026**, the 9th evaluation campaign of Natural Language Processing and Speech tools for Italian, which will take place in **Bari, Italy, on February 26–27, 2026**.

Social networks have become the primary means of communication for most people. The growth of online interactions has raised a new challenge for Natural Language Processing (NLP) systems: the ability to detect and prevent the spread of offensive content –as Hate Speech (HS) and abusive language– targeting specific groups, while also safeguarding freedom of expression and promoting inclusive and fair communication. This is particularly relevant in the case of **semantic reclamation**, a phenomenon in which words historically used as slurs are reappropriated by targeted communities, gaining new, empowering, or neutral meanings. In these contexts, such terms often lose their offensive intent and instead express a sense of belonging and solidarity among the group members (Bianchi, 2014 [[1]](#1), Cepollaro, 2023 [[2]](#2)). 

The MultiPRIDE task will focus on identifying reclaimed slurs, in Italian, Spanish and English, within  the context of the LGBTQ+ community.

### Target Audience

The task is open to everyone from industry and academia. In particular, we encourage the participation of researchers, industrial teams, and students. 



###
The motivation and importance of the task.

Although community visibility and the use of specific slang have been approached for years, only a few HS studies (Zsisku et al., 2024 [[3]](#3); Cuccarini et al., 2024 [[4]](#4)) have thoroughly examined the reclamation of slurs, a phenomenon in which terms once used to oppress lose their offensive intent and are transformed by targeted communities into expressions of pride, solidarity and belonging. 

For NLP tools, accurately recognizing these semantic shifts is now crucial to avoid the risk of misclassifying reclaimed language as HS, particularly when produced by marginalized users, thereby paradoxically reinforcing the very harm these tools aim to prevent.

The MultiPRIDE task addresses this challenge by establishing a baseline for detecting reclaimed slurs in LGBTQ+ context. Since the perception of this phenomenon can vary across social and cultural environments, we introduce the task in three different languages (Italian, Spanish, and English), enabling cross-linguistic analysis. Moreover, since reclamation is highly context-dependent and closely tied to the concept of legitimacy, the task also integrates contextual information about the authors (such as their biographies, when available).

### Bibliography
<a id="1">[1]</a> 
Bianchi, C. (2014). 
Slurs and appropriation: An echoic account. 
Journal of Pragmatics, 66, 35-44.

<a id="2">[2]</a> 
Cepollaro, B., de Sa, D.L. (2023). 
The successes of reclamation, Synthese 202 (6), 205.

<a id="3">[3]</a> 
Zsisku, E., Zubiaga, A., & Dubossarsky, H. (2024, May). 
Hate speech detection and reclaimed language: Mitigating false positives and compounded discrimination. 
In Proceedings of the 16th ACM Web Science Conference (pp. 241-249)

<a id="4">[4]</a> 
Cuccarini, M., Draetta, L., Ferrando, C., James, L., & Patti, V. (2024). 
ReCLAIM Project: Exploring Italian Slurs Reappropriation with Large Language Models. 
In CEUR WORKSHOP PROCEEDINGS (Vol. 3878, pp. 1-8). CEUR-WS.