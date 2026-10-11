# 🔍 Criminal Investigation System (CIS Dashboard)

A web-based **suspect management and crime-pattern prediction dashboard** with role-based access for **Admin** and **Officer** users. Built with HTML, CSS, Bootstrap 5 and vanilla JavaScript. All data is stored in the browser using `localStorage`, so no backend is needed.

![Login Page](screenshots/01-login.png)

---

## ✨ Features

- 🔐 **Role-based login**: Admin and Officer have different menus and permissions
- 📝 **Add suspects**: name, age, DOB, gender, address, crime type, notes and photo upload (Admin only)
- 👁️ **View suspects**: filter by crime type, gender or name
- 🎯 **Predict suspect**: score-based matching on crime type, age range, gender and location
- 📍 **Track on Google Maps**: opens the suspect's address in Google Maps
- ✅ **Completed cases**: move a case from Active to Completed
- 📜 **Activity history**: logs every add, delete, prediction and case completion, with filters
- 🎨 Hacker-style dark UI with green/red neon theme

---

## 🖼️ Screenshots

### Login (Admin & Officer)

| Empty form | Admin login | Officer login |
|---|---|---|
| ![Login](screenshots/01-login.png) | ![Admin Login](screenshots/02-login-admin.png) | ![Officer Login](screenshots/03-login-officer.png) |

### Admin Panel

**Add Suspect**

![Add Suspect](screenshots/04-add-suspect.png)

**View Suspects**

![View Suspects Admin](screenshots/05-view-suspects-admin.png)

**Predict Suspect**

![Predict Admin](screenshots/06-predict-admin.png)

**System History**

![History Admin](screenshots/07-history-admin.png)

### Officer Panel

**View Suspects**

![View Suspects Officer](screenshots/08-view-suspects-officer.png)

**Predict Suspect**

![Predict Officer](screenshots/09-predict-officer.png)

**Completed Cases**

![Completed Cases](screenshots/10-completed-cases.png)

**System History**

![History Officer](screenshots/11-history-officer.png)

### Google Maps Tracking

| Suspect card | Opens in Google Maps |
|---|---|
| ![Suspect Card](screenshots/13-suspect-card.png) | ![Google Maps](screenshots/12-google-maps.png) |

---

## 🔑 Demo Credentials

| Role | Username | Password |
|---|---|---|
| Admin | `admin` | `admin123` |
| Officer | `officer` | `officer123` |

> ⚠️ These are hardcoded demo credentials for a portfolio/learning project. Do not use this in a real environment.

---

## 🚀 How to Run

1. Clone the repository
   ```bash
   git clone https://github.com/YOUR_USERNAME/criminal-investigation-system.git
   cd criminal-investigation-system
   ```
2. Open `index.html` (or `login.html`) in any modern browser.
3. Log in with the demo credentials above.

No installation or server required.

---

## 📁 Project Structure

```
criminal-investigation-system/
├── index.html            # Redirects to login (for GitHub Pages)
├── login.html            # Login page
├── add_suspect.html      # Add / delete suspects (Admin)
├── view_suspects.html    # View, filter, complete cases
├── predict_suspect.html  # Crime pattern prediction
├── view_evidence.html    # Evidence / photo vault
├── history.html          # Activity log
├── screenshots/          # README images
└── README.md
```

---

## 🛠️ Tech Stack

- HTML5, CSS3
- Bootstrap 5.3
- JavaScript (ES6)
- Browser `localStorage` / `sessionStorage`

---

## 📌 Notes

- Data is saved only in your browser. Clearing site data removes all records.
- All names, addresses and cases shown in the screenshots are **dummy data** created for demonstration.
- This project is for educational purposes only.

---

## 👤 Author

Made by **YOUR NAME**
GitHub: [@YOUR_USERNAME](https://github.com/YOUR_USERNAME)
