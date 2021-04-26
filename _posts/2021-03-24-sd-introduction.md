---
layout: post
title: Introduction to System Design
author: Sanjib
date: 2021-04-20 12:00
category: sd
color: body-orange
category-desc: System Design
menu: Introduction
menu-desc: Introduction
---

Systems design is the process of defining the architecture, product design, modules, interfaces, and data for a system to satisfy specified requirements. Systems design could be seen as the application of systems theory to product development.  

TF-IDF
Term Frequency - Inverse Document Frequency

tf("term1", doc_i) = term1_count/ words_count

idf("term1") = log(N / nt)

N - Number of documents
nt - Number of documents containing the term1

for(Document doc in documents) {
  doc.score = tf("term1", doc_i) * idf("term1")
            + tf("term2", doc_i) * idf("term2")
            ----
            + tf("termN", doc_i) * idf("termN")
}
