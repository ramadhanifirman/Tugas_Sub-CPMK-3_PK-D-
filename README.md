# Tugas_Sub-CPMK-3_PK-D-
Ferdhie Fadhila Ardiansyah (202310370311319)

Firman Ramadhani (202110370311136)

Sistem Case-Based Reasoning (CBR) berhasil dibangun menggunakan dataset 31 putusan perkara narkotika yang diperoleh dari Direktori Putusan Mahkamah Agung Republik Indonesia. Setiap putusan diekstraksi dan diproses menggunakan teknik preprocessing teks, kemudian direpresentasikan dengan metode TF-IDF.

Tahap retrieval dilakukan menggunakan Cosine Similarity untuk mencari kasus yang memiliki kemiripan tertinggi dengan kasus baru. Tahap reuse dilakukan dengan mengambil label mayoritas dari kasus-kasus terdekat sebagai prediksi hasil kasus baru.

Untuk evaluasi klasifikasi digunakan algoritma Support Vector Machine (SVM) dengan metrik Accuracy, Precision, Recall, dan F1-Score. Hasil pengujian menunjukkan bahwa sistem mampu mengidentifikasi dan mengelompokkan perkara narkotika berdasarkan pola yang terdapat pada putusan sebelumnya.

Berdasarkan hasil implementasi dan evaluasi, metode CBR yang dikombinasikan dengan TF-IDF dan SVM dapat digunakan untuk membantu analisis kasus hukum narkotika secara otomatis.

