# 🇵🇭 Bantay-Kalsada API

> **Empowering Filipino citizens to monitor public works, upload geo-tagged defect reports, and hold local government units accountable.**

---

## 📌 Project Overview

**Bantay-Kalsada** is an open-source civic technology platform designed to track public infrastructure projects across the Philippines. By tapping into open government data (e.g., PhilGEPS, DPWH) and crowding-sourcing citizen reports, the API calculates dynamic **Corruption Risk Scores** for LGUs without requiring expensive infrastructure.

### Key Features
- **Citizen Report Ingestion:** Submit geo-tagged report logs with multi-photo uploads.
- **Geofenced Verification:** Ensures uploaded photos correspond to actual project coordinates.
- **Automated Anomaly Detection:** Flags projects with high citizen defect reports or delays.
- **Zero-Budget Stack:** Built to run on free-tier platforms (Render/Fly.io + Supabase + Redis).

---

## 🛠️ Tech Stack

- **Framework:** Laravel 11 (PHP 8.2+)
- **Database:** PostgreSQL + PostGIS (Hosted on Supabase)
- **Media Storage:** Supabase Storage / Cloudinary
- **Authentication:** Laravel Sanctum
- **Queue & Caching:** Redis / Database Driver

---

## 🚀 Quickstart (Local Setup)

### Prerequisites
- PHP 8.2+
- Composer
- PostgreSQL / SQLite

### Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/bantay-kalsada-api.git](https://github.com/your-username/bantay-kalsada-api.git)
   cd bantay-kalsada-api
