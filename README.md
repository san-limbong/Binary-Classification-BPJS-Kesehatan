Comparing **Decision Tree** and **Random Forest** in Case: BPJS Hackaton

Repo ini bertujuan untuk sarana pembelajaran bagi pengembang untuk mengasah kemampuan pada bidang penambangan data dengan mengambil case dari BPJS Hackaton sebagai pembanding dari https://github.com/san-limbong/Fraud-Detection-BPJS-Kesehatan-using-CNN dengan menggunakan algoritma lain serta pengembangan penulisan kode yang lebih baik.

Fraud Detection (Binary Classification)
Mengembangkan sebuah model data mining untuk melakukan prediksi potensi terjadinya fraud pada klaim pelayanan Rumah Sakit berdasarkan dataset train yang terdiri dari 200217 observasi dan 53 variable yaitu:
- visit_id = id kunjungan
- kdkc = kode wilayah kantor cabang BPJS Kesehatan
- dati2 = kode kabupaten/kota
- typeppk= kode tipe Rumah Sakit
- jkpst = jenis kelamin peserta JKN-KIS
- umur = umur peserta saat mendapatkan pelayanan rumah sakit
- jnspelsep = tingkat pelayanan; 1:rawat inap; 2. rawat jalan
- los = lama peserta dirawat di rumah sakit
- cmg = klasifikasi CMG (Case Mix Group)
- severitylevel = tingkat urgensi
- diagprimer = diagnosa primer
- dx2_..._... = diagnosa sekunder
- proc.._... = kode kelompok procedure
- label = flag fraud; 1:fraud; 0:tidak fraud

Dengan requirement sebagai berikut.
Kedua kategori tersebut harus dibagi menjadi data training dan data validation berbeda.

Hasil Evaluasi Classification problem:
- Precision > 0.60
- Accuracy > 0.60
- Recall > 0.65


Lebih lanjut repo ini akan membandingkan kinerja dari algoritma **Decision Tree** dan **Random Forest** untuk menentukan evaluasi dari algoritma mana yang lebih baik.
