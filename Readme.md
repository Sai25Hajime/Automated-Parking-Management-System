# 🚗 Automated Parking Management System
This project was developed as our Semester 4 Mini Project. It is a web-based Automated Parking Management System that allows users to view available parking slots in real time using Django and OCR integration.

---

# 🛠️ Tech Stack
**Frontend:** HTML, CSS, Javascript.

**Backend:** Django (Python Framework)

**OCR:** Pytesseract (Python wrapper for Tesseract OCR)

---
# 🧠 How It Works
The website allows users to view available parking slots in a selected mall.

OCR data is fetched via Pytesseract every 15 seconds, which updates the backend database with:

✅ Current parked vehicles

✅ Slot occupancy

✅ Slot availability is updated in real-time on the frontend.

---

# 📷 OCR Integration
Pytesseract processes images from a camera to scan and extract pictures of license plate numbers or relevant vehicle information.

This information is matched against the slot allocation logic to track active parking slots.

---

# 🔍 Features
✅ Real-time parking slot updates

✅ Visual display of slot availability

✅ OCR-based number plate recognition (via Pytesseract)

✅ Django-powered backend with periodic updates (every 15 seconds)

---

# Screenshots and Info
This website uses HTML, CSS, and the Django framework for the backend.

![image](https://github.com/Shibhya1/MiniProjectsem4/assets/123581067/b4f816cb-2780-4bd7-b1f2-0c2206590b00)

This is the main page for the website. The user can see the available parking slot in a specific mall by clicking on the View Slots.



![image](https://github.com/Shibhya1/MiniProjectsem4/assets/123581067/d8a8d2ca-f651-48bb-94fa-59228f7fb6a5)

The backend requests information from the Pytesseract OCR every 15 seconds and will update relevant details.

---

# 📁 Project Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Run the Django server:
   ```bash
   python manage.py runserver

---

# 🤝 Contributors/Collaborators
- [Shibhya Kaimal (@Shibhya1)](https://github.com/Shibhya1)
- [Alfred Vembil](https://www.linkedin.com/in/alfred-vembil-679073343/)
- [Saileen Fernandes (@Sai25Hajime)](https://github.com/Sai25Hajime)
- [Yohan Mavely (@BlueLightningWizard)](https://github.com/BlueLightningWizard) 
