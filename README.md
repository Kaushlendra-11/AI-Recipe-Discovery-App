AI Recipe Discovery App
A smart, web-based application that leverages generative AI to create unique recipes from a list of ingredients provided by the user. This project showcases the integration of a powerful AI model (Google's Gemini) with a real-time database (Firestore) to deliver a dynamic and personalized user experience.

✨ Features
AI-Powered Recipe Generation: Enter ingredients you have on hand, and the app will generate a complete recipe with a name, ingredient list, and step-by-step instructions.

Real-Time Database: Save your favorite generated recipes to a personal collection powered by Google Firestore.

Persistent User Sessions: Uses Firebase Anonymous Authentication to give each user a unique ID and persist their saved recipes across sessions.

Dynamic UI: The interface is built to be responsive and updates in real-time, displaying generated content and saved recipes without page reloads.

Modern & Responsive Design: Clean, modern interface built with Tailwind CSS that works seamlessly on desktop and mobile devices.

Loading & Error States: Provides clear feedback to the user during API calls and handles potential errors gracefully.

🛠️ Technologies Used
Frontend: HTML5, CSS3, JavaScript (ES6 Modules)

Styling: Tailwind CSS

Generative AI: Google Gemini API (via REST API)

Backend & Database: Google Firebase

Firestore: For real-time database functionality to store saved recipes.

Authentication: For anonymous user authentication to manage user-specific data.

Fonts: Google Fonts (Inter)
