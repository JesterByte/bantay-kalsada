# 🇵🇭 Bantay-Kalsada API

> **Empowering citizens to monitor, report, and flag public infrastructure projects in the Philippines.**

Bantay-Kalsada is a zero-budget, open-source RESTful API built with **Laravel 13** and **PostgreSQL**. It allows citizens to log geotagged reports with photo evidence on ongoing or completed road and public works projects, automatically calculating LGU-level infrastructure risk scores.

---

## 🚀 Features

- **Public Works Tracking:** Ingests official project data (DPWH / PhilGEPS / LGU allocations).
- **Citizen Reporting:** Ingests geotagged photos, issue classifications (potholes, delays, abandoned sites, substandard materials), and descriptions.
- **Risk Score Analytics:** Computes corruption risk and discrepancy scores per barangay, city, and region.
- **Zero-Budget Architecture:** Designed to run entirely on free-tier services (Render, Fly.io, Supabase, Cloudinary).

---

## 🛠 Tech Stack

- **Framework:** Laravel 13 (PHP 8.3+)
- **Database:** PostgreSQL (with PostGIS spatial extensions)
- **Authentication:** Laravel Sanctum (Optional / Anonymous reporting enabled)
- **Storage:** Cloudinary / Supabase Storage (Free Tiers)
- **Testing:** Pest PHP / PHPUnit

---

## ⚡ Quick Start (Local Setup)

### Prerequisites

- PHP 8.3+
- Composer 2.7+
- PostgreSQL 15+

### Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/bantay-kalsada-api.git](https://github.com/your-username/bantay-kalsada-api.git)
   cd bantay-kalsada-api
