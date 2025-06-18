
# KLASIFIKASI TUBERKULOSIS PADA CITRA X-RAY MENGGUNAKAN TRANSFER LEARNING DENGAN ARSITEKTUR CONVNEXT MODEL CONVNEXT-TINY
Repositori ini berisi kode dan sumber daya untuk penelitian klasifikasi tuberkulosis (TBC) dari citra X-ray dada menggunakan model ConvNeXt-Tiny. Proyek ini mengimplementasikan beberapa teknik untuk menangani ketidakseimbangan data dan Hyperparameter Tuning untuk meningkatkan performa model, termasuk augmentasi adaptif dan Weighted Random Sampling.

## Abstrak
Tuberkulosis adalah penyakit menular yang disebabkan oleh Mycobacterium Tuberculosis. Sebagai penyakit yang mudah menular diperlukan diagnosis yang cepat dan efisien, salah satunya adalah menggunakan diagnosis citra X-ray dada menggunakan deep learning. Banyaknya penelitian klasifikasi tuberkulosis sebelumnya diperlukan adanya eksplorasi model terbaru. Penelitian ini bertujuan untuk mengembangkan model klasifikasi tuberkulosis berbasis machine learning menggunakan model CNN terbaru yaitu ConvNeXt yang mampu mencapai akurasi tertinggi pada dataset ImageNet. Dataset tuberkulosis yang digunakan berasal dari Kaggle. Kemudian dataset di split menjadi data training, testing, dan validasi. Proses selanjutnya dilakukan augmentasi adaptif dan pembobotan kelas minoritas. Pada tahap klasifikasi, arsitektur ConvNeXt yang dipilih adalah varian ConvNeXt-Tiny, kemudian dilakukan proses transfer learning untuk menyesuaikan model dengan dataset tuberkulosis. Hasil evaluasi menggunakan confusion matrix menunjukkan bahwa model mencapai akurasi sebesar 99,40%, nilai precision sebesar 99%, nilai recall sebesar 99%, dan nilai F1-Score sebesar 99%.

**Kata Kunci**: *Klasifikasi, Tuberkulosis, CNN, ConvNeXt*

## Dataset dan Model
Dataset yang digunakan dalam penelitian ini serta hasil model yang telah dilatih dapat diakses melalui tautan Google Drive di bawah ini.

- *https://drive.google.com/drive/folders/18llgzaPDpU6G4Xob2ZhG-hKX1_xDSlU_?usp=sharing*



## Instalasi
untuk menjalankan notebook ini, Anda perlu menginstal semua library yang dibutuhkan.

1. Clone Repository:

```bash
  git clone https://github.com/Wazven/ConvNeXt-Tiny_TB_Classification
```

2. Go to the project directory

```bash
  cd ConvNeXt-Tiny_TB_Classification
```


## Authors


- [@Wazven](https://www.github.com/Wazven) *Aka* **Aldi Rhiyadi**

