# Tik-Tok-
This project analyzes TikTok video data to understand how content type, creator verification, and author ban status impact visibility and engagement. It includes data cleaning, exploratory data analysis (EDA), and visual storytelling using Python.
# 📊 TikTok Content & Moderation EDA

## 📌 Project Overview
This project analyzes TikTok video data to understand how content type, creator verification, and author ban status impact visibility and engagement. It includes data cleaning, exploratory data analysis (EDA), and visual storytelling using Python.

---

## 🗂️ Dataset
- Records: [Add count]
- Features analyzed:
  - `claim_status` (claim / opinion)
  - `verified_status`
  - `author_ban_status`
  - `video_view_count`

---

## 🛠️ Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 🔍 Exploratory Data Analysis

### 1️⃣ Claim Status vs Verification Status
- Non-verified creators dominate content production.
- Verified users produce fewer videos but show higher engagement.

### 2️⃣ Total Views by Claim Type
- **Claim videos account for ~99% of total views**.
- Opinion videos receive very little audience reach.

### 3️⃣ Median Views by Author Ban Status
- **Banned** and **Under Review** authors have significantly higher median view counts.
- Active users receive much lower median views.

### 4️⃣ Claim Status Distribution by Ban Category
- Claim content appears across all moderation groups.
- Opinion content is mostly produced by active authors.

---

## 📈 Key Insights
- Verified creators, though fewer, produce highly-engaging content.
- Claim-type content receives the highest visibility and user attention.
- High-reach creators are more likely to fall under moderation review or banning.
- Moderation actions correlate strongly with content that goes viral.
<img width="358" height="343" alt="eda-3" src="https://github.com/user-attachments/assets/d74daacd-fa4c-4b14-803e-e1124f02aecf" />



<img width="373" height="207" alt="eda-4" src="https://github.com/user-attachments/assets/1053c87d-6125-4800-837f-49735711b278" />



<img width="452" height="281" alt="eda-5" src="https://github.com/user-attachments/assets/58b9f4a2-bd56-4023-8f82-a698c1c1534a" />



<img width="503" height="281" alt="eda-6" src="https://github.com/user-attachments/assets/21894b74-7976-4be1-ac88-17b1e8d92af7" />



---

## 🧾 Conclusion
This EDA highlights clear relationships between creator characteristics, moderation decisions, and content performance on TikTok. Claim-heavy content drives most of the platform's viewership, and creators facing moderation tend to have higher engagement levels. These insights can support platform policy evaluation, content quality assessment, and risk analysis.
