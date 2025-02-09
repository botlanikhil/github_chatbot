# github_chatbot
# 🗣️ Voice Assistant for GitHub  

🚀 **Enhance your GitHub workflow with voice commands!**  
This project enables hands-free interaction with GitHub, allowing users to create issues, search repositories, and manage projects using their voice.  

---

## 🔥 Key Features  
✅ **Voice-Controlled GitHub Actions** – Create issues, search repositories, and more  
✅ **Speech-to-Text Conversion** – Converts spoken commands into GitHub API requests  
✅ **Text-to-Speech Responses** – Reads back results using Google TTS  
✅ **Seamless GitHub API Integration** – Automates tasks directly from your voice  
✅ **Customizable & Open-Source** – Easily modify commands and add new features  

---

## 🛠️ Setup & Usage  

### **1️⃣ Install Dependencies**  
```bash
pip install speechrecognition pyaudio pygithub gtts openai-whisper

###**2️⃣ Set Up GitHub Authentication
Generate a GitHub Personal Access Token from GitHub Settings.
Ensure the token has repo permissions.
Save the token in an .env file inside the project folder:
env
Copy
Edit
GITHUB_TOKEN=your_token_here
3️⃣ Run the Voice Assistant
bash
Copy
Edit
python main.py
4️⃣ Use Voice Commands
🎙️ Command	🔧 Action
"Create an issue in repo X"	Creates a new issue in the specified repository
"Search for repository X"	Searches GitHub for a repository
"Exit"	Stops the program
📚 Dependencies
📌 Library	🔍 Purpose
speechrecognition	Converts speech to text
pyaudio	Captures microphone input
pygithub	Connects to GitHub API
gtts	Converts text to speech (optional)
openai-whisper	(Optional) High-accuracy speech recognition
🚀 Future Enhancements
🔹 Add voice commands for pull requests & commits
🔹 Implement AI-powered issue summaries
🔹 Create a user-friendly GUI for easy interaction
🔹 Support for multiple programming languages

📜 License
This project is open-source under the MIT License. Contributions are welcome! 🤝

🤝 Contributing
🔸 Fork the repository
🔸 Create a new branch (git checkout -b feature-branch)
🔸 Commit your changes (git commit -m "Added a new feature")
🔸 Push the branch (git push origin feature-branch)
🔸 Submit a Pull Request 🚀


