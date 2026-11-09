# TEC Aspirants (Homepage Web Platform)

A modern, responsive, dynamic, and clean single-page educational website for **"TEC Aspirants"** — the leading community and admission preparation platform for Bangladesh's **10 Government Textile Engineering Colleges (TECs)**.

---

## 🌟 Key Features & Layout Architecture

### 1. 🚀 Top Header Navigation (Strictly Single Horizontal Line)
- **Single Horizontal Line**: Designed with a strict `flex-row no-wrap` layout ensuring that all items align seamlessly on a single horizontal line.
- **Components**:
  1. **Platform Logo & Name**: "TEC Aspirants" with textile engineering emblem.
  2. **"কলেজ পছন্দের নির্দেশনা" (College Choice Priority Guideline)**: ১০টি সরকারি টেক্সটাইল কলেজের ক্রমানুসার ও চয়েস গাইড।
  3. **Theme Switcher**: আইকন-অনলি বাটন (Moon/Sun icon), 'কলেজ পছন্দের নির্দেশনা' বাটনের ঠিক পাশে অবস্থিত। কোনো টেক্সট ছাড়া শুধুমাত্র আইকন টগল।
  4. **"যোগ্যতা যাচাই" (Eligibility Check)**: জিপিএ ক্যালকুলেটর ও সার্কুলার।
  5. **"ক্যাম্পাস ভিত্তিক ভলান্টিয়ার খুঁজুন"**: ৩-স্তরের ক্যাসকেডিং ফিল্টার মডাল (প্রতিষ্ঠান -> বিভাগ -> জেলা)।
  6. **"কন্ট্রোল প্যানেল" (Admin Control Panel)**: ভলান্টিয়ার আবেদন এক ক্লিকে অনুমোদন ও নেটওয়ার্ক নিয়ন্ত্রণ।

---

### 2. 👥 সিনিয়র ক্যাম্পাস ভলান্টিয়ার্স (ত্রিভুজাকার বিন্যাস / Triangle Podium)
- **ত্রিভুজ বিন্যাস**:
  - **মাঝে (Elevated Vertex)**: `Ruhul Amin Ikram` (সেন্ট্রাল প্রতিনিধি, ক্রাউন ব্যাজ সহ কিছুটা উপরের দিকে উত্তোলিত)।
  - **দুই পাশে (Wings)**: `Ariful Haque Arif` (বামে) এবং `Mahmud Hasan Miraz` (ডানে), উভয়েই Ruhul Amin Ikram-এর তুলনায় কিছুটা নিচের দিকে অবস্থিত, একটি নিখুঁত ত্রিভুজ/পোডিয়াম শেপ তৈরি করে।
- **নামসমূহ আপডেট**:
  - `Ariful Haque` পরিবর্তিত হয়ে `Ariful Haque Arif`
  - `Mahmudul Hasan` পরিবর্তিত হয়ে `Mahmud Hasan Miraz`

---

### 3. 🛡️ কন্ট্রোল প্যানেল ও ১-ক্লিক ভলান্টিয়ার অনুমোদন (1-Click Approval)
- কোনো ভিজিটর **"ক্যাম্পাস ভিত্তিক ভলান্টিয়ার হিসেবে যুক্ত হন"** ফরম পূরণ করলে আবেদনটি অনিষ্পন্ন তালিকায় জমা হয়।
- **কন্ট্রোল প্যানেল** থেকে অ্যাডমিন **"এক ক্লিকে যুক্ত করুন"** বাটনে চাপ দেওয়া মাত্রই আবেদনকারী সক্রিয় ভলান্টিয়ার হিসেবে যুক্ত হয়ে যান।
- সাথে রয়েছে টেস্ট আবেদন তৈরি ও রিয়েল-টাইম ডাটাবেজ মনিটরিং সুবিধা।

---

### 4. 🔍 ৩-স্তরের ভলান্টিয়ার ফিল্টারিং (Cascading Filter)
- ক্রমানুসারে ৩টি ড্রপডাউন অপশন:
  1. **প্রতিষ্ঠান (ক্যাম্পাস)**: ১০টি সরকারি টেক্সটাইল কলেজ।
  2. **বিভাগ**: ৮টি প্রশাসনিক বিভাগ।
  3. **জেলা**: নির্বাচিত বিভাগের ওপর ভিত্তি করে জেলা তালিকা ডায়নামিকভাবে ফিল্টার হয়।

---

### 5. 👨‍💻 ওয়েবসাইট নির্মাতা পরিচিতি (Developer Information)
- ওয়েবসাইটের সবচেয়ে নিচে (Footer-এর একদম শেষাংশে) নির্মাতা পরিচিতি সংযুক্ত:
  - **Ruhul Amin Ikram**
  - **16th Batch**
  - **Department of Apparel Engineering**
  - **Barishal Textile Engineering College**

---

### 2. 🏛️ Hero Section (Dynamic Banner)
- **High-Resolution Educational Banner**: Positioned right below the header with subtle gradient overlays for contrast and readability.
- **Dynamic & Configurable**:
  - Easily updated via `js/config.js` or via the built-in **"⚙️ ব্যানার পরিবর্তন"** customizer panel.
  - Comes with 3 curated high-res presets (Central Admission 2026, Modern Lab & Campus, Volunteer Network) plus custom image URL & text inputs.
- **Live Statistics**: Displaying 10 Colleges (Center 101 to 110), 1200 Total Seats (120 per college), 64 Districts Volunteer Network, and 100% Free Senior Mentorship.

---

