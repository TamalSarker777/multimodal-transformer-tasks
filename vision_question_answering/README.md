# 🧠 Visual Question Answering with ViLT on MEDPIX-ClinQA

This project showcases a Visual Question Answering (VQA) pipeline using the [`dandelin/vilt-b32-mlm`](https://huggingface.co/dandelin/vilt-b32-mlm) model. It is fine-tuned on the [MEDPIX-ClinQA](https://huggingface.co/datasets/adishourya/MEDPIX-ClinQA) dataset, a medical QA dataset composed of image-question-answer triples from radiological cases.

## 📌 Project Overview

- **Task**: Visual Question Answering (VQA)
- **Model**: `dandelin/vilt-b32-mlm` (ViLT: Vision-and-Language Transformer)
- **Dataset**: `adishourya/MEDPIX-ClinQA`
- **Approach**: Multi-label classification for medical answers
- **Objective**: Given a medical image and a related clinical question, the model predicts the most accurate medical answer.

## 🧰 Key Features

- Preprocessing of medical image-question pairs
- Mapping textual answers to numerical labels
- Fine-tuning ViLT on a medical dataset
- Evaluating performance on clinical VQA tasks

## 📦 Dependencies

- `transformers`
- `datasets`
- `torch`
- `Pillow`

Install them via:

```bash
pip install transformers datasets torch pillow
