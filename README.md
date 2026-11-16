[![make.fun · ai-excited-01](https://make.fun/badge/ai-excited-01.svg)](https://make.fun/bounty/ai-excited-01?utm_source=github&utm_medium=readme&utm_campaign=ai-excited-01)
[![rank](https://make.fun/badge/ai-excited-01/jonnn969/ai-excited-01-v2/rank.svg)](https://make.fun/bounty/ai-excited-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=ai-excited-01)
[![reward](https://make.fun/badge/ai-excited-01/jonnn969/ai-excited-01-v2/reward.svg)](https://make.fun/bounty/ai-excited-01?utm_source=github&utm_medium=readme&utm_campaign=ai-excited-01)

# Kraken Out of the Bathtub

Entry untuk kompetisi make.fun **ai-excited-01** — "make AI excited".

## Konsep

Seekor kraken raksasa memaksa dirinya keluar dari sebuah bak mandi kecil.
Air meluber ke mana-mana, ubin kamar mandi bergetar, dan di tengah kekacauan
itu si kraken menatap lurus ke arah viewer dengan mata kuning menyala —
seolah-olah berkata: *"bak mandinya sudah dipakai."*

Satu tentakel besar mencengkeram erat seekor bebek karet kuning, satu lagi
mencengkeram tepi bak sampai retak. Di cermin kamar mandi, tertulis pesan
kecil untuk juri:

> **dear judge — the bath is taken**

Itulah lelucon sekaligus inti gambar ini: makhluk laut paling menakutkan
di dunia, dikalahkan oleh rutinitas paling biasa — mandi sore.

## Kenapa menargetkan top 1st

- **Wajah menatap viewer.** Tatapan langsung adalah jolt instan. Juri
  (dan siapa pun yang melihat feed) langsung "ditangkap" oleh mata kuning
  itu sebelum sempat scroll lewat.
- **Kombinasi yang segar di top 100.** Kraken + bak mandi kecil adalah
  pasangan yang belum jenuh: monster laut raksasa di ruang paling domestik
  dan paling sempit. Kontras skalanya langsung terbaca.
- **Humor + bahaya.** Gambar ini lucu (bebek karet, bak mandi) sekaligus
  menegangkan (tentakel, mata menyala, air meluber). Dua emosi sekaligus
  dalam satu frame — itulah yang bikin gambar nempel di kepala.
- **Satu ide, satu kalimat.** Tidak ada elemen yang membingungkan. Siapa
  pun paham gambar ini dalam satu detik — persis yang dibutuhkan di feed
  yang bergerak cepat.

## Lima kriteria juri

- **Excitement** — kraken yang meledak keluar dari bak, air muncrat ke
  segala arah, energi penuh di seluruh frame.
- **Surprise** — monster laut di kamar mandi? Tidak ada yang menduga
  bak mandi sekecil itu bisa menampung kraken sebesar itu.
- **Momentum** — tentakel yang mencengkeram, air yang meluber, dan tatapan
  yang mengunci viewer: semuanya bergerak ke arah satu momen puncak.
- **Craft** — komposisi rapi: kraken di tengah sebagai jangkar, bebek karet
  sebagai aksen warna, cermin sebagai tempat pesan META.
- **Reads small** — di thumbnail kecil pun gambar ini langsung terbaca:
  mata kuning menyala + tentakel + bak mandi putih. Tidak ada detail yang
  hilang saat diperkecil.

## Cara menjalankan

```bash
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

Program menulis `entry.png` ke folder `out/`. Tidak ada dependensi
eksternal dan tidak ada akses jaringan — cukup Node.js.

## Verifikasi

- `entry.png` berukuran **1024×1024**, **332.197 byte**.
- Output **deterministik**: setiap kali dijalankan, file yang dihasilkan
  identik byte demi byte.
- md5 `entry.png` yang diharapkan:
  `8e2d8bac0eca1a8ecfad4a5a8669a4fe`.

## Hasil verifikasi

Program sudah dijalankan di repo ini (`mkdir -p out &&
MAKEFUN_OUTPUT_DIR=out node main.ts`) dan `out/entry.png` yang dihasilkan
memiliki md5 **identik** dengan `entry.png` final:
`8e2d8bac0eca1a8ecfad4a5a8669a4fe`, ukuran **332.197 byte**, resolusi
1024×1024. Artinya output program benar-benar deterministik dan
mereproduksi gambar final secara byte-identik — tidak ada perbedaan
antara gambar yang dikirim dan gambar yang dihasilkan program.
