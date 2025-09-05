# WealthPro – Financial Dashboard

A responsive financial dashboard built with **Next.js 14, TypeScript, TailwindCSS, and Recharts**.  
This project demonstrates a modern frontend dashboard with charts, mock APIs, PDF export, and dark mode support.  

---

## 🚀 Features

- **Top Navigation Bar** with icons (CRM, Utilities, Insurance, Assets, Mutual, Research, Transact Online, Goal GPS, Financial Planning, Wealth Report, Other).  
- **Two Main KPI Cards**  
  - AUM: Value, MoM % change, and “View Report” button.  
  - SIP: Value, MoM % change, and “View Report” button.  
- **Time Range Filter** (3 Days, 7 Days, 10 Days, 30 Days).  
- **Stat Cards**: Purchases, Redemptions, Rejected Transactions, SIP Rejections, New SIP.  
- **Charts** (powered by Recharts):  
  - Clients Bubble Chart  
  - SIP Business (Bar + Line Combo) Chart  
  - Monthly MIS Multi-line Chart  
- **Responsive Design** → Works across mobile, tablet, and desktop.  
- **Dark Mode Toggle** 🌙  
- **Loading Animations** while fetching data.  
- **Dynamic Filter Buttons** (data reloads on range change).  
- **Export Dashboard to PDF** using `html2canvas` + `jsPDF`.  

---

## 📂 Tech Stack

- **Next.js 14 (App Router)**
- **TypeScript**
- **TailwindCSS**
- **Recharts**
- **Lucide React (Icons)**
- **html2canvas + jsPDF** (PDF export)

---

## 📊 Data

Mock API endpoints are served from JSON files inside `/public/data/`:

- `metrics.json`  
- `stats.json`  
- `clients.json`  
- `sipBusiness.json`  
- `monthlyMis.json`  

The app fetches and filters data dynamically based on the selected time range.

-<img width="1434" height="662" alt="Screenshot 2025-09-05 at 12 33 37 PM" src="https://github.com/user-attachments/assets/123f8443-4ad9-4c35-acd9-9fe33545291a" />
--<img width="1253" height="438" alt="Screenshot 2025-09-05 at 12 33 22 PM" src="https://github.com/user-attachments/assets/75ec5dc7-a68f-474b-9e36-83d3489b8801" />
<img width="1343" height="478" alt="S<img width="1436" height="656" alt="Screenshot 2025-09-05 at 12 32 59 PM" src="https://github.com/user-attachments/assets/002f703c-491a-4206-86df-743987809bcf" />
creenshot 2025-09-05 at 12 33 13 PM" src="https://github.com/user-attachments/assets/4a16e556-2b88-44a0-a039-b4cd7c14bc4f" />


## 🛠️ Setup & Run

Clone the repository:

```bash
git clone https://github.com/your-username/wealthpro-dashboard.git
cd wealthpro-dashboard
