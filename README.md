# Berkas KP PLN IP UBP Saguling 
## File Aplikasi ada di Link Drive Berikut
Menggunakan Drive karena file terlalu banyak dan besar


[Drive] : https://drive.google.com/drive/folders/1eyo-83THayv1950JHSFkXu2aCLMJ6j2P?usp=sharing


Terdapat 2 File Aplikasi, Yakni untuk Aplikasi Temperature Prediction dan Aplikasi Data Barang


# Assets Aplikasi
## Assets Canva 

https://www.canva.com/design/DAGdrqAULik/WTWGdHTvsQcg_4i1exmIjw/edit?utm_content=DAGdrqAULik&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton 


## Temperature Prediction
### Assets Figma 
https://www.figma.com/design/yEOuq1wG2QMxrGPyyQAOLJ/Magang?node-id=0-1&t=2BQZE5RL3pEH69g3-1 

Untuk Aplikasi Temperature prediction apabila anda ingin mengubah modelnya, sesuaikan juga pathnya. 
Jika anda hendak menggunakan model lstm, dipath tolong disesuaikan lagi, kemudian ubah juga pada kode prediksinya karena bentuk inputnya berbeda

## Data Barang
### Assets Figma
https://www.figma.com/design/YoaLrsazcRCwG5ai6FFIDz/Magang---Data-Gudang?t=2BQZE5RL3pEH69g3-1 

# Cara Mengatur Database
sebagai catatan kami menggunakan postgresql
1. Install Vs Code
2. Masuk kan file Aplikasi yang diinginkan sebagai Worksheet
3. buka folder flask_api_project kemudian masuk ke script app.py
4. Ada bagian koneksi database baris 21 sampai 35 untuk temperature winding dan 17 sampai 30 untuk data barang.
5. Database yang digunakan harus memuat class yang ada di baris diatas
6. ketikkan python app.py
7. jalan kan ulang main.dart



# Cara Menjalankan Server local
1. Install Vs Code
2. Masuk kan file Aplikasi yang diinginkan sebagai Worksheet
3. buka folder flask_api_project kemudian masuk ke script app.py
4. ketikkan python app.py
5. Ubahlah Link Server sesuai yang anda inginkan (dalam kasus kami menggunakan ngrok), buka folder lib dan pilih file main.dart di folder aplikasi (temperature winding atau data barang) kemudian untuk setiap variabel final uri (baris 124,257, dan 407) ganti dengan link server yang digunakan ( dalam kasus kami final uri = Uri.parse('https://sloth-sure-genuinely.ngrok-free.app/upload');) hanya ganti dari https://sloth-sure-genuinely.ngrok-free.app saja pada setiap final uri
6. ketikkan flutter run di terminal vscode

 
