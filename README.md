# ScamShield 🛡️

AI-Powered SMS/WhatsApp Scam Detection for Malaysians

Built for: Be U by Bank Islam × UMPSA Hackathon 2026  
Track: Track 1 - Reimagine Money

## 🎯 What is ScamShield?

ScamShield detects scams in real-time. Paste a suspicious message, and our AI instantly tells you:
- Is it a scam? (Risk score 1-10)
- Why is it suspicious? (Red flags found)
- What should you do? (Clear explanation)

## 🚀 How to Use

1. Open `scamshield.html` in your browser
2. Paste a suspicious message
3. Click "Analyze"
4. Get instant results with risk score, red flags, and explanation

## ✨ Features

✅ AI-powered scam detection (built-in algorithm)  
✅ Malaysian-context aware (Maybank, CIMB, BNM scams)  
✅ Risk scoring system (1-10)  
✅ Red flag analysis  
✅ Detection history tracking  
✅ Safety tips and emergency hotlines  
✅ Works offline  
✅ Mobile responsive  
✅ No dependencies - just open and use  

## 🧪 Try It Now

Open `scamshield.html` in any browser. No installation needed!

### Test Messages:

*High Risk:*
```
Maybank Alert: Your account will be suspended immediately. Verify: bit.ly/verify123
```
Expected: Risk 9/10, Multiple red flags

*Low Risk:*
```
Your order #12345 is ready for pickup. Store hours: 10am-9pm daily.
```
Expected: Risk 1/10, No flags

## 🛠️ Technology Stack

- Frontend: HTML5, CSS3, JavaScript
- AI Algorithm: Built-in scam pattern detection
- Optional: Claude API integration ready (see code)
- Storage: Browser local storage (privacy-first)

## 📊 How It Works

The app analyzes messages for:
- Urgency language ("Act now", "Limited time")
- Shortened URLs (bit.ly, tinyurl)
- Bank impersonation (Maybank, CIMB, RHB)
- Personal data requests (password, OTP, IC)
- Prize/reward offers
- Investment fraud indicators
- Job offer scams
- Account threats
