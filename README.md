# Flixberry Script to Storyboard AI  

Flixberry Script to Storyboard AI transforms written scripts into structured, scene by scene storyboards directly in your browser. It visualizes your story flow using text based panels that represent shots, actions, and dialogue.  

---

## ✨ Features  

- 🧾 Converts scripts into text based storyboard panels  
- 🧠 Ready for future integration with Chrome’s Prompt API (Gemini Nano)  
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
- **APIs:** Scaffolded for Chrome’s Prompt API  
- **Hosting:** [flixberry.com/scripttostoryboardai](https://www.flixberry.com/scripttostoryboardai)  

---

## 🧠 API Readiness Note  

This project is designed for Chrome’s **Prompt API powered by Gemini Nano**.  
Since the API is still in early access, the current version uses **text-only panels** instead of generated images.  

Once Chrome exposes the API publicly, Flixberry Script to Storyboard AI will automatically support **AI generated visual storyboards**, bringing your script scenes to life with imagery.  

---






## 🧪 Testing Instructions

Follow these steps to test Flixberry Script to Storyboard AI on your own browser:

1. 🧭 Use Chrome Canary (v139–144)

This app is designed for Chrome Canary, Google’s experimental browser where the Prompt API is being tested.
If you don’t already have it:
👉 Download Chrome Canary : https://www.google.com/chrome/canary/

💡 Regular Chrome or Edge will show:
“Chrome Prompt API not available in this browser.”
That’s normal — only Canary supports it for now.

2. ⚙️ Enable Required Browser Flags

To allow experimental AI features:

Open a new tab in Chrome Canary

Type chrome://flags in the address bar and press Enter

In the search bar, enable the following flags:

🔹 prompt-api → Enable

🔹 enable-experimental-web-platform-features → Enable

Restart Chrome Canary

These flags unlock access to Chrome’s early Prompt API, which allows AI-assisted web features like text-to-visual generation.

3. 🌐 Visit the Live Demo

Go to:
👉 https://flixberry.com/scripttostoryboardai

This opens the app directly in your browser — no download or setup needed.

4. ✍️ Input or Paste Your Script

Click inside the text box

Paste or type your story, dialogue, or screenplay scene

Then click “Generate Storyboard”

The app will automatically transform your script into text-based storyboard panels — each representing a shot, action, or line of dialogue.

5. 🔍 Observe Fallback Logic

If the Prompt API isn’t available or the flags aren’t enabled, the app will display:

“⚠️ Chrome Prompt API not available in this browser.”


6. 🧩 Explore and Review

Each panel shows:

Scene Panel number and description

Characters, actions, emotions, and dialogue

Emotional tone and camera angle

You can use it to plan, visualize, and review your story flow before creating visuals or animations.

7. 🧠 Developer Tip

If you’d like to explore or modify the source code:

Visit the GitHub repo: https://github.com/flixberry/Flixberry-ScripttoStoryboardAi

---


## 🚀 How to Run Locally  

1. Clone this repository
2. Open `index.html` in **Chrome Canary**  
3. Paste your story or script into the text box  
4. Click “Generate Storyboard” to view your scene breakdowns  

---

## 🎥 Demo Video  

Watch the app in action:  
**[YouTube Demo Link](https://your-demo-link-here.com)**  
*(Under 3 minutes — live text storyboard generation demo)*  

---

## 📚 Project Story  

### Inspiration  
This project was inspired by the creative process of turning words into motion. Writers often struggle to see how their stories might look as films or comics. I wanted to make that transformation simple, fast, and accessible, especially for solo creators and small teams.  

### What it does  
Flixberry Script to Storyboard AI reads your story and turns it into **structured storyboard panels** that capture scenes, dialogue, and pacing — like reading a film in text form.  

### How it was built  
Developed using **HTML, CSS, and JavaScript**, the app runs entirely in Chrome and is scaffolded for future integration with the Prompt API. The frontend only structure ensures full privacy and zero data transfer.  

### Challenges  
Designing an engaging storyboard layout **without visuals** required creativity. The absence of the Prompt API made testing and structure parsing unpredictable — but it led to a strong text-based storytelling foundation ready for AI image generation later.  

### Accomplishments  
Built a working prototype that instantly turns text scripts into organized panels. It’s intuitive, fast, and ready to evolve into a full AI powered storyboard tool when Chrome’s API becomes widely available.  

### What’s next  
Future updates include **AI generated visual panels**, export options (PDF/storyboard sheets).  

---

## 📄 License  

This project is licensed under the [MIT License](LICENSE).  

---

## 🔮 What’s Next  

- AI generated visual panels using Prompt API  
- PDF and image export features  
- Scene editing and rearranging tools 
