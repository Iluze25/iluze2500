# DOCUMENT USERFORM

- Document khusus untuk bagian userform pada app utama
- disini akan menjelaskan tentang bagaimana komponen, tema, fungsi userform ini ada
---
---
---
## NAVIGASI 
    1. Menu
    2. Transaksi
        - Daftar Transaksi
        - Data Barang
        - Total Rupiah
        - Detail Data
        + Komponen
    3. Data Transaksi
    4. Data Barang
    5. Data Pemasukkan
    6. Data Pesanan
    7. Data Barang Kosong
    8. Rank
---
---

## TRANSAKSI

- Saya membuat bagian bagian ini terpisah karena ada banyak sekali pendataan di bagian transaksi
- Dan disini akan sekalian memberikan dokumentasi terkait

**1. Daftar Transaksi**

- Disini bagian pemberian nama transaksinya apa

komponen :

*Frame : FrDaftarTransaksi*
- Tanggal : Tanggal
- Nama Pembeli : NamaPembeli
- Alamat : Alamat
- Nomor Telepon = Telepon

- Clear = Hapus
- Next = Lanjut
---

**2. Data Braang**

- Disini kita akan mendata barang, dari list harga yang sudah ditentuka dengan otomatis
- Memilih salah satua checkbox, tentang apakah data ini pesanan atau langsung Lunas dan dibawa
- Karena Data barang ada banyak sekali kategori yang berbeda. 
- Maka Saya membuat persediaan data, sebelum itu tidak ada
---
*Frame : frDataBarang*
- Nama Barang : NanamaBarang
- Rupiah : Harga
- Opsi Pesanan : chPesanan
---
*Frame : frDataFrame*
- Merk  : merkFrame
- Type : typeFrame
- Ukuran : sizeFrame
- Nama Frame : ListDataFrame
- Pcs : pcsFrame

+ Untuk bagian list data frame adalah full datanya
---
*Frame : frDataLensa*
- Jenis : jenisLensa
- Sph : sphLensa
- Cyl : cylLensa
- Add : addLensa
- Nama Lensa : namaLensa
- Pcs : pcsLensa
+ Untuk bagian Nama Lensa adalah full datanya
---
*Frame : frDataSoftlen*
- Merk : merkSft
- Sph : sphSoftlen
- DIA = diaSoftlen
- Color = colorSoftlen
- Nama Softlen : namaSoftlen
- Pcs : pcsSoftlen
+ Untuk bagian Nama Lensa adalah full datanya
---
*Frame : frBarangLainnya
- Nama Barang / Jasa : namaBarangJasa
- Pcs : pcsBarangLain

+ Khusus untuk bagian List (Pengeluaran), diberikan sebuah komponen textbox untuk memberikan list pengeluaran apa? 
+ List : 
    - Service
    - Cek Mata
    - Over Lens
    - Ganti Warna
    - (Pengeluaran)
    - Noseped
---