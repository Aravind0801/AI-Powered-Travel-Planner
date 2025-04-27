✈️ AI-Powered Travel Planner 🚗🛤️
🌟 Overview
Welcome to the AI-Powered Travel Planner! This Streamlit app helps you plan your travels efficiently by providing AI-powered recommendations for the best travel options between your source and destination. Whether you're looking for a cab, train, bus, or flight, this app will suggest the best choices along with estimated costs.

💡 Key Features
🚗 Travel Recommendations: Get suggestions for cab, train, bus, and flight options.

💰 Cost Estimates: Receive real-time estimated prices for each travel option.

🖥️ User-Friendly Interface: Built with Streamlit, making it easy to use and interact with.

🤖 AI-Powered: Powered by Google Generative AI (Gemini 2.0) through LangChain for personalized recommendations.

🛠️ Setup Instructions
1️⃣ Clone the Repository
Clone the repository to your local machine:

bash
Copy
Edit
git clone <repository_url>
2️⃣ Install Dependencies
Install required libraries using:

bash
Copy
Edit
pip install -r requirements.txt
3️⃣ Google API Key
To use Google Generative AI, you'll need an API key from Google Cloud. Follow this guide to create your API key.

After getting your API key, update the GOOGLE_API_KEY variable in the app.py file.

4️⃣ Run the Application
Start the app by running:

bash
Copy
Edit
streamlit run app.py
5️⃣ Use the App
✍️ Enter your source and destination locations.

🟢 Click the "Get Travel Options" button.

🚀 View your personalized travel recommendations and estimated costs!

🔧 Technologies Used
Streamlit: For building the interactive and user-friendly frontend.

LangChain: To integrate Google Generative AI and provide smart travel suggestions.

Google Generative AI (Gemini 2.0): To generate the travel recommendations and cost estimates.

📝 Example Use Case
Source: New York City 🗽

Destination: Los Angeles 🌴

Once entered, the app will provide you with travel options such as flights, trains, buses, or cabs, along with estimated prices for each.

🚀 Future Improvements
🏙️ Add support for more travel modes and route preferences.

📅 Enable date-based travel recommendations.

🌍 Expand the app to support international destinations.

📄 License
This project is open-source under the MIT License.

