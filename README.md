# Perbandingan Analisis Algoritma Load Balancing antara Weighted Round Robin (WRR) dengan Per Connection Classifier (PCC) Menggunakan HAProxy pada Aplikasi Moodle

## Skripsi

**Universitas Negeri Makassar**

### Penulis

**Daffa Shifa Fachrezzy**  
NIM: 200210502054

---

## Deskripsi

Repository ini merupakan **lampiran digital** dari penelitian skripsi yang berjudul:

> **Perbandingan Analisis Algoritma Load Balancing antara Weighted Round Robin (WRR) dengan Per Connection Classifier (PCC) Menggunakan HAProxy pada Aplikasi Moodle.**

Repository ini berisi file konfigurasi, dokumentasi implementasi, serta hasil pengujian yang digunakan selama proses penelitian. Seluruh berkas yang tersedia bertujuan untuk mendukung transparansi penelitian serta memudahkan proses verifikasi dan replikasi implementasi yang dilakukan.

---

## Struktur Repository

```
WRR/
├── haproxy.cfg

PCC/
├── haproxy.cfg

DNS/
├── named.conf.default-zones
├── db.loadbalancing.ac.id
└── db.54.168.192

MariaDB/
├── 50-server.cnf

Moodle/
├── config.php

Pengujian/
├── ApacheBenchmark/
├── Monitoring/
└── HAProxyStats/

Dokumentasi/
├── Topologi.png
├── VirtualBox_Manager.png
├── Moodle_Login.png
└── Moodle_Dashboard.png
```

---

## Lingkungan Implementasi

- Sistem Operasi : Ubuntu Server 22.04 LTS
- Load Balancer : HAProxy 2.4
- Web Server : Apache2
- Database : MariaDB 10.6
- Aplikasi : Moodle 4.3
- Virtualisasi : Oracle VM VirtualBox

---

## Tujuan Repository

Repository ini dibuat sebagai dokumentasi pendukung penelitian yang memuat:

- Konfigurasi implementasi algoritma **Weighted Round Robin (WRR)**.
- Konfigurasi implementasi algoritma **Per Connection Classifier (PCC)**.
- Konfigurasi layanan pendukung (DNS, MariaDB, dan Moodle).
- Dokumentasi implementasi sistem.
- Hasil pengujian menggunakan Apache Benchmark, monitoring server, dan HAProxy Statistics.

---

## Lisensi

Repository ini disediakan sebagai lampiran akademik untuk mendukung penelitian skripsi di Universitas Negeri Makassar.
