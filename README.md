# OCR-confidence-validator-RAG
This repo contains references for OCR Confidence validator that validates vertex AI output using RAG system
ocr-confidence-validator-rag/
├── data/
│   ├── Medicine_Details.csv          ← from drug data kaggle
│   └── icd10_codes.csv          ← ICD-10 code list
├── embeddings/
│   ├── drug_index.faiss
│   ├── drug_meta.pkl
│   ├── icd_index.faiss
│   └── icd_meta.pkl
├── build_indexes.py             ← run once to build FAISS indexes
├── validators/
│   ├── drug_validator.py
│   ├── icd_validator.py
│   └── npi_validator.py
├── app.py                       ← FastAPI service
└── requirements.txt
