# 🗓️ dailydesk – Smart Shift Scheduling System

**dailydesk** is a Django-based application for managing shift schedules, absence tracking, and replacements in a real-world NOC environment.

🔒 This is a **showcase repo only**. Source code is not shared due to internal usage and privacy policies.

---

## 📸 How It Works (Screenshots)

### 1. Uploading the Shift File via Django Admin

- Upload Excel file in admin panel  
  ![](dailydesk-showcase/screenshots/excel_p1.png)

- Django admin – file upload interface  
  ![](dailydesk-showcase/screenshots/django_admin_p2.png)  
  ![](dailydesk-showcase/screenshots/django_adminUpload_excel_p3.png)

- Uploaded file confirmation  
  ![](dailydesk-showcase/screenshots/excel_uploades_p4.png)

---

### 2. Web View After Upload

- Shift view rendered on the web  
  ![](dailydesk-showcase/screenshots/after_upload_on_the_web_p5.png)  
  ![](dailydesk-showcase/screenshots/afternoon_part_desk_p6.png)

---

### 3. User Login & Role-Based Access

- Login page  
  ![](dailydesk-showcase/screenshots/login_page_p7.png)

- User creation in admin  
  ![](dailydesk-showcase/screenshots/adduser_in_admin_p8.png)

- User list in Django admin  
  ![](dailydesk-showcase/screenshots/listofusers_in_admin_p9.png)

---

### 4. Absence & Replacement Features

- Marking absence  
  ![](dailydesk-showcase/screenshots/onopera_anotheruser_p10.png)

- Disable/Enable users  
  ![](dailydesk-showcase/screenshots/disable_p11.png)  
  ![](dailydesk-showcase/screenshots/activate_p12.png)  
  ![](dailydesk-showcase/screenshots/disables_p12.png)

- Visual feedback  
  ![](dailydesk-showcase/screenshots/justseeit_p13.png)  
  ![](dailydesk-showcase/screenshots/kermani_p14.png)

---

## ✅ Features

- Excel shift plan → Web view (auto parsed)
- User authentication and access control
- Absence reporting with live update
- Auto-replacement mechanism (only one replacement allowed)
- Visual indicators for status updates
- Admin user control (enable/disable)

---

## 🧩 Tech Stack

- **Python** + **Django**
- **Django Admin** for uploads and user control
- **Excel parser** via `openpyxl`
- Responsive HTML frontend (auto-generated views)

---

## 📌 Note

This system was actively used in a professional data center team.  
The UI is fully dynamic, and shift handovers are visually tracked and controlled.

> If you’re hiring for a DevOps, infrastructure, or backend role, feel free to contact me for more information about this project.
