# Didik Skills

**AI yang bertanya dulu sebelum menjawab.**

Kebanyakan AI langsung menyodorkan daftar panjang. Skill Didik membuat AI Anda bekerja seperti rekan yang baik: mengenali situasi Anda lebih dulu, memandu satu langkah per giliran, jujur soal batasnya, dan berakhir pada lembar satu halaman yang bisa langsung Anda bawa ke rapat.

Gratis, terbuka, dan bisa dicoba dalam dua menit di Claude, ChatGPT, dan AI lain berstandar Agent Skills. Dibuat oleh [Didik & Co](https://www.didik.co), dari pengalaman melatih eksekutif dan tim.

## Coba sekarang

1. Pasang `didik-core` dan satu skill yang Anda butuhkan (cara pasang di bawah).
2. Tulis salah satu kalimat ini ke AI Anda:
   - "Bantu saya menyusun KPI untuk tim saya."
   - "Saya perlu menyiapkan pitch tiga menit untuk atasan."
   - "Saya ingin mencoba AI di tim saya, mulai dari mana?"
3. Perhatikan bedanya: AI tidak langsung memberi daftar, tetapi menanyakan situasi Anda, lalu memandu Anda sampai hasil yang bisa dipakai.

## Apa bedanya dengan meminta AI biasa?

AI biasa cenderung langsung menjawab dan menyodorkan daftar panjang. Skill Didik mengubah caranya bekerja:

- **Bertanya dulu.** AI mengenali situasi Anda sebelum memberi arahan, satu pertanyaan per giliran.
- **Berhenti di batas.** AI tidak mengarang angka atau patokan industri tanpa sumber, dan tidak memutuskan hal yang berdampak pada nasib orang.
- **Menghasilkan sesuatu yang dipakai.** Setiap skill berakhir pada lembar satu halaman.
- **Jujur soal empati.** AI tidak merasakan apa pun. Skill hanya meniru cara bertanya yang sabar dan tidak menghakimi, dan empati tidak berarti setuju.

## Isi

| Kebutuhan | Skill |
| --- | --- |
| Pintu masuk dan peta semua skill | `didik-core` |
| Strategi, arah, OKR, eksekusi | `didik-essential-strategic-leadership` |
| Masalah, data, cerita temuan | `didik-essential-analytics-storytelling` |
| Ide baru, pelanggan, model bisnis | `didik-essential-innovation-bmc` |
| Transformasi digital, cara kerja tangkas | `didik-essential-digital-agility` |
| Memimpin sesuai kesiapan, coaching | `didik-essential-situational-coaching` |
| Pesan, pitch, percakapan sulit | `didik-essential-communication-influence` |
| Model keuangan untuk keputusan | `didik-essential-financial-modelling` |
| AI untuk pemimpin | `didik-essential-ai-leaders` |
| Keberlanjutan, transisi energi | `didik-essential-sustainability-energy` |
| KPI, target, kinerja bisnis | `didik-essential-bpm` |
| Pengukuran, pelaporan, verifikasi data | `didik-essential-mrv-qa` |

Kerangka DIDIK: Diagnosis, Inovasi, Digital, Investasi, Kepemimpinan.

Tidak yakin mulai dari mana? Pasang `didik-core` dan ceritakan kebutuhan Anda; AI akan mengarahkan ke skill yang cocok.

## Cara memakai

Salin folder skill yang Anda butuhkan dari `skills/`. Setiap skill berdiri sendiri.

| Platform | Cara |
| --- | --- |
| Claude (claude.ai dan aplikasi) | Kompres satu folder skill menjadi `.zip`, lalu unggah lewat Settings, Capabilities, Skills. |
| Claude Code | Taruh folder di `~/.claude/skills/` (semua proyek) atau `.claude/skills/` (satu proyek). |
| Codex dan AI lain berstandar Agent Skills | Taruh di `~/.agents/skills/` atau `~/.codex/skills/`; jalur persis berbeda tiap alat, cek dokumentasi alat Anda. |
| ChatGPT | Unggah lewat menu Skills bila akun Anda memilikinya. Fitur ini baru dan menunya dapat berubah. |

Dengan perintah `npx skills add Bijikaret/didik-skills`, alat komunitas dapat memasang skill ke banyak AI sekaligus.

Setelah terpasang, tulis kebutuhan Anda secara biasa, misalnya: "Bantu saya menyusun KPI untuk tim saya." AI akan memakai skill yang cocok.

## Contoh singkat

Anda menulis: "Bantu saya bikin KPI untuk tim penjualan, secepatnya." Tanpa skill, AI umumnya langsung memberi daftar sembilan KPI lengkap dengan bobot dan target. Dengan `didik-essential-bpm`, AI menanyakan dulu siapa yang memakai angkanya dan keputusan apa yang ingin dibantu, lalu memandu Anda sampai lembar satu halaman.

## Batas

- Skill ini alat bantu berpikir, bukan nasihat keuangan, hukum, atau SDM.
- Jawaban AI bisa keliru. Periksa dengan orang yang paham konteksnya.
- Jangan memasukkan data rahasia atau data pribadi ke AI.
- Level essential berhenti di satu putaran praktik sederhana.

## Lebih dalam bersama Didik & Co

Versi lanjutan, alat kerja, dan pendampingan oleh manusia tersedia lewat Didik & Co. Skill tidak menggantikan pendampingan. Hubungi didik@didik.co atau kunjungi www.didik.co.

## Lisensi dan kontribusi

Isi repositori ini berlisensi [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Anda boleh memakai dan mengubahnya, termasuk untuk komersial, dengan mencantumkan "Didik & Co, www.didik.co". Lisensi hanya berlaku untuk isi repositori ini, bukan untuk materi Didik & Co lain.

Saran dan temuan kesalahan dapat dikirim lewat Issues atau ke didik@didik.co.

Versi: 0.1.0
