<h1>KLASIFIKASI DIABETES MENGGUNAKAN MACHINE LEARNING</h1>

Model yang digunakan adalah
MODELING
Modeling ada 3 model yang akan saya terapkan berdasarkan apa yang sudah dijabarkan pada bagian latar belakang yaitu.
Logistic Regression
Logistic Regression menunjukkan kinerja terbaik di antara ketiga model. Model ini bekerja dengan baik pada dataset dengan hubungan linear antara fitur dan target. Hasil ini menunjukkan bahwa hubungan antara fitur dan prediksi diabetes mungkin sebagian besar bersifat linear, sehingga Logistic Regression dapat memanfaatkannya secara optimal. Sehingga Menghasilkan Akurasi : 0.754
Random Forest
Random Forest memiliki akurasi terendah di antara ketiga model. Sebagai metode berbasis ensemble, Random Forest biasanya unggul dalam menangani dataset non-linear dan berisi interaksi kompleks antara fitur. Namun, akurasi yang lebih rendah ini mungkin mengindikasikan bahwa dataset lebih cocok untuk metode sederhana seperti Logistic Regression, atau bahwa Random Forest memerlukan tuning hyperparameter lebih lanjut untuk meningkatkan performanya. Akurasi yang didapat metode Random Forest adalah : 0.721
Support Vector Machine
SVM menunjukkan performa yang cukup baik, meskipun sedikit lebih rendah dari Logistic Regression. SVM cenderung kuat untuk data non-linear, terutama jika kernel yang tepat digunakan. Namun, pada dataset ini, hubungan mungkin lebih mendekati linear, sehingga SVM tidak sepenuhnya mengungguli Logistic Regression. Sehingga Akurasi yang didapat metode SVM adalah : 0.734
