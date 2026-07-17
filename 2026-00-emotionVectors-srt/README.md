# (Slides) Partial Replication of Anthropic's Emotion Vectors Using Gemma 4 E2B and GPT 2 Medium Inside a Google Colab T4 Notebook

## Event

Internal Research Seminar

## Organizer

Samsung Research Tijuana

## Date

May 12, 2023

## Format

Virtual Oral Presentation

## Location

Online

## Abstract

We discuss the results obtained by replicating specific sections of Anthropic's Emotion Vectors. These particular sections encompass (i) PCA Valence/Arousal Projection, (ii) Emotion Vector Cosine Similarity, and (iii) Causal Effects of Emotion Vector Steering. Anthropic found that emotion vectors do affect reasoning and output of Claude Sonnet 4.5, an LLM developed by Anthropic. Their findings suggest that the semantic understanding of the model is comprised of the operative emotion vector, which is the vector currently processed by the model originating from the input prompt. These claims are partially supported by other non-academic replications using meta-llama/Llama-3.3-70B-Instruct and google/gemma-4-E4B, although other models have not been used for replication attempts such as openai-community/gpt-2-medium and google/gemma-4-E2B. Our contribution replicates (i), (ii), and (iii) using openai-community/gpt-2-medium and google/gemma-4-E2B inside a Google Colab environment. We found that (1) both models display an emergent Valence axis in the PCA plot, (2) both models display similarity clusters of related emotion vectors, and (3) openai-community/gpt-2-medium displays greater steering sensitivity compared to google/gemma-4-E2B. Our findings suggest that emotion vectors do emerge on antiquated LLMs such as openai-community/gpt-2-medium, and on modern offerings such as google/gemma-4-E2B. Furthermore, our findings about emotion vector steering offer compelling evidence of their functional effects being present on models not related to the Claude family.

## Related Work

Repository: [EmotionVectorExtraction-Gemma4-GPT2](https://github.com/NotsoJharedtrollOx17/EmotionVectorExtraction-Gemma4-GPT2)

## Materials

- slidesPartialReplicationEmotionVectors.pdf

## Citation

```
@misc{floresazcona2026emotionSlides,
  author       = {Flores-Azcona, Abraham Jhared},
  title        = {Partial Replication of Anthropic's Emotion Vectors Using Gemma 4 E2B and GPT 2 Medium Inside a Google Colab T4 Notebook},
  year         = {2026},
  month        = may,
  type         = {Presentation Slides},
  eventtitle   = {Internal Research Seminar},
  institution  = {Samsung Research Tijuana},
  note         = {Slides written with open source material},
  url          = {https://github.com/NotsoJharedtrollOx17/technical-presentations/tree/main/2026-00-emotionVectors-srt}
}
```

## Notes

- _Although an internal presentation, research materials were posted in the relevant GitHub repo 5 days prior._