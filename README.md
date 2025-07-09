---

# 📘 API Kalender Akademik Jawa Barat 2025/2026

API ini menyajikan **kalender akademik Jawa Barat tahun 2025/2026** secara lengkap, termasuk **tanggal merah**, hari libur nasional, dan kegiatan sekolah.
Cocok untuk diintegrasikan pada website sekolah, aplikasi pendidikan, dan dashboard akademik.

---

## 🔗 Endpoint Utama

```
https://api.fazriansyah.eu.org/v1/kaldik
```

---

## 🧩 Parameter Query

| Parameter | Tipe  | Default    | Keterangan                                  |
| --------- | ----- | ---------- | ------------------------------------------- |
| `smt`     | angka | *otomatis* | Pilih semester: `1` (ganjil), `2` (genap)   |
| `dark`    | 0 / 1 | `0`        | Mode tampilan: `1` = dark mode, `0` = light |
| `bulan`   | 1–12  | *semua*    | Tampilkan hanya bulan tertentu (opsional)   |

---

## ✅ Contoh Penggunaan

### 📅 Kalender Semester Genap (mode gelap)

```
https://api.fazriansyah.eu.org/v1/kaldik?smt=2&dark=1
```

### 📅 Kalender Semester Ganjil (mode terang)

```
https://api.fazriansyah.eu.org/v1/kaldik?smt=1&dark=0
```

---

## 🌐 Embed ke Website (Iframe)

```html
<iframe 
  src="https://api.fazriansyah.eu.org/v1/kaldik?smt=2&dark=1" 
  width="100%" 
  height="800" 
  frameborder="0" 
  style="border:1px solid #ccc; border-radius:8px;">
</iframe>
```

---

## 📦 Output Format

Tampilan langsung berupa halaman HTML interaktif (client-side rendered).
Jika membutuhkan versi JSON mentah untuk integrasi data, silakan hubungi kami.

---

## 🏷️ Tag Terkait

`kaldik jabar` · `kalender 2025 lengkap dengan tanggal merah` · `kalender akademik jawa barat 2025`

---
