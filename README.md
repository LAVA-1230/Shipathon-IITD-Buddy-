# 📌 IITD Buddy: Intelligent Campus Navigator

## 🚀 Overview
IITD Buddy is an AI-powered assistant designed to enhance student life at **IIT Delhi**. It provides guidance on:
- 📚 **Academics**: Courses, mentorship, and professor resources.
- 🏠 **Hostel Facilities**: Information about accommodation and amenities.
- 🎉 **Campus Events**: Updates on the latest happenings and student activities.
- 📍 **Local Hotspots**: Best places to eat, study, and relax.

By leveraging **LLMs and RAG-based retrieval**, IITD Buddy aims to simplify navigation and enrich the student experience.

## 🛠 Methodology
1. **Familiarization with LLM APIs** (e.g., Groq, Gemini)
2. **Data Accumulation**: 
   - Courses of Study, BSW Website
   - Department resources, Google Drives
   - YouTube video transcripts, Professor web pages
3. **Vector Search Database**: Using Qdrant to index and retrieve relevant information.
4. **RAG Implementation**: Fetching context-aware responses from the database and feeding it to LLM for accurate answers.

## ⚙️ Tech Stack
- **LLM API**: Groq / Gemini
- **Vector Database**: Qdrant
- **Frontend**: Streamlit

## 💡 Future Enhancements
- AI-powered **course planner** to assist students in selecting courses aligned with degree requirements, workload, and career aspirations.
- Personalized **mentorship recommendations** based on student interests.

## 🎯 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/iitd-buddy.git
   cd iitd-buddy
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   streamlit run app.py
   ```


## 🤝 Contributing
We welcome contributions! Feel free to fork the repository, submit issues, or open pull requests. 

## 📜 License
This project is licensed under the **MIT License**.
