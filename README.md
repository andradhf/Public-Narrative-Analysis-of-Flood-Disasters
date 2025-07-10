# 🌀 Analisis Narasi Publik Terhadap Bencana Banjir

## 📌 Project Overview

Proyek ini bertujuan untuk menganalisis narasi publik di media sosial (X/Twitter) terkait bencana banjir di Indonesia. Fokus utamanya adalah mengevaluasi bentuk sentimen, jenis interaksi masyarakat, dan pola naratif yang muncul secara real-time, sebagai landasan untuk perencanaan respon kebencanaan berbasis data sosial.

Analisis dilakukan menggunakan pendekatan kuantitatif (EDA) dan kualitatif berbasis AI (LLM) untuk mengklasifikasi, meringkas, dan menafsirkan data percakapan publik.

---

## 🗂️ Raw Dataset

- Data dikumpulkan melalui scraping dari platform X/Twitter.
- Waktu scraping: 7 Juli 2025
- Bahasa: Indonesia
- Jumlah tweet: 566
- Kata kunci: `"banjir"`, `#BanjirJakarta`
- Format: CSV
Link : https://drive.google.com/file/d/1Ciosq0zHh507VZ3CvxDa1R6fmT2IibX0/view?usp=sharing

---

## 📈 Insight & Findings

1. **Lonjakan Aktivitas Tweet:**
   - Aktivitas tertinggi terjadi antara pukul 21:00–23:00, menunjukkan momen krusial dari kejadian banjir.
   - Lonjakan ini disinyalir sebagai reaksi langsung terhadap puncak bencana.

2. **Dominasi Narasi & Sentimen:**
   - Sentimen publik didominasi oleh **sentimen negatif**, menandakan ketidakpuasan terhadap penanganan banjir.
   - Narasi yang paling banyak muncul adalah **laporan langsung (direct reports)** dari masyarakat di lokasi.

3. **Engagement Tinggi pada Visual Konten:**
   - Tweet dengan gambar memiliki engagement jauh lebih tinggi daripada tanpa gambar:
     - Likes: 11.72 (vs 2.16)
     - Retweet: 3.44 (vs 0.54)
     - Replies: 1.55 (vs 0.48)

4. **Lokasi dan Kritik Spesifik:**
   - Wilayah terdampak yang paling sering disebut: Ciputat, Pondok Kacang, Setia Budi.
   - Kritik langsung diarahkan pada pemimpin daerah dengan nada ketidakpuasan terhadap respons pemerintah.

---

## 🤖 AI Support Explanation

Dalam proyek ini, model AI digunakan untuk mendukung proses analisis sebagai berikut:

- **Sentiment Classification**  
  Mengelompokkan tweet menjadi tiga kelas utama: `Positive`, `Negative`, dan `Neutral`.

- **Narrative Type Classification**  
  Mengkategorikan isi tweet ke dalam: `Direct Reports`, `Requests for Help`, dan `Complaints`.

- **Engagement-Based Summarization**  
  Merangkum tweet-tweet dengan engagement tertinggi untuk menggambarkan narasi dominan secara ringkas.

Model AI yang digunakan adalah **LLM (Large Language Model)** dari Hugging Face, dengan integrasi LangChain untuk pengolahan batch tweet dan prompting sistematis.

---

## 📌 Conclusion

Analisis ini menunjukkan bahwa media sosial dapat digunakan sebagai **sumber informasi krisis berbasis publik**, baik untuk:
- Mendeteksi titik tekanan sosial saat bencana,
- Memonitor respon masyarakat terhadap pemerintah,
- Dan mengekstrak laporan langsung yang dapat berguna untuk decision making instan.

---

