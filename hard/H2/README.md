# HARD — Soal 03: Kuis dengan Skor

## Instruksi

Buat mini kuis dengan **3 pertanyaan** (tampil satu per satu).  
Setiap pertanyaan punya dua pilihan jawaban.

- Jawaban benar → skor bertambah 1
- Setelah 3 pertanyaan selesai → tampilkan **"Kuis selesai! Skormu: X/3"**

**Data Kuis:**

1. "2 + 2 = ?" → Benar: "4", Salah: "5"
2. "Ibu kota Jepang?" → Benar: "Tokyo", Salah: "Osaka"
3. "Warna langit siang hari?" → Benar: "Biru", Salah: "Merah"

---

## Aturan

- Gunakan `getElementById`
- Gunakan `addEventListener`
- Gunakan `innerText` dan `.disabled`
- **Jangan** ubah apapun di bagian HTML

---

## Output yang Diharapkan

**Saat pertanyaan 1 aktif:**

```
2 + 2 = ?
[ 4 ]  [ 5 ]
Skor: 0
```

**Setelah semua selesai:**

```
Kuis selesai! Skormu: 2/3
```

---
