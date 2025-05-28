# Deteksi Emosi Wajah Real-Time Menggunakan Webcam dengan Streamlit

## Gambaran Umum

Proyek ini memanfaatkan Streamlit untuk membuat antarmuka pengguna yang mudah digunakan dalam mendeteksi emosi wajah secara real-time menggunakan webcam. Aplikasi ini menggunakan classifier Haar Cascade untuk deteksi wajah dan model transfer learning berbasis ImageNet yang dilatih pada dataset FER 2013 untuk klasifikasi emosi wajah.

## Fitur

* **Antarmuka Web Streamlit**: Aplikasi menyediakan pengalaman pengguna yang interaktif dan mulus melalui framework Streamlit.

* **Deteksi Wajah**: Haar Cascade classifier digunakan untuk mendeteksi wajah secara real-time dari aliran video webcam.

* **Klasifikasi Emosi**: Model transfer learning ImageNet yang sudah dilatih pada dataset FER 2013 digunakan untuk klasifikasi emosi dengan akurasi tinggi.

* **Pembaruan Real-Time**: Prediksi emosi diperbarui secara dinamis dan ditampilkan pada aplikasi Streamlit, memberikan umpan balik instan mengenai ekspresi wajah yang terdeteksi.

## Instalasi

1. **Clone repository:**

   ```bash
   git clone https://github.com/Aravind-SL/Real_Time_Face_Emotion_Detection.git
   cd Real_Time_Face_Emotion_Detection
   ```

2. **Install dependensi:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Jalankan aplikasi Streamlit:**

   ```bash
   streamlit run app.py
   ```

## Cara Penggunaan

1. **Buka aplikasi Streamlit di browser Anda:**
   Buka URL yang diberikan setelah menjalankan perintah `streamlit run app.py`.

2. **Aliran Webcam:**
   Tampilan video webcam akan muncul di aplikasi Streamlit, dengan wajah yang terdeteksi diberi kotak menggunakan Haar Cascade classifier.

3. **Prediksi Emosi Real-Time:**
   Prediksi emosi akan ditampilkan secara langsung pada wajah yang terdeteksi.

4. **Eksperimen:**
   Coba berbagai ekspresi wajah untuk melihat klasifikasi emosi secara real-time.

## Kontribusi

Kontribusi sangat disambut! Jangan ragu untuk membuka issue atau mengirim pull request untuk perbaikan atau fitur tambahan.

### Kekurangan dan Perbaikan di Masa Depan

Meskipun model deteksi emosi wajah real-time ini cukup efektif untuk emosi Bahagia, Sedih, Terkejut, Marah, dan Netral, terdapat beberapa keterbatasan yang perlu dicatat. Model ini masih kesulitan dalam memprediksi emosi takut dan jijik dengan akurat.


