# Optimasi Jam Posting Reels @aflahermanto

Skor = komen x3 + save x2 + share x2 + like + reach/100. Jam dalam WIB.

## 2026-10-23 (run 04:56 WIB)
Sumber: Windsor instagram akun 17841406164333353, 60 hari terakhir (data cache, paket TRIAL tidak bisa refresh). Tidak ada field follower online per jam di Windsor, jadi pakai skor engagement per jam posting.

| Waktu posting (WIB) | Tipe | Reach | Like | Komen | Save | Share | Skor |
|---|---|---|---|---|---|---|---|
| Sel 06 Okt 21:57 | Reels | 424 | 12 | 2 | 0 | 0 | 22.2 |
| Kam 08 Okt 14:51 | Reels | 377 | 14 | 2 | 0 | 0 | 23.8 |
| Rab 14 Okt 12:23 | Reels | 202 | 6 | 9 | 0 | 0 | 35.0 |
| Rab 14 Okt 16:11 | Carousel | 176 | 2 | 0 | 1 | 0 | 5.8 |
| Sel 20 Okt 16:22 | Reels | 213 | 10 | 0 | 4 | 1 | 22.1 |
| Rab 21 Okt 20:13 | Reels | 5590 | 147 | 35 | 16 | 23 | 385.9 |
| Rab 21 Okt 22:40 | Reels | 251 | 9 | 0 | 0 | 0 | 11.5 |

Rata-rata per jam: 20:00 = 385.9 | 12:00 = 35.0 | 14:00 = 23.8 | 21:00 = 22.2 | 16:00 = 14.0 (n=2) | 22:00 = 11.5. Belum ada data posting jam 04-05 (jadwal sekarang).

Kesimpulan: belum cukup data buat ubah jadwal. Total 7 postingan, tapi tiap jam cuma 1 sampel (16:00 ada 2). Skor 20:00 datang dari 1 Reels viral bertopik MSCI/pasar modal (topik beda dari konten AI), jadi lebih ke topiknya daripada jamnya. Kalau outlier itu dikeluarkan, 12:00 unggul (karena 9 komen), tapi itu juga cuma 1 postingan.
Keputusan: jadwal TIDAK diubah, tetap CRON_TZ=Asia/Jakarta 55 4 * * * (04:55 WIB). Kandidat yg dipantau: 19:55 dan 11:55. Dievaluasi ulang setelah ada data posting pagi (04:55) dan minimal 2 postingan per jam kandidat.
Riwayat perubahan jadwal: belum ada.
