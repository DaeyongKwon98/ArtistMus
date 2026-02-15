# 🎵 ArtistMus: A Globally Diverse, Artist-Centric Benchmark for Retrieval-Augmented Music Question Answering

Official repository for the paper: </br>
**ArtistMus: A Globally Diverse, Artist-Centric Benchmark for Retrieval-Augmented Music Question Answering, accepted at LREC 2026**.

# Overview

Large Language Models (LLMs) struggle with music-related question answering due to limited music knowledge in pretraining data.

We introduce:
- **MusWikiDB** — a vector database built from 3.2M passages across 144K music-related Wikipedia pages.
- **ArtistMus** — a multiple-choice QA benchmark of 1,000 questions covering 500 diverse artists.

Our MusWikiDB database outperforms general Wikipedia corpus in both accuracy (+6 pp) and speed (40% faster) in retrieval augmented generation (RAG) situation.

# Paper and Dataset

## Paper
<div align="left" style="display: flex; justify-content: center; margin-top: 10px; gap: 6px; flex-wrap: wrap;">
  <a href="https://arxiv.org/abs/2512.05430">
    <img src="https://img.shields.io/badge/arXiv-2512.05430-AD1C18.svg">
  </a>
</div>

## Dataset
<div align="left" style="display: flex; justify-content: center; margin-top: 10px; gap: 6px; flex-wrap: wrap;">
  <a href="https://drive.google.com/drive/folders/1YVBWTazYO7h8bZC8oVQMljLjUIM0eI7I?usp=sharing">
    <img src="https://img.shields.io/badge/Dataset-Download-2E8B57.svg">
  </a>
</div>

- `MusWikiDB_raw.csv`: 144K music-related Wikipedia pages segmented by category, page, and section.
- `MusWikiDB.csv`: A retrieval-ready database of 3.2M passages constructed using 256-token chunks with 10% overlap.
- `MusWikiDB_bm25_index.zip`: A BM25 index of MusWikiDB built with Pyserini.
- `ArtistMus.csv`: A multiple-choice QA benchmark containing 1,000 questions on 500 diverse artists, including rich metadata and corresponding gold passages for evaluation.

# 📖 Citation

If you find our paper useful in your research, please cite our paper:

```
@article{kwon2025artistmus,
  title={ArtistMus: A Globally Diverse, Artist-Centric Benchmark for Retrieval-Augmented Music Question Answering},
  author={Kwon, Daeyong and Doh, SeungHeon and Nam, Juhan},
  journal={arXiv preprint arXiv:2512.05430},
  year={2025}
}
```

# Contact

For questions, feedback, or collaboration inquiries, please contact: `daeyongkwon@snu.ac.kr`

# License

The code is released under the **MIT License**.
</br>
The dataset is released under the **CC BY 4.0 License**.
