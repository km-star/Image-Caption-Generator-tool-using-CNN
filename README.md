# Image Caption Generator — CNN + LSTM

An end-to-end deep learning pipeline for automated image captioning using CNN feature extraction and LSTM sequence generation.

**Published:** *Design Engineering Journal, 2021*

---

## 🏗 Architecture

```
Input Image → ResNet CNN → Feature Vector → LSTM Decoder → Caption Output
```

- **CNN:** ResNet-based feature extraction — extracts 2048-dimensional visual feature vectors
- **LSTM:** Sequence generation model trained on image-caption pairs
- **Interface:** Tkinter GUI for real-time caption generation

---

## 📊 Dataset

- **Flickr8k** — 8,000+ images with 5 captions each
- Train/validation/test split: 6,000 / 1,000 / 1,000
- Preprocessing: tokenization, vocabulary building, sequence padding

---

## 📈 Results

| Metric | Score |
|--------|-------|
| BLEU-1 | 0.57 |
| BLEU-2 | 0.34 |

---

## 🛠 Tech Stack

```
Python · TensorFlow · Keras · NumPy · PIL · Tkinter
```

---

## 📄 Publication

**Image Caption Generator Using CNN and LSTM**  
*Design Engineering Journal, 2021*  
Kumar Mahat et al.

---

## 👤 Author

**Kumar Mahat** | [LinkedIn](https://linkedin.com/in/kumar-mahat-b4a431178)
