# Youtube-Summarizer
# 🎬 Gemini-Powered YouTube Video Summarizer

This is a Flask web app that summarizes YouTube videos using **Google's Gemini API**
## 📌 What it Does

Paste a YouTube video link ➡️ Get an AI-generated summary powered by Gemini 1.5.

## 🧰 Technologies Used

- **Flask** (Python Web Framework)
- **Google GenAI SDK** (for Gemini API)
- **Cloud Run** (for Deployment)
- **HTML/CSS** (for frontend UI)
- **YouTube link ingestion** and summarization

## 🖼️ UI Preview

<img width="2818" height="1368" alt="image" src="https://github.com/user-attachments/assets/525305ff-0dcd-486a-a1a1-b46082822570" />


## 🚀 How to Run Locally

```bash
# Clone the repo
git clone https://github.com/your-username/youtube-gemini-summarizer.git
cd youtube-gemini-summarizer

# Create virtual environment
python -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Set your Google Cloud project ID in app.py
# Replace "REPLACE_WITH_YOUR_PROJECT_ID" accordingly

# Run the app
python app.py
