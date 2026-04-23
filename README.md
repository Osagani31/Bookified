## 📚 Bookified – AI Voice-Powered Book Interaction Platform

Transform static PDFs into interactive, voice-driven experiences.

# 🚀 Overview

Bookified is an AI-powered platform that allows users to have real-time voice conversations with their books. Instead of passively reading PDFs, users can talk to their documents, ask questions, and receive intelligent responses using natural voice synthesis.

Built with modern technologies like Next.js, Vapi, MongoDB, and ElevenLabs, this project demonstrates how AI can revolutionize digital reading.

# ✨ Features <br>
🎤 Real-time Voice Conversations<br>
Talk directly with your books using AI-powered voice interaction.<br>
📄 PDF Text Extraction<br>
Upload PDFs and convert them into structured, queryable content.<br>
🤖 AI-Powered Responses<br>
Intelligent answers based on extracted document content.<br>
🔊 Natural Voice Synthesis<br>
Human-like voice responses using ElevenLabs.<br>
👤 Authentication System<br>
Secure user login and session management.<br>
🧠 Conversation Memory<br>
Stores session transcripts for future reference.<br>
📚 Personal Library<br>
Manage and organize uploaded books.<br>

# 🛠️ Tech Stack <br>
 # Frontend

Next.js 16
React
Tailwind CSS

# Backend

Node.js
MongoDB

# AI & Voice

Vapi AI
ElevenLabs

# Authentication

Clerk

# Tools & DevOps

WebStorm (IDE)

# 📂 Project Structure
/app <br>
/components <br>
/lib   <br>
/database <br>
/public <br>
/styles <br>


# ⚙️ Installation & Setup
1️⃣ Clone the repository<br>
git clone https://github.com/Osagani31/bookified.git <br>
cd bookified<br>
2️⃣ Install dependencies<br>
npm install<br>
3️⃣ Setup environment variables<br>

Create a .env.local file and add:<br>

MONGODB_URI=your_mongodb_connection <br>
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_key <br>
CLERK_SECRET_KEY=your_secret_key <br>
VAPI_API_KEY=your_vapi_key <br>
ELEVENLABS_API_KEY=your_elevenlabs_key <br>
4️⃣ Run the development server <br>
npm run dev <br>

Open 👉 http://localhost:3000 <br>

# 🔐 Environment Variables
Variable	Description <br>
MONGODB_URI	MongoDB connection string <br>
CLERK_SECRET_KEY	Clerk authentication secret <br>
VAPI_API_KEY	Vapi voice AI API key <br>
ELEVENLABS_API_KEY	Voice synthesis API <br>

# 🧪 Key Functionalities Explained
📄 PDF Processing <br>
Extracts text from uploaded documents <br>
Stores structured data in MongoDB <br>
🎤 Voice Interaction <br>
Converts speech → text <br>
Sends query to AI <br>
Converts response → natural voice <br>
🧠 AI Logic <br>
Context-aware answers based on document content <br>
Maintains conversation history <br>
🚀 Deployment <br>

# You can deploy using:

Vercel (Frontend) <br>
OpenClaw VPS (Full-stack hosting)<br>

# 📸 Screenshots
<img width="1920" height="868" alt="image" src="https://github.com/user-attachments/assets/1f3331f7-2c2f-4327-a47c-5e970c36042b" />
<br>
<img width="1920" height="1805" alt="screencapture-localhost-3000-books-new-2026-04-22-11_48_25 (1)" src="https://github.com/user-attachments/assets/b28b1fe3-ffe5-4215-b9fe-e0cab5211109" />


