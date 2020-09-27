---
title: "Incomplete Utterance Rewriting as Semantic Segmentation"
collection: publications
permalink: /publication/2020-09-16-incomplete
excerpt: '**Qian Liu**, Bei Chen, Jian-Guang Lou, Bin Zhou, Dongmei Zhang<br>In *Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing (**NeurIPS-2020**)*'
date: 2020-09-16
venue:
---

Introduction
===

![Demo](/images/incomplete-demo.jpg)

Recent years the task of incomplete utterance rewriting has raised a large attention. Previous works usually shape it as a machine translation task and employ sequence to sequence based architecture with copy mechanism. In this paper, we present a novel and extensive approach, which formulates it as a semantic segmentation task. Instead of generating from scratch, such a formulation introduces edit operations and shapes the problem as prediction of a word-level edit matrix. Benefiting from being able to capture both local and global information, our approach achieves state-of-the-art performance on several public datasets. Furthermore, our approach is four times faster than the standard approach in inference.

Cite
===

```latex
@inproceedings{qian2020incomplete,
  title={Incomplete Utterance Rewriting as Semantic Segmentation},
  author={Liu, Qian and Chen, Bei and Lou, Jian-Guang and Zhou, Bin and Zhang, Dongmei},
  booktitle={Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing},
  year={2020}
}
```