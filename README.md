# Ringkasan Proyek Hands-On Machine Learning

Proyek ini berisi kumpulan notebook Jupyter yang merangkum berbagai konsep dan teknik dari buku "Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow". Setiap notebook mencakup bab atau topik tertentu dari buku tersebut, memberikan contoh kode dan penjelasan untuk membantu pemahaman.

Proyek ini mencakup berbagai topik dalam machine learning, mulai dari dasar-dasar seperti model linier dan support vector machines, hingga topik yang lebih lanjut seperti deep learning, natural language processing, dan reinforcement learning. Notebook-notebook ini menggunakan library populer seperti Scikit-Learn, Keras, dan TensorFlow untuk mengimplementasikan model dan teknik yang dibahas.

Selain itu, proyek ini menyertakan beberapa dataset yang digunakan dalam notebook untuk latihan dan eksperimen, serta gambar dan visualisasi untuk membantu menjelaskan konsep-konsep kunci.

Secara keseluruhan, proyek ini adalah sumber daya yang berharga bagi siapa saja yang ingin mempelajari machine learning dengan cara yang praktis dan langsung, dengan mengikuti contoh-contoh dari salah satu buku paling populer di bidang ini.

## Daftar Notebook

Berikut adalah daftar notebook yang tersedia dalam proyek ini:

*   **`01_the_machine_learning_landscape.ipynb`**: Notebook ini memberikan pengenalan umum tentang konsep-konsep dasar dalam Machine Learning. Ini mencakup definisi apa itu Machine Learning, mengapa kita menggunakannya, jenis-jenis sistem Machine Learning, dan alur kerja khas dalam sebuah proyek Machine Learning.
*   **`02_end_to_end_machine_learning_project.ipynb`**: Notebook ini menyajikan studi kasus proyek Machine Learning secara end-to-end. Mulai dari pengambilan data, eksplorasi data dan visualisasi, persiapan data untuk algoritma Machine Learning, pemilihan dan pelatihan model, hingga penyempurnaan model. Proyek ini menggunakan dataset perumahan California sebagai contoh.
*   **`03_classification.ipynb`**: Notebook ini berfokus pada tugas klasifikasi, salah satu tugas paling umum dalam Machine Learning. Ini mencakup metrik kinerja untuk klasifikasi, klasifikasi multi-kelas, klasifikasi multi-label, dan klasifikasi multi-output. Contoh yang digunakan adalah dataset MNIST untuk pengenalan digit.
*   **`04_training_linear_models.ipynb`**: Notebook ini membahas berbagai model linier untuk regresi dan klasifikasi. Ini mencakup Regresi Linier, Regresi Logistik, dan Regresi Softmax. Juga dibahas tentang Regularisasi untuk menghindari overfitting, seperti Ridge, Lasso, dan Elastic Net.
*   **`05_support_vector_machines.ipynb`**: Notebook ini menjelaskan cara kerja Support Vector Machines (SVM), sebuah model yang kuat untuk tugas klasifikasi dan regresi. Ini mencakup konsep-konsep seperti margin, kernel trick untuk menangani data non-linier, dan cara menggunakan SVM untuk regresi.
*   **`06_decision_trees.ipynb`**: Notebook ini membahas Decision Trees, sebuah model serbaguna yang dapat melakukan tugas klasifikasi dan regresi. Ini mencakup cara melatih dan memvisualisasikan Decision Tree, serta membahas batasan-batasannya dan cara mengatasinya.
*   **`07_ensemble_learning_and_random_forests.ipynb`**: Notebook ini memperkenalkan konsep Ensemble Learning, yaitu menggabungkan beberapa model untuk mendapatkan kinerja yang lebih baik. Ini mencakup metode-metode populer seperti Bagging, Boosting, Stacking, dan secara khusus membahas Random Forests secara mendalam.
*   **`08_dimensionality_reduction.ipynb`**: Notebook ini membahas teknik-teknik untuk mengurangi jumlah fitur dalam dataset (pengurangan dimensi) untuk mempercepat pelatihan dan mengatasi 'kutukan dimensi'. Teknik yang dibahas termasuk PCA (Principal Component Analysis), Kernel PCA, dan LLE (Locally Linear Embedding).
*   **`09_unsupervised_learning.ipynb`**: Notebook ini menjelajahi berbagai tugas dan algoritma Unsupervised Learning. Ini mencakup clustering dengan K-Means dan DBSCAN, serta Gaussian Mixture Models untuk pemodelan kepadatan.
*   **`10_neural_nets_with_keras.ipynb`**: Notebook ini memberikan pengenalan tentang jaringan saraf tiruan (Artificial Neural Networks) dan deep learning menggunakan library Keras. Ini mencakup cara membangun, melatih, dan mengevaluasi jaringan saraf untuk tugas klasifikasi dan regresi.
*   **`11_training_deep_neural_networks.ipynb`**: Notebook ini membahas tantangan dalam melatih jaringan saraf dalam (Deep Neural Networks) dan menyajikan solusi praktis. Topik yang dibahas termasuk masalah vanishing/exploding gradients, penggunaan fungsi aktivasi yang lebih baik, batch normalization, dan penggunaan kembali bobot dari model yang sudah ada (transfer learning).
*   **`12_custom_models_and_training_with_tensorflow.ipynb`**: Notebook ini menunjukkan cara menggunakan TensorFlow untuk membuat model kustom dan loop pelatihan. Ini memberikan fleksibilitas yang lebih besar daripada API Keras tingkat tinggi, memungkinkan Anda untuk mengimplementasikan arsitektur dan algoritma yang lebih kompleks.
*   **`13_loading_and_preprocessing_data.ipynb`**: Notebook ini berfokus pada cara memuat dan memproses data secara efisien untuk proyek deep learning. Ini mencakup penggunaan `tf.data` API untuk membuat pipeline input data yang sangat efisien, serta teknik-teknik prapemrosesan data.
*   **`14_deep_computer_vision_with_cnns.ipynb`**: Notebook ini memperkenalkan Convolutional Neural Networks (CNNs), arsitektur jaringan saraf yang sangat efektif untuk tugas-tugas computer vision. Ini mencakup blok bangunan dasar CNN seperti lapisan konvolusional dan pooling, serta arsitektur CNN modern seperti ResNet.
*   **`15_processing_sequences_using_rnns_and_cnns.ipynb`**: Notebook ini membahas cara memproses data sekuensial seperti time series atau teks menggunakan Recurrent Neural Networks (RNNs). Ini mencakup berbagai jenis sel RNN seperti LSTM dan GRU, serta cara menggunakan CNN satu dimensi untuk pemrosesan sekuensial.
*   **`16_nlp_with_rnns_and_attention.ipynb`**: Notebook ini menerapkan RNN untuk tugas-tugas Natural Language Processing (NLP). Ini mencakup topik-topik seperti text generation, analisis sentimen, dan mekanisme Attention yang telah merevolusi banyak tugas NLP, terutama dalam terjemahan mesin.
*   **`17_autoencoders_and_gans.ipynb`**: Notebook ini menjelajahi model generatif. Ini mencakup Autoencoder untuk pengurangan dimensi dan deteksi anomali, serta Generative Adversarial Networks (GANs) untuk menghasilkan data baru yang realistis, seperti gambar.
*   **`18_reinforcement_learning.ipynb`**: Notebook ini memberikan pengenalan tentang Reinforcement Learning (RL), sebuah cabang Machine Learning di mana agen belajar untuk membuat keputusan dengan melakukan tindakan di lingkungan untuk memaksimalkan imbalan. Ini mencakup konsep-konsep dasar RL dan implementasi sederhana menggunakan OpenAI Gym.
*   **`19_training_and_deploying_at_scale.ipynb`**: Notebook ini membahas cara melatih dan menerapkan model Machine Learning dalam skala besar. Ini mencakup topik-topik seperti penggunaan GPU untuk mempercepat pelatihan, pelatihan terdistribusi di beberapa server, dan cara menerapkan model ke lingkungan produksi menggunakan TensorFlow Serving.

