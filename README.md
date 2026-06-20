# OpenBioRQ — Project Page

**OpenBioRQ: Unsolved Biomedical Research Questions for Agents** · Minbyul Jeong (Upstage AI)

🌐 **Project page:** https://minstar.github.io/OpenBioRQ/
🤗 **Dataset:** https://huggingface.co/datasets/Minbyul/OpenBioRQ

A retrieval-grounded agentic benchmark of **12,553** unsolved biomedical research questions across 12 domains.
It treats open questions as a *faithfulness-and-abstention* probe: agent citations almost always resolve
(>99%), yet ~**15.9%** point to the wrong paper — a failure mode that answer-key QA cannot see.

This repository hosts the static project page (`index.html`, served via GitHub Pages). The benchmark data,
rubrics, and per-model predictions live on the [Hugging Face dataset](https://huggingface.co/datasets/Minbyul/OpenBioRQ).

## Citation

```bibtex
@misc{jeong2026openbiorq,
  title         = {OpenBioRQ: Unsolved Biomedical Research Questions for Agents},
  author        = {Minbyul Jeong},
  year          = {2026},
  howpublished  = {\url{https://huggingface.co/datasets/Minbyul/OpenBioRQ}},
  note          = {Dataset and benchmark}
}
```
