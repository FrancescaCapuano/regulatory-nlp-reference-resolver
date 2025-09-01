# 📄 Document Reference Extraction in Regulatory Texts

This project extracts and matches references to **paragraphs**, **annexes**, **figures**, and **tables** from complex legal and regulatory documents. It is designed to resolve internal references and link them to the correct document elements.

Developed as part of a technical take-home assessment, the system is based entirely on **rule-based NLP** and **regex pattern matching**, achieving high accuracy without using external APIs or ML models.

---

## ✨ Features

- ✅ Extracts structured references (e.g., `paragraph 1.2.3`, `Annex 4`, `Table 1`)
- ✅ Resolves ranges (e.g., `paragraphs 4. to 7.` or `paragraphs 2.5.1 and 2.5.2`)
- ✅ Matches extracted references to paragraph IDs in the document
- ✅ Outputs predictions in a format compatible with the original JSON schema
- ✅ Evaluates against gold data using accuracy and recall
- ✅ Handles edge cases like duplicated paragraph numbers and partial matches

---

## 🧠 Approach

The system is built in a single, well-documented Jupyter notebook using:

- `regex` for identifying references
- `pandas` for processing the data
- `json` for loading and saving structured input
- `typing` for type clarity
- Custom-built logic to:
  - Extract reference phrases from text
  - Normalize them to match document structure
  - Match references using exact and ranged mappings

Accuracy is evaluated using per-paragraph recall and precision-like metrics. An error analysis section identifies both missed and incorrect predictions.

---

## 🧪 Performance

| Metric      | Score     |
|-------------|-----------|
| Accuracy    | ~94–95%   |
| Recall      | ~94–95%   |
| Time Spent  | 3–4 hours |
| Cost        | $0 (no paid APIs or services) |

---