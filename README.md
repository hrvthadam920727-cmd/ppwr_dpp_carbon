# CompliPack - EU Compliance Automation Platform

**Professional PPWR & DPP compliance automation for EU e-commerce businesses**

🎯 Automate EU PPWR Article 24 packaging compliance and generate DPP-ready documentation. Reduce risk of €10K-500K non-compliance penalties.

---

## 🚀 Features

### ✅ PPWR Compliance (Article 24)
- Automatic void space calculation (<40% threshold)
- Smart box recommendations (8 standard EU sizes)
- Real-time compliance checking
- Cost optimization analysis

### 📄 Digital Product Passport (DPP)
- DPP-ready structured documentation
- Material composition tracking
- Carbon footprint estimates
- Recyclability scoring (A-E grades)

### 📊 EPR/MOHU Reporting
- Country-specific reports (HU/MOHU, DE/FR/AT/EPR)
- Quarterly aggregation
- Material categorization

### 🔌 Integrations
- Shopify webhook (automatic order processing)
- CSV bulk import (up to 1,000 products)
- Universal API

---

## 📦 Quick Start

```bash
npm install
npm run dev
```

See full documentation in this README.

---

## 🛠️ Tech Stack

- **Frontend:** Vite + React 18 + TypeScript + Tailwind + Shadcn/ui
- **Backend:** Supabase + Prisma + PostgreSQL
- **Compliance:** PPWR/DPP engines + EPR reporting
- **PDF/QR:** @react-pdf/renderer + qrcode

---

## 📂 Project Structure

```
complipack/
├── app/api/              # API endpoints
├── src/
│   ├── compliance/       # Core engines (PPWR, DPP, EPR)
│   ├── components/       # React components
│   ├── pages/           # App pages
│   ├── hooks/           # Custom hooks
│   └── services/        # Business logic
├── prisma/
│   └── schema.prisma    # Database schema
└── public/              # Static assets
```

---

## 🗄️ Database

Using Prisma with PostgreSQL. Models include:
- User, UserProfile, Subscription
- Product, StandardBox, ComplianceReport
- DPP, AuditLog, QuarterlyReport

Run `npx prisma db push` to setup.

---

## 🔒 Security & GDPR

✅ Cookie consent + Privacy Policy + Terms
✅ Data export + Account deletion
⚠️ TODO: Shopify HMAC + API auth + Rate limiting

---

## 📄 License

Copyright © 2026 CompliPack. All rights reserved.
