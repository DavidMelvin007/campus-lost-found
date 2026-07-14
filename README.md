# 🎒 Campus Lost & Found Portal

A web-based Lost & Found Management System designed to help students, faculty, staff, visitors, and the public efficiently report, search, and recover lost belongings within the campus.

Built with **HTML, CSS, JavaScript, and Supabase**, the application offers a simple and user-friendly interface for managing lost and found items, submitting ownership claims, and handling requests through an administrative dashboard.

---

## 🚀 Features

### 👤 User Authentication

• Secure User Registration  
• Login Authentication  
• Multiple User Roles:
  • Student
  • Faculty
  • Professor
  • Staff
  • Parent
  • Visitor
  • General Public

### 🔍 Lost & Found Management

• Report Lost Items  
• Report Found Items  
• Upload Item Images  
• Capture Images Using Mobile Camera  
• Add Item Location Details  
• Save Google Maps Location  
• Search Items by:
  • Item Name
  • Category
  • Date
  • Location

### 📦 Claim Management

Users can:

• Browse Found Items  
• View Detailed Item Information  
• Submit Ownership Proof  
• Send Claim Requests  
• Track Claim Status

### 💬 Complaint & Support

A built-in support system allows users and administrators to communicate easily.

Features include:

• Raise Complaints  
• Chat with Administrator  
• Receive Admin Responses  
• Track Complaint Status

### 👨‍💼 Admin Dashboard

Administrators can:

• View Dashboard Statistics  
• Manage User Accounts  
• Manage Lost & Found Listings  
• Review Claim Requests  
• View User Complaints  
• Respond to Queries  
• Track Returned Items

### 🌍 Multi-Language Support

Supports the following languages:

• 🇺🇸 English  
• 🇮🇳 Tamil  
• 🇮🇳 Hindi  
• 🇮🇳 Telugu  
• 🇮🇳 Malayalam  
• 🇮🇳 Kannada

### 🎨 User Experience

• Responsive Layout  
• Dark & Light Theme  
• Mobile-Friendly Interface  
• Image Preview Before Upload  
• Camera Capture Support  
• Modern Dashboard Design

---

## 🛠️ Tech Stack

### Frontend

• HTML5  
• CSS3  
• JavaScript (Vanilla)

### Backend

• Supabase

### Database

• PostgreSQL (Supabase)

### Authentication

• Supabase Authentication

### Storage

• Supabase Storage

### Hosting

• Netlify

---

## 📂 Project Structure

```text
campus-lost-found/
│
├── css/
│   └── style.css
│
├── js/
│   ├── app.js
│   └── supabase-config.js
│
├── index.html
├── login.html
├── lost-dashboard.html
├── found-dashboard.html
├── upload.html
├── item-details.html
├── complaints.html
│
├── admin-dashboard.html
├── admin-users.html
├── admin-items.html
├── admin-complaints.html
│
└── README.md
```

---

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/DavidMelvin007/campus-lost-found.git
```

### Navigate to the Project Directory

```bash
cd campus-lost-found
```

### Configure Supabase

Create a project in **Supabase** and update the following file:

```text
js/supabase-config.js
```

Replace the following values with your project credentials:

• `SUPABASE_URL`  
• `SUPABASE_ANON_KEY`

### Run the Application

Simply open:

```text
index.html
```

or launch the project using the **Live Server** extension in Visual Studio Code.

---

## 📸 Application Screens

• Landing Page  
• Login & Registration  
• User Dashboard  
• Found Items Dashboard  
• Upload Item Page  
• Item Details Page  
• Complaint & Support Chat  
• Admin Dashboard  
• User Management  
• Item Management

---

## 🔮 Future Enhancements

• Email Notifications  
• QR Code-Based Item Verification  
• AI-Powered Image Matching  
• Push Notifications  
• Campus ID Verification  
• Analytics Dashboard  
• OTP-Based Login  
• Real-Time Chat Support

---

## 🤝 Contributing

Contributions are welcome!

1. Fork this repository.
2. Create a new feature branch.

```bash
git checkout -b feature-name
```

3. Commit your changes.

```bash
git commit -m "Added new feature"
```

4. Push your branch.

```bash
git push origin feature-name
```

5. Open a Pull Request.

---

## 👨‍💻 Author

**David Melvin L**  

**GitHub:** https://github.com/DavidMelvin007

---

## 📄 License

This project is licensed under the MIT License.


---

⭐ **If you found this project helpful, consider giving the repository a star!**