## Struktur Proyek

Proyek ini memiliki struktur sebagai berikut:

*   **Notebooks Jupyter (`.ipynb`)**: File-file utama yang berisi ringkasan dan kode dari setiap bab buku.
*   **`datasets/`**: Direktori ini berisi berbagai dataset yang digunakan dalam notebook. Setiap dataset berada di dalam subdirektori sendiri, seringkali dengan file `README.md` yang menjelaskan dataset tersebut.
*   **`notebook-images/`**: Berisi gambar dan visualisasi yang dihasilkan oleh atau digunakan dalam notebook. Ini membantu dalam memahami konsep-konsep yang divisualisasikan.
*   **`textbook-images/`**: Berisi gambar-gambar dari buku teks asli, yang digunakan untuk referensi dalam notebook.
*   **`apt.txt`**: File ini mencantumkan dependensi tingkat sistem yang mungkin perlu diinstal untuk menjalankan beberapa notebook.
*   **`my_model.pkl`**: Contoh model machine learning yang telah dilatih dan disimpan.
*   **`README.md`**: File yang sedang Anda baca ini.

## Cara Menggunakan

1.  **Clone Repositori**:
    ```bash
    git clone https://github.com/ageron/handson-ml2.git
    cd handson-ml2
    ```

2.  **Instal Dependensi**:
    Pastikan Anda memiliki Python dan pip terinstal. Dependensi Python disebutkan di dalam setiap notebook dan dapat diinstal sesuai kebutuhan. Untuk dependensi tingkat sistem pada sistem berbasis Debian/Ubuntu, Anda dapat menggunakan perintah berikut:
    ```bash
    sudo apt-get update
    sudo apt-get install -y $(cat apt.txt)
    ```

3.  **Jalankan Jupyter Notebook**:
    Setelah dependensi terinstal, Anda dapat memulai server Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
    Kemudian, buka notebook yang ingin Anda pelajari dari browser Anda.


