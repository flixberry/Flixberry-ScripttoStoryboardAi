# 🎬 Flixberry Script to Storyboard AI  

Flixberry Script to Storyboard AI transforms written scripts into structured, scene-by-scene storyboards — directly in your browser.  
It visualizes your story flow using **text based panels** that represent shots, actions, and dialogue.  

---

## ✨ Features  

- 🧾 Converts scripts into text based storyboard panels  
- 🛡️ Privacy-first: runs locally, no backend or data sharing  
- 🎬 Designed for storytellers, screenwriters, and indie creators  
- ⚡ Instant browser based experience — no setup or install needed  

---

## 🧩 Problem Solved  

Turning written stories into visual structure can be challenging without artists or expensive tools.  
Flixberry Script to Storyboard AI bridges that gap by generating **panel-style breakdowns** from your script, helping you visualize pacing, dialogue, and flow even before any art is created.  

---

## 🛠️ Built With  

- **Languages:** HTML, CSS, JavaScript  
- **Platform:** Chrome Canary (Prompt API preview)  
- **Architecture:** Frontend-only, privacy-first  
- **APIs:** Chrome’s Prompt API  
- **Hosting:** [flixberry.com/scripttostoryboardai](https://www.flixberry.com/scripttostoryboardai)  

---

## 🧠 API Readiness Note  

This project is designed for Chrome’s **Prompt API powered by Gemini Nano**.  
Since the API is still in early access, the current version uses **text-only panels** instead of generated images.  

Once Chrome exposes the API publicly, Flixberry Script to Storyboard AI will automatically support **AI-generated visual storyboards**, bringing your script scenes to life with imagery.  

---

## 🧪 Testing Instructions  

Follow these steps to test Flixberry Script to Storyboard AI in your browser:

### 1. 🧭 Use Chrome Canary (v139–144)  
This app is designed for Chrome Canary — Google’s experimental browser where the Prompt API is being tested.  
👉 [Download Chrome Canary](https://www.google.com/chrome/canary/)  

💡 Regular Chrome or Edge will show:  
> “Chrome Prompt API not available in this browser.”  
That’s normal — only Canary supports it for now.

---

### 2. ⚙️ Enable Required Browser Flags  

To allow experimental AI features:  

1. Open a new tab in Chrome Canary  
2. Type `chrome://flags` and press **Enter**  
3. In the search bar, enable the following flags:  
   - `prompt-api` → **Enable**  
   - `enable-experimental-web-platform-features` → **Enable**  
4. Restart Chrome Canary  

These flags unlock access to Chrome’s early Prompt API for AI-assisted features like text-to-visual generation.  

---

### 3. 🌐 Visit the Live Demo  

👉 [https://flixberry.com/scripttostoryboardai](https://flixberry.com/scripttostoryboardai)  

No installation — runs instantly in your browser.  

---

### 4. ✍️ Input or Paste Your Script  

- Click inside the text box  
- Paste or type your story, dialogue, or screenplay scene  
- Click **“Generate Storyboard”**  

The app will automatically transform your script into **text-based storyboard panels** representing each shot, action, or line of dialogue.  

---

### 5. 🔍 Observe Fallback Logic  

If the Prompt API isn’t available or the flags aren’t enabled, the app will display:  
> ⚠️ “Chrome Prompt API not available in this browser.”

---

### 6. 🧩 Explore and Review  

Each generated panel includes:  
- Scene panel number and description  
- Characters, actions, and expressions  
- Dialogue and tone  
- Camera angle or mood cues  

You can use it to **plan, visualize, and refine your story flow** before adding visuals or animation.  

---

### 7. 🧠 Developer Tip  

Want to explore or modify the source?  
🔗 [GitHub Repo](https://github.com/flixberry/Flixberry-ScripttoStoryboardAi)  

---

## 🚀 How to Run Locally  

1. Clone this repository  
2. Open `index.html` in **Chrome Canary**  
3. Paste your story or script into the text box  
4. Click **“Generate Storyboard”** to view your scene breakdowns  

---

## 🎥 Demo Video  

Watch the app in action:  
**[YouTube Demo Link](https://youtu.be/Sg6HA_n8w3U?si=x5U99SDc1Lfz6hF4)**  
*(Under 3 minutes — live text storyboard generation demo)*  

---

## 📚 Project Story  

### 💡 Inspiration  
This project was inspired by the challenge of turning imagination into structure, the bridge between writing and visual storytelling. Many writers and filmmakers struggle to picture how their words translate to the screen or page. We wanted to make that transformation simple, fast, and accessible, especially for solo creators and small teams. 

---

### 🎭 What It Does  
Flixberry Script to Storyboard AI reads your story and turns it into **structured storyboard panels** capturing scenes, dialogue, and pacing — like reading a film in text form.  

---

### 🧱 How It Was Built  
Developed using **HTML, CSS, and JavaScript,** the app runs entirely in **Chrome Canary** and leverages the **Prompt API** to convert text scripts into structured storyboard panels. It operates fully on the frontend, ensuring complete user privacy and zero data transfer. The system was designed with modularity in mind, ready to expand into multimodal AI with visual storyboard generation in future versions.

---

### ⚔️ Challenges  
Designing an engaging storyboard layout using the Prompt API required careful structuring and testing. While the API performed well for generating text based panels, adding AI generated images for every panel would have made the process slow and resource heavy. We focused instead on optimizing the storytelling flow and accuracy of the text output, building a strong foundation that can easily support image generation in future updates.

---

### 🏆 Accomplishments  
We built a working prototype that instantly turns plain scripts into well organized storyboard panels. It’s intuitive, efficient, and future ready, a strong foundation for the next stage of AI assisted storytelling tools.

---

### 🔮 What’s Next  
We plan to integrate AI generated visual storyboards, improved PDF and sheet exports, and smarter scene breakdowns for filmmakers, animators, and novelists. The goal is to evolve Flixberry script to storyboard AI into a complete script to screen visualization tool, bringing every creator’s vision closer to life.

---

## 📄 License  

This project is licensed under the [MIT License](LICENSE).  

---
