![image](https://github.com/user-attachments/assets/e1ccd982-c6b4-4d89-85fd-0c80b5034bba)

# 🎤 SpeechSync AI

Passionate about empowering global communication? 🌍  
Help us build the ultimate **AI Speech Coach**! 🚀

Contributions welcome! ✨

---

## 👀 What is this?

Boost your English skills for global remote work with **SpeechSync.ai**. 🌎🗣️  
It's like having a personal pronunciation coach right in your pocket! 🎧

🎤 **Record your speech** and get instant **AI-powered feedback**.

> Many international students struggle with English pronunciation, limiting their remote work opportunities.  
> Traditional language apps don't focus on real-world speaking skills — SpeechSync.ai fixes this gap! 🎯

---

## ⚡ Key Features
- 🎤 **Real-time Recording**: Capture your speech easily with React Media Recorder.
- 🤖 **AI-powered Analysis**: Get accurate transcriptions using Whisper ASR.
- 📊 **Detailed Feedback**: Receive comprehensive pronunciation assessments from GPT-3.5.
- 🎯 **Personalized Improvement**: Get tailored recommendations to enhance your English.

---

## 🚀 How do I use this?

1. Visit 👉 [speechsync.ai](https://speechsync-ai.pages.dev/)
2. Click on `Get Started` to reach the main page.
3. Record, listen, improve — repeat! 🔥

---

## 🛠️ What's under the hood?

### 📁 `src/apps`: The main web UI

Built with:
- ⚡ Next.js 14
- 🎨 [TailwindCSS](https://tailwindcss.com)
- 🧹 [shadcn-ui](https://ui.shadcn.com)
- ☁️ Hosted on [Cloudflare Pages](https://pages.cloudflare.com/)

---

### 🧠 `apps/cf-ai-backend`: AI Response Generation Engine

This is where the magic happens! 💫

Built with:
- 🛠️ [Cloudflare Workers](https://workers.cloudflare.com/)
- 🧠 [Cloudflare AI](https://ai.cloudflare.com/)

---

## 🤝 How can I contribute?

1. 🍴 Fork this repo
2. 📅 Clone your forked repo
3. 🌿 Create a new branch
4. 🛠️ Make your changes
5. 🚀 Push your changes to your branch
6. 📬 Create a pull request

Let's make global communication better together! 🌟

---

## 🛠️ Setup Instructions

1. Clone the repo:
```bash
git clone git@github.com:arre-ankit/speechsync-ai.git
```

2. Set up the Next.js app:
```bash
npm install @cloudflare/next-on-pages
npm run dev
```

3. Set up the Cloudflare Worker Backend:
```bash
cd cf-backend-worker
npm run dev
```

4. Create `.env` file in the root of the project and add:
```bash
NEXT_PUBLIC_BASE_URL=http://localhost:3000
```

---

## 👨‍💻 Developers

Made with ❤️ by:
- **Sandeep Sharma** 🚀
- **Harinder Singh** 🛠️

---

> 🌟 *Empower your voice, unlock global opportunities with SpeechSync AI!* 🌟