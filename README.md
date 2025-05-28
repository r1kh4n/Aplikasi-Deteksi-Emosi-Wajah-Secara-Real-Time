## Instalasi
1. **Check Versi Python:**

   ```bash
   python --version
   ```
Wajib Versi Python **Python 3.8.10** 

2. **Clone repository:**

   ```bash
   git clone  https://github.com/r1kh4n/Aplikasi-Deteksi-Emosi-Wajah-Secara-Real-Time.git
   cd Real_Time_Face_Emotion_Detection
   ```

3. **Install dependensi:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Jalankan aplikasi Streamlit:**

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

Meskipun model deteksi emosi wajah real-time ini cukup efektif untuk emosi Bahagia, Sedih, Terkejut, Marah, dan Netral, terdapat beberapa keterbatasan yang perlu dicatat. Model ini masih kesulitan dalam memprediksi emosi takut dan jijik dengan akurat.


