# PTMIPDocsApp
# 📑 PTMIPDocsApp

![Electron](https://img.shields.io/badge/Electron-25.0-blue?logo=electron&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-18-green?logo=node.js&logoColor=white)
![Status](https://img.shields.io/badge/Status-In%20Development-orange)

**PTMIPDocsApp** adalah aplikasi desktop berbasis **Electron** untuk mendukung pengelolaan dokumen dan laporan keuangan internal perusahaan.  
Proyek ini dibangun untuk PT MIP sekaligus sebagai portofolio profesional di bidang **Software Engineering**.

Aplikasi berjalan **offline & portabel**, dapat dijalankan langsung dari laptop maupun flashdisk.

---

## 🎯 Tujuan
- 📂 Mempermudah pembuatan dokumen perusahaan (Invoice, Letter of Indemnity, Surat Jalan, Laporan Keuangan).
- 📊 Menyediakan perhitungan otomatis (pemasukan/pengeluaran, kurs, total harga).
- 📤 Mendukung ekspor ke **PDF, Word, Excel** (portrait/landscape, kop surat opsional).
- 🌍 Mendukung **multibahasa** (Indonesia & Inggris).
- 📝 Mendukung **Draft & History** (edit sebelum final, arsip setelah final).
- 💾 Aplikasi **offline & portable**.

---

## 🚀 Fitur Utama
- **Modul Dokumen**: Invoice, LOI, Surat Jalan, Laporan Keuangan.
- **Export Multi-Format**: PDF, Word, Excel.
- **Custom Layout**: portrait/landscape, dengan/ tanpa kop surat.
- **Draft & History**: versi draft (editable) dan final (arsip).
- **Multibahasa**: ID / EN.
- **Finance Module**: pencatatan & analisis sederhana.

### 🧭 Planned Upgrade
- Auto-numbering per jenis dokumen.
- Upload record & arsip digital + dashboard ringkasan.
- Integrasi data dokumen ↔ laporan keuangan.
- (Opsional) User login & role management.

---

## 📂 Struktur Project (ringkas)
-PTMIPDocsApp/
-Assets(Foto)/ → Aset gambar/logo
-Dokumen_Moduls/ → HTML, CSS, JS per dokumen (Invoice, LOI, SI, Finance)
-Exports_Msword&Pdf/ → Handler ekspor (PDF, Word, Excel)
-Modules_Common/ → Utility bersama (FileHandler, CalcHandler, ExportHandler)
-main.js → Entry point Electron
-package.json → Konfigurasi & script

---

## 📊 Roadmap / Progress
- [x] Setup project structure
- [ ] Dashboard (navbar + beranda)
- [ ] Document modules (Invoice, LOI, SI)
- [ ] Export to PDF/Word/Excel
- [ ] Upload & record system
- [ ] Finance module (Arus Kas, Laba Rugi, Neraca)
- [ ] Upgrade: auto-numbering, multi language

---

## 🔧 Cara Menjalankan
1) Clone repo  
```bash
git clone https://github.com/<USERNAME>/PTMIPDocsApp.git
cd PTMIPDocsApp

2) Install dependency
```bash
npm install

3) Jalankan aplikasi
```bash
npm start

!Catatan: Pastikan node & npm sudah terpasang. Script "start": "electron ." ada di package.json.

## License
This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.



























