# Final-Project-Visualization-With-Python
**Analisis Dampak Resesi terhadap Penjualan Mobil**

Anda telah dipekerjakan oleh XYZAutomotives sebagai data scientist. Tugas pertama Anda adalah menganalisis data historis dan memberikan wawasan kepada direktur perusahaan tentang bagaimana penjualan dipengaruhi selama masa resesi. Anda akan menyediakan sejumlah grafik/plot untuk memvisualisasikan data dan memudahkan direktur memahami analisis Anda.

**Instruksi untuk pengiriman**

Anda akan diminta untuk mengunggah gambar yang menunjukkan plot atau dashboard Anda, agar teman sejawat dapat meninjau dan memberikan poin. Untuk setiap tugas, Anda akan diarahkan untuk menyimpan gambar Anda secara lokal dengan nama spesifik. Kami merekomendasikan agar Anda membuat folder lokal dan menyimpan semua gambar Anda di sana untuk referensi mudah.

Di akhir setiap tugas, Anda akan diberikan nama untuk menyimpan gambar plot/chart Anda.

Contoh:
Simpan plot ini sebagai "Line_Plot_1.png"
*Hint: Anda dapat mengklik kanan pada plot dan kemudian klik opsi "Save image as" untuk menyimpannya di mesin lokal Anda*

**Tentang dataset**

Dalam tugas ini, Anda akan diberikan berbagai pertanyaan untuk menganalisis data untuk memahami tren historis dalam penjualan mobil selama periode resesi.

- Periode resesi 1 - tahun 1980
- Periode resesi 2 - tahun 1981 hingga 1982
- Periode resesi 3 - tahun 1991
- Periode resesi 4 - tahun 2000 hingga 2001
- Periode resesi 5 - akhir tahun 2007 hingga pertengahan 2009
- Periode resesi 6 - Februari hingga April 2020 (Dampak Covid-19)

Data yang digunakan dalam lab ini dibuat secara artifisial untuk tujuan tugas ini saja. Tidak ada data nyata yang digunakan.

**Deskripsi Data**

Dataset mencakup variabel-variabel berikut:

- **Date**: Tanggal observasi.
- **Recession**: Variabel biner yang menunjukkan periode resesi; 1 berarti sedang resesi, 0 berarti normal.
- **Automobile_Sales**: Jumlah kendaraan yang terjual selama periode tersebut.
- **GDP**: Nilai GDP per kapita dalam USD.
- **Unemployment_Rate**: Tingkat pengangguran bulanan.
- **Consumer_Confidence**: Indeks sintetis yang mewakili kepercayaan konsumen, yang dapat mempengaruhi pengeluaran konsumen dan pembelian mobil.
- **Seasonality_Weight**: Bobot yang mewakili efek musiman pada penjualan mobil selama periode tersebut.
- **Price**: Harga rata-rata kendaraan selama periode tersebut.
- **Advertising_Expenditure**: Pengeluaran iklan perusahaan.
- **Vehicle_Type**: Jenis kendaraan yang dijual; Supperminicar, Smallfamilycar, Mediumfamilycar, Executivecar, Sports.
- **Competition**: Ukuran persaingan di pasar, seperti jumlah pesaing atau pangsa pasar produsen utama.
- **Month**: Bulan dari observasi yang diekstraksi dari Tanggal.
- **Year**: Tahun dari observasi yang diekstraksi dari Tanggal.

Dengan memeriksa berbagai faktor yang disebutkan di atas dari dataset, Anda bertujuan untuk mendapatkan wawasan tentang bagaimana resesi berdampak pada penjualan mobil untuk perusahaan Anda.

**Proyek ini akan diselesaikan dalam 3 Bagian:**

1. Membuat Visualisasi menggunakan Matplotlib, Seaborn & Folium
2. Membuat Dashboard menggunakan Plotly dan Dash
3. Mengirimkan proyek Anda dan mengevaluasi teman sejawat

**Bagian 1: Membuat visualisasi menggunakan Matplotlib, Seaborn & Folium**

**Tujuan:**

Tujuan dari bagian tugas akhir ini adalah untuk menganalisis tren historis dalam penjualan mobil selama periode resesi. Tujuannya adalah untuk memberikan wawasan tentang bagaimana penjualan XYZAutomotives, perusahaan yang mengkhususkan diri dalam penjualan otomotif, terpengaruh selama masa resesi.

Dalam lab ini, Anda akan membuat visualisasi menggunakan Matplotlib, Seaborn, Pandas.

**Tugas yang harus dilakukan**

- **TASK 1.1**: Mengembangkan grafik garis menggunakan fungsionalitas pandas untuk menunjukkan bagaimana penjualan mobil berfluktuasi dari tahun ke tahun.
- **TASK 1.2**: Membuat garis yang berbeda untuk kategori jenis kendaraan dan menganalisis tren untuk menjawab pertanyaan "Apakah ada perbedaan yang mencolok dalam tren penjualan antara jenis kendaraan yang berbeda selama periode resesi?"
- **TASK 1.3**: Menggunakan fungsionalitas Seaborn Library untuk membuat visualisasi untuk membandingkan tren penjualan per jenis kendaraan untuk periode resesi dengan periode non-resesi.
- **TASK 1.4**: Menggunakan subplotting untuk membandingkan variasi GDP selama periode resesi dan non-resesi dengan membuat grafik garis untuk setiap periode.
- **TASK 1.5**: Mengembangkan plot Bubble untuk menampilkan dampak musiman pada Penjualan Mobil.
- **TASK 1.6**: Menggunakan fungsionalitas Matplotlib untuk mengembangkan scatter plot untuk mengidentifikasi korelasi antara harga kendaraan rata-rata dan volume penjualan selama resesi.
- **TASK 1.7**: Membuat pie chart untuk menampilkan porsi pengeluaran iklan XYZAutomotives selama periode resesi dan non-resesi.
- **TASK 1.8**: Mengembangkan pie chart untuk menampilkan total pengeluaran iklan untuk setiap jenis kendaraan selama periode resesi.
- **TASK 1.9**: Mengembangkan line plot untuk menganalisis efek tingkat pengangguran pada jenis kendaraan dan penjualan selama Periode Resesi.


