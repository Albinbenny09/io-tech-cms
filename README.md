# 🗂 IO-Tech CMS – Strapi Backend

This repository contains the **Strapi CMS** backend for the IO-Tech technical task.  



📦 **Frontend GitHub Repo**: [https://github.com/Albinbenny09/io-tech-frontend](https://github.com/Albinbenny09/io-tech-frontend)

---

## ✅ Features

- ✍️ Dynamic content for:
  - Services
  - Team Members
  - Clients (Testimonials)
  - Subscribers (Email capture)
  - Blog Posts (optional)
- 🌍 Multilingual content (English & Arabic)
- 🖼️ Image & media management using Strapi Upload plugin
- 🔄 Data import/export using `strapi-plugin-import-export-entries`
- 🔓 Public API access (GET) for frontend integration
- 🧾 Proper content relationships and Slug-based URL routing

---

## 🛠️ Tech Stack

| Tool          | Purpose                      |
|---------------|-------------------------------|
| Strapi v4     | Headless CMS (Node.js-based)  |
| SQLite (local) / PostgreSQL (Render) | Database |


---

## 🚀 Local Development Setup

### 1️⃣ Clone the Repo

```bash
git clone https://github.com/Albinbenny09/io-tech-cms
cd io-tech-cms
2️⃣ Install Dependencies
bash
Copy
Edit
npm install


4️⃣ Run Strapi Locally
bash
Copy
Edit
npm run develop
CMS will be available at: http://localhost:1337/admin

Now you can check the fortend at:

Create the first admin user when prompted.

📁 Content Types
Collection Name	Description
services	Title, slug, category, images, description
team-members	Name, position, contact info, photo
clients	Name, position, comment, image
subscribers	Email addresses for newsletter


📞 Contact
Albin Benny
📧 albinbenny1515@gmail.com
📱 +971-558819072
