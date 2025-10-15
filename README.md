 Watch Tower – Sunderland Streetlight Reporting 🌃💡

**Watch Tower** is a community-focused website that allows citizens of Sunderland to **report broken or faulty streetlights**. By empowering residents to submit reports and track their resolution, the platform helps improve street visibility and safety for everyone.

---

## 🌟 Features

- **Report a Streetlight:** Submit issues with location (GPS), description, and optional photos.  
- **Track Status:** View the status of submitted reports (reported, in-progress, resolved).  
- **Map View:** Interactive map showing reported streetlights and their current status.  
- **Notifications:** Optional email updates when report statuses change.  
- **Responsive Design:** Works seamlessly on desktop, tablet, and mobile devices.  

---

## 🛠️ Tech Stack

- **Frontend:** React + TypeScript  
- **Styling:** Tailwind CSS  
- **Maps:** Leaflet.js or Google Maps API  
- **Forms & Validation:** React Hook Form / Zod  
- **Notifications:** Email integration (SendGrid)  
- **Deployment:** Vercel / Netlify  

---

## 📦 Project Structure

watch-tower-website/
├─ public/ # Static assets (images, favicon, etc.)
├─ src/
│ ├─ components/ # Reusable UI components
│ ├─ pages/ # React pages (Home, Report, Dashboard)
│ ├─ services/ # API calls
│ ├─ styles/ # Global CSS/Tailwind overrides
│ └─ App.tsx # Main React app
├─ package.json
└─ README.md

yaml
Copy code

---

## ⚡ Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/watch-tower-website.git
cd watch-tower-website
2. Install dependencies
bash
Copy code
npm install
3. Configure environment variables
Create a .env file at the root:

env
Copy code
REACT_APP_API_URL=https://api.watchtower-sunderland.com
REACT_APP_MAP_API_KEY=your_map_api_key
4. Run the website locally
bash
Copy code
npm start
