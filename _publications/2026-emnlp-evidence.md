---
title: "Evidence-Grounded Reward Shaping for Document Visual Question Answering"
collection: publications
category: conferences
under_review: true
permalink: /publications/2026-emnlp-evidence
date: 2026-01-01
venue: 'Conference on Empirical Methods in Natural Language Processing (EMNLP)'
paperurl: '/files/evigrpo.pdf'
framework_image: '/images/publications/evigrpo-framework.png'
citation: 'Wang Z, et al. Evidence-Grounded Reward Shaping for Document Visual Question Answering. EMNLP 2026.'
---

**EMNLP 2026 (CCF-B), Under Review** — First Author

We propose EviGRPO, a reinforcement learning framework that augments Group Relative Policy Optimization (GRPO) with an evidence-grounded reward, encouraging the model to both answer correctly and cite verifiable evidence from the document. Our composite reward combines answer accuracy (measured by ANLS) with an evidence matching signal that evaluates whether claimed evidence spans appear in the ground-truth document text. Experiments on DocVQA show that evidence-grounded reward not only improves evidence quality but also boosts answer accuracy itself: our best model achieves 0.8054 ANLS on the official DocVQA test set, outperforming the accuracy-only RL baseline (0.7896) and supervised fine-tuning (0.6896).
