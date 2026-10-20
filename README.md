# 🎥 Movie Recommendation System using Emotion

This project bridges the gap between Computer Vision and Content Discovery. By analyzing a user's facial expression, the system identifies their current emotion and recommends a curated list of movies from IMDb that match their mood.
🌟 Key Features

    Emotion Detection: Uses Deep Learning (DeepFace) to identify emotions like Joy, Sadness, Anger, or Surprise from photos.

    Real-time Scraping: Dynamically fetches the latest and top-rated movies from IMDb using BeautifulSoup; no static/outdated CSV datasets required.

    Intelligent Mapping: Automatically translates emotional states into movie genres (e.g., "Sad" ➡️ "Comedy" to lift spirits, or "Fear" ➡️ "Horror" for thrill-seekers).

    Robust Parsing: Employs RegEx to cleanly extract movie titles and metadata from complex HTML structures.

## 🛠️ Tech Stack

    Facial Analysis: DeepFace, OpenCV

    Web Scraping: BeautifulSoup4, Requests, lxml

    Data Handling: Python, re (Regular Expressions)

    Visualization: Matplotlib

## 🚀 How It Works

    Input: The user provides an image (via webcam or file upload).

    Analysis: The DeepFace library analyzes facial features to predict the dominant emotion.

    Fetching: The system selects the corresponding IMDb genre URL (e.g., https://www.imdb.com/search/title/?genres=drama).

    Output: The top 10-15 movie titles currently trending in that category are displayed to the user.

## 📂 Project Structure
Plaintext

├── app.ipynb               # Main logic: Scraping, Emotion Detection, and Logic
├── data/                   # (Optional) Cache for frequently accessed genres
├── uploads/                # Directory for user-input images
└── README.md               # Documentation

## 📈 Future Enhancements

    Streamlit Integration: Build a web-based UI for a more interactive user experience.

    Video Support: Enable real-time emotion tracking via live webcam feed.

    Multi-Platform Scraping: Expand beyond IMDb to include Rotten Tomatoes and Netflix trending lists.

---

## 🌐 Complete Live Run & CI/CD Verification (24 Repositories)

Official production verification matrix for [Abishek Pranav G V](https://abishekpranavportfolio.lovable.app/) ecosystem:

| # | Repository | Tech Stack & Domain | CI/CD Status | Live Run Link | Direct Live App / Result URL |
|---|---|---|:---:|:---:|:---:|
| 1 | [abishekpranavportfolio](https://github.com/AbishekPranavGV/abishekpranavportfolio) | TypeScript / React / Vite Hub | ✅ Success | [Run #39456800487](https://github.com/AbishekPranavGV/abishekpranavportfolio/actions/runs/39456800487) | [Direct Live App (Lovable)](https://abishekpranavportfolio.lovable.app/) · [Pages Mirror](https://abishekpranavgv.github.io/abishekpranavportfolio/) |
| 2 | [Retail-Sales-Performance-Predictive-Analytics](https://github.com/AbishekPranavGV/Retail-Sales-Performance-Predictive-Analytics) | Demand Forecasting & Inventory Model | ✅ Success | [Run #39445648750](https://github.com/AbishekPranavGV/Retail-Sales-Performance-Predictive-Analytics/actions/runs/39445648750) | [Direct Result Dashboard](https://abishekpranavgv.github.io/Retail-Sales-Performance-Predictive-Analytics/) |
| 3 | [NICMS-SriLanka-Strategic-Blueprint](https://github.com/AbishekPranavGV/NICMS-SriLanka-Strategic-Blueprint) | National Digital Infrastructure Blueprint | ✅ Success | [Run #39445653533](https://github.com/AbishekPranavGV/NICMS-SriLanka-Strategic-Blueprint/actions/runs/39445653533) | [Direct Blueprint System](https://abishekpranavgv.github.io/NICMS-SriLanka-Strategic-Blueprint/) |
| 4 | [social-command-center](https://github.com/AbishekPranavGV/social-command-center) | Next.js 20 & Autonomous Dispatcher | ✅ Success | [Run #39449108783](https://github.com/AbishekPranavGV/social-command-center/actions/runs/39449108783) | [Direct Live App (Vercel)](https://nunes-social-post-machine-mu.vercel.app/) |
| 5 | [IndiaMART-AI-Content-Catalog-Generator](https://github.com/AbishekPranavGV/IndiaMART-AI-Content-Catalog-Generator) | B2B Commerce & Catalog Automation | ✅ Success | [Run #39449128617](https://github.com/AbishekPranavGV/IndiaMART-AI-Content-Catalog-Generator/actions/runs/39449128617) | [Direct Live Runner](https://abishekpranavgv.github.io/IndiaMART-AI-Content-Catalog-Generator/) |
| 6 | [MedX](https://github.com/AbishekPranavGV/MedX) | Healthcare & Lab Equipment Studio | ✅ Success | [Run #39449147425](https://github.com/AbishekPranavGV/MedX/actions/runs/39449147425) | [Direct Live App (Vercel)](https://nunes-catalogue-studio-live.vercel.app/) |
| 7 | [Streamlit](https://github.com/AbishekPranavGV/Streamlit) | Interactive Python Data App Framework | ✅ Success | [Run #39449166722](https://github.com/AbishekPranavGV/Streamlit/actions/runs/39449166722) | [Direct Live Runner](https://abishekpranavgv.github.io/Streamlit/) |
| 8 | [Climate-Impact-ESG-Dashboard](https://github.com/AbishekPranavGV/Climate-Impact-ESG-Dashboard) | Real-Time ESG Analytics & Scope 1-3 Monitoring | ✅ Success | [Run #39448557718](https://github.com/AbishekPranavGV/Climate-Impact-ESG-Dashboard/actions/runs/39448557718) | [Direct Result Dashboard](https://abishekpranavgv.github.io/Climate-Impact-ESG-Dashboard/) |
| 9 | [COVID-19-Global-Forecasting-Predictive-Analysis](https://github.com/AbishekPranavGV/COVID-19-Global-Forecasting-Predictive-Analysis) | Epidemiological Time-Series SEIR Modeling | ✅ Success | [Run #39449184831](https://github.com/AbishekPranavGV/COVID-19-Global-Forecasting-Predictive-Analysis/actions/runs/39449184831) | [Direct Result Dashboard](https://abishekpranavgv.github.io/COVID-19-Global-Forecasting-Predictive-Analysis/) |
| 10 | [Customer-Churn-Decision-Analysis](https://github.com/AbishekPranavGV/Customer-Churn-Decision-Analysis) | Retention Decision Trees & Churn Analytics | ✅ Success | [Run #39449203803](https://github.com/AbishekPranavGV/Customer-Churn-Decision-Analysis/actions/runs/39449203803) | [Direct Result Dashboard](https://abishekpranavgv.github.io/Customer-Churn-Decision-Analysis/) |
| 11 | [E-commerce-Recommendation-Engine](https://github.com/AbishekPranavGV/E-commerce-Recommendation-Engine) | Collaborative Filtering & SVD Matrix | ✅ Success | [Run #39449222852](https://github.com/AbishekPranavGV/E-commerce-Recommendation-Engine/actions/runs/39449222852) | [Direct Result Dashboard](https://abishekpranavgv.github.io/E-commerce-Recommendation-Engine/) |
| 12 | [Facedetection](https://github.com/AbishekPranavGV/Facedetection) | Computer Vision Haar Cascades Classifier | ✅ Success | [Run #39449244562](https://github.com/AbishekPranavGV/Facedetection/actions/runs/39449244562) | [Direct Result Dashboard](https://abishekpranavgv.github.io/Facedetection/) |
| 13 | [Movie_recommendation_using_emotion](https://github.com/AbishekPranavGV/Movie_recommendation_using_emotion) | Affective NLP Emotion-Aware Movie Recommender | ✅ Success | [Run #39449265411](https://github.com/AbishekPranavGV/Movie_recommendation_using_emotion/actions/runs/39449265411) | [Direct Result Dashboard](https://abishekpranavgv.github.io/Movie_recommendation_using_emotion/) |
| 14 | [Stock-Price-Prediction-using-ARIMA](https://github.com/AbishekPranavGV/Stock-Price-Prediction-using-ARIMA) | Quantitative ARIMA & Deep LSTM Hybrid | ✅ Success | [Run #39449282506](https://github.com/AbishekPranavGV/Stock-Price-Prediction-using-ARIMA/actions/runs/39449282506) | [Direct Result Dashboard](https://abishekpranavgv.github.io/Stock-Price-Prediction-using-ARIMA/) |
| 15 | [Sentimental-analysis-of-News-Headlines](https://github.com/AbishekPranavGV/Sentimental-analysis-of-News-Headlines) | NLP Headline Sentiment & Market Polarity | ✅ Success | [Run #39449304063](https://github.com/AbishekPranavGV/Sentimental-analysis-of-News-Headlines/actions/runs/39449304063) | [Direct Result Dashboard](https://abishekpranavgv.github.io/Sentimental-analysis-of-News-Headlines/) |
| 16 | [Autonomous-System-Temp-Cleaner](https://github.com/AbishekPranavGV/Autonomous-System-Temp-Cleaner) | Windows Maintenance & Cache Cleanup Automation | ✅ Success | [Run #39449322965](https://github.com/AbishekPranavGV/Autonomous-System-Temp-Cleaner/actions/runs/39449322965) | [Direct Result Dashboard](https://abishekpranavgv.github.io/Autonomous-System-Temp-Cleaner/) |
| 17 | [Crm](https://github.com/AbishekPranavGV/Crm) | Enterprise AI CRM Pipeline & Skill Bundle | ✅ Success | [Run #39449341161](https://github.com/AbishekPranavGV/Crm/actions/runs/39449341161) | [Direct Result Dashboard](https://abishekpranavgv.github.io/Crm/) |
| 18 | [drive-file-index](https://github.com/AbishekPranavGV/drive-file-index) | Google Drive Automated Indexer & Security Audit | ✅ Success | [Run #39449358685](https://github.com/AbishekPranavGV/drive-file-index/actions/runs/39449358685) | [Direct Result Dashboard](https://abishekpranavgv.github.io/drive-file-index/) |
| 19 | [Multi-Account-Gmail-Inbox-Hygiene-Agent](https://github.com/AbishekPranavGV/Multi-Account-Gmail-Inbox-Hygiene-Agent) | Autonomous Multi-Account Gmail Governance | ✅ Success | [Run #39449377198](https://github.com/AbishekPranavGV/Multi-Account-Gmail-Inbox-Hygiene-Agent/actions/runs/39449377198) | [Direct Result Dashboard](https://abishekpranavgv.github.io/Multi-Account-Gmail-Inbox-Hygiene-Agent/) |
| 20 | [NICMS-SriLanka-Strategic-Blueprint_Project](https://github.com/AbishekPranavGV/NICMS-SriLanka-Strategic-Blueprint_Project) | National Enterprise Architecture Specifications | ✅ Success | [Run #39449396297](https://github.com/AbishekPranavGV/NICMS-SriLanka-Strategic-Blueprint_Project/actions/runs/39449396297) | [Direct Result Dashboard](https://abishekpranavgv.github.io/NICMS-SriLanka-Strategic-Blueprint_Project/) |
| 21 | [NUNES-Local-AI-Marketing-Starter](https://github.com/AbishekPranavGV/NUNES-Local-AI-Marketing-Starter) | Local Edge AI Offline Marketing Automation | ✅ Success | [Run #39449415695](https://github.com/AbishekPranavGV/NUNES-Local-AI-Marketing-Starter/actions/runs/39449415695) | [Direct Result Dashboard](https://abishekpranavgv.github.io/NUNES-Local-AI-Marketing-Starter/) |
| 22 | [Smart-Brochure-to-Catalog-Converter](https://github.com/AbishekPranavGV/Smart-Brochure-to-Catalog-Converter) | IDP PDF Brochure to Structured Catalog Engine | ✅ Success | [Run #39449436146](https://github.com/AbishekPranavGV/Smart-Brochure-to-Catalog-Converter/actions/runs/39449436146) | [Direct Result Dashboard](https://abishekpranavgv.github.io/Smart-Brochure-to-Catalog-Converter/) |
| 23 | [Smart-Price-Master-Catalog-Generator](https://github.com/AbishekPranavGV/Smart-Price-Master-Catalog-Generator) | PriceMaster Cross-Platform Dynamic Pricing | ✅ Success | [Run #39449455239](https://github.com/AbishekPranavGV/Smart-Price-Master-Catalog-Generator/actions/runs/39449455239) | [Direct Result Dashboard](https://abishekpranavgv.github.io/Smart-Price-Master-Catalog-Generator/) |
| 24 | [SocmedX](https://github.com/AbishekPranavGV/SocmedX) | Unified Social Command Center Portfolio Suite | ✅ Success | [Run #39449474972](https://github.com/AbishekPranavGV/SocmedX/actions/runs/39449474972) | [Direct Result Dashboard](https://abishekpranavgv.github.io/SocmedX/) |

*Maintained by [Abishek Pranav G V](https://abishekpranavportfolio.lovable.app/) · Business Analyst & Data/AI Automation Specialist*
