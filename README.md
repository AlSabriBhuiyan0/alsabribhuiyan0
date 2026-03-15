<h1 align="center">Hi 👋, I'm Al Sabri Bhuiyan</h1>
<h3 align="center">"Data Analyst & Web Developer|Turning data into insights and Code into Solutions"</h3>
<h4 align="center">I'm a Data Analyst and Web Developer with a passion for turning complex data into actionable insights and building user-friendly, efficient web applications. With 3 years of experience in both fields, I bring a unique combination of analytical thinking and technical expertise. My goal is to create value by leveraging data and technology to solve real-world problems.</h4>
<img align="right" alt="coding" width="400" src="https://camo.githubusercontent.com/5046cb083418fd1922b7f5990e594c3bb06f5d87e5516cd8839ae0aa48b3aec4/68747470733a2f2f696d616765732e73717561726573706163652d63646e2e636f6d2f636f6e74656e742f76312f3537363966633430316236333162616231616464623261622f313534313538303631313632342d5445363451474b524a4738535741495553374e532f6b6531375a77644742546f6464493870446d34386b506f73776c7a6a53564d4d2d53784f703743563539425a772d7a505067646e346a557756634a45315a7657515578776b6d794578676c4e714770304976544a5a616d574c49327a76595748384b332d735f3479737a63703272795449304871544f6161556f68724938504936465879386339505774426c7141566c555335697a7064634958445a71445976707252715a32395077306f2f636f64696e672d667265616b2e676966">

<p align="left"> <img src="https://komarev.com/ghpvc/?username=alsabribhuiyan0&label=Profile%20views&color=0e75b6&style=flat" alt="alsabribhuiyan0" /> </p>

<p align="left"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=alsabribhuiyan0" alt="alsabribhuiyan0" /></a> </p>

