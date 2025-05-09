
# Proyek Klasifikasi Gambar Beras

Proyek ini adalah **Proyek Klasifikasi Gambar Beras** yang menggunakan dataset gambar beras berdasarkan kelasnya. Dalam proyek ini, berbagai teknik pembelajaran mesin dan pemrosesan gambar diterapkan untuk mengklasifikasikan gambar sesuai dengan kategori yang telah ditentukan. 

### **Deskripsi Proyek**
1. **Tujuan**: Mengembangkan model klasifikasi gambar yang dapat mengidentifikasi dan mengelompokkan gambar beras berdasarkan fitur visualnya.
2. **Dataset**: Dataset yang digunakan adalah kumpulan gambar beras dari Kaggle yang memiliki variasi bentuk dan warna.
3. **Teknik Pemrosesan Data**:
   - Penggunaan berbagai pustaka Python seperti NumPy, Pandas, dan Sklearn untuk manipulasi data.
   - Pemrosesan citra dengan Skimage dan OpenCV.
   - Augmentasi gambar untuk meningkatkan performa model.
4. **Model yang Digunakan**:
   - Model berbasis **TensorFlow dan Keras**, termasuk arsitektur populer seperti MobileNet dan DenseNet121.
   - Penerapan teknik **Convolutional Neural Networks (CNN)** untuk ekstraksi fitur visual.
5. **Evaluasi Model**:
   - Pembagian dataset menjadi data **latih dan uji** untuk evaluasi performa.
   - Penggunaan **metrik evaluasi** seperti confusion matrix dan classification report untuk menganalisis hasil.

## Cara Pakai

Berikut adalah langkah-langkah untuk menggunakan proyek **Klasifikasi Gambar Beras** di Google Colab:

### **1. Persiapan Awal**
- Pastikan Anda memiliki akun Google dan sudah masuk ke Google Colab.
- **Buka proyek Colab** melalui link berikut: [Proyek Klasifikasi Gambar](https://colab.research.google.com/drive/1plhq93FQ4SSqxcq7LEjibzZo916LV6o1#scrollTo=U4cU5-P9wzbF).
- Pastikan koneksi ke GPU aktif dengan pergi ke **Runtime** → **Change runtime type** → **Hardware accelerator** → pilih **T4 GPU**.

### **2. Install dan Import Library**
- Jalankan sel **"Import Semua Packages/Library yang Digunakan"** untuk mengimpor semua pustaka seperti NumPy, Pandas, TensorFlow, dan Skimage.
- Pastikan semua dependensi telah terinstal dengan baik.

### **3. Persiapan Data**
- **Upload dataset** jika belum tersedia dengan menjalankan sel yang berisi `files.upload()`.
- Dataset akan diproses dan dibagi menjadi **data latih dan uji** menggunakan `train_test_split`.

### **4. Pembuatan dan Pelatihan Model**
- Model berbasis **CNN (Convolutional Neural Networks)** akan dibuat menggunakan arsitektur seperti **MobileNet** atau **DenseNet121**.
- Jalankan sel yang berisi **ImageDataGenerator** untuk augmentasi data.
- Mulai pelatihan model dengan `model.fit()` menggunakan dataset yang sudah diolah.

### **5. Evaluasi Model**
- Gunakan **confusion matrix** dan **classification report** untuk menilai performa model.
- Jalankan sel evaluasi yang berisi `model.evaluate()` untuk melihat akurasi.

### **6. Prediksi Gambar**
- Upload gambar baru untuk diuji.
- Gunakan `model.predict()` untuk mendapatkan hasil klasifikasi.
- Visualisasikan hasil dengan `plt.imshow()` dan label prediksi.
    