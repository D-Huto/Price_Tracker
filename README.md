<div align="center"> <br /> <img src="https://img.shields.io/badge/-Web_Scraping-black?style=for-the-badge&logoColor=white&color=FF0000" alt="webscraping" /> <img src="https://img.shields.io/badge/-Next_JS-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=000000" alt="nextjs" /> <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" /> <img src="https://img.shields.io/badge/-MongoDB-black?style=for-the-badge&logoColor=white&logo=mongodb&color=47A248" alt="mongodb" /> </div> <h3 align="center">Track E-Commerce Prices with Ease</h3> </div>
📋 Table of Contents<br>
🤖 Introduction<br>
⚙️ Tech Stack<br>
🔋 Features<br>
🤸 Quick Start<br>
🔗 Links<br>
🤖 Introduction<br>
This application allows users to track e-commerce prices and get notifications on price drops or stock availability using automated web scraping. Built with Next.js, MongoDB, and Tailwind CSS, it leverages cron jobs to ensure up-to-date product data.<br>

⚙️ Tech Stack<br>
Next.js, 
Tailwind CSS,
MongoDB,
Bright Data,
Nodemailer<br>
🔋 Features<br>
Price Tracking: Track e-commerce products and get notified of price changes.<br>
Web Scraping: Extract detailed product data, including prices, images, and stock status.<br>
Email Notifications: Alerts for price drops or stock updates.<br>
Automated Cron Jobs: Keep data refreshed with periodic scraping.<br>
🤸 Quick Start<br>
Clone the repo:
bash
Copy code
git clone https://github.com/D-Huto/Price_Tracker.git
cd pricewise
Install dependencies:
bash
Copy code
npm install
Add environment variables:
bash
Copy code
BRIGHT_DATA_USERNAME=
BRIGHT_DATA_PASSWORD=
MONGODB_URI=
EMAIL_USER=
EMAIL_PASS=
Run the app:
bash
Copy code
npm run dev
Open http://localhost:3000 to see it in action.
