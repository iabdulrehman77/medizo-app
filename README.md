# Medizo – Medicine Information App 💊

##  Overview
**Medizo** is a mobile-based medicine information application designed to provide accurate, structured, and easily accessible details about medicines. The app allows users to search medicines by **name, category, or symptoms**, and includes an **AI-powered chatbot** to assist users with symptom-based medicine suggestions.

⚠️ Medizo is **not a replacement for professional medical advice**. It serves as a quick reference tool to promote safe and informed medicine usage.

---

##  Problem Statement
Many individuals rely on unverified or incomplete online sources for medicine-related information, which can lead to incorrect usage, dosage errors, and harmful side effects.

Medizo addresses this issue by offering a **reliable, categorized, and user-friendly platform** that provides authentic medicine information in one place.

---

##  Target Users
- General public
- Medical students
- Healthcare professionals
- Academic evaluators

---

##  Key Features
-  Search medicines by **name, category, or symptoms**
-  Category-based browsing (e.g., Analgesics, Antibiotics)
-  AI-powered chatbot using OpenAI API
-  Secure user authentication (Firebase)
-  Offline access to essential medicine information
-  Favorites and search history
-  Light / Dark mode support
-  Responsive and user-friendly UI

---

##  Tech Stack

### Frontend
- Flutter (Dart)

### Backend & Services
- Firebase Authentication
- Cloud Firestore (Database)
- Cloud Storage (Images & Assets)
- OpenAI API (AI Chatbot)

### Offline Storage
- Hive (Local Database)

### Tools
- Android Studio
- GitHub (Version Control)

---

##  System Architecture
- **3-Tier Architecture**
  - Presentation Layer: Flutter Mobile App
  - Application Layer: Firebase Authentication & App Logic
  - Data Layer: Cloud Firestore + Hive (Offline Cache)

- Supports both **online and offline** data synchronization.

---

##  Security & Safety
- Secure authentication via Firebase
- Encrypted data transmission using HTTPS
- Medical disclaimer clearly displayed
- Controlled access to user data

---

##  Screenshots
UI screenshots demonstrating app flow and design are included in this repository.

screenshots/
├── login.png
├── signup.png
├── home.png
├── search.png
├── chatbot.png
├── medicine-details.png
├── dark-mode.png

---

##  Source Code
The source code for this project is **private** due to academic and intellectual property considerations.

📩 Code can be shared **upon request**.

---

##  Academic Context
This project was developed as a **Final Year Project (BS Computer Science)**  
Department of Computer Science  
**Government College Samundri**

---

##  Author
**Abdul Rehman**  
 BS Computer Science  
 Email: itsrehmn@gmail.com  
 GitHub / LinkedIn: iabdulrehman77

---

##  Future Enhancements
- Expansion of medicine database
- Advanced AI health insights
- Doctor/pharmacist verification
- Multi-language support
- Performance optimization

---

⭐ If you found this project interesting, feel free to star the repository!


