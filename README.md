# Jarkom-Modul-1-IT20-2024
Write-up pengerjaan soal shift modul 1 praktikum Jaringan Komputer kelompok IT20

## Anggota Kelompok
1. George David Nebore (5027221043)
2. solo mode :)

## Soal yang dikerjakan selama praktikum
### 1. Advance Sanity Check
![Advance Sanity Check 2](https://github.com/user-attachments/assets/515860f9-2eb0-4cb6-ba69-90d6be3bf022)

pada soal ini ditanyakan beberapa pertanyaan yang harus dijawab terlebih dahulu sebelum mendapatkan flag buat selanjutnya diinput pada platform soal shift, antara lain:
- apa username pengirim?<br>
jawaban: JaneD03
![Screenshot 2024-09-22 073403](https://github.com/user-attachments/assets/ad44101a-ee13-4d8a-a1e5-b72a5d982e27)<br>
username sendiri tertera pada stream ke 3 paket TCP bisa dilihat seperti gambar diatas ada keterangan username dengan nama JaneD03

- apa nama file yang dikirim?<br>
jawaban: Clue3.txt
![Screenshot 2024-09-22 073424](https://github.com/user-attachments/assets/f3f8b63c-2deb-443b-b74d-58da3e24a60b)
nama file yang dikirim dapat dilihat pada stream ke 4 paket TCP, terdapat keterangan filename yaitu Clue3.txt

- Ikuti petunjuk untuk mendapatkan pesan rahasia<br>
jawaban: penword
![Advance Sanity Check](https://github.com/user-attachments/assets/515860f9-2eb0-4cb6-ba69-90d6be3bf022)

saya mendapatkan pesan rahasi yang ada pada peraturan soal shift yang selanjutnya perlu di decode menggunakan base64 dan menjadi string yang diinginkan

### 2. Packet barrage
![Advance Sanity Check](https://github.com/user-attachments/assets/0a4efbe0-9554-4bfb-9955-8ae5ffc256c7)

pertanyaan yang perlu dijawab untuk mendapat flag yaitu:
- Apa IP address dari attacker?<br>
jawaban: 172.21.80.1
![Screenshot 2024-09-22 080451](https://github.com/user-attachments/assets/e2af0201-7d4d-4ff1-8daa-e6020f720b7d)<br>
saya mengubah file paket stream TCP dalam forma YAML untuk mengecek source dari paket yang dikirimkan oleh attacker gambar tersebut tertera IP address dari attacker.<br>

- Berapa total attempt dari bruteforce attacker?<br>
jawaban: 1917<br>

- Apa nama file yang didownload oleh attacker setelah berhasil login?<br>
jawaban: Albatros.txt<br>

- Apa isi dari file yang disisipkan oleh attacker?<br>
jawaban: Der Rote Kampfflieger<br>
![Screenshot 2024-09-22 081151](https://github.com/user-attachments/assets/d789c434-e59a-4543-8a1e-db85795d3255)<br>


### 3. FTP login
![FTP login](https://github.com/user-attachments/assets/38d540a7-bdbd-43e3-b30c-2d7f60c3a847)

pertanyaan yang perlu dijawab yaitu:
- Apa username yang berhasil digunakan untuk FTP login?<br>
jawaban: sn34ky<br>

- Apa password yang berhasil digunakan untuk FTP login?<br>
jawaban: sup3rsn1ff3r<br>
![Screenshot 2024-09-22 081831](https://github.com/user-attachments/assets/c5423a68-09b4-4f64-aa78-c6793e7bf3c3)

### 4. Corporate Breach
![Pegawai Negeri Sebelah](https://github.com/user-attachments/assets/4252dddc-2fc4-46b4-a149-ea3dbf0031f1)

pertanyaan yang perlu dijawab yaitu:
- Siapa nama attacker?<br>
jawaban:Nakhimov<br>
![image](https://github.com/user-attachments/assets/49a15f1d-c5a8-48dc-9d93-68298438de6f)<br>

- Apa email yang digunakan untuk login?<br>
jawaban: jarkomsupport()@gmail.com<br>

- Apa password yang digunakan untuk login?
jawaban: j4rk0mg4c0rbg<br>
![Screenshot 2024-09-22 082644](https://github.com/user-attachments/assets/5f47d36c-a843-4f84-891d-d3a55242e1ca)

### 5. Pegawai Negeri sebelah
![Pegawai Negeri Sebelah](https://github.com/user-attachments/assets/fe13cde0-feda-400c-b6e3-a7b6e7a55e44)<br>

jawaban dari soal ini dapat ditemukan pada stream ke 1 paket TCP, yang dimana pada stream paket tersebut berisi semua jawaban yang dibutuhkan untuk dijawab agar bisa mendapat flag

pertanyaan yang perlu dijawab agar mendapat flag:<br>
- Siapa yang memiliki password nNnM%coQuF?<br>
jawaban: Vero Tampubolon<br>
![Screenshot 2024-09-22 083331](https://github.com/user-attachments/assets/53ed99f0-2ffe-4e77-ac0b-7567f0de5cdc)<br>

- Apa jabatan dari Taufan Kuswandari?<br>
jawaban: Analis Kebijakan<br>
![Screenshot 2024-09-22 083543](https://github.com/user-attachments/assets/f60c0bb3-0c43-4232-adb7-92c2210d3ea2)<br>

- Siapa yang paling awal di list?<br>
jawaban: Cici Mustofa<br>

- Apa password paling akhir dari list?<br>
jawaban: RyxaJPv^yF<br>

### 6. EZ
![EZ](https://github.com/user-attachments/assets/d6007205-3249-4314-94b6-0df18e82ccc2)

### 7. Gajah Terbang (Server Recon)
![Screenshot 2024-09-19 013551](https://github.com/user-attachments/assets/5a236189-4132-46cd-9ac0-a1472094633b)

## penutup
Sekian pengerjaan dari kami Terima Kasih
