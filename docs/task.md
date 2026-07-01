# Task

## Klasifikasi Citra Limbah Padat

Peserta ditantang mengembangkan model **klasifikasi citra** yang mampu mengidentifikasi objek sampah ke dalam **3 kategori**:

| Kode | Kelas       | Deskripsi |
|------|-------------|-----------|
| 0    | Recyclable  | Sampah non-elektronik yang dapat didaur ulang (botol plastik, kaleng, kertas, kardus, kaca) |
| 1    | Electronic  | Limbah elektronik/e-waste (telepon genggam, laptop, keyboard, mouse, charger, kabel, dll) |
| 2    | Organic     | Bahan hayati mudah terurai (daun, buah, sayuran, sisa makanan, ranting, bagian tumbuhan) |

## Metrik Evaluasi

**Macro-averaged F1-Score** -- rata-rata aritmetika dari nilai F1-Score yang dihitung secara terpisah untuk setiap kelas.

Peringkat ditentukan berdasarkan Macro-averaged F1-Score pada Data Uji. Semakin tinggi nilainya, semakin baik kemampuan model mengidentifikasi seluruh kategori secara konsisten dan seimbang.

## Output Submission

File CSV dengan dua kolom:
- `id`
- `predicted`

Nama file: `submission_NamaTim.csv`

Urutan data harus sesuai dengan `submission.csv` dari panitia.