- **Social Channels**:
  - **Facebook Page**: [https://www.facebook.com/tec.aspirants.bd/](https://www.facebook.com/tec.aspirants.bd/)
  - **Facebook Group**: [https://www.facebook.com/groups/tec.aspirants.bd/](https://www.facebook.com/groups/tec.aspirants.bd/)
  - **Telegram Channel**: [https://t.me/tec_aspirants](https://t.me/tec_aspirants)
  - **WhatsApp Channel**: [https://whatsapp.com/channel/0029VbEIPvBCnA7vt6o6XZ3n](https://whatsapp.com/channel/0029VbEIPvBCnA7vt6o6XZ3n)
  - **Email**: `tec.aspirants@gmail.com`
  - **Session**: সেন্ট্রাল অ্যাডমিশন ২০২৬-২৭ (১২০০ মোট আসন)
- **Two Interactive Dropdowns**:
  1. **Campus Select**: All 10 Government Textile Engineering Colleges (Center Codes 101-110, 120 seats each):
     - `CTEC` (Textile Engineering College, Chattogram - Code 101)
     - `PTEC` (Pabna Textile Engineering College - Code 102)
     - `TECN` (Textile Engineering College, Noakhali - Code 103)
     - `BTEC` (Barishal Textile Engineering College - Code 104)
     - `JhTEC` (Jhenaidah Textile Engineering College - Code 105)
     - `RTEC` (Rangpur Textile Engineering College - Code 106)
     - `GTEC` (Gopalganj Textile Engineering College - Code 107)
     - `JTEC` (Jamalpur Textile Engineering College - Code 108)
     - `MTEC` (Madaripur Textile Engineering College - Code 109)
     - `STEC` (Sylhet Textile Engineering College, South Surma - Code 110)
  2. **District Select**: All **64 Districts of Bangladesh** grouped cleanly by their 8 administrative divisions (Dhaka, Chattogram, Rajshahi, Khulna, Barishal, Sylhet, Rangpur, Mymensingh).
- **Dynamic Query & Instant Filtering**:
  - Automatically queries the volunteer dataset in real time.
  - Renders cards displaying **Name, Campus, District, Department, Batch, and a clickable WhatsApp contact icon** that opens a direct chat with the volunteer.
  - Search keyword input for quick name/department matching and a reset filter option.

---

### 4. 💬 Contact & Social Media Section (Middle Section)
- **Split Row / Flex Layout**:
  - **Left Side**: Prominent, large text button: **"আমাদের সাথে যোগাযোগ কর" (Contact Us)** with 24/7 helpdesk badge, triggering a contact drawer with WhatsApp hotline, phone support, and official email.
  - **Right Side**: Stacked/grid links to official social channels:
    - **Facebook Page** (অফিসিয়াল ফেসবুক পেজ - ২৫কে+ অনুসারী)
    - **Facebook Group** (ডিসকাশন গ্রুপ - ৪০কে+ মেম্বার)
    - **Telegram Channel** (পিডিএফ নোট ও সার্কুলার - ১৫কে+ সাবস্ক্রাইবার)
    - **WhatsApp Channel** (ইনস্ট্যান্ট আপডেট চ্যানেল)
    - **Official Support Email** (২৪/৭ সাপোর্ট)

---

### 5. 🖤 Footer Section (Pitch-Black Theme `#000000`)
- **Deep Pitch-Black Styling**: Formatted with `#000000` background, subtle borders, and glowing badges.
- **Divided into Two Main Sides**:
  - **Left Side**:
    - Large typography: **"TEC Aspirants"** (Platform Name) with mission statement.
    - Sub-text button: **"ক্যাম্পাসভিত্তিক ভোলান্টিয়ার হিসেবে যুক্ত হন" (Join as a campus volunteer)**.
      - Tapping opens an application popup modal containing the **exact 5-field form**:
        1. **নাম (Name)** - Text Input
        2. **ক্যাম্পাস (Campus)** - Select Dropdown (CTEC, PTEC, TECN, BTEC, JhTEC, RTEC, GTEC, JTEC, MTEC, STEC)
        3. **ডিপার্টমেন্ট (Department)** - Text Input
        4. **ব্যাচ নম্বর (Batch Number)** - Text Input
        5. **মোবাইল (Mobile Number / WhatsApp)** - Text Input
      - Form validation, instant feedback toast, and automatic saving into `localStorage` so new volunteers immediately appear in the search directory!
  - **Right Side**:
    - Large heading: **"যোগাযোগ" (Contact)**.
    - Circular icons for all social media platforms (Facebook, WhatsApp, Telegram, YouTube, LinkedIn, Email) with direct navigation links.

---

## 📁 Project Structure

```
c:\Users\IKRAM\Documents\TEC Aspirants\
├── index.html                  # Core single-page website
├── css/
│   └── styles.css              # Custom styling, animations, pitch-black theme, typography
├── js/
│   ├── config.js               # Central site configuration (banner, contacts, social links, guidelines)
│   ├── data.js                 # 10 TECs, 64 districts, and pre-populated volunteer dataset
│   └── app.js                  # Reactive state, theme switcher, query engine, form handling, modals
├── assets/
│   └── docs/
│       └── circular-viewer.html # Embedded official admission guidelines and downloadable circular
├── server.js                   # Lightweight static server (zero dependencies)
└── README.md                   # Documentation
```

---

## 🚀 How to Run

### Option 1: Open Directly in Any Web Browser
Simply double-click `index.html` or open it with Google Chrome, Microsoft Edge, Firefox, or Safari.

### Option 2: Run with the Local Server
From PowerShell or Command Prompt in this folder:
```powershell
& "C:\Users\IKRAM\AppData\Roaming\Antigravity\bin\agy-node.cmd" server.js
```
Then visit: `http://localhost:3000/` in your browser.
