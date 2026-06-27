# India-s-Got-Latent-S2E1---Word-Cloud-Analysis


🚀 Quick Start
Prerequisites
-Python 3.11 (recommended — tested and verified)
-Internet connection
-API Key of YouTube

🔑 API Keys

This project uses 1 free APIs. No credit card required for any of them.

Steps: 
1) Go to console.cloud.google.com - https://console.cloud.google.com/APIS
2) Create a new project (e.g. "YouTube Comments")
3) Go to APIs & Services → Enable APIs
4) Search for "YouTube Data API v3" → Click Enable
5) Go to APIs & Services → Credentials
6) Click "+ Create Credentials" → API Key
7) Copy your API key ✅
8) Build code and do analysis.


🎯 Architecture
────────────────────────────────────────────────────
│                    DATA COLLECTION                │
│                  (Python Programming)             │
│                  FETCH all data THROUGH           │
└───────────────────────────────────────────────────
                               │ 
                               │ 
────────────────────────────────────────────────────
│                 RAW DATA TEXT PROCESSING         │
│                  (Python Programming)            │
│          CLEANING | STOP WORDS | LEMMATIZATION   │
└───────────────────────────────────────────────────
        │             │                │             
┌────▼────┐      ┌────▼────┐      ┌────▼────┐
│ SENTIMENT│     │ WORD    │      │ EMOTION │
│  ANALYSIS│     │  ANALYSIS│     │DETECTION│
│          │     │          │     │         │
└─────────┘      └──────────┘     └──────────┘

────────────────────────────────────────────────────
│                           OUTPUT                  │
│                                                   │
│          CHARTS | REPORTS | WORD CLOUD            │
└───────────────────────────────────────────────────
     

