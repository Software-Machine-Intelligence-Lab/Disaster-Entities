# 🌪️ DURJOG: Disaster Entity Recognition Dataset (Bangla + English)

Welcome to the official GitHub repository of **DURJOG**, a unique and resourceful dataset designed for **Disaster Entity Recognition (DER)** in both **Bangla** and **English**. This dataset aims to assist researchers and developers working on disaster-related NLP applications such as crisis detection, event extraction, and information retrieval.

---

## 📂 Dataset Overview

This repository includes:

- `Disaster-Entity-Bangla.csv` – Disaster news annotated in Bangla with entity tags.
- `Disaster-Entity-English.csv` – Translated and annotated version of the Bangla dataset in English.
- Each file contains:
  - **News** – The full news text.
  - **Entities** – A comma-separated list of disaster-related entities (location, time, type).
  - **Label** – Type of disaster event, such as flood, fire, cyclone, etc.

---

## 🔍 Entity Types

Each annotated entity belongs to one of the following types:

- 🗺️ `Location` – Where the disaster occurred
- 📅 `Time` – When the disaster occurred
- 🌪️ `Disaster` – What type of disaster occurred

---

## 🧠 Purpose & Applications

The dataset supports:
- Named Entity Recognition (NER)
- Information Extraction (IE)
- Multilingual NLP (Bangla–English)
- Social Media Crisis Monitoring

---

## 📊 Dataset Statistics

| Category  | Total Count | Max Words | Max Characters | Min Words | Min Characters | Avg. Words | Avg. Characters |
|-----------|-------------|-----------|----------------|-----------|----------------|-------------|------------------|
| News      | 4,777       | 608       | 4,313          | 4         | 27             | 117         | 795              |
| Entities  | 19,704      | 70        | 834            | 0         | 2              | 4           | 39               |
| Label     | 4,777       | 1         | 8              | 1         | 4              | 1           | 6                |

---

## 🏷️ Annotation Process

- **Annotation Team:** Two researchers worked in pairs to manually annotate the dataset.
- **Validation:** A third researcher reviewed and validated the annotations to ensure quality and consistency.
- **Entity Types:** Disaster, Location, and Time entities were tagged using domain guidelines.

---

## 🗺️ Data Source Location

- **Institution:** [International University of Business Agriculture and Technology (IUBAT), Dhaka, Bangladesh](https://iubat.edu)
- **Original News Sources:** The news data was selected from disaster-related samples used in the aforementioned research paper.

---

## 🔗 Access & License

- **📦 Zenodo DOI:** [https://doi.org/10.5281/zenodo.13914925](https://doi.org/10.5281/zenodo.13914925)  
- **🔗 GitHub Repository:** [https://github.com/Software-Machine-Intelligence-Lab/Disaster-Entities](https://github.com/Software-Machine-Intelligence-Lab/Disaster-Entities)  
- **📜 License:** [MIT License](LICENSE)

---

Thank you for using DURJOG! If you have any questions or suggestions, feel free to open an issue or start a discussion!
