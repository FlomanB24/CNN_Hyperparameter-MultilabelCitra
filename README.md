Proyek ini berfokus pada **pengembangan model Convolutional Neural Network (CNN) dari awal (scratch)**. Dalam proyek ini, arsitektur jaringan CNN dirancang secara mandiri tanpa menggunakan model pra-latih (pretrained), serta dilakukan eksplorasi dan tuning terhadap berbagai hyperparameter untuk mengoptimalkan performa model.

📌 **Ruang lingkup proyek mencakup:**

* Mendesain arsitektur CNN dari nol,
* Melakukan tuning hyperparameter, termasuk:

  * Jumlah hidden layer,
  * Jumlah epoch,
  * Ukuran batch (batch size),
  * Fungsi aktivasi (activation function),
  * Learning rate,
  * Fungsi optimisasi (optimization function).

📊 **Dataset:**
Proyek ini menggunakan dataset dari Kaggle:
🔗 [Multi-Label Image Classification Dataset](https://www.kaggle.com/datasets/meherunnesashraboni/multi-label-image-classification-dataset/data)

Dataset ini merupakan kumpulan citra untuk **klasifikasi multilabel**, terdiri dari 10 kategori objek, yaitu:

* **Kendaraan**: motorcycle, truck, train, bus, cycle
* **Alat musik tradisional**: sitar, ektara, flutes, tabla, harmonium

Setiap citra dapat memiliki lebih dari satu label, sehingga model perlu mampu mengenali beberapa objek sekaligus dalam satu gambar.

🎯 **Tujuan:**
Memahami cara kerja CNN dari tingkat dasar, serta mengembangkan kemampuan dalam menyusun arsitektur dan mengoptimasi hyperparameter secara sistematis pada tugas klasifikasi multilabel citra.
