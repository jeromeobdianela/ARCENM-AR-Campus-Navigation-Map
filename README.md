# 📱 ARCENM: Augmented Reality-Based Campus Exploration and Navigation Map

An Android AR application for exploring and navigating the Southern Luzon State University (SLSU) Tayabas Campus. Developed as a Bachelor's research project (December 2024), it received the **Best Research in Innovation** award upon graduation in June 2025.

🎥 **Demo video:** https://drive.google.com/file/d/1FtSZp7RHs8XhLWUyuGzijVOSO_9czt67/view?usp=sharing

📦 **Download APK:** https://drive.google.com/file/d/1FvQgIOXxKmRDJheosQ84XA9YUqNX0pNr/view?usp=sharing


<img width="890" height="418" alt="Screenshot 2026-10-09 120401" src="https://github.com/user-attachments/assets/6037f9df-543d-4368-a01f-e983c29dda1f" />
<img width="416" height="890" alt="Screenshot 2026-10-09 120457" src="https://github.com/user-attachments/assets/f1bd0ada-3223-46bc-82ca-25e7610a9660" />

## 🎯 Problem and Solution

Printed campus information is limited, can be lost or damaged, and cannot hold everything students and visitors need. ARCENM replaces it with Marker-based (QR-triggered) AR content. Scanning a QR code placed around campus shows a 3D floor map with the user's current location, plus digital information such as the school profile, timeline, application requirements and library e-resources. This also supports a paperless campus.

## ✨ Features

- QR code scanning that displays AR content on the phone
- Augmented 3D floor maps with the user's current location (EARTH Building 1, Academic Building 2, LICUP Building 3)
- Campus information: profile, timeline, application requirements, library e-resources
- Buttons that open the campus Facebook page, email and e-resource websites
- Works offline, except for the external links
- In-app user manual and About Us page

## 🛠️ Tech Stack

- Unity 2022.3.20f1 and C#
- Vuforia Engine (QR/marker-based AR)
- Microsoft Visual Studio 2022
- Canva, Photopea, & Adobe Photoshop (UI and digital assets)
- Platform: Android 8.0 (Oreo) and higher

## 🔄 Development Methodology

The project followed an Agile process from planning to maintenance.

<img width="1280" height="768" alt="agile" src="https://github.com/user-attachments/assets/0bcff114-63d9-4a67-a68b-c1897f658297" />

## 🧪 Testing and Evaluation

- **Blackbox testing** with 63 respondents covering installation, launch, performance and graphics.
- **Acceptability evaluation** by 20 respondents (faculty and IT professionals) using a 4-point Likert scale based on ISO/IEC 25010 (functional suitability, performance efficiency, compatibility, usability, reliability, maintainability, portability).
- **Result:** rated **Highly Acceptable** (median and mode of 4).

## 👥 Team

- Programmer: Jerome E. Obdianela
- UI Designer and Documenter: Madelyn M. Llaguno
- Documenter: Joyce Marinelle B. Ablaña
- Adviser: Roland A. Calderon, DIT

## 🚀 Installation

1. Download the latest `.apk`.
2. Allow installation from unknown sources on your Android phone.
3. Install and open ARCENM.
4. Tap **Scan** and point the camera at an ARCENM QR code.

> The QR codes are placed around SLSU Tayabas Campus. A user guide is in docs file

## 💻 Run the Source Code

1. Install Unity 2022.3.20f1 with Android Build Support.
2. Clone this repo and open it in Unity Hub.
3. Add your own Vuforia license key (Window → Vuforia Engine → Configuration). It is not included in this repo.
4. Build for Android.

## 📄 Documentation

Full manuscript available upon request.