**Bagian 2: Membuat Dashboard menggunakan Plotly dan Dash**

**Tujuan:**

Tujuan dari bagian tugas akhir ini adalah untuk membuat dashboard yang berisi plot dan grafik Anda serta memberikan direktur kemampuan untuk memilih laporan tertentu atau periode waktu sehingga mereka dapat membahas data secara rinci.

Dalam lab ini, Anda akan membuat dashboard menggunakan Dash dan Plotly dan kemudian menambahkan interaksi pengguna ke dashboard Anda.

**Membuat dashboard dan menambahkan kustomisasi ke dashboard**

Direktur XYZAutomobiles telah meminta agar dashboard dikembangkan sehingga mereka dapat meneliti data secara lebih rinci untuk tahun-tahun tertentu atau berdasarkan kategori yang berbeda. Tugas kedua Anda adalah membuat dashboard yang sesuai dan menambahkan interaksi pengguna sehingga direktur dapat memilih data yang ingin mereka tinjau tanpa perlu meminta plot baru.

**Tugas yang harus dilakukan:**

- **TASK 2.1**: Membuat aplikasi Dash dan memberi judul yang bermakna.
- **TASK 2.2**: Menambahkan menu drop-down ke dashboard Anda dengan judul dan opsi yang sesuai.
- **TASK 2.3**: Menambahkan divisi untuk tampilan output dengan id dan properti classname yang sesuai.
- **TASK 2.4**: Membuat Callbacks; Mendefinisikan fungsi callback untuk memperbarui wadah input berdasarkan statistik yang dipilih dan wadah output.
- **TASK 2.5**: Membuat dan menampilkan grafik untuk Statistik Laporan Resesi.
- **TASK 2.6**: Membuat dan menampilkan grafik untuk Statistik Laporan Tahunan.

**Bagian 3: Kirimkan Proyek Anda dan Evaluasi Rekan**

Setelah Anda menyelesaikan semua lab dan menyimpan semua file Anda secara lokal, Anda akan mengirimkan tugas Anda yang akan dinilai oleh rekan-rekan Anda yang juga menyelesaikan kursus ini selama sesi yang sama.

Poin akan diberikan sebagai berikut untuk setiap tugas yang diselesaikan:

**Bagian 1: Total 10 poin**

- **TASK 1.1**: Mengembangkan grafik garis menggunakan fungsi pandas untuk menunjukkan bagaimana penjualan mobil berfluktuasi dari tahun ke tahun. (1 poin)
- **TASK 1.2**: Memplotkan garis yang berbeda untuk kategori jenis kendaraan dan menganalisis tren untuk menjawab pertanyaan "Apakah ada perbedaan yang mencolok dalam tren penjualan antara jenis kendaraan yang berbeda selama periode resesi?" (1 poin)
- **TASK 1.3**: Menggunakan fungsi Library Seaborn untuk membuat visualisasi untuk membandingkan tren penjualan per jenis kendaraan selama periode resesi dengan periode non-resesi. (1 poin)
- **TASK 1.4**: Menggunakan sub plotting untuk membandingkan variasi dalam GDP selama periode resesi dan non-resesi dengan mengembangkan grafik garis untuk setiap periode. (2 poin)
- **TASK 1.5**: Mengembangkan Bubble plot untuk menampilkan dampak musiman pada Penjualan Mobil. (1 poin)
- **TASK 1.6**: Menggunakan fungsi Matplotlib untuk mengembangkan scatter plot untuk mengidentifikasi korelasi antara harga kendaraan rata-rata dan volume penjualan selama resesi. (1 poin)
- **TASK 1.7**: Membuat pie chart untuk menampilkan bagian dari pengeluaran iklan XYZAutomotives selama periode resesi dan non-resesi. (1 poin)
- **TASK 1.8**: Mengembangkan pie chart untuk menampilkan total pengeluaran iklan untuk setiap jenis kendaraan selama periode resesi. (1 poin)
- **TASK 1.9**: Mengembangkan grafik garis untuk menganalisis efek tingkat pengangguran pada jenis kendaraan dan penjualan selama Periode Resesi. (1 poin)

**Bagian 2: Total 14 poin**

- **TASK 2.1**: Membuat aplikasi Dash dan memberi judul yang bermakna. (2 poin)
- **TASK 2.2**: Menambahkan menu drop-down ke dashboard Anda dengan judul dan opsi yang sesuai. (1 poin)
- **TASK 2.3**: Menambahkan divisi untuk tampilan output dengan id dan properti classname yang sesuai. (1 poin)
- **TASK 2.4**: Membuat Callbacks; Mendefinisikan fungsi callback untuk memperbarui wadah input berdasarkan statistik yang dipilih dan wadah output. (5 poin)
- **TASK 2.5**: Membuat dan menampilkan grafik untuk Statistik Laporan Resesi. (3 poin)
- **TASK 2.6**: Membuat dan menampilkan grafik untuk Statistik Laporan Tahunan. (2 poin)

Setelah semua tugas diselesaikan dan file disimpan, kirimkan proyek Anda untuk dinilai oleh rekan-rekan Anda.
