
🛡️ Chrome AI Security Shield

Smart Protection, Powered by Local AI

The Chrome AI Security Shield is a smart web extension designed to protect users in real time using AI threat analysis.
It monitors potential cyber-attacks, detects abnormal web behavior, and issues instant alerts — all locally, without sending user data to the cloud.

🚀 Features

✅ AI-based Threat Detection
Automatically analyzes suspicious activity or code execution on visited pages.

✅ Dynamic Thermal Shield
A visual shield that reacts to threats — it “heats up” when attacks are detected.

✅ Instant Alerts
Audio and visual alerts (custom .wav sound) notify users of detected threats.

✅ User-Controlled Response
With a single click, users can trigger an “antivirus action” to neutralize the threat.

✅ Threat Log Integration (optional)
A built-in AI log system records threat history and can sync with Chrome AI for educational analytics.
🧩 Tech Stack

Manifest V3 (Chrome Extension)

JavaScript (Background + Popup Scripts)

HTML/CSS (Popup UI)

Gemini Nano / Chrome Prompt API (AI integration)

Custom Icons (.png, .ico, transparent design)

WAV Sound Alerts
📁 Project Structure

chrome-ai-security-shield/
│
├── manifest.json
├── background.js
├── popup.html
├── popup.js
├── icons/
│   ├── icon16.png
│   ├── icon48.png
│   ├── icon128.png
│   └── icon128_transparent.png
├── sounds/
│   └── alert.wav
├── README.md
└── LICENSE
🧠 How It Works

1. The background service runs continuously to scan page activity.


2. When an anomaly or potential attack is detected, the AI model rates its severity.


3. The visual shield icon changes effect or color.


4. The alert sound is played.


5. The user can click the extension icon to trigger a defensive action.
👩‍💻 Developer Notes


👩‍💻 Developer Notes

This project was created for an AI & Chrome API educational competition, showcasing the integration of Gemini Nano and Chrome APIs in cybersecurity learning contexts.
📜 License

MIT License — feel free to fork, modify, and contribute.


🇪🇬  العربية

تم تطوير مشروع درع الحماية الذكي بالذكاء الاصطناعي ضمن مسابقة تعليمية خاصة بواجهات برمجة تطبيقات Chrome و Gemini Nano،
بهدف تعزيز الفهم العملي لدمج الذكاء الاصطناعي في الأمن السيبراني والتعلم الرقمي.
يعمل المشروع على تحليل سلوك المواقع في الوقت الفعلي وتنبيه المستخدم فور اكتشاف أي نشاط مشبوه،
مما يجعله أداة تعليمية وتطبيقية في آنٍ واحد.
