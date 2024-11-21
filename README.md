# PERTEMUAN 9

# PENJELASAN

1. Tujuan Program
Program ini dibuat untuk:

Memasukkan data mahasiswa secara dinamis.
Menghitung nilai akhir mahasiswa berdasarkan bobot tertentu:
Tugas: 30%
UTS: 35%
UAS: 35%.
Menampilkan semua data mahasiswa dalam format tabel yang rapi.
2. Cara Kerja Program
a. Inisialisasi

Program dimulai dengan mendeklarasikan list kosong bernama data_mahasiswa.
Tujuan: Menyimpan data setiap mahasiswa dalam bentuk dictionary (key-value).
b. Input Data

Pengguna diminta untuk memasukkan data berikut:
Nama mahasiswa.
NIM mahasiswa.
Nilai Tugas.
Nilai UTS.
Nilai UAS.
Program membaca input dan menyimpannya ke dalam variabel.
c. Hitung Nilai Akhir

Nilai akhir dihitung menggunakan rumus:
python
Salin kode
nilai_akhir = (nilai_tugas * 0.3) + (nilai_uts * 0.35) + (nilai_uas * 0.35)
Nilai ini disimpan bersama data lain ke dalam list data_mahasiswa.
d. Tambah Data Lagi

Setelah satu data mahasiswa selesai dimasukkan, program bertanya:
python
Salin kode
tambah_data = input("Tambah data (y/t)? ")
Jika jawaban adalah "y" (ya), program akan kembali meminta input data baru.
Jika jawaban adalah "t" (tidak), program keluar dari perulangan.
e. Tampilkan Data

Setelah semua data selesai dimasukkan, program mencetak tabel berisi:
Nomor urut.
Nama mahasiswa.
NIM.
Nilai Tugas.
Nilai UTS.
Nilai UAS.
Nilai Akhir.
Tabel ditampilkan dalam format rapi menggunakan fungsi format() untuk memastikan kolom sejajar.

3. Output Program
Program menampilkan data mahasiswa dalam format seperti berikut:

yaml
Salin kode
No    Nama            NIM        Tugas      UTS        UAS        Akhir
=================================================================
1     arif            352310870  80.0       90.0       85.0       85.25
2     muklis          352310854  75.0       80.0       95.0       83.75
3     lutfi           352310876  60.0       75.0       65.0       67.00
4     zidan           352310877  55.0       95.0       70.0       74.25
5     zulham          352310875  90.0       85.0       95.0       90.00
Penjelasan tabel:

No: Nomor urut mahasiswa.
Nama: Nama mahasiswa.
NIM: Nomor Induk Mahasiswa.
Tugas: Nilai tugas mahasiswa.
UTS: Nilai ujian tengah semester mahasiswa.
UAS: Nilai ujian akhir semester mahasiswa.
Akhir: Nilai akhir berdasarkan perhitungan bobot.
4. Alur Program
Start: Program dimulai.
Input data mahasiswa: Masukkan data mahasiswa.
Hitung nilai akhir: Menggunakan formula perhitungan.
Tambahkan data lagi?: Jika "ya", ulangi proses; jika "tidak", tampilkan semua data.
Tampilkan data: Cetak tabel.
End: Program selesai.
5. Kelebihan Program
Fleksibel: Dapat menambahkan data sebanyak yang diinginkan.
Interaktif: Bertanya kepada pengguna sebelum berhenti.
Otomatis: Menghitung nilai akhir dan menampilkan dalam format rapi.
Jika ada bagian yang kurang jelas atau memerlukan tambahan, silakan beri tahu!
