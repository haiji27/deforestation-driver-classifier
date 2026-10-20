# DeforestAI: Attributing Direct Drivers to Deforestation Alerts

Repository ini berisi studi kasus dan implementasi model Machine Learning sederhana untuk mengatribusikan pemicu langsung (direct drivers) dari titik peringatan dini deforestasi berdasarkan metrik spasial turunan citra satelit.

## Fitur Proyek
- Simulasi Dataset Spasial: Menghasilkan data fitur geometri lahan.
- Model Klasifikasi: Menggunakan Random Forest Classifier.
- Skrip Prediksi: Modul siap pakai untuk menguji titik alert baru.

## Cara Menjalankan
1. Install pustaka: pip install pandas numpy scikit-learn
2. Melatih model: python train.py
3. Menguji prediksi: python predict.py