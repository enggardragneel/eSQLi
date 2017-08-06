# eSQLi
Automatic generate query for manual SQL injection

#Penggunaan :

poi@kirin : python esqli.py

# Keterangan :

1. Masukkan Jumlah Kolom :

Masukkan Jumlah kolom yang ingin diinject
ex : 1,2,3,4,5,6,dst

2. Masukan no Togel ( magic number ) :

Masukkan Magic number / no togel yang ditampilkan site saat diinjeksi.

3. Masukkan nama :

Masukkan Nama Injector nya 
ex : kirin 

4. Tampilkan MySQL ? (Y/n)
5. Tampilkan user MySQL ? (Y/n)
6. Tampilkan hostname ? (Y/n)
7. Tampilkan database ? (Y/n)
8. Tampilkan OS yg dipakai ? (Y/n)
9. Cek Symlink ? (Y/n)
10. Cek Port Sql ? (Y/n) 
11. Cek SSL ? (Y/n)

Jika Menekan tombol "Y" Maka nantinya di dalam Query akan menampilkan perintah seperti version(),user(),dll
jika menekan tombol "N" Maka tidak akan ditampilkan / di skip

12. Pilih Dios !! 

    1. Dios Normal 
    2. Madblood 
    3. Zen 
    4. Makman 
    5. Makman(SQLi Gods Syntax ) 
    6. Dr.Z3r0 
    7. T-PRO 
    8. Ajkaro 
    9. Tr0jan 

  Pilihan :

Silahkan pilih versi DIOS yang disediakan ( tinggal pilih berdasarkan no urut ) / bisa juga dikosongi 

Nantinya jika semua sudah komplit akan ditampilkan didalam Final Query :
example :

---------------Final Query---------------
1,concat(0x6b6972696e,0x3a,version(),0x3c62723e55736572203a20,user(),0x3c62723e4461746162617365203a20,database()),3

#Note 

- Tools ini hanya untuk mempermudah dalam menampilkan query dalam SQL injection bukan untuk melakukan test injeksi seperti ( SQLmap , Havij dll) 
- Terkadang Query yang dihasilkan tidak bekerja dibeberapa situs. terutama situs yang dilindungi oleh WAF
- Tool ini dibuat hanya untuk pembelajaran tentang bagaimana para "injector" bisa menampilkan data melalui SQL injection
