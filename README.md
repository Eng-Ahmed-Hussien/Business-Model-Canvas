# TrackUp — Business Model Canvas

An interactive **Business Model Canvas** built for **TrackUp** — Egypt's first structured pre-career decision platform for engineering students.

Built with **TailwindCSS**, **JavaScript**, and **MongoDB**. 🚀

> TrackUp helps engineering students discover the right career path through smart assessment, personalized roadmaps, and expert mentorship.

---

## ✨ Features

- **Interactive Canvas** 📌 – View and edit all 9 BMC blocks.
- **Custom Colors** 🎨 – Change card background and text colors with a built-in color picker.
- **Secure Edit Mode** 🔑 – Password-protected editing (owner only).
- **Dark / Light Mode** 🌙 – Toggle between themes with a single click.
- **MongoDB Integration** 💾 – Data automatically saved and loaded from the database.
- **Export Options** 📤 – Export your canvas as a **high-quality PNG or PDF**.
- **Responsive Design** 📱 – Works across desktop and mobile devices.

---

## 🗂️ TrackUp BMC Overview

| Block | Content |
|---|---|
| **Key Partners** | ITI Egypt · Udemy · University Career Offices |
| **Key Activities** | Platform Dev · Mentor Vetting · Algorithm Tuning |
| **Key Resources** | Web Platform · Matching Algorithm · Mentor Network |
| **Value Proposition** | First pre-career decision tool for EG engineering students — result in under 5 min |
| **Customer Relationships** | Free Self-service · Premium 1-on-1 Mentorship |
| **Channels** | Web App · Social Media · University Ambassadors |
| **Customer Segments** | Engineering Students (420K) · Fresh Graduates |
| **Cost Structure** | Hosting · Mentor Fees · Marketing |
| **Revenue Streams** | Test 99 EGP · Session 299 EGP · Premium 199 EGP/mo · Commission 10–15% |

---

## 🛠️ Tech Stack

- **Frontend:** HTML, TailwindCSS, JavaScript, FontAwesome
- **Backend:** Node.js, Express.js, MongoDB
- **Libraries:**
  - `html2canvas` (for screenshots)
  - `jsPDF` (for PDF export)
  - `dotenv` (for environment variables)

---

## 📂 Project Structure

```
├── assets/
│   ├── CSS/
│   │   └── style.css
│   ├── JS/
│   │   ├── main.js       # App logic
│   │   ├── data.js       # Default canvas data
│   │   ├── server.js     # Express + MongoDB backend
│   │   └── tailwind.js   # Tailwind config
│   └── imgs/
├── index.html
├── package.json
├── .env              # Environment variables (not committed)
└── README.md
```

---

## ⚙️ Installation & Setup

### 1. Clone Repository

```bash
git clone https://github.com/Eng-Ahmed-Hussien/Business-Model-Canvas.git
cd Business-Model-Canvas
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the project root:

```env
MONGODB_URI=your-mongodb-connection-string
PORT=3000
DB_NAME=your-database-name
COLLECTION_NAME=your-collection-name
ADMIN_PASS=your-admin-password
```

### 4. Run Backend

```bash
node assets/JS/server.js
```

### 5. Open Frontend

Open `index.html` in your browser.

---

## 🔐 Password Protection

- Edit Mode requires authentication.
- Password is set via `ADMIN_PASS` in `.env`.
- Only the owner can edit canvas content.

---

## 📤 Export Options

- **Export as PNG** – High-resolution canvas screenshot.
- **Export as PDF** – A4 landscape PDF of the full canvas.
- Dark mode is preserved during export.

---

## 🔗 Links

- 🚀 **Live BMC:** [trackupv1-bcm.vercel.app](https://trackupv1-bcm.vercel.app/)
- 📱 **Platform Demo:** [track-up-orpin.vercel.app](https://track-up-orpin.vercel.app/)
- 📄 **Pitch Deck:** [View on Canva](https://canva.link/jsrkrkqke81hj9y)

---

## 👨‍💻 Team

**Ali Elsyed** — Product & Strategy
- Al-Azhar University, Electrical Engineering
- [LinkedIn](https://www.linkedin.com/in/ali-elsyed)

**Ahmed Hussein** — Tech Lead & Software Architect
- Menofia University, Electronic Engineering (CSE)
- [LinkedIn](https://www.linkedin.com/in/ahmed-hussien-front-end-developer/)
