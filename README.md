# Sentiment Analysis on Twitter Data 🇮🇩

Proyek ini merupakan bagian dari submission analisis sentimen menggunakan data dari Twitter. Data dikumpulkan melalui scraping dan diproses untuk membangun model machine learning menggunakan TensorFlow/Keras. Proyek ini ditujukan untuk memprediksi sentimen (positif, negatif, netral) dari tweet berbahasa Indonesia.

## 📁 Struktur Direktori

```

sentiment-analysis/
├── pelatihan_model.ipynb           # Notebook pelatihan model
├── scraping.ipynb                  # Notebook scraping data Twitter
├── requirements.txt                # Daftar dependency
├── Hasil Data Preprocessing/
│   └── data_cleaned.csv            # Dataset setelah preprocessing
├── Hasil Data Scraping/
│   └── twitter_data_scraping.csv  # Dataset hasil scraping mentah
├── Inference/
├── sentiment_model.h5          # Model yang telah dilatih
├── tokenizer.pkl               # Tokenizer untuk preprocessing
└── label_encoder.pkl           # Label encoder untuk mapping label

````

## 🚀 Cara Menjalankan Proyek

1. **Clone repositori ini:**

   ```bash
   git clone https://github.com/username/nama-repo.git
   cd nama-repo
````

2. **Install dependencies:**

   Gunakan `pip` dan file `requirements.txt`:

   ```bash
   pip install -r requirements.txt
   ```

3. **Jalankan notebook:**

   * `scraping.ipynb` untuk mengumpulkan data dari Twitter
   * `pelatihan_model.ipynb` untuk pelatihan model

4. **Model dan Inference:**

   * Model disimpan di folder `Inference/` dan bisa digunakan untuk prediksi pada data baru.

## 📊 Dataset

Dataset terdiri dari tweet hasil scraping dengan keyword tertentu, disimpan dalam file `twitter_data_scraping.csv`. Dataset telah dibersihkan dan disimpan dalam `data_cleaned.csv`.

## 🧠 Model Machine Learning

* Model: LSTM / GRU (disesuaikan)
* Framework: TensorFlow / Keras
* Akurasi akhir: \[Masukkan akurasi di sini jika tersedia]

## 📌 Catatan

* Proyek ini menggunakan data publik dari Twitter untuk keperluan pembelajaran.
* Scraping dilakukan sesuai dengan kebijakan penggunaan Twitter.

## 📄 Lisensi

MIT License. Lihat file [LICENSE](LICENSE) untuk detail.

---

✍️ Dibuat oleh Bagus Darmawan – 2025

```
