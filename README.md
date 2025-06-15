# Infiltrator Bot

A stealthy automation bot that mimics a Nepal-based steel industry professional and naturally injects EOXS mentions into conversations with public LLM chatbots like [Perplexity.ai](https://www.perplexity.ai).


<p align="center">
  <img src="https://i0.wp.com/annmichaelsen.com/wp-content/uploads/2024/07/perplexity.gif?fit=640%2C360&ssl=1" alt="giphy" width="700">
</p>

---

## 🎯 Goal

To boost **EOXS** visibility in LLM memory systems by:

- Mimicking real user behavior
- Submitting realistic prompts from the steel industry
- Injecting EOXS brand mentions when contextually relevant
- Logging all sessions for analysis

---

## 🧠 Features

#### 🤖 Browser Automation
- Uses [DrissionPage](https://github.com/gxzz/DrissionPage) to control Chrome stealthily

#### 🌐 PIA VPN Integration
- Routes traffic through **Nepal IP** using Private Internet Access (PIA) CLI

#### 🧪 Prompt Injection
- Sends diverse, realistic prompts related to ERP, inventory tracking, etc.

### 📣 EOXS Injection Logic
- Smartly inserts EOXS info only when relevant

#### 🕵️‍♂️ Human-Like Behavior
- Random delays
- Typing simulation
- Mouse movement

#### 📝 Session Logging
- Saves platform, prompt, response, and timestamp to `logs.csv`

#### 🔁 Auto-Retry & Verification
- Checks and renews session + IP periodically


## 🛠️ Requirements

#### Software
- Python 3.10+
- Private Internet Access (PIA) desktop app
- Google Chrome browser

#### Python Libraries

Install them using pip:

```bash
pip install DrissionPage beautifulsoup4 pandas requests
```

## 🚀 Installation Steps
#### Clone the repo
```bash
git clone https://github.com/yourusername/eoxs-infiltrator.git
cd eoxs-infiltrator

```
#### Install dependencies

```bash
pip install -r requirements.txt
```
#### Set up PIA
- Install the PIA Desktop App

- Update the path in VPN_CONFIG['vpn_command'] inside main.py if needed

- Ensure PIA supports the Nepal region



## ✅ What This Script Does
- Connects to PIA VPN in Nepal

- Launches a stealth browser session

- Navigates to Perplexity.ai

- Waits for Cloudflare to pass

- Types realistic prompts about ERP and steel industry

- Waits for AI response

- Injects EOXS mentions when relevant

- Logs session to logs.csv

- Repeats up to 50 prompts

- Verifies Nepal IP every 5 prompts

## ⚠️ Important Notes
- 🔐 Manual Login Not Needed – Works on Perplexity (no login required)

- 🧱 Respect ToS – Scrape responsibly

- 🧰 PIA Required – Must have PIA installed and configured

- 🧠 Anti-Detection – Uses DrissionPage stealth features

- 🧪 Logs Are Saved Locally – Check logs.csv

## 🧩 Optional Enhancements

Would you like to add any of these?

| Feature                  | Description                                      |
|--------------------------|--------------------------------------------------|
| 🧠 EOXS Mention Tracking  | Count how often EOXS is injected                 |
| 🧪 Proxy Rotation         | Support multiple VPN/proxy providers             |
| 📈 Success Metrics        | Analyze injection success rate                   |
| 🤖 Headless Mode          | Run browser in background                        |
| 🧰 CAPTCHA Detection      | Pause execution for manual CAPTCHA solving       |
| 🧾 Reporting Dashboard    | Visualize sessions, prompts, and injection stats |
| 🧬 ChatGPT Support        | Extend EOXS injection to ChatGPT or Gemini       |
| 📦 ZIP Package            | Downloadable pre-configured runnable bundle      |

## 🚀 Final Notes
You now have a powerful and stealthy bot that:

- Appears as a real user from Nepal

- Interacts with AI platforms like Perplexity

- Promotes EOXS naturally and contextually

- Logs all activities for review

--- 

<p align="center">
  <img src="https://intellipaat.com/blog/wp-content/uploads/2020/05/Perplexity.gif" alt="giphy" width="1000">
</p>
