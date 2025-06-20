# Proyek Tugas Deep Learning

Repositori ini berisi kumpulan tugas dan proyek yang dikerjakan dalam mata kuliah Deep Learning. Setiap folder mingguan berisi notebook Jupyter dengan implementasi berbagai model dan teknik deep learning.

CATATAN: untuk mengakses folder `week8-16 (UAS)`, Anda perlu menginisialisasi submodule Git yang tertaut dengan repositori [Ringkasan buku Hands-on](https://github.com/Kaasyiful/handson-ml-sklearn-keras-tf-summary) sebagai pemenuhan tugas minggu 8-16.

Caranya:
```bash
git submodule update --init --recursive
```

## Daftar Isi

- [Ujian Tengah Semester (UTS)](#ujian-tengah-semester-uts)
- [Minggu 1: Model Klasifikasi dan Regresi Dasar](#minggu-1-model-klasifikasi-dan-regresi-dasar)
- [Minggu 2: Klasifikasi Data Tabular](#minggu-2-klasifikasi-data-tabular)
- [Minggu 3: Convolutional Neural Networks (CNN) untuk Klasifikasi Gambar](#minggu-3-convolutional-neural-networks-cnn-untuk-klasifikasi-gambar)
- [Minggu 4: Analisis Perbandingan Model](#minggu-4-analisis-perbandingan-model)
- [Minggu 5: Klasifikasi Teks](#minggu-5-klasifikasi-teks)
- [Minggu 6: Deteksi Sarkasme](#minggu-6-deteksi-sarkasme)
- [Minggu 7: Recurrent Neural Networks (RNN)](#minggu-7-recurrent-neural-networks-rnn)
- [Minggu 8-16 (UAS), yang tertaut dengan repositori sebagai submodule](#minggu-8-16-uas)

## Ujian Tengah Semester (UTS)

Folder ini berisi analisis kasus menggunakan model CNN dan MLP.

- **CNN/Deep_Learning_UTS_CNN.ipynb**: Notebook ini menerapkan Convolutional Neural Network (CNN) untuk tugas klasifikasi gambar pada dataset `FishImgDataset`. Ini mencakup augmentasi data, pelatihan model, dan evaluasi menggunakan metrik seperti confusion matrix dan kurva ROC.
- **MLP/Deep_Learning_UTS_MLP.ipynb**: Notebook ini menggunakan Multi-Layer Perceptron (MLP) untuk tugas regresi pada dataset `RegresiUTSTelkom_engineered_sample.csv`. Ini melibatkan rekayasa fitur, analisis korelasi, dan evaluasi model.

## Minggu 1: Model Klasifikasi dan Regresi Dasar

Folder ini berisi notebook yang memperkenalkan model klasifikasi dan regresi dasar menggunakan PyTorch dan TensorFlow.

- **Deep_Learning_Week_1_income.ipynb**: Notebook ini mengeksplorasi dataset `income.csv` untuk memprediksi pendapatan.
- **Deep_Learning_Week_1_Infrared.ipynb**: Notebook ini menggunakan dataset `Infrared.csv` untuk tugas klasifikasi.

## Minggu 2: Klasifikasi Data Tabular

Folder ini berfokus pada klasifikasi data tabular.

- **Deep_Learning_Week_2_covert.ipynb**: Notebook ini melatih model pada dataset `compressed_data.csv.gz` untuk tugas klasifikasi.
- **Deep_Learning_Week_2_secondhand.ipynb**: Notebook ini menggunakan dataset `secondhanddataset.csv` untuk memprediksi harga mobil bekas.

## Minggu 3: Convolutional Neural Networks (CNN) untuk Klasifikasi Gambar

Folder ini berisi implementasi CNN untuk klasifikasi gambar pada dataset standar.

- **CIFAR-10/Deep_Learning_Week_3_CIFAR-10.ipynb**: Notebook ini melatih model CNN pada dataset CIFAR-10.
- **SVHN/Deep_Learning_Week_3_SVHN.ipynb**: Notebook ini melatih model CNN pada dataset Street View House Numbers (SVHN).

## Minggu 4: Analisis Perbandingan Model

Folder ini berisi perbandingan kinerja antara PyTorch dan TensorFlow untuk tugas yang sama.

- **PyTorch/Deep_Learning_Week_4_PyTorch.ipynb**: Implementasi model menggunakan PyTorch.
- **TensorFlow/Deep_Learning_Week_4_Tensorflow.ipynb**: Implementasi model yang sama menggunakan TensorFlow untuk perbandingan.

## Minggu 5: Klasifikasi Teks

Folder ini berfokus pada klasifikasi teks menggunakan data ulasan.

- **PyTorch/Deep_Learning_Week_5_PyTorch.ipynb**: Notebook ini mengimplementasikan model klasifikasi teks pada dataset `ReviewTokoBaju.csv` menggunakan PyTorch.
- **TensorFlow/Deep_Learning_Week_5_Tensorflow.ipynb**: Notebook ini mengimplementasikan model yang sama menggunakan TensorFlow.

## Minggu 6: Deteksi Sarkasme

Folder ini berisi notebook untuk deteksi sarkasme dalam teks.

- **PyTorch/Deep_Learning_Week_6_PyTorch.ipynb**: Notebook ini mengimplementasikan model deteksi sarkasme pada dataset `DeteksiSarkasme.json` menggunakan PyTorch.
- **TensorFlow/Deep_Learning_Week_6_Tensorflow.ipynb**: Notebook ini mengimplementasikan model yang sama menggunakan TensorFlow.

## Minggu 7: Recurrent Neural Networks (RNN)

Folder ini mengeksplorasi berbagai arsitektur RNN untuk tugas-tugas Natural Language Processing (NLP).

- **IMDb/Deep_Learning_Week_7_IMDb.ipynb**: Notebook ini menerapkan model Bidirectional RNN dan Deep RNN pada dataset IMDb untuk analisis sentimen.
- **ReviewTokoBaju/Deep_Learning_Week_7_ReviewTokoBaju.ipynb**: Notebook ini menggunakan model Bidirectional RNN dan Deep RNN pada dataset `ReviewTokoBaju.csv` untuk klasifikasi ulasan.
- **DeteksiSarkasme/Deep_Learning_Week_7_DeteksiSarkasme.ipynb**: Notebook ini menerapkan model RNN untuk deteksi sarkasme.
- **EncoderDecoder_WMT/Deep_Learning_Week_7_WMT.ipynb**: Notebook ini mengimplementasikan arsitektur encoder-decoder untuk tugas terjemahan mesin.

## Minggu 8-16 (UAS)

Folder ini dicadangkan untuk Ujian Akhir Semester (UAS).
Folder ini tertaut dengan repositori 

[handson-ml-sklearn-keras-tf-summary](https://github.com/Kaasyiful/handson-ml-sklearn-keras-tf-summary) 

yang berisi rangkuman dari buku ["Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow"](https://github.com/ageron/handson-ml2) oleh Aurélien Géron. Repositori ini mencakup berbagai topik dan teknik dalam machine learning dan deep learning. Repositori tersebut tertaut dengan cara menggunakan submodule Git, sehingga Anda dapat mengaksesnya dengan mudah.
Cara mengaksesnya adalah dengan menjalankan perintah berikut di terminal:

```bash
git submodule update --init --recursive
```

Setelah itu, Anda dapat mengakses folder `week8-16 (UAS)` yang berisi berbagai notebook dan materi terkait dengan isi buku tersebut.
