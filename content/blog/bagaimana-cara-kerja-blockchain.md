---
title: "Bagaimana Cara Kerja Blockchain?"
date: 2025-04-10T10:54:42+07:00
created_date: "10/04/2025"
updated_date: "17/04/2025"
has_updated: true

meta_robot_is_indexed: true
meta_published_time: "2025-04-10T10:54:42+07:00"
meta_modified_time: "2025-04-10T10:54:42+07:00"
meta_description: "Blockchain adalah teknologi dibalik mata uang kripto yang semakin menjadi tren di kalangan trader. Apa sebenarnya blockchain dan bagaimana ia bekerja? Dalam artikel ini akan dibahas dengan sangat sederhana bagaimana cara blockchain bekerja"
meta_keywords:
- blockchain
- crypto currency
- bitcoin

ads_disclosure: false
ads_sidebar: false
ads_sidebar_name: ""
ads_header: false
ads_header_name: ""

featured_image: "/img/featured-images/blockchain1.jpg"
alt_featured_image: "cara kerja blockchain"

author: "Defitra"
read_time: "5 min read"
type: "post"

categories:
- Teknologi
tags:
- blockchain
- crypto currency
- bitcoin
series:
-

description: "Blockchain adalah teknologi dibalik mata uang kripto yang semakin menjadi tren di kalangan trader. Apa sebenarnya blockchain dan bagaimana ia bekerja? Dalam artikel ini akan dibahas dengan sangat sederhana bagaimana cara blockchain bekerja"

show_table_of_content: true
archive: false
draft: false
---

Beberapa dari kita mungkin sudah tidak asing lagi dengan yang namanya mata uang kripto atau *crypto currency*. Namun tahukah kamu bahwa terdapat teknologi di balik mata uang kripto, yaitu *Blockchain*.

## Apa itu *Blockchain*?

*Blockchain* adalah teknologi yang berisi banyak blok yang saling terkait satu sama lain dan bersifat terdesentralisasi. Bayangkan ada 1 blok yang berisi banyak transaksi. Kemudian dibuat blok baru dan di-*chain* dengan blok sebelumnya. Sampai disini dulu, masih mudah dipahami kan?

Nah, setiap blok dalam *blockchain* harus diverifikasi dengan metode konsensus, salah satunya adalah *Proof of Work*. Apa itu *Proof of Work*?

## Metode *Proof of Work*

Cara kerja metode atau mekanisme *Proof of Work* adalah dengan mencari kombinasi alfanumerik yang cocok untuk memverifikasi transaksi pada satu blok.

Secara teknis, setiap blok pada *blockchain* memiliki *header* yang di-*hash* menggunakan SHA256 untuk memastikan bahwa blok tidak dapat diubah. Kalaupun diubah, pasti bisa dideteksi. Berikut contohnya:

{{<prompt_box>}}
<div><strong>Transaksi =</strong></div>
<br>
<center>"Defitra memiliki 100 koin"</center>
<center>"John memiliki 200 koin"</center>
<center>"Fitra mengirimkan 20 koin kepada John"</center>
<br>
<div> Nonce = 7235</div>
<br>
<div>Output (Hash) = 653404901254...</div>
{{</prompt_box>}}


Dapat dilihat pada contoh di atas bahwa 3 (tiga) transaksi siap diverifikasi dalam 1 (satu) blok. Ingat ya, ini hanya contoh sederhana. Kenapa harus diverifikasi? Tentu saja agar blok tersebut tidak dapat diubah. Bayangkan jika kita punya 5 buku yang masing-masing berisi transaksi tahun 2019, 2020, 2021, 2022, 2023. Buku ke-6 sedang kita kerjakan. Bisa saja seseorang mengubah transaksi pada 2020 tanpa kita ketahui. Apalagi kita tidak menghafal isi transaksi tersebut. Dengan adanya verifikasi, maka tidak ada lagi pihak yang dapat mengubah transaksi. Jikapun ada yang mencoba mengubah transaksi, maka perubahan itu akan terlihat dengan sangat jelas. Verifikasi menjadikan *blokchain* hampir mustahil untuk diretas.

Lantas siapa yang memverifikasi transaksi tersebut? Mereka kita sebut dengan penambang atau *miner*. Bagaimana mereka memverifikasi transaksi? Ayo kita balik lagi ke contoh di atas. Ada bagian *Nonce* yang berisi angka acak, bukan? Apabila kita mengubah angka *nonce*, maka outputnya juga akan berubah. Nah, tugas dari *miner* adalah mengubah nilai *nonce* agar output (*hash*) yang dihasilkan sesuai dengan aturan. Aturan itu misalnya output (*hash*) harus diawali angka nol sebanyak 4, bisa juga sampai 30 angka nol. Apabila ditemukan *nonce* yang sesuai, maka blok baru ditambahkan ke dalam *blockchain*.

## Dari mana asal *bitcoin*

*Miner* yang berhasil menemukan *nonce* yang sesuai akan diberikan mata uang kripto sebagai *reward*. Mencari *nonce* yang sesuai tentunya membutuhkan sumberdaya komputasi alias butuh komputer dengan kinerja yang tinggi. Kira-kira transaksinya akan menjadi seperti ini:

{{<prompt_box>}}
<div><strong>Transaksi =</strong></div>
<br>
<center>"Miner mendapatkan 12,5 koin"</center>
<center>"Defitra memiliki 100 koin"</center>
<center>"John memiliki 200 koin"</center>
<center>"Fitra mengirimkan 20 koin kepada John"</center>
<br>
<div> Nonce = 6354</div>
<br>
<div>Output (Hash) = 00007236476...</div>
{{</prompt_box>}}

Seperti yang dilihat di atas, ternyata *nonce* 6354 menghasilkan output (*hash*) dengan angka nol sebanyak 4 (empat). Maka *miner* berhak atas sejumlah mata uang kripto. (Tentunya ini hanya contoh ilustrasi ya).

## Apa itu *Chain* pada *Blokchain*?

Output (*hash*) pada blok tadi akan menjadi *header* pada blok berikutnya. Jadi, blok yang baru ditambahkan ke *blockchain* akan berkaitan langsung dengan blok-blok sebelumnya. Itu artinya, jika ada yang mengubah transaksi pada 1 blok saja, maka itu akan mempengaruhi seluruh blok yang ada. Jadi sangat sangat sangat sangat.... sulit untuk meretas *Blockchain*.

![Simulasi blockchain](/img/blog/simulasi-blockchain.jpg)

## Kesimpulan
*Blockchain* adalah teknologi yang melibatkan blok-blok yang saling terkait dan berisi transaksi yang diverifikasi dengan cara konsensus dan bersifat terdesentralisasi. Penggunaan *blockchain* tidak hanya sebatas pada pengiriman/transaksi uang saja ya. Bisa juga digunakan untuk transaksi lain, salah satunya adalah pembuatan kontrak.

Jika kamu ingin melihat bagaimana cara kerja *blockchain*, silakan klik tautan [*blockchain demo*](https://andersbrownworth.com/blockchain/coinbase) oleh Anders Brown Worth.
