## Pengantar

Proyek ini bertujuan untuk membangun sebuah model klasifikasi sampah berbasis machine learning, yang dapat mengidentifikasi jenis sampah secara otomatis dan mengonversi model ke berbagai format agar bisa digunakan di platform website.

## Struktur Proyek
Struktur proyek ini terorganisir dengan baik untuk memandu Anda melalui setiap langkah pengembangan model.

```
├── **S♻️MPIS**/
│   ├── Import Semua Packages/Libraries
├── Data Preparation/
│   ├── Data Loading
│   ├── Data Preprocessing
│   │   └── Split Dataset
├── Modelling
├── Evaluasi dan Visualisasi
├── Konversi Model/
│   ├── Saved Model
│   ├── TFJS
│   ├── TF-Lite
│   └── Inference (Optional)
```

## Penjelasan Singkat:

1. Import Semua Packages/Libraries: Berisi semua pustaka Python yang digunakan.
2. Data Preparation: Memuat proses load data, preprocessing, dan split dataset ke training/testing.
3. Modelling: Proses pelatihan model klasifikasi sampah.
4. Evaluasi dan Visualisasi: Analisis performa model menggunakan metrik evaluasi dan visualisasi.
5. Konversi Model: Model yang telah dilatih dikonversi ke berbagai format (`SavedModel`, `TensorFlow.js`, `TensorFlow Lite`) agar bisa dijalankan di berbagai perangkat, termasuk opsi inference.
