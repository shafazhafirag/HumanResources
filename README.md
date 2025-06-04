# Proyek Akhir: Menyelesaikan Permasalahan Perusahaan PT. Solusi Talenta Nusantara

## Business Understanding

### Latar Belakang Bisnis
PT. Solusi Talenta Nusantara adalah perusahaan penyedia jasa teknologi yang mengalami lonjakan pertumbuhan pasca-pandemi. Seiring ekspansi cepat, tantangan utama yang muncul adalah mempertahankan talenta terbaik. Turnover karyawan menjadi hambatan besar bagi stabilitas proyek teknologi dan kepuasan klien.

Dengan tingginya persaingan tenaga kerja digital, kehilangan karyawan berpengalaman bukan hanya berdampak pada biaya rekrutmen, tapi juga menurunkan kualitas layanan dan memperpanjang waktu delivery proyek. Oleh karena itu, perusahaan ingin mengadopsi pendekatan berbasis data untuk mengidentifikasi risiko turnover dan mengantisipasinya secara proaktif.

---

## Permasalahan Bisnis

Permasalahan yang hendak diatasi dalam proyek ini adalah:

1. Kurangnya visibilitas terhadap risiko resign dari tiap karyawan — manajemen HR tidak memiliki alat untuk memantau sinyal awal ketidakpuasan karyawan.
2. Pengambilan keputusan HR yang tidak berbasis data — strategi retensi masih bersifat general dan tidak disesuaikan dengan karakteristik karyawan tertentu.
3. Tidak adanya sistem peringatan dini untuk mendeteksi potensi attrition berdasarkan perilaku kerja, demografi, dan kepuasan.

Dengan memahami pola dan faktor risiko turnover, perusahaan dapat:
- Mempersonalisasi kebijakan retensi.
- Mengurangi kejutan turnover yang berdampak pada delivery proyek.
- Meningkatkan kepuasan kerja dengan intervensi berbasis data.

---

## Cakupan Proyek
Proyek ini dirancang untuk membantu manajemen HR memahami dan merespon risiko turnover melalui langkah-langkah berikut:

1. Analisis Deskriptif:
  - Melakukan segmentasi karyawan berdasarkan usia, jabatan, dan departemen.
  - Menganalisis distribusi kepuasan kerja, beban kerja (lembur), dan kompensasi.

2. Identifikasi Pola Attrition:
   - Menemukan kombinasi faktor (misal: lembur tinggi + gaji rendah) yang berasosiasi dengan risiko keluar.
   - Mendeteksi tren dari karyawan dengan masa kerja pendek dan penilaian atasan yang rendah.

3. Model Prediktif:
   - Mengembangkan model machine learning (seperti XGBoost) untuk memprediksi kemungkinan seorang karyawan resign.
   - Menyediakan skor risiko individual sebagai input bagi tim HR.

4. Visualisasi Interaktif:
   - Membangun dashboard interaktif untuk memantau risiko attrition dan distribusinya dalam organisasi.

5. Rekomendasi Intervensi:
   - Memberikan rekomendasi spesifik berdasarkan temuan model, seperti revisi beban kerja, penyesuaian kompensasi, atau program retention onboarding.


---

## Persiapan

### Sumber Data

Dataset yang digunakan:
- 📦 **Employee Data** 

Link langsung ke file `.csv`:
- [https://raw.githubusercontent.com/selva86/datasets/master/student-mat.csv](http://github.com/dicodingacademy/dicoding_dataset/blob/main/employee/employee_data.csv)


### Setup Environment

Library yang dibutuhkan:
```bash
pip install pandas matplotlib seaborn plotly scikit-learn streamlit
