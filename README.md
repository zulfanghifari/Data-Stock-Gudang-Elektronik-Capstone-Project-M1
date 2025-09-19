# Sistem Stok Gudang Elektronik (Python)

Program ini dibuat untuk memudahkan admin gudang elektronik dalam melakukan pendataan stok barang.  
Admin dapat:
- Melihat jumlah stok barang yang tersedia.
- Menambahkan produk baru ke gudang.
- Mengubah stok produk yang sudah ada.
- Menghapus produk.
- Mencatat transaksi barang masuk dan barang keluar sehingga data selalu ter-update.

##  Teknologi yang Digunakan
- **Python 3**

##  Cara Menjalankan Program
1. Pastikan Python 3 terpasang di komputer.
2. Install library `tabulate`:
   ```bash
   pip install tabulate
   ```
   atau gunakan:
   ```bash
   pip install -r requirements.txt
   ```
3. Jalankan program:
   ```bash
   python CapstoneProject-M1-MuhammadZulfanAlghifari.py
   ```

##  Fitur Utama
Ketika program dijalankan, akan muncul menu utama dengan fitur berikut:

1. **Tampilkan Semua Stok**  
   Menampilkan seluruh stok barang berdasarkan data awal.

2. **Tambah Produk Baru**  
   Menambahkan produk baru (input jumlah harus angka bulat).

3. **Ubah Stok Produk**  
   Mengubah stok produk yang ada (input angka bulat sesuai data).

4. **Hapus Produk**  
   Menghapus produk dari gudang (input sesuai data, jika tidak program meminta input ulang).

5. **Transaksi Masuk Barang**  
   Menambahkan stok produk yang sudah ada di database (input sesuai produk).

6. **Transaksi Keluar Barang**  
   Mengurangi stok produk yang sudah ada (stok dicek agar mencukupi).

7. **Keluar**  
   Mengakhiri program.

##  Struktur Folder
```
/project-folder
│
├─ CapstoneProject-M1-MuhammadZulfanAlghifari.py
├─ README.md
├─ requirements.txt
├─ .gitignore
└─ images/         # opsional untuk screenshot/flowchart
```

##  Catatan
- Pastikan input jumlah berupa angka bulat.

## 👤 Author
Muhammad Zulfan Alghifari
