# Transformer from Scratch with NumPy 
### Tugas Mata Kuliah Pemrosesan Bahasa Alami (NLP)

- **Nama:** Barbara Neanake Ajiesti
- **NIM:** 22/494495/TK/54238

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1pjlB8n3V139YseCJDl3LmaHbnWY4RtRl/view?usp=sharing)

---

Sebagai asisten dosen, saya sering menerima pertanyaan serupa dari mahasiswa menjelang ujian, mulai dari jadwal, tenggat tugas, hingga aturan kelompok. Lama-lama saya penasaran, bagaimana jika sistem bisa mengenali pola pertanyaan seperti itu dan menjawabnya otomatis? Kebetulan pada mata kuliah ini saya mendapat tugas untuk mengimplementasikan decoder-only Transformer (GPT-style) dari nol, jadi saya sekalian menjadikannya tools untuk belajar sekaligus bereksperimen. Dengan **membangun seluruh komponennya sendiri menggunakan NumPy**, mulai dari embedding, sinusoidal positional encoding, multi-head attention, hingga causal masking, saya belajar bagaimana model bahasa benar-benar memproses teks dan menghasilkan prediksi kategori pertanyaan maupun respons yang sesuai.

Agar lebih jelas, saya menggunakan vocabulary berupa kumpulan kata yang mungkin muncul dalam konteks tanya-jawab (misalnya: kapan, tugas, deadline, kelompok, dll). Dari sini, kita bisa melihat bagaimana model memperhatikan hubungan antar-kata lewat visualisasi perhatian (attention) di berbagai layer berikut:

<p align="center"> <img width="600" alt="attention-heatmap" src="https://github.com/user-attachments/assets/ac9779d0-e360-4746-8faa-f179a94d5149" /> <img width="600" alt="attention-plot" src="https://github.com/user-attachments/assets/bb8a254f-67ea-47dd-9941-2ad19a1e908d" /> </p>

Untuk mengetahui lebih lanjut tentang implementasi detailnya, silakan cek notebook di Google Colab atau file yang ada di repositori ini :D

---

## 📂 Struktur Repositori

Repositori ini berisi empat file utama:

1.  **`Barbara_NLP_Transformer_From_Scratch.ipynb`**: Notebook utama berisi seluruh implementasi kode, analisis, dan visualisasi.
2.  **`Laporan_NLP_Transformer.pdf`**: Laporan singkat yang merangkum desain arsitektur, komponen, dan kesimpulan proyek.
3.  **`Dokumentasi_Hasil.pdf`**: Ekspor PDF dari *output* notebook sebagai bukti uji dan dokumentasi visual.
4.  **`README.md`**: Penjelasan singkat dan panduan repositori ini.

## 🚀 Cara Menjalankan

-   **Dependensi:** Proyek ini hanya memerlukan **NumPy**. Library lain seperti `matplotlib` dan `seaborn` digunakan untuk visualisasi dan umumnya sudah tersedia di environment seperti Google Colab.

-   **Cara Termudah:** Cukup buka *notebook* ini di **Google Colab** melalui *badge* atau [link ini](https://drive.google.com/file/d/1pjlB8n3V139YseCJDl3LmaHbnWY4RtRl/view?usp=sharing). Atau jika mau yang agak effort, silakan **clone repository ini lalu buka file ipynb lewat Jupyter Notebook**. Semua sel kode dapat dijalankan secara berurutan dari atas ke bawah.

## Terima Kasih!
