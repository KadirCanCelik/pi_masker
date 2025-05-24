# pi_masker

# 🔒 PII Masker

A lightweight Python tool to detect and mask Personally Identifiable Information (PII) such as emails, phone numbers, names, locations, and dates — using spaCy's Named Entity Recognition (NER) and regular expressions.

## 🚀 Features

- 🧠 Detects PII using **spaCy NER** (`PERSON`, `ORG`, `GPE`, `DATE`)
- 🧾 Detects PII using **regex patterns** (e.g., email, phone number)
- 🛡️ Outputs a **fully masked version** of the original text
