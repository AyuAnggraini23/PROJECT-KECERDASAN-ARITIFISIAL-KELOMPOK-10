Klasifikasi Balasan Chat Empatik

Proyek ini bertujuan untuk mengklasifikasikan balasan chat menjadi **empatik** dan **tidak empatik** menggunakan algoritma **Multinomial Naive Bayes**.

Dataset
- Emotional Reactions Reddit (Empathy Mental Health Dataset)
- Label disederhanakan menjadi:
  - 0 → Tidak Empatik
  - 1 → Empatik
- Dataset bersifat tidak seimbang

Metode
- Preprocessing teks
- Ekstraksi fitur menggunakan **TF-IDF**
- Klasifikasi menggunakan **Naive Bayes**
- Penanganan data tidak seimbang dengan **SMOTE** (hanya pada data latih)

Evaluasi
- Accuracy, Precision, Recall, F1-Score, Confusion Matrix
- Perbandingan model **baseline** dan **SMOTE**

Hasil Utama
- Model baseline bias terhadap kelas mayoritas
- SMOTE meningkatkan kemampuan model dalam mengenali balasan empatik
- Performa model menjadi lebih seimbang meskipun akurasi menurun

Tools
Python, Scikit-learn, Pandas, Imbalanced-learn

Anggota kelompok
Ananta Putri Clara  
Ayu Anggraini  
Aulia Aziza  
S1 Sains Data
(Universitas Negeri Surabaya)