- 🔭 I’m currently working on [BrickToken](https://github.com/AlSabriBhuiyan0/BrickToken-Local-version-updated.git)

- 🌱 I’m currently learning **Sentimmental Analysis**

- 👨‍💻 All of my projects are available at [https://alsabribhuiyan.xyz/](https://alsabribhuiyan.xyz/)

- 📝 I regularly write articles on [https://medium.com/@alsabribhuiyan](https://medium.com/@alsabribhuiyan)

- 💬 Ask me about **Data Science**

- 📫 How to reach me **Contact@alsabribhuiyan.xyz**

- 📄 Know about my experiences [https://alsabribhuiyan.xyz/](https://alsabribhuiyan.xyz/)

- ⚡ Fun fact **I want to know more**

---

## 🏢 Ryofin — Business Management System

**Ryofin** is a cloud-based, multi-tenant ERP/POS (Enterprise Resource Planning / Point of Sale) system designed to help small and medium-sized businesses manage their entire operations from a single platform.

> 🔗 Platform URL: `https://your-business.ryofin.com` — the tenant-specific subdomain indicates a **multi-tenant SaaS architecture**, where each business client gets its own isolated environment.

---

### 🧱 System Architecture & Tech Stack

Based on the system's observable characteristics:

| Layer | Technology / Pattern |
|-------|----------------------|
| **Deployment** | Multi-tenant SaaS (subdomain-per-tenant: `tenant1.ryofin.com`) |
| **Authentication** | Phone-number-based login with password |
| **Frontend** | Responsive web application (likely a JavaScript framework such as Vue.js, React, or Laravel Blade — confirm with the vendor) |
| **Backend** | Server-side web application (likely PHP/Laravel or Node.js, common for POS/ERP SaaS — confirm with the vendor) |
| **Database** | Relational database (MySQL or PostgreSQL) for transactional data (products, sales, purchases) |
| **Architecture** | MVC (Model-View-Controller) pattern, RESTful API |

---

### 📋 Core Modules & Function Breakdown

#### 📦 1. Product Management
Manages the complete product catalog for the business.

| Function | What It Does |
|----------|--------------|
| **Add Product** | Create a new product with name, SKU/barcode, category, unit of measure, and pricing |
| **Edit Product** | Update existing product details (price changes, description updates) |
| **Product Categories** | Group products into categories for easier navigation and reporting |
| **Unit Management** | Define units of measurement (pcs, kg, litre, box, etc.) |
| **Pricing** | Set purchase price (cost) and selling price; supports multiple price tiers |
| **Product List View** | Paginated table of all products with search and filter capabilities |

#### 🛒 2. Purchase Management
Tracks all incoming goods from suppliers.

| Function | What It Does |
|----------|--------------|
| **Create Purchase Order** | Record a new purchase from a supplier with line items, quantities, and costs |
| **Supplier Management** | Maintain a list of suppliers with contact information |
| **Purchase List** | View all past and pending purchases with dates, amounts, and status |
| **Purchase Details** | Drill down into a specific purchase to see itemized line items |
| **Stock Auto-Update** | When a purchase is confirmed, inventory levels are automatically incremented |
| **Cost Tracking** | Records the cost price of goods, feeding into profit margin calculations |

#### 💰 3. Sales Management
Handles all customer-facing transactions and invoicing.

| Function | What It Does |
|----------|--------------|
| **Create Sale / Invoice** | Process a new sale, add products to a cart, apply discounts, and generate an invoice |
| **Customer Management** | Optionally attach sales to customer records for history tracking |
| **Sales List** | View all completed and pending sales with amounts and dates |
| **Invoice / Receipt** | Generate printable or PDF invoices/receipts for customers |
| **Payment Tracking** | Record full or partial payments against sales invoices |
| **Revenue Dashboard** | View total sales revenue over selected date ranges |
| **Stock Auto-Deduction** | When a sale is confirmed, inventory levels are automatically decremented |

#### 🔄 4. Stock Adjustments
Handles manual corrections to inventory levels.

| Function | What It Does |
|----------|--------------|
| **Manual Stock Increase** | Add stock for reasons like found items, returns from customers, or opening balance entry |
| **Manual Stock Decrease** | Reduce stock for reasons like damaged goods, theft, or write-offs |
| **Adjustment Reason Codes** | Categorize adjustments by reason (damage, return, opening stock, etc.) |
| **Audit Trail** | Every adjustment is logged with date, user, and reason for accountability |
| **Stock List** | Real-time view of current stock levels per product after all transactions |

---

### ✅ How Ryofin Benefits You

- **Centralized Control** — Manage products, purchases, sales, and inventory all from a single platform, eliminating the need for multiple disconnected tools.
- **Real-Time Inventory Visibility** — Every sale, purchase, and adjustment instantly updates stock levels — always know exactly what you have on hand.
- **Accurate Financial Tracking** — Monitor purchase costs and sales revenue side-by-side to understand profit margins clearly.
- **Multi-Tenant Isolation** — Each business tenant gets a completely isolated data environment, ensuring privacy and data security between clients.
- **Phone-Based Authentication** — Simple mobile-number login means no email setup required, ideal for business owners in regions where mobile is primary.
- **Time Savings** — Automate repetitive data-entry tasks; stock auto-updates on sales and purchases remove the need for separate inventory counts.
- **Error Reduction** — Structured stock adjustment workflows with reason codes and audit trails reduce human error and ensure inventory records stay accurate.
- **Scalability** — Whether you run a small shop or a growing enterprise, Ryofin's SaaS architecture means no installation or server maintenance is needed.

> 💡 *Ryofin turns complex business operations into simple, manageable workflows — helping business owners make better decisions faster.*

---

### ⚠️ Security Note

If you use Ryofin, follow these best practices to keep your account and business data secure:

- **Never share your login credentials** in public forums, GitHub issues, chat apps, or email.
- **Use a strong, unique password** — at least 12 characters with a mix of letters, numbers, and symbols.
- **Change your password immediately** if you suspect it has been exposed.
- **Enable two-factor authentication (2FA)** if the platform supports it.
- **Limit user permissions** — grant each team member only the access level they need for their role.
- **Review your account activity** regularly for any unauthorized transactions or logins.

---

### Blogs posts
<!-- BLOG-POST-LIST:START -->
<!-- BLOG-POST-LIST:END -->

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/https://www.linkedin.com/in/alsabribhuiyan/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="https://www.linkedin.com/in/alsabribhuiyan/" height="30" width="40" /></a>
<a href="https://kaggle.com/alsabribhuiyan" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/kaggle.svg" alt="alsabribhuiyan" height="30" width="40" /></a>
<a href="https://fb.com/alsabribhuiyan" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="alsabribhuiyan" height="30" width="40" /></a>
<a href="https://instagram.com/alsunny65" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="alsunny65" height="30" width="40" /></a>
<a href="https://medium.com/@alsabribhuiyan" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/medium.svg" alt="@alsabribhuiyan" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://firebase.google.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase" width="40" height="40"/> </a> <a href="https://flask.palletsprojects.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/pocoo_flask/pocoo_flask-icon.svg" alt="flask" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://kubernetes.io" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg" alt="kubernetes" width="40" height="40"/> </a> <a href="https://www.microsoft.com/en-us/sql-server" target="_blank" rel="noreferrer"> <img src="https://www.svgrepo.com/show/303229/microsoft-sql-server-logo.svg" alt="mssql" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a> <a href="https://www.php.net" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="php" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://pytorch.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" alt="pytorch" width="40" height="40"/> </a> <a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> </a> <a href="https://www.tensorflow.org" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="tensorflow" width="40" height="40"/> </a> </p>

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=alsabribhuiyan0&show_icons=true&locale=en&layout=compact" alt="alsabribhuiyan0" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=alsabribhuiyan0&show_icons=true&locale=en" alt="alsabribhuiyan0" /></p>

