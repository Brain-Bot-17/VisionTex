# 🧠 VisionTex — Fine-tuned LaTeX OCR with Qwen2-VL & Unsloth

VisionTex is a project that fine-tunes the [Qwen2-VL-7B-Instruct](https://huggingface.co/Qwen/Qwen2-VL) model using the [Unsloth](https://github.com/unslothai/unsloth) library for high-speed and memory-efficient vision-language fine-tuning.

---

## 📌 Project Objective

To improve LaTeX OCR accuracy by fine-tuning a visual language model on the [Latex-OCR dataset](https://huggingface.co/datasets/unsloth/Latex_OCR).

---

## 🚀 Colab Notebook

👉 **[Run the Notebook in Google Colab](https://colab.research.google.com/drive/1zFMAPu4ChWEE6gRVqHu0iMfFPCZIhyJ6)**

---

## 📊 Training Summary

| Metric            | Value                        |
|------------------|------------------------------|
| Dataset Size     | 68,686 samples               |
| Training Steps   | 50                           |
| Batch Size       | 8 (2 × 4 × 1 GPUs)           |
| Trainable Params | ~50M (0.73% of model)        |
| Final Loss       | 0.28                         |

---

## 🎯 Before vs After Fine-Tuning (Char Accuracy)

| Sample | Before | After  |
|--------|--------|--------|
| 0      | 0.322  | 0.588  |
| 1      | 0.162  | 0.480  |
| 2      | 0.011  | 0.011  |

---



