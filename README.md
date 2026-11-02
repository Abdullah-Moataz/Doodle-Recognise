# 🎨 Doodle Search Engine

A simple image similarity search engine built with **Python, Streamlit, and MobileNetV2**.

Users can draw a doodle or upload an image to find similar drawings from the Google Quick, Draw! dataset.

## 🚀 Live Demo

**[Try the Doodle Search Engine](https://doodle-recognise-5efin3me5wsfn7xr9mrike.streamlit.app/)**

## ✨ Features

- ✏️ Draw doodles directly on an interactive canvas.
- 📤 Upload images of drawings.
- 🔍 Find up to 25 similar doodles.
- 📊 Display similarity scores for matching drawings.
- 🧠 Extract image features using pretrained MobileNetV2.

## 🛠️ Technologies

- Python
- Streamlit
- TensorFlow / Keras
- MobileNetV2
- NumPy
- Pillow

## ⚙️ How It Works

1. The user draws or uploads an image.
2. The image is preprocessed into a 28×28 format.
3. MobileNetV2 extracts image features.
4. Cosine similarity compares the query with stored embeddings.
5. The application displays the most similar doodles.

## 📂 Dataset

Google Quick, Draw! Dataset (CC BY 4.0).

## ▶️ Run Locally

Install dependencies:

```bash
pip install -r requirements.txt
```

Start the application:

```bash
streamlit run app.py
```
