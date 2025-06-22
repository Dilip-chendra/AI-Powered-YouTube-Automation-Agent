🎥 AI-Powered YouTube Automation Agent using n8n


This project is an AI-driven automation agent built with n8n that helps you automatically generate, schedule, and upload videos to YouTube — making content creation faster and easier.

🚀 Features
✅ Automatically generate video titles, descriptions, and hashtags using ChatGPT

✅ Auto-upload videos to YouTube with thumbnails and metadata

✅ Set a schedule for publishing videos at specific times

✅ Track uploads and errors using notifications

✅ No-code and low-code friendly (built using n8n)

🧠 How It Works
Trigger: The workflow starts manually or via a schedule (cron).

Generate Content: ChatGPT generates a YouTube title, description, and tags based on your prompt/topic.

Video Handling: Pre-made or AI-generated video files are selected or uploaded.

Upload to YouTube: The video is uploaded using the YouTube Data API node.

Notify: Sends a success or error notification to your email or preferred app (like Telegram or Discord).

📁 Project Structure
arduino
Copy
Edit
📂 n8n-workflows/
   └── youtube-upload-workflow.json
📄 README.md
📄 instructions.md (optional guide for setup)
🔧 Requirements
A free or self-hosted instance of n8n

A Google Developer Console project with YouTube Data API v3 enabled

OAuth 2.0 credentials for your YouTube account

OpenAI API Key (for ChatGPT integration)

Video files or a way to generate video content

🛠️ Setup Instructions
Clone this repo.

Import the youtube-upload-workflow.json into your n8n dashboard.

Configure the following:

Google OAuth2 Credentials (YouTube API)

OpenAI API Key

Paths to your video files or input source

Test the workflow and schedule it as per your needs.

📌 Use Cases
Content creators who want to automate their YouTube channel

Educational channels with templated video updates

Daily AI-generated content uploads (e.g., news, quotes, tutorials)

Productivity and marketing automation

💡 Future Improvements
AI-generated thumbnails

Auto video editing using ffmpeg or APIs

Multi-platform publishing (e.g., Instagram, TikTok, Shorts)

🤖 Built With
n8n

OpenAI GPT

YouTube Data API

Node.js (underlying environment)

📬 Contact
If you have suggestions or want to collaborate, feel free to reach out!
📧 dilip.madagari@gmail.com
