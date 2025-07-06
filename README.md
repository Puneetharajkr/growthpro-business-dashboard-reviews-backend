# 🛠️ GrowthProAI – Business Dashboard Backend

This is the **backend** of the GrowthProAI Full Stack Internship Assignment. Built using **Node.js + Express**, this server simulates a small business dashboard with randomly generated ratings, reviews, and SEO headlines.

### 🌐 Live API

🔗 [https://growthpro-business-dashboard-reviews-usys.onrender.com](https://growthpro-business-dashboard-reviews-usys.onrender.com)

---

## 📦 Features

- `POST /business-data`  
  Accepts `name` and `location`, returns:
  - Randomized Google rating (3.5–5)
  - Randomized review count
  - SEO headline (randomly picked and personalized)

- `GET /regenerate-headline?name=...&location=...`  
  Returns a fresh AI-style headline

- Simulated data — no database required
- CORS-enabled for frontend integration

---

## 🧠 Tech Stack

- Node.js
- Express.js
- CORS middleware

---

## 🔧 Setup Instructions

```bash
# Clone the backend repo
git clone https://github.com/Puneetharajkr/growthpro-business-dashboard-reviews-backend.git
cd growthpro-business-dashboard-reviews-backend

# Install dependencies
npm install

# Start the backend
node index.js
```

> App runs on [http://localhost:5000](http://localhost:5000) locally

---

## 📁 Folder Structure

```
backend/
├── index.js          // Express server + routes
├── headlines.js      // Static headline list
└── package.json
```

---

## 📄 Assignment Context

This backend simulates Google Business data using Express, responding to React frontend requests with randomized, AI-style SEO content. It was submitted as part of GrowthProAI’s Full Stack Internship Assignment.

---

## 📎 Related Repos

- Frontend Repo: [growthpro-business-dashboard-reviews-frontend](https://github.com/Puneetharajkr/growthpro-business-dashboard-reviews-frontend)
- Fullstack Repo: [growthpro-business-dashboard-reviews-fullstack](https://github.com/Puneetharajkr/growthpro-business-dashboard-reviews-fullstack)
