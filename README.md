# Streamlit Data App 🌎🚀

An interactive **Streamlit web application** that visualizes environmental data and integrates NASA’s **Astronomy Picture of the Day (APOD) API** to display daily space imagery and information.

This project focuses on **data visualization**, **external API integration**, and **clean Python application structure**.

---

## Features

- 📊 Interactive data visualization using Streamlit
- 🌊 Analysis of real-world environmental data from CSV files
- 🛰️ Live integration with **NASA’s APOD API**
- 🖼️ Displays daily astronomy image, title, and description
- 🔐 Secure API key handling using environment variables
- 🧩 Modular Python design for maintainability

---

## Tech Stack

- **Python 3.10+**
- **Streamlit**
- **Pandas**
- **NumPy**
- **Requests**
- **NASA APOD API**
- **python-dotenv**

---

## API Used
### 🚀 NASA Astronomy Picture of the Day (APOD)

Provides a daily astronomy image along with metadata

Includes title, explanation, and media type

Official API documentation: https://api.nasa.gov/

Environment Variables

Create a .env file in the project root:

NASA_API_KEY=your_nasa_api_key_here


### 🔑 You can get a free NASA API key from https://api.nasa.gov/

## Installation & Setup
### 1️⃣ Clone the repository
git clone https://github.com/yusufdirdis/Streamlit-Data-App.git
cd Streamlit-Data-App

### 2️⃣ Create a virtual environment
python -m venv .venv
source .venv/bin/activate   # macOS/Linux

.\.venv\Scripts\Activate.ps1 # Windows

### 3️⃣ Install dependencies
pip install -r requirements.txt

Running the App
streamlit run dashboard.py

Then open:

http://localhost:8501

## Project Structure

```text
Streamlit-Data-App/
├─ dashboard.py                    # Streamlit UI & app logic
├─ apis.py                         # NASA APOD API integration
├─ manage.py                       # Optional runner / helper script
├─ biscayneBay_waterquality.csv    # Environmental dataset
├─ requirements.txt                # Python dependencies
├─ InternshipReady/                # Polished project assets
└─ temp_doc/                       # Temporary notes / docs
