# 📊 Executive Vulnerability Report Viewer

Web-based viewer untuk membaca report hasil scan dalam format **JSON** dan menampilkannya dalam bentuk **dashboard interaktif** + **executive report**.

## ✨ Fitur
- Upload file JSON hasil scan
- Tabel **Scan Summary**
- Card **Vulnerabilities** (severity badge, details, remediation, AI analysis, evidence)
- Dashboard distribusi severity (pie chart + summary cards)
- Export ke **PDF** (multi-page, ada cover page otomatis)
- Tombol **Clear Report** untuk reset input file

## 🚀 Cara Jalankan (Docker Compose)

1. Clone repository ini:
   ```bash
   git clone https://github.com/<username>/vuln-report-viewer.git
   cd vuln-report-viewer
   ```

2. Jalankan container:
   ```bash
   docker compose up -d
   ```

3. Akses di browser:
   ```
   http://localhost:8092
   ```

4. Upload file JSON hasil scan → report otomatis tampil.

---

## 📦 Struktur Project
```
vuln-report-viewer/
│── docker-compose.yml
│── nginx.conf
│── html/
│   ├── index.html
│   ├── style.css
```

---

## 👨‍💻 Developer
Dibuat untuk kebutuhan **executive security reporting** dengan tampilan profesional dan mudah dipakai.
