# Deteksi Objek dengan YOLOv4

**Project ini siap digunakan**. Dapat diunduh dengan perintah:

```sh
git clone https://github.com/andrewmanuelt/eksperimen_yolov4.git
```

kemudian silahkan rename file **backup_annotations.txt** dalam folder **dataset/main** menjadi **_annotations.txt**, juga **backup_classes.txt** menjadi **_classes.txt** 

**Berikut ini untuk proses inisialisasi project**

Tutorial dapat diakses [di sini](https://neptune.ai/blog/object-detection-with-yolo-hands-on-tutorial)
Original project dapat di clone via GitHub [di sini](https://github.com/taipingeric/yolo-v4-tf.keras)
Dataset dapat diunduh [di sini](https://public.roboflow.com/object-detection/bccd)

Clone project terlebih dahulu. Pastikan telah menginstall Git dan clone repositori dengan perintah berikut:
```sh
git clone https://github.com/taipingeric/yolo-v4-tf.keras.git
```

Dataset telah tersedia pada project ini, namun ada beberapa catatan dalam memulai project dengan dataset berbeda:

atau bisa langsung mendownload file zip project. Kemudian siapkan dataset dengan mengakses link diatas. 
Download dataset dengan format **YoloV4-PyTorch**, tempatkan pada folder **dataset** sebagai root. Kemudian satukan saja antara **training** dan **test** baik dataset image yang digunakan maupun isi dari **_annotations**. Copy file **_annotations.txt** dan **_classes.txt** ke root directory. File pada folder **valid** dapat digunakan untuk untuk proses prediksi. Project di desain untuk melakukan training dan testing berdasarkan rasio (**DataGenerator**).

Untuk mulai melakukan pelatihan, jalankan Jupyter Notebook **train.ipynb**

Done.

