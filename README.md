# Dynamic-Budget-vs-Actuals-Dashboard-on-Excel

## 1. Pendahuluan
Proyek ini bertujuan untuk membuat dashboard dinamis yang membandingkan antara anggaran bulanan (budget) dengan realisasi aktual (actual) untuk pemasukan dan pengeluaran. Dashboard ini dirancang agar memudahkan pengguna dalam memantau efisiensi anggaran dan pengeluaran secara interaktif.

## 2. Deskripsi Data
### Sumber Data
#### 1.	Data Actual
o	Tabel berisi transaksi aktual (pemasukan dan pengeluaran):
Kolom	Deskripsi
Tanggal	Tanggal transaksi dalam format DD-MM-YYYY.
Bulan	Bulan transaksi (contoh: Januari).
Kategori	Jenis transaksi (contoh: Belanja Harian, Hiburan).
Keterangan	Penjelasan tambahan transaksi.
Jumlah	Nilai transaksi dalam Rupiah.
![aktual pemasukan dan pengeluaran_Page_1](https://github.com/user-attachments/assets/e6edd0e4-d6b0-43cc-963f-2c703fb4fcbd)

#### 2.	Data Budget
o	Tabel berisi anggaran bulanan:
![budgeting](https://github.com/user-attachments/assets/4d9eb7b4-b0d6-4278-b31b-d7fede6f1e23)

## 3. Proses Pengolahan Data
### Tahapan Proses
#### 1.	Data Cleaning:
-	Menghapus nilai kosong (null values).
-	Standarisasi format angka dan tanggal.
#### 2.	Integrasi Data:
-	Menggabungkan tabel Actual dan Budget menggunakan VLOOKUP atau INDEX-MATCH.
-	Menambahkan kolom perhitungan:
	Var. Abs = Actual - Budget.
	Var. % = (Var. Abs / Budget) * 100.
#### 3.	Pembuatan Tabel Analisis:
-	Merangkum data menggunakan Pivot Table.

## 4. Visualisasi Dashboard
![Dashboard](https://github.com/user-attachments/assets/8e83a3d3-a6c1-48c5-b697-0833532a1da5)

### Dashboard berisi komponen berikut:
1.	Tabel Perbandingan Budget vs Actual
2.	Grafik Batang Budget vs Actual Income:
o	Menampilkan perbandingan pemasukan bulanan (Budget vs Actual).
3.	Grafik Batang Budget vs Actual Expense Breakdown:
o	Menunjukkan perbandingan pengeluaran untuk kategori seperti Belanja Harian, Hiburan, dll.
4.	Grafik Pie Actual Expense: Menampilkan proporsi pengeluaran aktual berdasarkan kategori.
  
Fitur Interaktif
- Slicer:	Untuk memilih bulan atau kategori spesifik.
- -Dynamic Range: Data grafik akan otomatis terupdate ketika tabel sumber berubah.



