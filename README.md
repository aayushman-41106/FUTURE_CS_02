# 🔐 Phishing Email Detection & Awareness System

## 📌 Overview
This project focuses on analyzing real-world financial phishing emails and creating awareness to prevent cyber attacks. It simulates the work of a Security Analyst by identifying technical phishing indicators, uncovering spoofed domains, and explaining the attack mechanics in simple terms.

---

## 🎯 Objective
- Analyze real-world phishing email samples (`.eml` files)
- Identify phishing indicators and psychological triggers
- Perform header analysis to detect spoofing
- Classify email risks 
- Create actionable security awareness guidelines

---

## 🛠️ Tools Used
- Kali Linux
- Google Message Header Analyzer
- Browser Developer Tools (URL Inspection)
- Text Editor (Raw `.eml` analysis)

---

## 📧 Email Analysis

### 1. Axis Bank Impersonation Scam
- Brand impersonation (Axis Bank)
- False promise of a ₹2,35,900 credit limit
- Hidden malicious tracking link (`mc.tripshrip.com`)
👉 **Risk: PHISHING**

---

### 2. Credit Score / Personal Loan Trap
- Psychological trigger (Greed: ₹30,20,000 loan)
- Display name spoofing ("e-Pdf Statement")
- Malicious embedded image link
👉 **Risk: PHISHING**

---

### 3. Flexiloan Business Loan Scam
- Targeting business owners (MSME Loan)
- False sense of urgency/ease ("Zero Paper Work")
- Suspicious sender address
👉 **Risk: PHISHING**

---

### 4. Fake Loan Approval Notification
- Image-based payload (entire email is a clickable image)
- Confusion tactic (Approval for an unrequested loan)
- Malicious redirect hidden in the image
👉 **Risk: PHISHING**

---

## 🌐 Domain Analysis

### ✔ Legitimate Domain
- `axisbank.com`
- Verified ownership
- Trusted financial institution

### ❌ Suspicious Domain
- `tripshrip.com`
- Mismatch between display name and actual sender
- Used for tracking and potential credential harvesting

---

## 📊 Header Analysis
- **Display Name Spoofing:** Senders appear as official banks but originate from unrelated domains.
- **Sender Mismatch:** The `From:` display name contradicts the actual `Return-Path:`.
- **Suspicious Routing:** Emails routed through non-standard servers attempting to bypass spam filters.

---

## 🚨 Common Phishing Indicators
- Urgency, fear, or extreme greed tactics
- Fake sender domains mimicking trusted brands
- Suspicious masked links (CTAs redirecting to unknown sites)
- Unsolicited financial offers

---

## 🛡️ Prevention Tips

### ✅ Do’s
- Verify the true sender by expanding the email details
- Hover over buttons and links before clicking to inspect the destination URL
- Navigate manually to official banking websites

### ❌ Don’ts
- Don’t let urgency or greed rush your decisions
- Don’t click on emails that are entirely composed of a single image
- Don’t provide financial credentials through email links

---

## 📸 Screenshots
- Raw `.eml` File Inspection
- Google Message Header Analysis
- Mismatched Sender Domain Proof
- Malicious URL Hover Proof

---

## 📂 Project Structure

FUTURE_CS_02/  
│── [IMP. MSG]⚡️Your Feb'24 𝐂𝐫𝐞𝐝𝐢𝐭.𝐒𝐜𝐨𝐫𝐞...eml  
│── IMP_ Activate your new 𝐋𝐢𝐟𝐞𝐓𝐢𝐦𝐞 𝐅𝐫𝐞𝐞 𝐀𝐱𝐢𝐬...eml  
│── ✍️ RefID_ FL98XX_2024_3422...eml  
│── Your Loan Application No. MSME_2024_FebXX...eml  
│── Phishing_Email_Detection_Report.pdf  
│── README.md  

---

## 🚀 Outcome
This project demonstrates how sophisticated financial phishing attacks bypass user scrutiny using brand impersonation and psychological triggers, and how users can identify and prevent them effectively.

---

## 👩‍💻 Author
**AaYuushman Parab**

CyberSecurity Intern

