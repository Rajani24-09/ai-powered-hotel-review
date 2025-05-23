# 🏨 *AI Response Generator*

This is a full-stack application for analyzing hotel guest reviews using AI-powered sentiment analysis and auto-generated hotel responses.

## 🔧 Features

- ✍️ **Review Submission** – Guests can submit reviews with detailed ratings.
- 💬 **AI Response Generator** – Automatically generate AI-powered replies for each review.
- 📊 **Sentiment Dashboard** – Visualize review sentiments (Positive, Negative, Neutral) using bar charts.
- ✅ **Review Approval System** – Admins can edit and approve AI-generated replies.

---

## 🗂️ Project Structure
hotel-review/
├── backend/
│ ├── models/
│ │ └── Review.js
│ ├── routes/
│ │ ├── reviews.js
│ │ └── aiReply.js
│ ├── utils/
│ │ └── sentimentUtils.js
│ └── server.js
├── frontend/
│ ├── src/
│ │ ├── components/
│ │ │ ├── ReviewCard.js
│ │ │ └── Dashboard.js
│ │ ├── App.js
│ │ └── index.js
│ └── public/
├── README.md
└── package.json

Start Backend
cd backend
npm install
node server.js

Make sure MongoDB is running on your system. The app connects to:
mongodb://localhost:27017/hotel-reviews

Start Frontend
cd frontend
npm install
npm start
App will open on http://localhost:3000
