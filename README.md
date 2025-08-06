# newspaper-headline-generator
📰 Newspaper Headline Generator – A Colab tool that extracts text from newspaper images using OCR and generates clean, human-like headlines using a transformer model. Includes cleanup and rephrasing for headline quality.

**Newspaper Headline Generator** is a Google Colab-based project that extracts text from newspaper images using OCR and generates concise, human-readable headlines using a transformer-based language model.

It combines **Tesseract OCR** for text extraction and **BART-large-CNN** from Hugging Face's Transformers library for summarization. The pipeline includes automatic text cleanup—removing URLs, domains like `.com`, and rephrasing weak sentence starts—to produce more professional headlines.

---

## 🔍 Features

- 🖼️ Upload newspaper images (JPG, PNG, etc.)
- 🔠 Extract text using Tesseract OCR
- 🧠 Generate concise headlines with a summarization model
- 🧹 Automatically clean and format the headline
- ☁️ Runs entirely on Google Colab (no setup needed)

---

## 🚀 Getting Started

1. Open the Colab notebook: **[Colab Link Here]**
2. Upload a newspaper image
3. The model extracts text and outputs a clean headline

---

## 📦 Requirements

These are installed automatically in Colab:

- `pytesseract`
- `pillow`
- `transformers`
- `tesseract-ocr`

---

## 📄 Example

**Input Image**: Newspaper screenshot  
**Generated Headline**:  
`Headline: New education reforms spark national debate`

---

## 📝 License

This project is licensed under the MIT License.


