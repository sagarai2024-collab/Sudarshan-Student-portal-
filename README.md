# Sudarshan Agrawal Classes – Student Registration & Study Material Management

> **Domain:** Education / Online Learning Management  
> **Author:** Sagarika Chakraborty — *Full Stack .NET Engineer | React.js | Web API | SQL Server*

A web application to streamline **student registration**, **fee payments**, and **study material distribution**. Built with **ASP.NET MVC 5 / .NET Core 3**, **Entity Framework**, and **LINQ**, the system supports online payments via a secure **payment gateway**, and generates **financial & academic reports** (Word, PDF, Excel) using **RDLC**. CI/CD and production support were managed through **TFS**.

---

## ✨ Key Features
- **Student Registration & Profiles**: onboarding, KYC, course & batch selection, guardians, and documents.
- **Fee Management**: online payment gateway integration, fee plans, dues & reminders, receipts/invoices.
- **Study Materials**: upload/download with access control, versioning, and download tracking.
- **Reporting**: RDLC-based financial and academic reports exportable to **Word/PDF/Excel**.
- **Admin Console**: manage courses, batches, materials, fees, and users.

---

## 🧱 Technology Stack
- **Framework**: ASP.NET MVC 5 / .NET Core 3 (server-rendered)
- **Data**: Entity Framework, LINQ, SQL Server
- **Frontend**: Razor Views, jQuery, AJAX, Bootstrap (responsive)
- **Reporting**: RDLC (Word/PDF/Excel)
- **Payments**: Pluggable payment gateway (REST + webhook)
- **DevOps**: TFS (version control, CI/CD)

---

## 📁 Repository Structure
```
.
├─ README.md
└─ docs
   ├─ HLD.md
   ├─ LLD.md
   └─ architecture.png
```

---

## 🚀 Quick Start (Dev)
Update `appsettings.json` / `Web.config` (depending on MVC5 or .NET Core target):
```json
{
  "ConnectionStrings": {
    "SqlServer": "Server=.;Database=SAC;Trusted_Connection=True;TrustServerCertificate=True"
  },
  "Payments": { "Provider": "GatewayX", "ApiKey": "..." }
}
```
Then run the web project from Visual Studio / `dotnet run`.

---

## 🧭 Documentation
- **HLD**: [`/docs/HLD.md`](docs/HLD.md)
- **LLD**: [`/docs/LLD.md`](docs/LLD.md)
- **Architecture Diagram**: [`/docs/architecture.png`](docs/architecture.png)

---

## 👩‍💻 Credits
**Sagarika Chakraborty** — Student registration & fee modules, payment gateway integration, study-material workflows, RDLC reports, and TFS CI/CD.
