🌍 Travel Planner
Author: Batool Hussien

🚀 Project Overview
Travel Planner is a modern web application designed to help users efficiently plan their trips. This application provides essential travel details, including:

✅ Weather Forecasts – Get real-time weather updates for your destination.
✅ Trip Duration Calculation – Automatically calculate the length of your trip.
✅ Countdown Timer – Keep track of your departure date.
✅ Destination Images – View related images to enhance your planning experience.

🛠 Tech Stack
This project is built using the following technologies:

Frontend:

HTML
SCSS
JavaScript
Backend:

Node.js
Express.js
Build Tools:

Webpack
🌍 APIs Used
This project integrates several APIs to provide real-time travel information:

🌎 GeoNames API – Retrieves geographical location details.
☁ Weatherbit API – Provides weather forecasts for the selected destination.
🖼 Pixabay API – Fetches high-quality images related to the destination.

🚀 Installation & Setup
Follow these steps to run the project locally:

1️⃣ Prerequisites
Ensure you have the following installed:

Node.js (Tested on v22.13.1, but the latest stable version should work)
2️⃣ Clone the Repository
Run the following commands in your terminal:

sh
Copy
Edit
git clone https://github.com/batoolhu/travel-app.git  
cd travel-app  
3️⃣ Install Dependencies
sh
Copy
Edit
npm install  
4️⃣ Configure Environment Variables
Create a .env file in the root directory and add the following API keys:

env
Copy
Edit
GEONAMES_USERNAME=b.k.husein  
WEATHERBIT_API_KEY=a75d9b72e8f6450db2a25d17379080ef  
PIXABAY_API_KEY=49088082-18c17e4c7db45fff4ab7a0e26  
5️⃣ Run the Development Server
sh
Copy
Edit
npm run build-dev  
npm start  
🔍 Open http://localhost:8080/ in your browser to test the application.

6️⃣ Build for Production
sh
Copy
Edit
npm run build-prod  
🛠 Usage
Enter your travel destination and departure date.
The app fetches real-time weather data and related images.
View a countdown timer until your trip starts.
Enjoy a seamless travel planning experience!
📝 Contributing
Contributions are welcome! If you'd like to improve this project, follow these steps:

Fork the repository.
Create a new branch:
sh
Copy
Edit
git checkout -b feature-branch  
Commit your changes:
sh
Copy
Edit
git commit -m "Add new feature"  
Push to the branch:
sh
Copy
Edit
git push origin feature-branch  
Open a pull request.
💡 Tip: Before submitting a pull request, ensure your code follows the project's coding style and passes all tests.

📄 License
This project is licensed under the MIT License.

📌 Notes
Ensure all dependencies are installed before running the project.
If you encounter issues, check the API key configurations.
Feel free to report bugs or suggest improvements in the GitHub Issues section.
