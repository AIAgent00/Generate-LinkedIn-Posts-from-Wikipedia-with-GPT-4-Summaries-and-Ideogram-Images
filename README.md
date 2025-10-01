<img width="711" height="370" alt="image" src="https://github.com/user-attachments/assets/68e44166-8b77-40dd-8fc3-d51ad83425cc" />

# 🤖 Wikipedia → LinkedIn AI Content Poster with Image (via Bright Data)

Automatically scrape Wikipedia articles, generate AI-powered LinkedIn summaries ✍️, create professional visuals 🎨, and post them directly to LinkedIn 💼 — all in one seamless **n8n workflow** powered by Bright Data + AI.

---

## 📋 Overview
**Workflow Description:**  
This automation takes a Wikipedia article name, extracts the content, summarizes it into a professional LinkedIn post, generates a custom AI image, and publishes it automatically.

---

## 🚀 How It Works
1. 📝 **Article Input** → User submits a Wikipedia article name through a simple form  
2. 🌐 **Data Extraction** → Bright Data scrapes the full article text & title  
3. 🤖 **AI Summarization** → GPT-4 (or Claude) creates a LinkedIn-ready summary under 2000 characters  
4. 🎨 **Image Generation** → Ideogram AI generates a high-quality visual  
5. 💼 **LinkedIn Publishing** → Posts summary + image directly to your LinkedIn profile  
6. 🔗 **URL Generation** → Returns a shareable LinkedIn post link  

---

## ⚡ Setup Requirements
⏱️ Estimated Setup Time: *10-15 minutes*  

### Prerequisites
- 🛠️ **n8n instance** (self-hosted or cloud)  
- 🌐 **Bright Data** account (Wikipedia dataset access)  
- 🤖 **OpenAI API** (GPT-4 access)  
- 🔮 **Anthropic API** (Claude access - optional)  
- 🎨 **Ideogram AI** account (image generation)  
- 💼 **LinkedIn API** account  

---

## 🔧 Configuration Steps

### Step 1: Import Workflow
- Copy the provided **JSON workflow file**  
- In **n8n**: `Workflows → + Add workflow → Import from JSON`  
- Paste JSON → Click *Import* → Save  

### Step 2: Configure API Credentials
- 🌐 **Bright Data** → Add API key in credentials → Replace `BRIGHT_DATA_API_KEY`  
- 🤖 **OpenAI** → Add GPT-4 credentials → Link to "OpenAI Chat Model" node  
- 🎨 **Ideogram AI** → Replace `IDEOGRAM_API_KEY` in "Image Generate" node  
- 💼 **LinkedIn** → Configure OAuth2 → Replace `LINKEDIN_PROFILE_ID`  

### Step 3: Configure Workflow Parameters
- 📝 **Form Trigger** → Customize labels & instructions  
- 🤖 **AI Agent** → Adjust tone/style (professional, casual, technical)  
- 🎨 **Image Node** → Set resolution & style preferences  
- 💼 **LinkedIn Post** → Add hashtags, mentions, etc.  

### Step 4: Test the Workflow
✅ Start with a simple article (e.g., *Artificial Intelligence*)  
✅ Monitor execution logs in n8n  
✅ Verify summary, image & LinkedIn post  

---

## 🎯 Usage Instructions
- Access the **form webhook URL**  
- Enter an article name  
- Submit & watch automation run  
- 🎉 Get a shareable **LinkedIn post URL** at the end  

---

## 📌 Expected Output
### 📝 Content Summary
- LinkedIn-optimized text (≤2000 chars)  
- Professional & engaging tone  
- Can include bullet points ✅  

### 🖼️ Generated Image
- High-quality AI image  
- Default: **1280x704 resolution**  
- Relevant & professional  

### 🔗 LinkedIn Post
- Auto-published with summary + image  
- Shareable **public URL**  

---

## 🛠️ Customization Options
- ✍️ **Content Style** → Change AI system prompt for tone (casual, technical, inspiring)  
- 🔖 **Hashtags** → Auto-add industry hashtags  
- 🎨 **Image Style** → Customize Ideogram prompts for branding/logo colors  
- 📏 **Character Limit** → Adjust summary length  

---

## 🔍 Troubleshooting
⚠️ **Bright Data Issues** → Check API key, dataset access & credits  
🤖 **AI Errors** → Verify API quotas, simplify input text  
🎨 **Image Failures** → Check Ideogram API key, reduce prompt complexity  
💼 **LinkedIn Issues** → Re-authenticate OAuth, confirm profile ID  

---

## ⚡ Performance & Limitations
- ⏱️ Processing Times:  
  - Wikipedia Scraping: 30-60s  
  - AI Summarization: 15-30s  
  - Image Generation: 45-90s  
  - LinkedIn Posting: 10-15s  
  - **Total Workflow:** 2-4 mins per article  

- 🔑 Best Practices:  
  - Use well-known Wikipedia topics  
  - Monitor API usage across services  
  - Avoid posting too frequently on LinkedIn  

---

## 📊 Use Cases
📚 **Educational Content** → Share science, history, or tech insights  
🏢 **Thought Leadership** → Turn research into industry-focused posts  
📰 **Content Marketing** → Maintain active presence with minimal effort  
🔬 **Research Sharing** → Quickly summarize & publish discoveries  

---

## 🎉 Final Note
This workflow is your **AI-powered content assistant** 🤖 helping you:  
- Save time ⏳  
- Stay consistent on LinkedIn 💼  
- Share professional, engaging content 📢  

---

👨‍💻 **Built with n8n + Bright Data + OpenAI + Ideogram + LinkedIn API**  
