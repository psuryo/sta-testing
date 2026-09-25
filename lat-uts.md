## BAGIAN A — SOAL TEORI

---

**SOAL 1** — Teori | CPMK001 | Bobot: 15 poin

Jelaskan mengapa pada **V-Model**, rancangan test case untuk setiap level testing (Unit, Integration, System, Acceptance) disusun **bersamaan** dengan tahap development pasangannya, bukan setelah seluruh development selesai. Jelaskan pula risiko yang mungkin timbul jika prinsip ini tidak diikuti.

---

**SOAL 2** — Teori | CPMK001 | Bobot: 15 poin

Jelaskan konsep **Decision Table Testing** dan kapan teknik ini lebih tepat digunakan dibandingkan Equivalence Partitioning dan Boundary Value Analysis. Berikan satu contoh singkat kasus yang cocok diuji dengan Decision Table.

---

**SOAL 3** — Teori | CPMK002 | Bobot: 20 poin

Jelaskan konsep **Basis Path Testing** dan mengapa pendekatan ini lebih praktis digunakan dibandingkan menguji seluruh kemungkinan jalur eksekusi secara harfiah (all-path coverage). Jelaskan pula hubungan antara **Cyclomatic Complexity** dengan jumlah minimum test case yang dibutuhkan untuk mencapai basis path coverage.

---

## BAGIAN B — SOAL STUDI KASUS

---

**SOAL 4** — Studi Kasus | CPMK002 | Bobot: 25 poin

Sebuah aplikasi mengharuskan pengguna membuat **password** dengan aturan validasi: panjang password harus **8 sampai 20 karakter** (inklusif). Berdasarkan aturan tersebut:

a. Tentukan seluruh partisi menggunakan **Equivalence Partitioning** (EP), lengkap dengan status valid/invalid dan satu nilai wakil untuk masing-masing partisi. (8 poin)

b. Tentukan titik-titik uji menggunakan **Boundary Value Analysis** (BVA) untuk kedua batas (minimum dan maksimum). (9 poin)

c. Susun tabel test case gabungan EP + BVA, lengkap dengan nilai input (panjang karakter) dan hasil yang diharapkan (diterima/ditolak) untuk setiap test case. (8 poin)

---

**SOAL 5** — Studi Kasus | CPMK002 | Bobot: 25 poin

Perhatikan potongan kode berikut yang menghitung bonus poin member suatu aplikasi:

```
function hitungBonusPoin(totalBelanja, isUlangTahun):
    bonus = 0

    if (totalBelanja > 200000):
        bonus = 50

    if (isUlangTahun):
        bonus = bonus + 100

    return bonus
```

Berdasarkan kode di atas, kerjakan:

a. Gambarkan **Control Flow Graph** (CFG) dari kode tersebut, lengkap dengan penomoran node. (6 poin)

b. Hitung **Cyclomatic Complexity** menggunakan kedua rumus (V = E − N + 2 dan V = Decision Point + 1), dan tunjukkan bahwa hasil keduanya sama. (7 poin)

c. Rancang test case minimum untuk mencapai **100% Statement Coverage**. (4 poin)

d. Rancang test case minimum untuk mencapai **100% Branch Coverage**. (4 poin)

e. Rancang **basis path test case** sejumlah Cyclomatic Complexity yang telah dihitung pada poin (b), lengkap dengan nilai input dan jalur (path) yang dilalui. (4 poin)

---

*Mata Kuliah Software Testing · 3 SKS | Dosen Pengampu: Philipus Suryo Subandoro | Latihan UTS — Sesi 1–7*
