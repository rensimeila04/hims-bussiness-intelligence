# HIMS Business Intelligence

Repository ini berisi proyek Business Intelligence untuk Hospital Information Management System (HIMS) yang mencakup analisis data, dashboard interaktif, dan ETL processes menggunakan Pentaho Data Integration.

## 📋 Deskripsi Proyek

Proyek ini mengimplementasikan solusi Business Intelligence untuk sistem manajemen rumah sakit, dengan fokus pada analisis layanan medis, pasien, dokter, dan biaya perawatan.

## 👥 Kelompok

| Nama | NIM |
|------|-----|
| Abdullah Shamil Basayev | 2341720166 |
| Keisya Nisrina Aulia | 2341720146 |
| Muhammad Naufal Pratomo | 2341720075 |
| Rensi Meila Yulvinata | 2341720201 |
| Yefta Octavianus Santo | 2341720110 |

## 📄 Dokumentasi

Dokumentasi lengkap proyek dapat dilihat di file berikut: 

**[📖 BI_FINALPROJECT.pdf](./BI_FINALPROJECT.pdf)**

[![Lihat Dokumentasi](https://img.shields.io/badge/Lihat-Dokumentasi%20PDF-blue?style=for-the-badge&logo=adobe-acrobat-reader)](./BI_FINALPROJECT.pdf)

> **Catatan**: Klik link di atas atau unduh file `BI_FINALPROJECT.pdf` untuk melihat dokumentasi lengkap proyek.

## 📊 File Visualisasi

**[Dashboard_HIMS_BI.pbix](./Dashboard_HIMS_BI.pbix)** - File Power BI Dashboard  
**[Dashboard_HIMS_BI. pdf](./Dashboard_HIMS_BI.pdf)** - Preview Dashboard dalam format PDF

## 🗂️ Struktur Repository

```
hims-bussiness-intelligence/
│
├── BI_FINALPROJECT.pdf              # Dokumentasi lengkap proyek
├── Dashboard_HIMS_BI.pbix            # Dashboard Power BI
├── Dashboard_HIMS_BI.pdf             # Dashboard dalam format PDF
├── HIMS_Dataset.sql                  # Dataset SQL
│
├── ETL Transformations (Pentaho):
│   ├── HIMS_dim doctor.ktr           # ETL untuk dimensi dokter
│   ├── HIMS_dim patient category.ktr # ETL untuk kategori pasien
│   ├── HIMS_dim patient.ktr          # ETL untuk dimensi pasien
│   ├── HIMS_dim service.ktr          # ETL untuk dimensi layanan
│   ├── HIMS_dim unit.ktr             # ETL untuk dimensi unit
│   └── HIMS_fact charge. ktr          # ETL untuk fakta biaya
│
└── Data Files:
    ├── vw_charge_enriched.csv        # Data OLAP dalam format CSV
    └── vw_charge_enriched.xls        # Data OLAP dalam format Excel
```
