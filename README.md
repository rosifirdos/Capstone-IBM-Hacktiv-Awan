# Capstone Project: Analisis Sentimen Ulasan Game Clash of Clans

## Project Overview

Proyek ini bertujuan untuk melakukan analisis sentimen terhadap ulasan pengguna aplikasi game mobile "Clash of Clans" yang tersedia di Google Play Store. Dengan memanfaatkan kecerdasan buatan, khususnya model bahasa besar (LLM) IBM Granite, kami mengklasifikasikan ulasan-ulasan ini menjadi kategori sentimen (Positif, Negatif, Netral). Hasil analisis kemudian divisualisasikan dalam bentuk dashboard interaktif untuk mengidentifikasi tren, preferensi pengguna, dan area potensial untuk peningkatan game.

Tujuan utama proyek ini adalah:
1.  Mengembangkan sistem klasifikasi sentimen menggunakan IBM Granite.
2.  Mengekstrak wawasan berharga dari ulasan teks tidak terstruktur.
3.  Menyajikan temuan dalam format yang mudah dipahami (dashboard) untuk membantu pengembang game dalam pengambilan keputusan strategis.

## Raw Dataset Link

Dataset mentah yang digunakan dalam proyek ini adalah "Clash of Clans Mobile Game Reviews", yang berisi ulasan pengguna dari Google Play Store.

Anda dapat mengunduh dan mengakses dataset ini secara publik melalui tautan berikut:
[**SISIPKAN LINK PUBLIC DATASET ANDA DI SINI (misalnya dari Google Drive, Kaggle, dll.)**]

## Insight & Findings

Berdasarkan analisis sentimen terhadap ulasan pengguna Clash of Clans, beberapa *insight* dan temuan kunci telah diidentifikasi:

* **Dominasi Sentimen Positif:** Sebagian besar ulasan menunjukkan sentimen positif (sekitar 85.67%), mengindikasikan kepuasan tinggi di antara basis pemain. Ini menunjukkan bahwa fundamental game diterima dengan baik.
* **Korelasi Sentimen dengan Skor Ulasan:** Terdapat korelasi yang jelas antara sentimen yang diprediksi dengan skor ulasan asli (1-5 bintang). Ulasan dengan sentimen positif cenderung memiliki skor bintang tinggi (4-5), sementara sentimen negatif berkorelasi dengan skor bintang rendah (1-2).
* **Tren Sentimen Stabil (Desember 2024 - Juni 2025):** Data menunjukkan distribusi sentimen yang relatif stabil dari waktu ke waktu dalam periode yang dianalisis, dengan sentimen positif secara konsisten mendominasi. Ini menyiratkan bahwa perubahan atau pembaruan game dalam periode ini tidak menyebabkan fluktuasi drastis dalam persepsi keseluruhan pengguna.
* **Kata Kunci Positif Teratas:** Kata kunci yang paling sering muncul dalam ulasan positif mencakup istilah seperti "game", "bagus", "keren", "seru", dan "update". Ini menyoroti aspek-aspek inti dari pengalaman bermain yang disukai pemain. Kata kunci ini bisa menjadi fokus untuk kampanye pemasaran atau pengembangan fitur yang lebih jauh.

Temuan ini memberikan gambaran umum yang komprehensif tentang apa yang berhasil di Clash of Clans dan di mana potensi peningkatan mungkin ada, berdasarkan suara langsung dari basis pemainnya.

## AI Support Explanation

Proyek ini memanfaatkan **IBM Granite (Large Language Model)** melalui integrasi Langchain untuk melakukan tugas kunci analisis sentimen.

* **Peran AI dalam Proyek:**
    * **Klasifikasi Sentimen Skala Besar:** AI memungkinkan pemrosesan dan klasifikasi sentimen yang efisien dari ribuan ulasan teks tidak terstruktur. Tanpa AI, proses ini akan memakan waktu dan sumber daya yang sangat besar jika dilakukan secara manual.
    * **Mengubah Data Kualitatif Menjadi Kuantitatif:** IBM Granite berfungsi sebagai jembatan untuk mengubah teks ulasan (data kualitatif) menjadi label sentimen terstruktur (Positif, Negatif, Netral), yang kemudian dapat dianalisis secara kuantitatif dan divisualisasikan dalam bentuk *dashboard*.
    * **Ekstraksi Wawasan:** Kemampuan NLP canggih dari IBM Granite memungkinkan pemahaman konteks dan nuansa dalam ulasan, menghasilkan klasifikasi yang akurat yang menjadi dasar untuk mengidentifikasi kata kunci penting dan pola sentimen.

* **Relevansi dan Efektivitas Penggunaan AI:**
    * Penggunaan IBM Granite sangat relevan dengan kebutuhan proyek untuk mengekstrak wawasan dari volume data teks yang besar.
    * Model ini menunjukkan akurasi yang baik (sekitar **85.67%** pada klasifikasi sentimen positif), menegaskan efektivitas AI dalam tugas ini. Meskipun tantangan mungkin muncul pada klasifikasi kelas minoritas (negatif dan netral), kinerja keseluruhan sangat berharga untuk memahami sentimen pemain secara umum.
    * AI adalah *enabler* utama, mengubah data mentah yang tidak terstruktur menjadi wawasan yang terukur dan dapat ditindaklanjuti, yang berkontribusi pada pemahaman yang lebih baik tentang pengalaman pemain "Clash of Clans".

---
