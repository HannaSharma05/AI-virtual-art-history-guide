The AI Virtual Art History Guide is a full-stack conversational chatbot designed to make learning art history more interactive and accessible. The idea was to create a virtual guide that can answer users' questions about artists, paintings, art movements, historical periods, and artistic techniques using natural language.


🚀 Key Features

🤖 AI‑Powered Answers	Uses Gemini 1.5 Pro to generate accurate, detailed responses about art periods, artists, techniques, and artworks

🌍 Multilingual Support	Seamlessly switch between English, Hindi, Spanish, and French—all UI elements and responses adapt instantly

🎤 Voice Input	Speak your questions using the browser's Web Speech API—perfect for hands‑free exploration

💾 Conversation Memory	Chat history persists in local storage, so you never lose context even after refreshing the page

🎨 Daily Masterpiece	Each day features a new artwork with image, title, artist, and period—a mini art calendar built in.


🌓 Mood‑Based Theming	Choose from Serene, Scholarly, Vibrant, or Classic themes—each changes the entire visual mood

🌙 Dark Mode	Toggle between light and dark themes for comfortable viewing anytime



🛠️ Tech Stack

Frontend

HTML5 – Semantic structure

CSS3 – Custom properties, Grid/Flexbox, transitions

Vanilla JavaScript (ES6+) – Lightweight, no frameworks

Font Awesome – Iconography

Web Speech API – Voice recognition


Backend

Python 3.8+ – Core language

Flask – Web framework

Flask‑CORS – Cross‑origin resource sharing

Google Generative AI (Gemini 1.5 Pro) – AI model

python‑dotenv – Environment variable managemen

The chatbot also maintains conversation history on the client side using DOM-based data binding and localStorage, allowing users to revisit previous interactions even after refreshing the page.
