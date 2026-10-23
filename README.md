# AssetLifecycle
Enterprise IT hardware asset lifecycle auditor and license compliance tracker.
AssetLifecycle

Enterprise IT Hardware Asset Lifecycle Auditor & License Compliance Tracker

AssetLifecycle is a web-based dashboard designed to help IT Department Heads manage hardware assets throughout their lifecycle and help auditors identify software license compliance issues.

The project aims to replace scattered spreadsheets with a single place to track assets, employees, warranties, software licenses, and audit findings.

 Project Objectives

- Track IT hardware assets from procurement to disposal.
- Assign assets to employees and monitor ownership.
- Track warranty expiry and asset lifecycle status.
- Monitor software licenses and purchased versus used seats.
- Identify over-deployed, expiring, and expired licenses.
- Allow auditors to verify assets and record audit findings.
- Store demo data locally so records remain available after refreshing the page.

 Key Features

1. Dashboard

- View asset counts by lifecycle stage.
- Identify warranty alerts.
- Review software license compliance status.
- Switch between IT Department Head and Auditor views.

2. Asset Register

- Register and manage hardware assets.
- Track asset tags, models, serial numbers, purchase dates, costs, and warranties.
- Assign assets to employees.
- Track lifecycle changes and assignment history.

3. License Compliance Tracker

- Record software products, vendors, purchased seats, and expiry dates.
- Compare seats used against seats purchased.
- Identify over-deployed, expiring soon, and expired licenses.

4. Audit Management

- Verify whether assets exist and match inventory records.
- Mark assets as Verified, Missing, or Mismatch.
- Add notes to audit findings.
- Review audit results and compliance gaps.

5. Data Persistence

- Use browser localStorage or JSON-based data storage for the demonstration.
- Retain supported records after a page reload.

6. Responsive Interface

- Use a responsive layout suitable for laptops, tablets, and mobile devices.
- Provide readable tables, forms, status labels, and validation messages.

🛠️ Technology Stack

- HTML5 — Web page structure
- CSS3 — Styling and responsive layouts
- JavaScript — Application logic, validation, and interactions
- Bootstrap 5 — Responsive UI components
- Git — Version control
- GitHub — Source code hosting

Optional stretch technologies: React, Vite, Chart.js, or Leaflet.

 Project Scope

The minimum viable product (MVP) includes:

- Hardware asset registration and lifecycle management
- Employee assignment tracking
- Software license seat and expiry tracking
- Audit checklists and findings
- Local data persistence
- Input validation and responsive design

Optional enhancements include CSV/PDF exports, search and filters, charts, and a role-based view switch.

Getting Started

Prerequisites

- A modern web browser
- A code editor such as Visual Studio Code
- Git installed on your computer

Installation

1. Clone the repository:
   
   git clone https://github.com/YOUR_USERNAME/AssetLifecycle.git

2. Open the project folder:
   
   cd AssetLifecycle

3. Open "index.html" in your browser, or use the Live Server extension in VS Code if the project is a static HTML application.

Replace "YOUR_USERNAME" with your GitHub username.

If the project uses React and Vite, follow the corresponding setup instructions and install its dependencies before running it.

 Example Project Structure

AssetLifecycle/
├── index.html
├── style.css
├── script.js
├── README.md
└── assets/

The actual folder structure may vary depending on the implementation.

 License Compliance Rules

The demonstration uses the following simplified rules:

- Over-deployed: Seats used exceed seats purchased.
- Expired: The license expiry date has passed.
- Expiring Soon: The license expires within 30 days.
- Compliant: No other compliance condition applies.

 Asset Lifecycle

The planned lifecycle stages are:

"In Stock → Assigned → In Repair → Assigned or Retired → Disposed"

Disposed assets cannot be reassigned. Lifecycle changes should be recorded in the asset history.

 Limitations

- The application uses synthetic sample data for demonstration.
- localStorage is browser-specific and is not a shared database.
- Role checks and compliance calculations run in the browser and are intended for demonstration purposes.
- License compliance results are simplified and are not a legal or vendor-approved audit.
- Real enterprise use would require a trusted backend, authentication, access controls, and appropriate data protection.

 Future Enhancements

- Export asset registers and audit findings to CSV or PDF.
- Add charts for asset lifecycle stages and license seat usage.
- Add stronger authentication and role-based access controls.
- Integrate with approved enterprise inventory and license management systems.
- Deploy the application using GitHub Pages or Vercel.

 Project Team

- Alisha Karmele
- Avani Patel

 Project Information

- Project: AssetLifecycle
- Track ID: PST_PD_025
- Duration: 4 weeks
- Focus: Frontend Development Basics
- Audience: IT Department Heads and Auditors

 Disclaimer

AssetLifecycle is an educational demonstration project. It is not a substitute for an authorized enterprise asset management platform or a legally binding software license audit.
