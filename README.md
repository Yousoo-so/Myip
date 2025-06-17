# 🛡️ MyIp – Sistem Keamanan Bot WhatsApp HenryAi

**IpUsrHenry.json** adalah file database berformat **JSON** yang digunakan sebagai sistem keamanan internal untuk bot WhatsApp **Will Graham** (buatan Yousoo). File ini menyimpan data validasi berupa **IP server** agar hanya perangkat yang sah yang dapat menjalankan bot ini.

---

## 🔐 Fungsi Keamanan

Bot hanya akan berjalan jika:

- IP server saat ini sesuai dengan IP yang tersimpan.

Jika tidak sesuai, bot akan **otomatis dihentikan** untuk mencegah penyalahgunaan.

---

## 🧾 Format YosoNumber.json

```json
{
  "ip": [
    "123.45.678.90"
  ]
}