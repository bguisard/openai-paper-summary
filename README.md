# Summarizing a Research Paper with OpenAI Completion API

OpenAI is hosting a Climate Change Hackathon on November 12-13. As a warm-up to
the hackathon I decided to use their Completion API to summarize the
[Tackling Climate Change with Machine Learning] paper.

[Tackling Climate Change with Machine Learning]: https://arxiv.org/pdf/1906.05433.pdf


This code is heavily inspired by [eco-faqs], which was demo'ed as a proof of
concept from OpenAI.

[eco-faqs]: https://github.com/shyamal-anadkat/eco-faqs


## Colab notebook

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bguisard/openai-paper-summary/blob/main/notebooks/openai_paper_summary.ipynb)


The notebook was designed to run on Google colab, but it should be trivial to
adjust it to run locally if you prefer.


## Summaries

The [summaries] in the repository are the unmodified output of the `text-davinci-002`
model.

[summaries]: ./summaries/
