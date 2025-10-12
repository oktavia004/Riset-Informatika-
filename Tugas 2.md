# Methods vs Methodology

## **Paper 1 Method**  
**Judul:** *Automated imaging and machine learning for soil bacteria classification: Challenges and insights* \
**Link:** https://www.sciencedirect.com/science/article/pii/S0952197625013715

## **Methods yang digunakan:**
Dalam penelitian ini, penulis menggunakan beberapa metode machine learning untuk klasifikasi gambar bakteri tanah: 
- Classical Machine Learning: Support Vector Machine (SVM), Random Forest (RF), K-Nearest Neighbor (KNN), Multilayer Perceptron (MLP). 
- Extreme Learning Machine (ELM-RBF): termasuk variasi k-means, k-medoids, dan mean shift clustering. 
- Deep Learning (Residual Neural Networks / ResNet152v2): arsitektur CNN yang memanfaatkan transfer learning dari ImageNet.

## **Alasan Paper 1 termasuk Method:**
Karena bagian ini menjelaskan metode dan algoritma spesifik yang digunakan untuk melakukan klasifikasi gambar bakteri, seperti penerapan Extreme Learning Machine (ELM) dan Residual Neural Network (ResNet). Bagian ini tidak membahas latar belakang atau pemilihan data, melainkan berfokus pada proses teknis dan langkah-langkah analisis yang digunakan dalam penelitian untuk memproses data citra dan menghasilkan model klasifikasi otomatis.

## **Paper 2 Methodology**  
**Judul:** *An analysis of the effects of various polarimetric features and decomposition algorithms on PolSAR image classification through CNN* \
**Link:** https://www.sciencedirect.com/science/article/pii/S2590123025032803

## **Methodology yang digunakan:**
- Pengolahan Data Awal: PolSAR image dilakukan multi-look filtering untuk mengurangi speckle noise sehingga menghasilkan matriks koherensi (T).
- Ekstraksi Fitur: Menggunakan tiga metode polarimetric decomposition (PD) klasik yaitu Freeman–Durden (F3D), Yamaguchi (Y4D), dan Reflection Symmetric Decomposition (RSD). Dari sini diperoleh berbagai polarimetric features (PF).
- Skema Eksperimen:\
a.) Skema 1: hanya menggunakan power-based PF (fitur terkait daya).\
b.) Skema 2: menggunakan semua PF dari hasil dekomposisi.
- Normalisasi & Input ke CNN: Fitur dinormalisasi lalu dimasukkan ke CNN (AlexNet, VGG, ResNet). Model dengan akurasi terbaik disimpan. 
- Evaluasi & Interpretasi: Akurasi diukur dengan OA, AA, Kappa, confusion matrix. Lalu dilakukan analisis SHAP (Shapley Additive Explanations) untuk mengetahui kontribusi tiap fitur terhadap hasil klasifikasi.

## **Alasan Paper 2 termasuk Methodology:**
Bagian ini termasuk Methodology karena menjelaskan langkah-langkah teknis dan rancangan eksperimen yang digunakan dalam penelitian. Di bagian ini dijelaskan proses pengolahan citra PolSAR, mulai dari penerapan metode polarimetric decomposition (F3D, Y4D, RSD) untuk mengekstraksi fitur, proses normalisasi data, hingga penerapan CNN dan SHAP analysis untuk klasifikasi dan interpretasi hasil. Bagian ini tidak membahas teori atau latar belakang penelitian, melainkan berfokus pada prosedur, algoritma, dan parameter yang digunakan untuk mencapai tujuan analisis.
