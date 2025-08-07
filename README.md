# QR Menu Card Generator

This project allows restaurant administrators to digitally generate QR codes for their menu cards instead of using physical menus. The admin inputs the restaurant name and menu link (e.g., Google Drive), and the system generates a downloadable QR code. This QR code can be printed and placed on tables for customers to scan and view the menu.

This solution ensures a modern, hygienic, and cost-effective dining experience.

---

## Features

- Admin can enter:
  - Restaurant Name
  - Online Menu Link (e.g., Google Drive)

- Instantly generates a QR code

- Option to download and print the QR code

- Clean and responsive interface

---

## Tech Stack

- **Backend**: Python, Django  
- **Frontend**: HTML, CSS 
- **QR Code Generation**: `qrcode` and `pillow` Python libraries  
- **Styling**: Bootstrap

---

## Benefits

- Improved customer convenience  
- Hygienic and touchless menu access  
- Reduces printing costs  
- Admin-friendly interface  
- Easily updateable menu links anytime

---

## Getting Started

1. Clone the repository

2. Create and activate a virtual environment
```bash
python -m venv env
env\Scripts\activate         # Windows
```

3. Install dependencies
```bash
pip install -r requirements.txt
```

4. Run Django server
```bash
python manage.py runserver
```


---

## Future Enhancements
- Admin authentication (login system)

- Store data in a database (restaurant + links)

- QR code analytics (how many scans)

- Generate multiple QR codes for multiple branches

---

## Conclusion
The QR Menu Card Generator streamlines the dining experience by offering a clean, contactless solution for accessing restaurant menus. With its user friendly interface and dynamic QR code generation, this project modernizes menu distribution while ensuring hygiene and operational efficiency.

---
