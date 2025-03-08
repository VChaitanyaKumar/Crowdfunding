# Crowdfunding
This is a crowdfunding platform built using React.js that allows individuals or organizations to create, manage, and support various types of campaigns. The platform supports startup funding, creative projects, charity donations, and product pre-orders. It provides a seamless experience for fundraisers and backers alike.
Crowdfunding Platform Overview
This project is a simple and efficient crowdfunding platform that helps users discover fundraising campaigns and contribute financially to support various causes. The payment process is handled securely through PayTM, ensuring transparency while also maintaining donor anonymity.

Key Features
For Users:
Browse through ongoing fundraising campaigns on the homepage.
Click on a campaign to view detailed information.
Donate securely via PayTM with just a few clicks.
Share campaigns with friends and family to increase support.
View transaction details on the campaign page while keeping donor identities private.
Reach out for assistance or queries through the Contact Us section.
For Admins:
Access all user functionalities.
Create and manage fundraising campaigns by adding relevant details.
Deactivate campaigns once the funding goal is met or if needed.
Modify campaign details, except for the amount already raised.
Add new admins if required (only existing admins can do this).
Perform essential database operations to manage data.
Secure admin login, accessible only via website_url/admin/login (hidden from general users).
Technology Stack
This platform is built using the MERN stack, which provides a smooth and scalable experience.

Frontend: React.js
Backend: Node.js & Express.js
Database: MongoDB Atlas
Payments: PayTM API
Hosting: Vercel
Why This Project?
This project was developed as part of the Winter Project event by AASF IIITM. It was inspired by the need for a dedicated crowdfunding platform for the ROTARACT CLUB at IIITM. The goal was to create a user-friendly and transparent system that makes fundraising simple while ensuring safe and efficient transactions.

Live Demo
🔗 Try it here: Crowdfunding App

How to Set Up
Prerequisites:
Install Node.js & npm
Get a PayTM Merchant ID & API Key
Have a MongoDB database URI
Backend Setup:
Open the backend folder.
Run npm install to install required packages.
Set up the environment variables (refer to the env-sample file).
Start the backend server using node server.js.
Frontend Setup:
Navigate to Frontend/crowd-funding-frontend.
Run npm install to install frontend dependencies.
Add the backend URL in config.js.
Start the frontend using npm start.
