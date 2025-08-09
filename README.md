# Proyek Klasifikasi Gambar Hewan dengan Transfer Learning (MobileNet)

**Deskripsi:** Proyek ini mengimplementasikan sistem klasifikasi gambar hewan, mengidentifikasi berbagai jenis hewan (kucing, anjing, dan ular) menggunakan teknik transfer learning dengan arsitektur MobileNet. Model dilatih menggunakan dataset gambar hewan dan dikonversi ke format TensorFlow Lite (TFLite) dan TensorFlow.js (TFJS) untuk potensi deployment di berbagai platform.

**Struktur Submission:**
proyek_klasifikasi_gambar/
├── Animals_final/          # Direktori data yang telah diproses dan model
│   ├── saved_model/        # Berisi model dalam format SavedModel (.pb, variables)
│   ├── test/               # Berisi data untuk pengujian (terstruktur per kelas)
│   ├── tf_lite/           # Berisi model dalam format TensorFlow Lite (.tflite, label.txt)
│   ├── tfjs_model/         # Berisi model dalam format TensorFlow.js (model.json, .bin)
│   ├── train/              # Berisi data untuk pelatihan (terstruktur per kelas)
│   └── val/                # Berisi data untuk validasi (terstruktur per kelas)
├── images_classification.ipynb
├── README.md
└── requirements.txt

**Prasyarat:**

Untuk menjalankan notebook (`images_classification.ipynb`), Anda memerlukan library Python tertentu. Pastikan Anda telah menginstal semua dependensi yang tercantum dalam file `requirements.txt`. Anda dapat menginstalnya menggunakan perintah:

```bash
pip install -r requirements.txt