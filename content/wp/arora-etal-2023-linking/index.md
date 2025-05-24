---
title: "Linking Representations with Multimodal Contrastive Learning"
authors:
  - Abhishek Arora
  - Xinmei Yang
  - Shao-Yu Jheng
  - Melissa Dell
date: "2024-06-21"
publication_types:
  - working-paper
# draft: true
abstract: |
  Many applications require linking individuals, firms, or locations across datasets.
  Most widely used methods, especially in social science, do not employ deep learning,
  with record linkage commonly approached using string matching techniques. Moreover,
  existing methods do not exploit the inherently multimodal nature of documents. In
  historical record linkage applications, documents are typically noisily transcribed by
  optical character recognition (OCR).

  Linkage with just OCR'ed texts may fail due to noise, whereas linkage with just image
  crops may also fail because vision models lack language understanding (e.g., of
  abbreviations or other different ways of writing firm names). To leverage multimodal
  learning, this study develops CLIPPINGS (Contrastively LInking Pooled Pre-trained
  Embeddings). CLIPPINGS aligns symmetric vision and language bi-encoders, through
  contrastive language-image pre-training on document images and their corresponding
  OCR'ed texts.

  It then contrastively learns a metric space where the pooled image-text embedding for a
  given instance is close to embeddings in the same class (e.g., the same firm or location)
  and distant from embeddings of a different class. Data are linked by treating linkage as
  a nearest-neighbor retrieval problem with the multimodal embeddings. CLIPPINGS
  outperforms widely used string matching methods by a wide margin in linking mid-20th
  century Japanese firms across financial documents.

links:
  - name: "ArXiv PDF"
    url: "https://arxiv.org/pdf/2304.03464.pdf"
  - name: "ArXiv abstract"
    url: "https://arxiv.org/abs/2304.03464"
---
