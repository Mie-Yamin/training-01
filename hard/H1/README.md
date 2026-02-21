# HARD — Soal 1: Mini Mesin ATM

## Instruksi

Buat simulasi ATM sederhana dengan saldo awal **Rp 500.000**.  
Ada input nominal dan tiga tombol: **"Tarik Tunai"**, **"Setor"**, dan **"Cek Saldo"**.

- **Cek Saldo** → tampilkan **"Saldo kamu: Rp [saldo]"**
- **Setor** → tambahkan nominal ke saldo, tampilkan **"Setor berhasil. Saldo: Rp [saldo]"**
- **Tarik Tunai** → kurangi saldo. Jika saldo kurang → tampilkan **"Saldo tidak cukup!"**
- Nominal tidak boleh 0 atau kosong → tampilkan **"Masukkan nominal yang valid!"**

---

## Aturan

- Gunakan `getElementById`
- Gunakan `addEventListener` untuk tiap tombol
- Gunakan `.value` dan `Number()`
- Gunakan `innerText`
- **Jangan** ubah apapun di bagian HTML

---

## Output yang Diharapkan

**Cek Saldo (awal):**
```
Saldo kamu: Rp 500000
```

**Tarik 200000:**
```
Penarikan berhasil. Saldo: Rp 300000
```

**Tarik 400000 (saldo kurang):**
```
Saldo tidak cukup!
```

---
