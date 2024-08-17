# VidSnap: AI-Powered Video Summarization Tool

## Overview

VidSnap is an AI-driven web application designed to revolutionize video content consumption. In a world filled with lengthy videos and information overload, VidSnap helps you quickly grasp the essence of a video by generating concise summaries in various formats, such as text, images, and summary videos. Whether you're a busy professional or a passionate tech enthusiast, VidSnap makes it easier to access and understand video content without spending hours watching it.

## Key Features

- **Generates Concise Summaries**: Extracts the core ideas of a video, allowing you to quickly understand the content.
- **Answer Any Query**: Skip the video, ask a question, and get fast, precise video insights without watching the whole clip.
- **Provides Visual Highlights**: Offers key images that visually encapsulate the video's main points.
- **Delivers Compact Video Recaps**: Generates condensed versions of the original video, focusing on the most important information.

## 🎥 What VidSnap Does:

1. **Text Summaries**: Quickly grasp the key points of any video through concise text summaries.
2. **Visual Summaries**: Receive snapshots that visually represent the content, highlighting essential moments.
3. **Video Recaps**: Enjoy a condensed version of the original video, providing a quick overview of the key information.

## ✍️ Steps to Use VidSnap:

1. **Enter YouTube URL**: Paste the link of the video you want to summarize.
2. **Context Extraction**: VidSnap analyzes the video content and extracts the context.
3. **Provide a Prompt**: Guide the AI with a specific query, or let it summarize the video on its own.
4. **Receive the Summary**: Get the response in text, images, and even a short summary video.

## 🔧 Technologies Used:

- **Python**: Core programming language for backend development and AI processing.
- **Flask**: Web framework used to deploy the application.
- **Machine Learning**: Algorithms for content summarization.
- **Gemini API**: Natural language processing for text generation and context analysis.
- **Computer Vision**: Frame extraction and image summarization.
- **ffmpeg**: Video processing and editing tool.
- **HTML/CSS/JavaScript**: Frontend design and responsiveness to ensure a user-friendly interface.

## ⚙️ How to Run the code

** NOTE: Before doing anything first install and setup ffmpeg in your system. **

1. Clone the Repository
```bash
git clone https://github.com/SaadARazzaq/VidSnap.git
cd src
```

2. Set Up Python Environment
Create a virtual environment to manage the project's Python dependencies:
```bash
python -m venv venv
source venv/bin/activate  # For Windows use venv\Scripts\activate
```

3. Install Python Dependencies
```bash
pip install -r requirements.txt
```

4. Install Node.js Dependencies
```bash
npm install
```

5. Set Up Environment Variables
Follow the sample env file syntax for setting up .env
```bash
touch .env
```

6. Run the Backend Server
```bash
python app.py
```
This should start the backend server, and Flask will listen on a port (usually http://127.0.0.1:5000).

7. Run Frontend
```bash
npm start
```

---

Thank you for your support and interest in VidSnap!
