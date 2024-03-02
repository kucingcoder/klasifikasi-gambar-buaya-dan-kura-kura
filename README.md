# KLASIFIKASI GAMBAR BINER DENGAN CNN

Dalam klasifikasi gambar buaya dan kura - kura menggunakan Convolutional Neural Network (CNN) dengan TensorFlow menggunakan bahasa pemrograman Python, langkah-langkah utama melibatkan pengumpulan dan pra-pemrosesan data, pembangunan model CNN, pelatihan model, dan evaluasi kinerja. Pertama-tama, dataset yang terdiri dari gambar-gambar buaya dan kura-kura dikumpulkan dan dipersiapkan dengan membaginya menjadi set pelatihan dan set pengujian. Selanjutnya, model CNN dibangun menggunakan TensorFlow, sebuah framework machine learning populer. Lapisan konvolusi, pooling, dan lapisan fully connected digunakan untuk mengekstraksi fitur dari gambar. Setelah pembangunan model, dilakukan pelatihan menggunakan set pelatihan untuk mengoptimalkan parameter-model. Akhirnya, model dievaluasi menggunakan set pengujian untuk mengukur akurasi dan kinerja keseluruhan dalam mengklasifikasikan gambar buaya dan kura-kura. Implementasi ini memanfaatkan kekuatan CNN dalam menangani data gambar dan mendemonstrasikan kemampuan TensorFlow sebagai alat yang efektif dalam pengembangan model machine learning.

## Cara Memakai Model Yang Sudah Jadi

- Download file model (.keras) yang sudah disediakan
- Install framework tensorflow pada bahasa pemograman yang akan anda pakai
- Buat variabel untuk menyimpan model yang berisi model yang dimual lewat file
- Sebelum digunakan sebagai input gambar harus diganti ukurannya menjadi 50 x 50 pixel
- Ubah gambar menjadi array dan kemudian perluas dimensi array tersebut dengan menambahkan dimensi baru di axis 0.
- Lakukan prediksi dengan menggunakan model dengan input array gambar tersebut
- Jika nilai prediksi pertama lebih besar dari 0.5, maka hasilnya adalah Kura - Kura, dan jika lainnya maka hasilnya Buaya

## Membuat Model Dengan Training Sendiri

- Download file ipynb dan folder evaluasi
- Upload ke google colab atau Jupyter Notebook file dan folder tersebut
- Lalu pilih jalankan semua / run all
