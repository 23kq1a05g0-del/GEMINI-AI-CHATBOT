🤖 AI Studio
An end-to-end Generative AI Studio built with Python and Streamlit that combines multiple AI capabilities into a single application.

✨ Features
💬 Gemini AI Chat
🖼️ Gemini Vision (Image Understanding)
🎨 AI Image Generation
🎬 AI Video Generation
📄 PDF Chat (RAG)
🌐 Web Search
💾 Chat History
📥 Image & Video Download
📤 Image Upload
🖥️ Modern Streamlit UI
📂 Project Structure
AI-Studio/
│
├── app.py
├── config.py
├── chatbot.py
├── vision.py
├── image_generator.py
├── video_generator.py
│
├── models/
│
├── uploads/
│
├── generated_images/
│
├── generated_videos/
│
├── requirements.txt
├── README.md
└── .env
🛠 Technologies Used
Python 3.11+
Streamlit
Google Gemini API
Hugging Face
PyTorch
Transformers
Pillow
OpenCV
python-dotenv
🚀 Installation
1. Clone the Repository
git clone https://github.com/yourusername/AI-Studio.git

cd AI-Studio
2. Create Virtual Environment
Windows
python -m venv venv

venv\Scripts\activate
Linux / macOS
python3 -m venv venv

source venv/bin/activate
3. Install Dependencies
pip install -r requirements.txt
4. Configure Environment Variables
Create a .env file.

GEMINI_API_KEY=YOUR_GEMINI_API_KEY

HF_TOKEN=YOUR_HUGGINGFACE_TOKEN
▶️ Run the Project
streamlit run app.py
The application will open in your browser.

💬 Gemini Chat
Supports:

Multi-turn conversations
Chat history
Context-aware responses
Fast response generation
🖼 Gemini Vision
Upload an image and:

Describe the image
Answer questions about the image
Extract text (OCR)
Explain diagrams
Analyze charts
🎨 Image Generator
Generate images using a text prompt.

Example prompts:

A futuristic AI robot working in a laboratory
A cyberpunk city at sunset
An astronaut riding a horse on Mars
A realistic tiger in a rainforest
🎬 Video Generator
Generate videos from text prompts.

Supported providers depend on your local setup or chosen service.

Example prompt:

A futuristic AI robot walking through a neon cyberpunk city while it rains.

📄 PDF Chat (RAG)
Features:

Upload PDF
Vector embeddings
Semantic search
Question answering
Context-aware responses
🌐 Web Search
Search the web and combine search results with AI-generated answers.

📁 Generated Files
Images are stored in:

generated_images/
Videos are stored in:

generated_videos/
Uploaded files are stored in:

uploads/
📦 requirements.txt
Example:

streamlit
google-genai
huggingface_hub
python-dotenv
pillow
opencv-python
torch
torchvision
transformers
accelerate
numpy
requests
📸 Screenshots
You can add screenshots here after running the application.

Example:

screenshots/

home.png

chat.png

vision.png

image_generator.png

video_generator.png
🔮 Future Enhancements
Voice Assistant
Speech-to-Text
Text-to-Speech
AI Agents
Memory
SQL Chat
CSV Chat
Excel Chat
AI Code Generator
AI Presentation Generator
AI Resume Builder
Docker Deployment
Authentication System
Multi-user Support
🤝 Contributing
Contributions are welcome.

Fork the repository.
Create a feature branch.
Commit your changes.
Push the branch.
Open a Pull Request.
📄 License
This project is licensed under the MIT License.

👨‍💻 Author
Lakshman Ulli

Python Developer
AI & Data Science Enthusiast
Generative AI Developer
⭐ Support
If you found this project useful:

⭐ Star the repository
🍴 Fork the repository
🛠 Contribute improvements
📢 Share it with others
Happy Coding! 🚀