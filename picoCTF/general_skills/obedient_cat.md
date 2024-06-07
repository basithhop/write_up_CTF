# Write_up: Obedient Cat

## Pendahuluan
- **Penyelenggara**: picoCTF
- **Kategori**: General Skills
- **Poin**: 5
- **Deskripsi Tantangan**: This file has a flag in plain sight (aka "in-the-clear"). Download flag.

## Informasi Tantangan
Nama tantangan adalah "Obedient Cat". Tantangan ini termasuk dalam kategori General Skills dan bernilai 5 poin.
Tantangan ini termasuk di level easy.
Tantangan ini berkaitan dengan perintah/command “cat” di terminal dengan sistem operasi linux.

Command cat adalah salah satu perintah yang wajib kita pelajari. Namanya diambil dari kata “Concatenate”, yang berfungsi untuk membuat,
menggabungkan, atau menampilkan file di layar output standar atau ke file lain, dan banyak lagi.(sumber : https://www.hostinger.co.id/tutorial/cat-command-linux).

## Langkah-langkah Penyelesaian

### Analisis Awal
Langkah pertama adalah memahami deskripsi tantangan dan mengidentifikasi celah keamanan yang mungkin ada.
Dalam tantangan ini, kita dapat memahami dari judul bahwa akan menggunakan operasi cat di dalam terminal dengan sistem operasi linux untuk mendapatkan flag.

### Langkah Teknis

#### 1. Klik kanan mouse dan klik copy link pada tulisan “Download flag” dalam deskripsi tantangan.
#### 2. Buka terminal linux.
#### 3. Gunakan perintah “wget” untuk download file yang disediakan oleh picoCTF.
Sintaks perintah : wget <URL>
Contoh perintah : wget https://mercury.picoctf.net/static/704f877da185904ec3992e7255a15c6c/flag
#### 4. Cek file yang sudah didownload dengan perintah “ls”.
#### 5. Buka isi file dengan perintah “cat”.
Sintaks perintah : cat nama file
Contoh perintah : cat flag
#### 6. Flag ditemukan.

#### Potongan kode atau perintah yang digunakan

### Tools yang Digunakan
#### Terminal kali llinux

### Flag
#### picoCTF{s4n1ty_v3r1f13d_1a94e0f9}

## Kesimpulan
Tantangan Obedient Cat merupakan latihan untuk kita dalam memahami salah satu perintah dasar di linux yang perlu dipahami, yaitu perintah  “cat”.
Cat umumnya digunakan untuk membuat, menggabungkan, atau menampilkan file di layar output standar atau ke file lain.
Tantangan ini juga perlu pemahaman dasar untuk perintah “wget” yang digunakan untuk download sebuah file yang ada di dalam website.
