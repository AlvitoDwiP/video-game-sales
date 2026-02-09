# Video Game Market Analysis Portfolio

## Project Overview
Project ini menganalisis struktur dan dinamika industri video game menggunakan data penjualan lintas platform, genre, dan region.

Tujuan utama analisis adalah:
- Memahami struktur pasar platform.
- Mengidentifikasi perbedaan kontribusi genre antar region.
- Menganalisis dinamika platform sepanjang waktu.

Analisis difokuskan pada pola struktural, bukan prediksi atau inferensi kausal.

---

## Dataset
Dataset berisi informasi penjualan video game per judul dan platform, dengan variabel utama:
- Platform
- Genre
- Year (tahun rilis)
- Penjualan regional: NA, EU, JP, Other
- Total Sales

Satu baris data merepresentasikan satu judul game pada satu platform.  
Kolom Year merepresentasikan tahun rilis, bukan tahun penjualan aktual.

---

## Analytical Scope and Assumptions
- Penjualan digunakan sebagai proksi ukuran pasar, bukan preferensi konsumen murni.
- Analisis bersifat agregatif dan deskriptif.
- Tidak dilakukan inferensi kausal atau prediksi.
- Faktor eksternal seperti strategi publisher, distribusi, dan siklus hardware tidak dimodelkan secara eksplisit.

---

## Notebook Structure

### Notebook 01. Data Preparation
Notebook ini menyiapkan dataset yang konsisten dan siap dianalisis.

Fokus utama:
- Validasi kondisi awal data.
- Pembersihan dan standardisasi kolom.
- Menjaga konsistensi metrik antar notebook.

Output utama:
- Dataset bersih yang digunakan langsung pada seluruh notebook berikutnya.

Notebook ini berfungsi sebagai fondasi analisis, bukan eksplorasi insight.

---

### Notebook 02. Market Structure Analysis
Notebook ini menganalisis struktur pasar video game berdasarkan platform.

Pertanyaan utama:
Apakah pasar didominasi oleh sedikit platform besar atau terfragmentasi ke banyak platform.

Fokus analisis:
- Distribusi total penjualan per platform.
- Tingkat konsentrasi pasar.
- Perbandingan kontribusi platform besar dan long tail.

Analisis bersifat struktural dan tidak mengevaluasi kinerja bisnis platform.

---

### Notebook 03. Regional Genre Analysis
Notebook ini menganalisis komposisi genre antar region.

Fokus analisis:
- Distribusi genre per region dalam bentuk proporsi.
- Perbandingan struktur regional terhadap struktur global.
- Identifikasi pola spesialisasi pasar regional.

Catatan penting:
Analisis ini tidak menyimpulkan preferensi budaya.  
Penjualan mencerminkan hasil interaksi supply, distribusi, dan demand.

---

### Notebook 04. Platform Lifecycle Analysis
Notebook ini menganalisis dinamika platform sepanjang waktu.

Fokus analisis:
- Pola perubahan agregat penjualan tahunan.
- Identifikasi fase puncak secara heuristik.
- Perbandingan bentuk lifecycle antar platform.

Lifecycle didefinisikan secara deskriptif dan tidak merepresentasikan siklus produk resmi.

---

## Key Takeaways
- Struktur pasar video game menunjukkan konsentrasi pada platform tertentu.
- Komposisi genre berbeda antar region dan tidak selalu mengikuti struktur global.
- Platform memiliki variasi lifecycle yang signifikan dalam bentuk dan durasi.

Analisis menekankan kehati-hatian interpretasi sesuai keterbatasan data.

---

## Tools
- Python
- pandas
- numpy
- matplotlib

---

## Notes for Reviewers
Project ini dirancang sebagai portofolio Data Analyst tingkat junior hingga early-mid.

Fokus utama penilaian:
- Kejelasan framing analisis.
- Konsistensi logika antara data, metode, dan interpretasi.
- Kesadaran terhadap keterbatasan data.

Project ini tidak membuat klaim prediktif atau rekomendasi bisnis langsung.
