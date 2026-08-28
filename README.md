# Awesome LLMs for Academic Writing

A curated, independently verified collection of research papers, datasets, tools, implementations, and learning resources on Large Language Models in academic and scientific writing — with a focus on **stylistic homogenization risk**: how LLM assistance both lowers linguistic barriers for non-native English researchers and risks flattening scholarly voice into a uniform algorithmic style.

## Contents
- [Overview](#overview)
- [AI-Assisted Research Paper](#ai-assisted-research-paper)
- [Survey Papers](#survey-papers)
- [Foundational Papers](#foundational-papers)
- [Stylistic & Lexical Impact Studies](#stylistic--lexical-impact-studies)
- [Automated Writing & Literature Review Generation](#automated-writing--literature-review-generation)
- [Ethics, Authorship & Integrity](#ethics-authorship--integrity)
- [Datasets](#datasets)
- [Tools and Libraries](#tools-and-libraries)
- [GitHub Implementations](#github-implementations)
- [Tutorials](#tutorials)
- [Citation Integrity Audit](#citation-integrity-audit)
- [License](#license)

## Overview

Large Language Models such as ChatGPT and GPT-4 have become embedded in nearly every stage of the academic writing pipeline — drafting abstracts, outlining literature reviews, and polishing prose for non-native English speakers. This assistance offers genuine benefits, most notably as a "linguistic equalizer" that measurably raises the lexical sophistication of research produced by non-native English-speaking authors. At the same time, because millions of researchers now lean on the same small set of underlying models, a growing empirical record shows LLM-assisted writing converging toward a narrower, more uniform style: reduced lexical and semantic diversity in co-written text, homogenized creative ideation, and detectable shifts in the vocabulary of published abstracts across entire disciplines.

This repository curates the research base for that tension. It brings together survey papers mapping LLM capabilities and adoption in academia, foundational architecture papers, empirical studies quantifying stylistic and lexical convergence, systems that automate literature-review and survey writing, and work on the ethics, authorship, and integrity questions raised by AI-assisted scholarship — including the well-documented problem of hallucinated citations. Every paper listed here was independently checked against its primary source (arXiv, DOI/Crossref, ACM DL, or JMIR) rather than accepted on an AI tool's word, in keeping with the citation-integrity audit that accompanies this repository.

## AI-Assisted Research Paper

**Stylistic Homogenization Risk in Large Language Model-Assisted Academic Writing** — examines the double-edged nature of LLM writing assistance: its role as a linguistic equalizer for non-native English researchers, weighed against the risk of a stagnant, homogenized academic writing style, an eroding sense of authorship accountability, and a self-reinforcing "epistemic echo chamber" as future models train on LLM-influenced text.
[View Paper](paper/AI_Assisted_Research_Paper.pdf)

## Survey Papers

- **Large Language Models for Automated Scholarly Paper Review: A Survey**
  Zhuang, Chen, Xu, Jiang, Lin (2025), arXiv preprint
  [Paper](https://arxiv.org/abs/2501.10326)
  Comprehensive survey of LLMs used specifically in automated manuscript review.

- **How much are LLMs changing the language of academic papers after ChatGPT? A multi-database and full text analysis**
  (2025), arXiv preprint
  [Paper](https://arxiv.org/abs/2509.09596)
  Large-scale analysis of 2.4M+ PubMed Central articles measuring LLM-associated term frequency in published writing.

- **Exploring the adoption of ChatGPT in academic publishing: insights and lessons for scientific writing**
  Homolak (2023), *Croatian Medical Journal*, 64(3), 205–207
  [Paper (DOI)](https://doi.org/10.3325/cmj.2023.64.205)
  Early editorial on AI-detection inconsistency in scientific abstracts.

## Foundational Papers

- **A Comprehensive Overview of Large Language Models**
  Naveed, Khan, Qiu, Saqib, Anwar, Usman, Akhtar, Barnes, Mian (2023), arXiv preprint
  [Paper](https://arxiv.org/abs/2307.06435)
  Widely-cited survey of LLM architectures and emergent capabilities underlying every downstream application discussed here.

## Stylistic & Lexical Impact Studies

- **ChatGPT as Linguistic Equalizer? Quantifying LLM-Driven Lexical Shifts in Academic Writing**
  Lin, Zhao, Tian, Li (2025), arXiv preprint
  [Paper](https://arxiv.org/abs/2504.12317)
  Causal analysis of 2.8M OpenAlex articles showing ChatGPT raises lexical complexity for non-native-English authors.

- **Homogenization Effects of Large Language Models on Human Creative Ideation**
  Anderson, Shah, Kreminski (2024), *Creativity and Cognition (C&C '24)*
  [Paper (DOI)](https://doi.org/10.1145/3635636.3656204)
  36-participant study finding ChatGPT users produce less semantically distinct ideas than users of an alternative tool.

- **Homogenizing effect of large language models (LLMs) on creative diversity: An empirical comparison of human and ChatGPT writing**
  Moon, Green, Kushlev (2025), *Computers in Human Behavior: Artificial Humans*, 6, 100207
  [Paper (DOI)](https://doi.org/10.1016/j.chbah.2025.100207)
  Direct empirical comparison of human vs. ChatGPT writing diversity.

- **Does Writing with Language Models Reduce Content Diversity?**
  Padmakumar, He (2024), *ICLR 2024*
  [Paper](https://arxiv.org/abs/2309.05196)
  Controlled experiment showing InstructGPT significantly reduces lexical and content diversity in co-written essays.

- **The Homogenizing Effect of Large Language Models on Human Expression and Thought**
  Sourati, Ziabari, Dehghani (2025), arXiv preprint
  [Paper](https://arxiv.org/abs/2508.01491)
  Broader treatment of LLM-driven homogenization extending into human thought patterns.

- **Divergent LLM Adoption and Heterogeneous Convergence Paths in Research Writing**
  Cong, Zhu (2024), arXiv preprint
  [Paper](https://arxiv.org/abs/2504.13629)
  627,000-paper analysis showing convergence is uneven — most pronounced among early adopters and junior scholars.

- **Examining Linguistic Shifts in Academic Writing Before and After the Launch of ChatGPT: A Study on Preprint Papers**
  Bao, Zhao, Mao, Zhang (2025), arXiv preprint
  [Paper](https://arxiv.org/abs/2505.12218)
  823,798-abstract analysis finding Computer Science shows the most pronounced post-ChatGPT style shift.

## Automated Writing & Literature Review Generation

- **Large Language Models for Automated Literature Review: An Evaluation of Reference Generation, Abstract Writing, and Review Composition**
  Tang, Duan, Cai (2025), arXiv preprint
  [Paper](https://arxiv.org/abs/2412.13612)
  Introduces hallucination-rate and semantic-coverage metrics for LLM-generated literature reviews.

- **AutoSurvey: Large Language Models Can Automatically Write Surveys**
  Wang, Guo, Yao, et al. (2024), arXiv preprint
  [Paper](https://arxiv.org/abs/2406.10252)
  Automated survey-writing pipeline addressing context-window and evaluation-benchmark limitations.

- **InteractiveSurvey: An LLM-based Personalized and Interactive Survey Paper Generation System**
  (2025), arXiv preprint
  [Paper](https://arxiv.org/abs/2504.08762)
  RAG-based system letting users customize outline and categorization during generation.

- **Evaluation Sheet for Deep Research: A Use Case for Academic Survey Writing**
  Azime, Belay, Tonja (2025), arXiv preprint
  [Paper](https://arxiv.org/abs/2510.01283)
  Evaluation rubric comparing OpenAI's and Google's deep-research tools on academic survey generation.

## Ethics, Authorship & Integrity

- **ChatGPT for scientific paper writing—promises and perils**
  He, Yang, Zuo, Lin (2023), *The Innovation*, 4(6), 100524
  [Paper (DOI)](https://doi.org/10.1016/j.xinn.2023.100524)
  Frames LLM writing assistance as a "double-edged sword" — origin of the stylistic-stagnation concern this repository examines.

- **Do Language Models Know When They're Hallucinating References?**
  Agrawal, Suzgun, Mackey, Kalai (2024), *Findings of ACL: EACL 2024*, pp. 912–928
  [Paper](https://arxiv.org/abs/2305.18248)
  Proposes hallucinated references as a tractable "model organism" for studying LLM hallucination.

- **On the Detectability of ChatGPT Content: Benchmarking, Methodology, and Evaluation through the Lens of Academic Writing**
  Liu, Yao, Li, Luo (2024), *ACM CCS '24*
  [Paper](https://arxiv.org/abs/2306.05524)
  2.8M-sample benchmark and detector (CheckGPT) built specifically for academic abstracts.

- **ChatGPT or academic scientist? Distinguishing authorship with over 99% accuracy using off-the-shelf machine learning tools**
  Desaire, Chua, Isom, Jarosova, Hua (2023), arXiv preprint
  [Paper](https://arxiv.org/abs/2303.16352)
  High-accuracy authorship attribution using simple, interpretable stylometric features.

- **Influence of Topic Familiarity and Prompt Specificity on Citation Fabrication in Mental Health Research Using Large Language Models: Experimental Study**
  Linardon, Jarman, McClure, Anderson, Liu, Messer (2025), *JMIR*
  [Paper (DOI)](https://doi.org/10.2196/80371)
  Shows citation-fabrication rates vary systematically with topic familiarity and prompt specificity.

## Datasets

- **arXiv Dataset (Kaggle bulk metadata)** — [Link](https://www.kaggle.com/datasets/Cornell-University/arxiv) — metadata/abstracts for 2M+ papers, used by several stylistic-shift studies above.
- **OpenAlex** — [Link](https://openalex.org/) — the 2.8M-article corpus behind Lin et al.'s (2025) lexical-shift study.
- **CHEAT Dataset** — [Link](https://arxiv.org/abs/2304.12008) — 35,304 synthetic ChatGPT-written/polished abstracts paired with originals, for training/evaluating detectors.

## Tools and Libraries

- **Zotero** — [Link](https://www.zotero.org/) — reference management.
- **Semantic Scholar API** — [Link](https://api.semanticscholar.org/) — programmatic paper search/verification.
- **Crossref API** — [Link](https://www.crossref.org/) — DOI metadata verification.
- **scite.ai** — [Link](https://scite.ai/) — citation-context verification (supports/contrasts/mentions).
- **Grammarly** — [Link](https://www.grammarly.com/) — AI-assisted writing/grammar tool.

## GitHub Implementations

- **AutoSurveys/AutoSurvey** — [Link](https://github.com/AutoSurveys/AutoSurvey) — official AutoSurvey implementation.
- **microsoft/hallucinatedreferences** — [Link](https://github.com/microsoft/hallucinatedreferences) — hallucinated-reference consistency-check methodology.
- **eric-mitchell/detect-gpt** — [Link](https://github.com/eric-mitchell/detect-gpt) — official DetectGPT implementation.
- **openai/gpt-2-output-dataset** — [Link](https://github.com/openai/gpt-2-output-dataset) — OpenAI's original GPT-2 output detector.
- **huggingface/transformers** — [Link](https://github.com/huggingface/transformers) — standard library underlying most LLM tooling referenced here.

## Tutorials

- [GitHub Docs — Get Started](https://docs.github.com/en/get-started)
- [Markdown Guide](https://www.markdownguide.org/)
- [Semantic Scholar API Docs](https://www.semanticscholar.org/product/api)
- [Crossref REST API Docs](https://github.com/CrossRef/rest-api-doc)
- [DetectGPT Project Page](https://ericmitchell.ai/detectgpt) — background tutorial on zero-shot AI-text detection methodology.

## Citation Integrity Audit

This repository's reference list — including the AI-assisted paper's own citations — was independently checked for authenticity and claim-support accuracy: every title/author/year was confirmed against arXiv, DOI/Crossref, ACM DL, or JMIR before inclusion.
[View Audit](citation-audit/Citation_Integrity_Audit.pdf)

## License

Original content (this README, the audit, and the paper) is licensed under the MIT License — see [LICENSE](LICENSE). Linked external papers and resources remain under their own copyright/license.
