# Rules

## Timeline

| Event              | Tanggal                          |
|--------------------|----------------------------------|
| Waktu pengerjaan   | 1 s.d. 30 Juli 2026              |
| Submission dibuka  | 8 Juli 2026                      |
| Batas akhir submission | 30 Juli 2026 pukul 16:00 WIB |

## Mekanisme Submission

- File CSV dengan nama `submission_NamaTim.csv`
- Dua kolom: `id` dan `predicted`
- Label numerik: 0 = Recyclable, 1 = Electronic, 2 = Organic
- Urutan data **tidak boleh diubah**
- **Maksimal 3 kali submission** -- nilai tertinggi digunakan sebagai nilai akhir
- Tidak ada perpanjangan waktu

## Batasan (Constraints)

1. Model dibangun hanya menggunakan Data Latih dari panitia
2. Hanya informasi visual (image) yang boleh digunakan sebagai fitur
3. Data augmentation diperbolehkan, asal tidak memanfaatkan Data Uji
4. Data Uji hanya untuk prediksi akhir, dilarang untuk training/validasi/selection/tuning
5. Boleh menggunakan library dan framework open source
6. Model pre-trained publik diperbolehkan untuk transfer learning, wajib didokumentasikan
7. **Dilarang** menambahkan data citra berlabel dari sumber lain
8. Format submission harus sesuai ketentuan panitia
9. Seluruh pengembangan harus mandiri, tidak memanfaatkan label Data Uji

## Aturan Tambahan

- Maksimal **3 tim per perguruan tinggi** yang lolos
- Jika nilai metrik sama, tim yang mengunggah lebih awal mendapat peringkat lebih tinggi
- Tim terpilih wajib membuktikan pekerjaannya **tidak dikerjakan manual** (via video)
- **22 tim** terpilih lolos ke semifinal

## Diskualifikasi / Sanksi

Panitia berhak mendiskualifikasi peserta jika terbukti:

- Melanggar ketentuan kompetisi (format tidak sesuai, data/informasi tidak diizinkan, metode bertentangan aturan)
- Melanggar integritas akademik (plagiarisme, manipulasi hasil, pemalsuan informasi)
- Melakukan kecurangan (penggunaan label Data Uji, rekayasa hasil prediksi, kolusi)
- Melanggar etika kompetisi (mengganggu jalannya kompetisi, informasi menyesatkan, konten tidak pantas)
- Tidak dapat menunjukkan proses pengembangan model saat diminta verifikasi (kode program, dokumentasi)

Keputusan panitia bersifat final dan tidak dapat diganggu gugat.
