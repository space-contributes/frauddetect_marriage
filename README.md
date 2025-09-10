
# Matrimony Fraud Detector – AI-Powered Profile Analysis 💌


## 🛡️ **Detect suspicious matrimonial profiles with AI-driven insights — fully local and privacy-conscious.**
![Commit milestone](https://img.shields.io/badge/commits-400-orange?style=for-the-badge&logo=git)
![Version](https://img.shields.io/badge/version-1.0-blue)
![Privacy-First](https://img.shields.io/badge/privacy-local-yellow)
![Language](https://img.shields.io/badge/language-JavaScript-brightgreen)
![Framework](https://img.shields.io/badge/framework-TensorFlow%20JS-blueviolet)
![Open Source](https://img.shields.io/badge/open%20source-yes-lightgrey)
![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen)
![Local Processing](https://img.shields.io/badge/processing-local-blue)
![AI-Powered](https://img.shields.io/badge/AI-powered-lightblue)
![Version](https://img.shields.io/badge/version-1.0-blue)
![Privacy-first](https://img.shields.io/badge/privacy-local-yellow)
*Made with ❤️ by Aryaman M*
## NO INSTALL NEEDEED FOR TENSORFLOW LIBRARY
---

Matrimony Fraud Detector is a **browser-based AI-LIKE tool** that analyzes uploaded profiles to identify **suspicious activity patterns**. Using a **multi-feature ensemble**, it evaluates profiles for potential fraud while keeping all data **local to your device**.


---


## ❓ Typical profile screening vs. our system


### 🔹 Traditional approaches


* Manual vetting and verification

* Limited cross-profile comparison

* Often misses subtle duplications or reused data

* Privacy risk when data leaves the device


### 🔹 Matrimony Fraud Detector


**Living profiles, intelligently analyzed. Not just scanned, but understood.**


* Computes **bio similarity, photo reuse, credential overlap, timing variance, visit frequency, Aadhaar verification weight, and phonetic name similarity**

* Detects patterns like reused phone/email, repeated photos, or similar bios across multiple profiles

* Multi-layered scoring: **Linear model + Naive Bayes ensemble**

* Interactive controls: Sliders for ensemble weights, thresholds, and the real-time results display make it highly usable and experimentable.

* Fully **in-browser execution**: no data leaves your device

* Adjustable ensemble weights & thresholds for **custom detection sensitivity**

* Real-time visualization of suspicious scores with intuitive color coding:
LOW - GREEN
MEDIUM - YELLOW
RED - VERY HIGH

* Detailed feature breakdown per profile for audit & transparency

* Export results as JSON for reporting or research


---


## 🔍 Feature Breakdown


* **Bio Analysis** – Detect overlapping phrases or word patterns across profiles

* **Photo Reuse Detection** – Matches photo content or filenames across profiles

* **Customization** - Sliders for ensemble weights, thresholds, and the real-time results display make it highly usable and experimentable.

* **Credential Overlap** – Detects reused phone numbers and emails

* **Activity Timing Analysis** – Checks visit patterns and timing variance

* **Name Phonetic Similarity** – Boosts similarity score for similar-sounding names

* **Aadhaar Verification Weight** – Trusted identity markers influence scores

* **Linear + Naive Bayes Ensemble** – Combines deterministic and probabilistic scoring

* **Noise Layer** – Adds slight randomness to prevent overfitting in small datasets

* **Privacy-First Design** – All processing stays **on your device**

* **Exportable Results** – Save suspicious scores for offline analysis


---


## 👥 Who Is It For?


* Matrimony platform moderators

* Fraud detection & risk teams

* Researchers analyzing online identity reuse

* Developers building safer matchmaking systems


---


## ⚙️ Setup & Usage


Simply open the HTML in a modern browser (Chrome/Edge/Firefox recommended):


1. **Upload or paste JSON profiles**

2. **Optionally train the linear + Naive Bayes ensemble**

3. **Adjust thresholds and ensemble weights**

4. **Run detection**

5. **View results or export as JSON**


All calculations are **performed locally**, ensuring maximum privacy. Compliance matched*
*subject to terms and conditions and not guaranteed
# JSON FORMAT:

[
  {
    "id": "p1",
    "name": "Asha Sharma",
    "bio": "I love traveling, photography, and exploring new cuisines.",
    "phone": "+911234567890",
    "email": "asha@example.com",
    "photos": ["asha1.jpg", "asha2.jpg"],
    "activity": {
      "visits": 120,
      "logs": [{"time": 1620012345}, {"time": 1620013345}]
    },
    "verifications": {
      "aadhaar": true
    }
  },

---


## 🚀 Milestones

- 🎉 100th commit – First working prototype shipped  
- ⚡ 200th commit – Fraud detection scoring logic improved  
- 🔥 300th commit – Much advanced with custom algorithms derived from my other project, although not needed in this one, I simplified it so the math is simplified and easy to read.
- 🏆 400th commit – Major stability release & dataset scaling.
### All this can't be seen from the Website, it's the squash history which is erased, and that branch is gone.
-----
## 🔮 Roadmap


* Automated batch imports from CSV/JSON

* Visualization dashboard for networked fraud patterns

* Integration with identity verification APIs

* Mobile-friendly web version


---


## ⚖️ License & Legal


By using **Matrimony Fraud Detector**, you agree to the terms in **[LICENSE.md](https://github.com/space-contributes/frauddetect_marriage/blob/main/LICENSE.md)**.


💡 **Educational and ethical use only** — unauthorized use to harm or defraud is strictly prohibited.


### Disclaimer – Educational and Research Use Only


* Profiles are analyzed **for pattern detection** only; results are **probabilistic estimates**, not definitive proof of fraud.

* This project is **independent**, with no affiliation to any matrimony service or platform.

* All misuse is the **sole responsibility of the user**.


### Not to Defame


This material is **informational and research-focused**, not intended to disparage or harm any individual or company.


--- 
