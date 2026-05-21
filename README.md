🛡️ VeraHire — AI-Powered Candidate Fraud Screener
> *"Verify before you hire."*
> Built by a tech recruiter, for tech recruiters — because a perfect resume means nothing if the person behind it isn't real.
---
The Problem (From Someone Who's Lived It)
After 10+ years in IT and corporate staffing, I kept running into the same costly fraud patterns:
Resumes written word-for-word to mirror the job description — zero real depth behind them
Proxy interviews — someone aces the screen, a different person shows up on day one
AI-generated resumes that are polished, keyword-rich, and completely hollow
Visa misrepresentation — H1B, OPT, CPT status that doesn't hold up to scrutiny
Body shop vendors submitting the same consultant through five different agencies
Skills claims that are technically impossible given the timeline on the resume
Hiring managers lose hours. Companies waste money. Real candidates lose opportunities to fraudsters.
VeraHire was built to fix that.
---
What It Does
VeraHire is an AI-powered screening tool that analyzes candidate resumes and documents across 10 fraud dimensions — before a single interview is scheduled.
🔍 The 10 Fraud Signals
Signal	What It Catches
JD Fabrication	Resume written to mirror the job description, not real experience
Proxy Interview Risk	Skills that don't match claimed years; someone else likely interviewing
AI / Copied Resume	ChatGPT-style language, identical bullet structure, no personality
Fake Experience	Timeline gaps, unverifiable employers, impossible promotions
Visa Mismatch	Authorization status inconsistent with location, dates, or claims
Job-Hop Pattern	Every 4–6 months, always "contract ended" — proxy farm signals
Skills Timeline	Claiming years of experience in technology that didn't exist that long ago
Location Mismatch	Resume, LinkedIn, and availability don't align
Body Shop / Vendor	Generic formatting, coordinator-written summaries, vendor fingerprints
Rate vs Experience	Senior title asking below-market rate — fabrication or large vendor cut
🪪 Document Verification
Upload government-issued IDs and immigration documents for AI authenticity analysis:
US Driver's License, Passport, State ID, Social Security Card
H1B Approval Notice (I-797), EAD Card, Green Card, I-140, OPT/CPT, TN Visa
The AI checks formatting standards, font consistency, security features, date logic, case number formats, and signs of digital alteration.
> ⚠️ **Legal note:** Per IRCA and I-9 regulations, identity documents should only be requested at the point of hire — not during pre-screening. Always confirm legal hiring decisions through [E-Verify](https://www.e-verify.gov) or [USCIS](https://egov.uscis.gov).
📋 Interview Question Generator
Paste any job description → get four categories of role-specific questions:
Technical Depth — separates people who did the work from those who read about it
Real Experience Verification — surfaces specific details only genuine experience provides
Proxy / Fraud Detection — questions a proxy candidate can't answer naturally
Behavioral / Situational — STAR-format questions for judgment and fit
---
How to Use
Open `index.html` in any browser
Enter your password to unlock the app
Paste a candidate's resume into Screen Candidate
Paste the job description (strongly recommended)
Toggle which fraud signals to check
Click Run Full Fraud Screen — results in ~20 seconds
Use the interview probes to verify findings in your phone screen
At offer stage, use Verify ID / Visa for document authentication
Use Interview Questions to generate a full question set for any role
Copy Report to share findings with hiring managers
---
Setup
No installation. No server. No npm. Just download and open.
```bash
git clone https://github.com/YOUR_USERNAME/verahire.git
cd verahire
# Open index.html in your browser
```
API Key
VeraHire uses the Anthropic Claude API. You will need an API key to run AI features. New accounts receive free credits.
Password
The app is password-protected for authorized use only. To set or change your password, open `index.html` in a text editor and find this line:
```javascript
const APP_PASSWORD = 'your-password-here';
```
Replace `'your-password-here'` with your chosen password and save.
> **Security note:** This is a client-side password — it protects casual access but is not intended as enterprise-grade security. Do not use this tool to store sensitive candidate data.
---
Tech Stack
Frontend: Vanilla HTML / CSS / JavaScript — no framework, runs in any browser
AI Engine: Claude (Anthropic) — `claude-sonnet-4-20250514`
Document Analysis: Claude multimodal vision API
No backend required — all processing runs client-side
---
About the Creator
I'm Radhika Pothuraju, a Senior Technical Recruiter with 10+ years of full-cycle experience in IT staffing and corporate recruiting. I've placed candidates at Apple, Cisco, Kaiser Permanente, Capital One, Google, Fannie Mae, and many others.
I built VeraHire because I was frustrated. Frustrated watching fabricated resumes sail through ATS systems. Frustrated when a "strong" candidate couldn't answer a basic question. Frustrated knowing proxy interviews are more common than anyone admits — and that no tool was built to catch them.
Every fraud signal in VeraHire is a real pattern I've seen. The interview probe questions are based on techniques I use myself. This is the screener I wished I'd had from day one.
📧 radhikabvk@gmail.com
💼 linkedin.com/in/radhika-devi-pothuraju-6a1051180
---
Disclaimer
VeraHire is a decision-support tool, not a final arbiter. AI findings should complement — never replace — human judgment and proper legal verification. No candidate data is stored; everything runs in your browser session only.
---
License
MIT — free to use, modify, and share.
---
If this tool resonates with you, star the repo and share it with your recruiting network.
The more honest recruiters use it, the harder it gets for bad actors to game the system.
