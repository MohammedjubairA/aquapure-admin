# AquaPure – E-Commerce Admin Panel & AI Automation

 Project Overview
AquaPure is a product management system that combines an admin panel, a Spring Boot backend, an Android application, and an AI-powered content automation workflow. It simplifies product management and automates the preparation of social media content using AI.

 Objectives
- Develop a user-friendly admin panel for managing product information.
- Provide REST APIs for retrieving product data.
- Display product details and images in an Android application.
- Automate product caption and hashtag generation using AI.
- Store generated content and product details in Google Sheets.

 Features
- Admin Panel:** React-based interface for viewing product information.
- REST API:** Spring Boot backend for product data integration.
- Database Integration:** Firebase Firestore for product data storage.
- Android Application:** Displays product details and images on mobile devices.
- AI Content Generation:** Uses the Groq API to generate product captions and hashtags.
- Workflow Automation:** Uses n8n to automate daily content preparation.
- Google Sheets Integration:** Stores product names, captions, image URLs, and timestamps.
- Image Hosting:** Uses ImgBB to provide accessible product image URLs.

Technologies Used

| Category | Technologies |
|---|---|
| Frontend | React, HTML, CSS, JavaScript |
| Backend | Java 21, Spring Boot |
| API | RESTful APIs |
| Database | Firebase Firestore |
| Mobile Application | Android, Java |
| AI Integration | Groq API |
| Automation | n8n |
| Data Storage | Google Sheets |
| Image Hosting | ImgBB |
| Deployment | Vercel |
| Version Control | Git, GitHub |

 System Architecture
1. The React admin panel provides the user interface for product information.
2. The Spring Boot backend exposes REST APIs and integrates with Firebase Firestore.
3. The Android application retrieves and displays product data through the backend API.
4. The n8n workflow reads product details from Google Sheets.
5. The Groq API generates product captions and hashtags based on the available information.
6. The workflow saves the generated content, image URL, and timestamp to Google Sheets for review and reuse.

AI Automation Workflow
**Workflow:** Schedule Trigger → Google Sheets → Groq API → Edit Fields → Google Sheets

- Reads product details from Google Sheets.
- Generates AI-powered captions and hashtags.
- Extracts the product name and image URL.
- Adds the generated content and timestamp to the output sheet.
- Runs on a daily schedule when the local n8n instance is running and the workflow is enabled/published.

**Note:** The current workflow prepares and stores Instagram content; it does not directly publish posts to Instagram.

 Project Links
- Live Admin Panel:** https://aquapure-admin-pslidk6g7-mohammed-jubair.vercel.app/
- GitHub Repository:** https://github.com/MohammedjubairA/aquapure-admin
- Android APK:** Add your Google Drive APK link here.
- AI Automation Demo:** Add your Google Drive recording link here.
- Google Sheets Demo:** Add your shareable Google Sheets link here.

 Key Learnings
- Developing and integrating REST APIs using Spring Boot.
- Connecting backend services with Firebase Firestore.
- Building an Android application that consumes API data.
- Integrating AI APIs into automated workflows.
- Automating data processing with n8n and Google Sheets.
- Deploying a frontend application using Vercel.
- Managing source code using Git and GitHub.

 Future Enhancements
- Implement direct Instagram publishing through the Meta Graph API.
- Add authentication and role-based access to the admin panel.
- Add product creation, editing, deletion, and search features.
- Improve workflow monitoring and error handling.
- Add analytics for generated content and product engagement.

 Author
Mohammed Jubair A

