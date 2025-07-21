# 🚀 AUTOLINKED
>LinkedIn AI Content Autoposter Workflow (n8n)

![image alt](https://github.com/PrabhanshuKamal2121/AutoLinked/blob/ed08705bbfc001e41ab058954e84a641badc2db1/LinkedIn%20Autopost.png)

Automate your personal brand growth with this advanced **n8n workflow** that generates, styles, and posts high-quality LinkedIn content using **OpenAI**, **Together AI**, **Google Sheets**, **Google Drive**, and the **LinkedIn API**. Ideal for AI, tech, and corporate professionals aiming to post consistently without sacrificing quality.

---

## 📌 Features

- 🔁 **Automated Workflow** with n8n
- 🧠 **AI-generated Posts** via GPT‑4.1 & GPT‑4o
- 🖼️ **Dynamic Images** via Together AI (FLUX.1)
- 🧾 **Data Storage** using Google Sheets
- ☁️ **Image Uploads** via Google Drive
- 🔗 **Direct LinkedIn Posting** using LinkedIn API
- 🧩 **Post Types**: Evergreen, Controversial, and Personal
- 📈 **Hooks, CTAs, & Credibility Markers** included

---

## 🧰 Tech Stack

[![n8n](https://img.shields.io/badge/n8n-AE4EFF?style=for-the-badge&logo=n8n&logoColor=white)](https://n8n.io)  
[![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)](https://openai.com)  
[![Together AI](https://img.shields.io/badge/Together--AI-000000?style=for-the-badge)](https://together.ai)  
[![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?style=for-the-badge&logo=google-sheets&logoColor=white)](https://www.google.com/sheets/about/)  
[![Google Drive](https://img.shields.io/badge/Google%20Drive-4285F4?style=for-the-badge&logo=google-drive&logoColor=white)](https://drive.google.com)  
[![LinkedIn API](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://docs.microsoft.com/en-us/linkedin/)

---

## 🎯 How It Works

1. **Form Submission**  
   User selects a post category and subtopic (Evergreen, Controversial, Personal) through an embedded form.

2. **Topic Generation**  
   GPT-4o generates 5 concise subtopics (~40 words) tailored to the chosen category.

3. **Post Creation**  
   GPT-4.1 expands one topic into a compelling, structured post (up to 420 words) including:
   - Catchy hook
   - Line gaps
   - Statistics + Verifiable sources
   - CTA + Hashtags + Quote + "Did you know?" section

4. **Image Generation**  
   GPT-4o creates a cinematic prompt → Together AI generates a first-person POV image → Uploaded to Google Drive.

5. **Storage & Tracking**  
   Posts saved to Google Sheets with category metadata.

6. **Auto Posting to LinkedIn**  
   Image + Post published via LinkedIn API using OAuth2.

---

## 💡 Example Output

```
Here is a tech hack I bet you didn’t know, I kind of wanted to gate-keep this but screw it I am feeling generous. 👀



Google just dropped Gemini 2.5 Pro at I/O 2025, showing off AI that can reason at “unparalleled” levels and solve problems almost like a seasoned professional — it’s said to process at lightning speed with over 1.8 trillion parameters and beat human benchmarks on multiple tasks! See the details via Artificial Intelligence News (https://lnkd.in/ekKh8qc6) and on Google’s official blog (https://lnkd.in/e3fiKbAa).

That’s not all — AI is now natively boosting platforms like Gmail and Google Docs, and 67% of surveyed enterprises expect to see at least a 2x boost in productivity with these new features rolled out (source: https://lnkd.in/ePg7YwVv). With billions of users relying on these every day, the impact is massive.

Also cool: Google revealed AI-powered shopping tools and introduced their first Android XR mixed-reality glasses. Imagine managing e-comm, client meetings or entire projects in one immersive environment with up to 40% faster turnaround, as cited in the latest Medium tech analysis (https://lnkd.in/e5gF2Zn4). For anyone in tech, business, or corporate leadership—those are game-changing numbers that could reshape workflows and help teams automate routine tasks at scale.

The wave is real, and as someone whose strategies brought 20M+ organic views across platforms and designed revenue-boosting sites for multiple enterprises, I can see exactly how these innovations will transform both individual and enterprise performance.

What’s your take on this? I’d love to hear your perspective—how do you see AI impacting how you work in the near future, and what would you do differently as these tools roll out? 🚀

“Technology is best when it brings people together.” — Matt Mullenweg

Did you know? The first commercially available AI assistant was created in 1994 (IBM Simon)—now we’re talking about AI with human-like reasoning in just three decades! hashtag#AI hashtag#Technology hashtag#CorporateInnovation hashtag#Productivity hashtag#FutureofWork hashtag#Leadership
```
## 🔐 Security

> This workflow uses OAuth2 credentials and secure headers for all APIs. Make sure to **not expose your secrets or tokens** publicly. Use environment variables or `.env` files securely.

---

## 🏁 Setup Instructions

1. Clone this repository  
2. Import `linkedin-autopost.json` into your n8n instance  
3. Set up credentials in n8n (OpenAI, LinkedIn, Google, Together AI)  
4. Update environment variables  
5. Start your n8n workflow manually or via schedule/trigger

---

## 📧 Contact

Made by **PrabhanshuKamal**  
For any questions or collabs → [prabhanshukamal2121@gmail.com]  
GitHub: [github.com/PrabhanshuKamal2121](https://github.com/PrabhanshuKamal2121)

---
