# Pertemuan 07 Fungsi Python

Nama: Dita Amalia Veronica
NIM: 2225250162
Kelas: 3F

## Tujuan
Menggunakan fungsi, parameter, return value, dan scope untuk membuat program modular.

## Cara Menjalankan
python praktik/utilitas_matematika.py

## Struktur Fungsi
| Fungsi | Parameter | Return |
|---|---|---|
| luas_persegi_panjang | p, l | luas (p * l) |
| luas_segitiga | a, t | luas (0.5 * a * t) |
| jumlah_n | n | jumlah 1 sampai n |
| faktorial | n | n! |
| tampilkan_menu | - | tidak ada (hanya print) |

## Hasil Pengujian
| Operasi | Input | Diharapkan | Aktual | Status |
|---|---|---|---|---|
| Luas persegi panjang | p=8, l=5 | 40 | 40.0 | Lulus |
| Luas segitiga | a=10, t=6 | 30.0 | 30.0 | Lulus |
| Jumlah 1..n | n=10 | 55 | 55 | Lulus |
| Faktorial | n=5 | 120 | 120 | Lulus |
| Faktorial | n=0 | 1 | 1 | Lulus |

## Refleksi
Bagian program yang menjadi jauh lebih sederhana setelah dipisah menjadi fungsi adalah logika perhitungan faktorial dan penjumlahan deret 1 sampai n (jumlah_n).Sebelum menggunakan fungsi, seluruh alur perulangan for, pembacaan input, dan pencetakan hasil harus ditulis menumpuk di dalam blok seleksi if-elif. Hal ini membuat kode program utama menjadi panjang, rumit, dan berisiko salah jika ingin dipakai kembali. Setelah dipisah ke dalam fungsi terpisah (faktorial dan jumlah_n), program utama hanya perlu memanggil nama fungsinya saja. Selain itu, penggunaan return membuat fungsi murni fokus pada proses perhitungan matematika, sehingga pengujian kode menjadi jauh lebih mudah dan struktur program terlihat jauh lebih rapi.