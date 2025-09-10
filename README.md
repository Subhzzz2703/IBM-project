# IBM-project

🌍 Sustainable Smart City AI Assistant

An AI-powered Sustainable Smart City Dashboard built with Python, Hugging Face Transformers, and Gradio.
This tool provides eco-friendly lifestyle guidance, policy summarization, carbon footprint estimation, renewable energy advice, and interactive sustainability Q&A.

✨ Features

🌱 Eco Tips Generator
Generate actionable eco-friendly lifestyle tips based on environmental keywords.

📜 Policy Summarization
Upload a PDF or paste policy text, and get a concise summary with key provisions.

💬 Q&A Chatbot
Chat with an AI assistant specialized in sustainability and smart cities.

🌎 Carbon Footprint Estimator
Estimate your daily CO₂ emissions based on travel, energy usage, and diet.

🔆 Renewable Energy Advisor
Get renewable energy recommendations based on your location and budget.

📊 Analytics Dashboard
Visualize how many eco-tips, policies, chats, and footprint estimates you’ve generated.

📂 Export Center
Download all your session results (tips, summaries, etc.) as a ZIP file.

🛠 Installation

Clone the repository:

git clone https://github.com/your-username/sustainable-smart-city.git
cd sustainable-smart-city


Install dependencies:

pip install -r requirements.txt


Or manually:

pip install torch transformers gradio PyPDF2 matplotlib

🚀 Usage

Run the app locally:

python sustainable_smart_city.py


You’ll see a Gradio interface open in your browser with all features.

📒 Example (Colab)

You can also run this project in Google Colab:

!git clone https://github.com/your-username/sustainable-smart-city.git
%cd sustainable-smart-city
!pip install -r requirements.txt
!python sustainable_smart_city.py

📦 Export & Downloads

Eco tips → saved as eco_tips.txt

Policy summaries → saved as policy_summary.txt

Export all → smart_city_outputs_YYYYMMDD_HHMMSS.zip

On Colab, download with:

from google.colab import files
files.download("eco_tips.txt")
files.download("policy_summary.txt")

📊 Example Dashboard

The analytics tab generates a bar chart showing how many tasks were completed in your session.

🧰 Tech Stack

Python 3.9+

Gradio (UI framework)

PyTorch + Transformers (LLM inference)

Matplotlib (analytics dashboard)

PyPDF2 (policy PDF text extraction)

🔮 Future Enhancements

🌍 Region-specific renewable energy recommendations via APIs

🛰️ Integration with IoT sensors for real-time sustainability data

📡 Cloud deployment (Streamlit/Spaces/Docker)

📜 License

This project is licensed under the MIT License.
