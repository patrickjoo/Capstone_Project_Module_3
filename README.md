# SwiftBuy E-Commerce Customer Churn Prediction

## Project Overview
Proyek ini bertujuan untuk memprediksi kemungkinan pelanggan e-commerce melakukan churn (berhenti bertransaksi dalam periode tertentu) menggunakan pendekatan machine learning.
Dengan prediksi ini, perusahaan dapat mengidentifikasi pelanggan yang berisiko tinggi dan menerapkan strategi retensi yang lebih tepat sasaran untuk mengurangi potensi kehilangan pendapatan.

## Dataset Information
Dataset yang digunakan memuat atribut perilaku dan profil pelanggan, seperti:
- **CityTier**: Klasifikasi kota tempat pelanggan tinggal
- **CouponUsed**: Jumlah kupon yang pernah digunakan
- **HourSpendOnApp**: Rata-rata waktu penggunaan aplikasi per hari
- **CashbackAmount**: Total cashback yang diterima pelanggan
- **DaySinceLastOrder**: Jumlah hari sejak terakhir melakukan pemesanan
- **MaritalStatus**: Status pernikahan pelanggan
- **Complain**: Pernah atau tidaknya pelanggan mengajukan keluhan (1 = Yes, 0 = No)
- **Churn**: Variabel target (1 = Churn, 0 = No Churn)

## Objectives
- Melakukan EDA untuk memahami distribusi data dan pola perilaku pelanggan.
- Membersihkan dan mempersiapkan data, termasuk penanganan missing values, encoding variabel kategorikal, dan scaling.
- Membangun dan membandingkan beberapa model machine learning untuk memprediksi churn.
- Mengidentifikasi fitur yang paling berpengaruh terhadap churn.
- Memberikan rekomendasi strategi retensi berbasis data..

## Technologies Used
- **Python**
- **Pandas, NumPy** (Data Manipulation)
- **Matplotlib, Seaborn** (Data Visualization)
- **Scikit-Learn** (Machine Learning)
- **Jupyter Notebook** (Development Environment)

## Project Workflow
1. **Business Understanding**
   - Memahami permasalahan churn dan dampak finansialnya.
   - Menentukan metrik evaluasi utama (F2-score) yang lebih menekankan pada Recall, karena biaya kehilangan pelanggan jauh lebih tinggi dibanding biaya intervensi.
   
2. **Data Understanding**
   - Meninjau kualitas data, memeriksa distribusi fitur, dan mendeteksi missing values serta outlier.
   
3. **Data Preparation**
   - Membersihkan data, mengatasi nilai yang hilang, melakukan encoding, scaling, serta penyeimbangan kelas menggunakan SMOTE.
   
4. **Modeling**
   - Mencoba beberapa algoritma seperti Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, AdaBoost, KNN, dan XGBoost.
   - Melakukan hyperparameter tuning pada model terbaik.

4. **Evaluation**
   - Mengevaluasi model menggunakan F2-score, akurasi, recall, precision, dan AUC-ROC.
   - Menganalisis confusion matrix untuk melihat proporsi kesalahan Type I & II.

## Results & Insights
- Model terbaik menghasilkan F2-score tertinggi dibanding model lainnya, dengan performa baik pada recall.
- Fitur seperti CashbackAmount, HourSpendOnApp, dan DaySinceLastOrder menjadi indikator utama churn.
- Pelanggan yang jarang membuka aplikasi dan lama tidak melakukan pesanan memiliki risiko churn lebih tinggi.
  
## Future Improvements
- Menguji model lain seperti LightGBM atau CatBoost untuk melihat potensi peningkatan performa.
- Mengintegrasikan data tambahan seperti aktivitas media sosial atau riwayat interaksi dengan customer service.
- Mengembangkan API untuk prediksi churn secara real-time.

## Conclusion
Dengan memanfaatkan machine learning, analisis ini membantu SwiftBuy mengenali pelanggan yang berisiko churn lebih dini.
Pendekatan ini memungkinkan penerapan strategi retensi yang lebih efektif, mengurangi kehilangan pendapatan, dan meningkatkan loyalitas pelanggan.

## Rekomendasi
1. **Peningkatan Engagement Aplikasi**
   - Kirimkan notifikasi personal (push notification atau email) untuk mengingatkan pelanggan yang jarang membuka aplikasi.
   - Buat kampanye gamifikasi seperti reward points untuk meningkatkan waktu penggunaan aplikasi.
  
2. **Strategi Cashback yang Tepat**
   - Berikan penawaran cashback yang lebih tinggi untuk pelanggan yang memiliki nilai pembelian tinggi tetapi jarang bertransaksi akhir-akhir ini.
   - Sesuaikan besaran cashback berdasarkan segmen pelanggan untuk memaksimalkan retensi.
  
3. **Program Reaktivasi Pelanggan Lama**
   - Untuk pelanggan dengan DaySinceLastOrder tinggi, kirimkan voucher eksklusif atau diskon khusus untuk pembelian berikutnya.
   - Gunakan channel SMS atau WhatsApp untuk menjangkau pelanggan yang jarang membuka email.
  
4. **Penanganan Keluhan yang Proaktif**
   - Pelanggan yang pernah mengajukan komplain memiliki risiko churn lebih tinggi. Tingkatkan kecepatan dan kualitas respon customer service.
   - Buat follow-up otomatis setelah penyelesaian komplain untuk memastikan kepuasan pelanggan.

5. **Pemantauan Model Secara Berkala**
   - Lakukan retraining model setiap 3–6 bulan untuk menyesuaikan perubahan perilaku pelanggan.
   -Integrasikan model ke dalam sistem CRM untuk deteksi churn secara real-time.

## Future Improvement
- Menguji model lain seperti LightGBM atau CatBoost untuk potensi peningkatan performa.
- Mengintegrasikan data eksternal seperti aktivitas media sosial atau histori interaksi layanan pelanggan.
- Mengembangkan API untuk prediksi churn yang dapat langsung digunakan oleh tim marketing.
  
  
   
