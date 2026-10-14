# Audit Bank Soal Statistika

## Ringkasan perubahan

- Bank awal: **1034 soal**.
- Menghapus **334 soal Benar/Salah** agar latihan tidak terlalu mudah ditebak.
- Menghapus soal pilihan ganda yang berulang/terlalu mirip secara isi, terutama pada konsep tujuan statistika, siklus pemanfaatan data, sampling, pengacakan, pengendalian lingkungan, RAL, serta percobaan vs survei.
- Memperbaiki salah ketik yang terdeteksi, termasuk “tuhan utama” → “tujuan utama”, “Deketahui” → “Diketahui”, “presisis” → “presisi”, dan beberapa bentuk ejaan lain.
- Bank setelah penyaringan: **649 soal pilihan ganda**.

## Sebaran soal menurut enam materi

| Materi | Jumlah soal |
|---|---:|
| 1. Konsep Dasar Statistika | 87 |
| 2. Penyajian Data | 140 |
| 3. Peringkasan Data | 126 |
| 4. Eksplorasi Data | 96 |
| 5. Metode Survei | 118 |
| 6. Perancangan Percobaan | 82 |

Semua soal tersisa terpetakan ke salah satu dari enam materi melalui sumber kuliah atau topiknya.

## Pemeriksaan otomatis yang lulus

- JSON dapat diparse.
- Setiap soal memiliki tepat 4 opsi.
- Indeks kunci jawaban berada dalam rentang opsi.
- Kolom soal, opsi, penjelasan, topik, sumber, dan ID tersedia.
- Tidak ditemukan teks soal yang duplikat setelah normalisasi.
- Tidak ada soal dua opsi yang tersisa.

## Batas audit

Pemeriksaan struktur, duplikasi redaksi, tingkat kemudahan dari format Benar/Salah, dan pemetaan topik telah dilakukan pada seluruh bank. Pemeriksaan otomatis **tidak membuktikan bahwa setiap kunci jawaban secara substantif benar**; verifikasi isi setiap kunci terhadap materi kuliah perlu diperlakukan sebagai pemeriksaan terpisah, bukan dianggap lulus hanya karena indeks jawabannya valid.
