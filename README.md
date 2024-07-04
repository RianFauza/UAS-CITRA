## UAS-PENGOLAHAN CITRA

| Nama  |  Nim | Kelas |
| ------------- | ------------- |------------- |
| Agus Setiawan  | 312210193 | TI 22 A2 |
| Rian Fauza  | 312210083 | TI 22 A2 |

### App K-Means Clutering Segmentasi Gambar 

1. **Imports**: Mengimpor library yang diperlukan seperti `streamlit`, `numpy`, `cv2` (OpenCV), `Image` (dari PIL), dan `matplotlib` untuk plotting.

2. **Fungsi `segment_image`**: Fungsi ini menggunakan K-Means Clustering untuk membagi gambar menjadi beberapa segmen berdasarkan warna. Ini dilakukan dengan mereshape gambar menjadi array piksel dan mengaplikasikan K-Means menggunakan OpenCV.

3. **Fungsi `get_color_name`**: Fungsi ini mengidentifikasi nama warna berdasarkan nilai RGB dari pusat cluster yang dihasilkan oleh K-Means.

4. **Konfigurasi Halaman Streamlit**: Mengatur judul halaman, ikon, dan layout halaman menggunakan `st.set_page_config` dan menambahkan gaya CSS untuk mempercantik tampilan.

5. **Tampilan Aplikasi**: Memanfaatkan markup HTML dan fungsi Streamlit seperti `st.markdown` untuk menampilkan judul aplikasi dan segmen.

6. **Layout Kolom**: Membagi antara kolom untuk mengunggah gambar dan kolom untuk pengaturan segmentasi menggunakan `st.columns`.

7. **Unggah Gambar**: Memungkinkan pengguna untuk mengunggah gambar, kemudian menampilkan gambar tersebut menggunakan `st.image`.

8. **Parameter Segmentasi**: Di sidebar, menampilkan slider untuk memilih jumlah cluster (k) dan tombol untuk memicu proses segmentasi.

9. **Proses Segmentasi**: Ketika tombol "Segmentasikan Gambar" ditekan, aplikasi akan memproses gambar yang diunggah menggunakan K-Means Clustering. Hasil segmentasi dan persentase warna setiap segmen ditampilkan.

10. **Plot Warna**: Menampilkan plot warna untuk setiap segmen menggunakan warna yang diidentifikasi.

11. **Menjalankan Aplikasi**: Menggunakan `if __name__ == '__main__':` untuk memastikan aplikasi dijalankan dengan benar saat skrip dieksekusi.

Aplikasi ini memanfaatkan kekuatan Streamlit untuk membuat antarmuka pengguna yang interaktif dan menampilkan hasil segmentasi gambar secara visual.


#### Tampilan Home

<img src="https://github.com/RianFauza/UAS-CITRA/assets/115542822/705added-7514-49b2-84dd-b34fa611a9c3" alt="deskripsi_gambar" style="width: 70%; height: auto;">

#### Gambar Asli

<img src="https://github.com/RianFauza/UAS-CITRA/assets/115542822/4984b8d8-a097-4397-9aa0-68814f81cfc6" alt="deskripsi_gambar" style="width: 70%; height: auto;">

#### Gambar Tersegmentasi

<img src="https://github.com/RianFauza/UAS-CITRA/assets/115542822/705added-7514-49b2-84dd-b34fa611a9c3" alt="deskripsi_gambar" style="width: 70%; height: auto;">

#### Hasil Presentase Warna Setiap Segmen

<img src="https://github.com/RianFauza/UAS-CITRA/assets/115542822/0f2c2afd-2b54-4dca-8390-148c9f6fce8f" alt="deskripsi_gambar" style="width: 70%; height: auto;">

#### Gambar Asli Kedua

<img src="https://github.com/RianFauza/UAS-CITRA/assets/115542822/6beb1a9f-18fe-4ea5-ae8b-e0568bf2e2cb" alt="deskripsi_gambar" style="width: 70%; height: auto;">

#### Gambar Tersegmentasi

<img src="https://github.com/RianFauza/UAS-CITRA/assets/115542822/7a69f38f-876e-46b4-8be5-91c1237eab0c" alt="deskripsi_gambar" style="width: 70%; height: auto;">

#### Hasil Presentase Warna Setiap Segmen

<img src="https://github.com/RianFauza/UAS-CITRA/assets/115542822/0d14062b-41af-4247-be0e-a1fa056ac3a2" alt="deskripsi_gambar" style="width: 70%; height: auto;">

#### Hasil k-means clustering dengan jumlah cluster(5)

<img src="https://github.com/RianFauza/UAS-CITRA/assets/115542822/7b296845-c3f8-4de6-b891-cd42fa4380ff" alt="deskripsi_gambar" style="width: 70%; height: auto;">

