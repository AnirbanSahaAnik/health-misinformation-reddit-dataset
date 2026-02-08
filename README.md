# Health Misinformation Reddit Dataset

A curated dataset of health misinformation posts on **COVID-19**, **influenza**, and **HIV**, collected from Reddit.  
Posts were annotated using a combination of **classifier-assisted labeling** and **expert validation**.

This dataset supports peer-reviewed research published at **COLM 2025** and **EMNLP 2025**, focusing on **multi-agent retrieval-augmented counterspeech** and **literacy-controlled response generation**.

---

## 📁 Dataset Access

### 📄 CSV File
```
data/Health_Misinformation_Reddit_Dataset.csv
```

### 🤗 Hugging Face Dataset
https://huggingface.co/datasets/AnirbanSaha/health-misinformation-reddit-dataset

---

## 📊 Data Schema

| Column | Description |
|------|------------|
| `idx` | Unique index for each Reddit post |
| `text` | Reddit post content containing health misinformation |

---

## 🎯 Intended Use

This dataset is designed for research on:

- Health misinformation detection  
- Evidence-based counterspeech generation  
- Retrieval-Augmented Generation (RAG)  
- Multi-agent LLM systems  
- Literacy- and audience-aware response generation  
- Public health communication  

---

## ⚠️ Ethical Considerations

- The dataset contains **real-world misinformation** and should be used responsibly.  
- Content may include **misleading or harmful claims** related to public health.  
- Models trained on this data should incorporate safeguards to avoid amplifying misinformation.

---

## 📜 License

This dataset is released under the  
**Creative Commons Attribution 4.0 International (CC BY 4.0)**

https://creativecommons.org/licenses/by/4.0/

You are free to use, share, and adapt the dataset with appropriate attribution.

---

## 📚 Citation

If you use this dataset, please cite the relevant paper(s) below.

### 🔹 Main Dataset & Multi-Agent Framework (COLM 2025)

```bibtex
@inproceedings{anik2025multiagent,
  title={Multi-Agent Retrieval-Augmented Framework for Evidence-Based Counterspeech Against Health Misinformation},
  author={Anirban Saha Anik and Xiaoying Song and Elliott Wang and Bryan Wang and Bengisu Yarimbas and Lingzi Hong},
  booktitle={Second Conference on Language Modeling},
  year={2025},
  url={https://openreview.net/forum?id=P61AgRyU7E}
}
```

---

### 🔹 Literacy-Controlled Counterspeech with RAG-RL (Findings of EMNLP 2025)

```bibtex
@inproceedings{song2025speaking,
  title={Speaking at the Right Level: Literacy-Controlled Counterspeech Generation with RAG-RL},
  author={Song, Xiaoying and Anik, Anirban Saha and Barua, Dibakar and Luo, Pengcheng and Ding, Junhua and Hong, Lingzi},
  booktitle={Findings of the Association for Computational Linguistics: EMNLP 2025},
  pages={2812--2830},
  year={2025}
}
```

---

## 👨‍💻 Maintainer & Contact

**Anirban Saha Anik**  
University of North Texas  
📧 AnirbanSahaAnik@my.unt.edu

---

## ⭐ Acknowledgment

If you find this dataset useful, please consider starring ⭐ the repository and citing our work.
