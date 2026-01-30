# Weather-based-on-userpreference
Weather Report Generator 🌤️
A sophisticated weather analysis tool that provides personalized weather reports and recommendations based on your planned activities. Built with Streamlit and powered by AI for intelligent weather analysis.

RUN COMMAND: streamlit run app.py Weather Report Generator Demo

🌟 Features
Real-time Weather Data: Fetch current weather conditions and forecasts for any location worldwide
AI-Powered Analysis: Utilizes GROQ LLM for intelligent weather analysis and activity recommendations
Interactive Visualizations:
Dynamic temperature trends
Precipitation forecasts
Weather condition indicators
Customized Reports: Generate detailed PDF reports tailored to your specific activities
User-Friendly Interface: Clean, intuitive design with responsive weather cards and charts
Comprehensive Forecasts: 5-day weather forecasts with detailed metrics
🚀 Getting Started
Prerequisites
Python 3.8 or higher
API keys for:
WeatherAPI (for weather data)
GROQ (for AI analysis)
Installation
Clone the repository:
git clone https://github.com/yourusername/weather-report-generator.git
cd weather-report-generator
Create and activate a virtual environment:
# On Windows
python -m venv venv
venv\Scripts\activate

# On macOS/Linux
python3 -m venv venv
source venv/bin/activate
Install dependencies:
pip install -r requirements.txt
Create a .env file in the root directory:
WEATHER_API_KEY=your_weather_api_key
GROQ_API_KEY=your_groq_api_key
Running the Application
streamlit run app.py
The application will be available at http://localhost:8501

📱 Usage
Enter Location: Input a city name or postal code
Specify Activity: Describe your planned activity (e.g., "Having a picnic", "Going hiking")
Generate Report: Click the "Generate Report" button
View Analysis:
Current weather conditions
AI-generated recommendations
Interactive forecast charts
Download Report: Get a detailed PDF report for future reference
🛠️ Project Structure
weather_report_app/
├── .env                  # Environment variables
├── requirements.txt      # Project dependencies
├── README.md            # Project documentation
├── config/
│   └── config.py        # Configuration settings
├── utils/
│   ├── __init__.py
│   ├── weather_api.py   # Weather API integration
│   ├── pdf_generator.py # PDF generation utility
│   └── llm_analyzer.py  # LLM analysis utility
└── app.py               # Main Streamlit application
📊 Features in Detail
Weather Analysis
Current temperature, humidity, and wind conditions
Weather trend visualization
Precipitation probability
Activity-specific recommendations
Visualization Components
Interactive temperature charts
Precipitation forecasts
Weather condition indicators
Responsive weather cards
Report Generation
Detailed PDF reports
Custom activity recommendations
5-day weather forecasts
Printable format
🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

Fork the repository
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request
🙏 Acknowledgments
WeatherAPI for weather data
GROQ for AI analysis
Streamlit for the web interface
Plotly for interactive charts
