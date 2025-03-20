🚀 YouTube Video Summarizer Extension with AI Chatbot
🔹 Save time and get instant insights from YouTube videos with multilingual support and smart search.

📚 Table of Contents
Project Overview
Features
Tech Stack
Installation
How It Works
Usage
Challenges Faced
Future Enhancements
Contributors
License
🚦 Project Overview
The YouTube Video Summarizer Extension is a Chrome extension that uses AI to summarize YouTube videos and provides an AI-powered chatbot for real-time video-related Q&A. It aims to save time by extracting the key points of any video without watching the entire content.

🌟 Features
✅ YouTube Summarization: Generates concise video summaries.
✅ AI Chatbot: Allows users to ask questions related to the video content.
✅ Persistent Chat History: Retains chat history across videos.
✅ Multi-Language Support: Summarizes videos in multiple languages (if captions are enabled).
✅ Smart Search: Enables quick term-based information retrieval from the summary.
✅ User-Friendly UI: Designed with an intuitive and sleek Chrome extension interface.
✅ Real-Time Processing: Fast and accurate transcript-to-summary generation.

🔥 Tech Stack
💻 Languages: HTML, CSS, JavaScript, Python
🔥 AI Models: Gemini
🔧 Libraries: youtube-transcript-api
🛠️ Manifest Version: 3

⚙️ Installation
🔹 Clone the Repository
bash
Copy
Edit
git clone <YOUR_GITHUB_REPO_LINK>
cd youtube-summarizer-extension
🔹 Set Up the Extension
Open Chrome and navigate to chrome://extensions/.
Enable Developer Mode (top right corner).
Click on "Load unpacked".
Select the project folder to install the extension.
🔹 Backend Setup
Install required Python libraries:
bash
Copy
Edit
pip install youtube-transcript-api
Add your Gemini API key to the code.
Run the Python backend script:
bash
Copy
Edit
python app.py
⚙️ How It Works
Transcript Extraction:

The extension uses the youtube-transcript-api to fetch the transcript of the YouTube video.
If captions are disabled, the extension cannot generate a summary.
AI-Powered Summarization:

The transcript is sent to Gemini AI via API calls.
Gemini processes the content and generates a concise summary.
Chatbot Functionality:

Users can ask questions related to the video content.
The AI responds based on the summarized information.
Persistent Chat History:

The chat history is preserved as users switch between videos.
When they revisit, previous conversations remain intact.
🚀 Usage
Open a YouTube Video:

Click on the extension icon.
The extension automatically fetches the video transcript.
Generate Summary:

The extension displays the summarized content.
Supports multiple languages (if captions are available).
Chat with AI:

Use the chatbot to ask questions related to the video.
Get relevant and accurate answers instantly.
Persistent Chat History:

Switch between different videos while maintaining your chat history.
🔥 Challenges Faced
Transcript Fetching:

Initially, fetching transcripts was challenging.
Solved it using the youtube-transcript-api library.
Multi-Language Support:

Supporting multiple languages was difficult due to varying transcript availability.
Fixed it by refining the Python code.
Real-Time Performance:

Optimized the extension for faster and more accurate real-time processing.
🚀 Future Enhancements
✅ Improved Language Support:

Add more language models for better multilingual performance.
✅ Enhanced UI/UX:

Refine the user interface for a more seamless experience.
✅ Offline Mode:

Enable the summarizer to work offline by caching transcripts.
✅ API Rate Limiting:

Implement handling for API rate limits and errors.
👥 Contributors
💡 Team Members:
Prathik Balaji
Pavin S
Rohith T M 
Prasath
