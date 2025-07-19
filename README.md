# 🐄 Pashu Swastha – Doot

**Pashu Swastha – Doot** is a full-stack web platform built to help rural farmers easily connect with nearby veterinary doctors, get trusted livestock disease remedies, and trade animals or products via an integrated stock buy/sell feature. The platform bridges the gap between modern veterinary care and grassroots rural needs.

## 📽 Demo

🎥 [Click here to watch the demo video](https://drive.google.com/your-video-link-here) 

---

## 💡 Problem Statement

Many farmers in rural areas struggle to access timely and trustworthy veterinary care for their livestock. Traditional methods of disease treatment may not always be effective, and access to professionals is often limited.

---

## 🚀 Features

- 🧑‍⚕️ Find local veterinary doctors near your village
- 📚 Home remedies and educational articles/videos for livestock health
- 🔄 Buy/Sell livestock and related stock products
- 👥 Multiple login panels:
  - **Farmer**
  - **Doctor**
  - **Admin**
- 🔍 Search functionality for diseases and remedies
- 🐮 Doctor approval and verification mechanism by Admin

---

## 🛠 Tech Stack

- **Frontend**: React.js
- **Backend**: Node.js + Express.js
- **Database**: MongoDB (Atlas)
- **Web Scraping**: Python (BeautifulSoup)

---

## 🧪 Installation & Usage

### Prerequisites
- Node.js & npm
- MongoDB
- Python 3 (for scraping scripts)

### Setup

1. **Clone the Repository**  
   ```
   git clone https://github.com/your-username/pashu-swastha-doot.git
   cd pashu-swastha-doot
    ```

2. **Backend Setup**

   ```bash
   cd server
   npm install
   npm start
   ```

3. **Frontend Setup**

   ```bash
   cd client
   npm install
   npm start
   ```

4. **Run Scraper (Optional)**

   ```bash
   python3 scrape.py
   ```

> ⚠️ Make sure your MongoDB is running locally or update the `MONGO_URI` in `.env` accordingly.

---

## 📚 Use Cases

* Connect farmers to local, trusted veterinarians
* Enable low-cost home-based remedies
* Create a small-scale livestock marketplace
* Empower rural India through technology-driven veterinary care

---

## 📂 Project Structure

```
pashu-swastha-doot/
├── client/             # React frontend
├── server/             # Express + Node backend
├── scraper/            # Python scripts for data scraping
└── README.md
```

