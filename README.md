# 🏥 MedQueryRAG

## 📌 Overview
The **MedQueryRAG** is a **Retrieval-Augmented Generation (RAG)-based system** designed to extract **medical information from PDF documents** efficiently. It enables users to input queries related to **diseases, symptoms, and treatments** and fetches the most relevant medical insights from pre-loaded PDFs.

This system uses **pdfquery** to parse medical PDFs, **cosine similarity** to match queries with relevant document sections, and **Llama3 AI model** to generate concise and meaningful responses. The goal is to provide **quick, AI-powered medical insights** while ensuring users are encouraged to seek professional medical advice when necessary.

Key highlights:
- 📄 **Extracts and processes medical text from PDFs** automatically.
- 🔍 **Finds relevant medical insights** based on user queries.
- 🤖 **Uses AI to generate responses** with contextual accuracy.
- 🏥 **Supports disease and symptom-based inquiries** for easy information retrieval.
- 🔄 **Interactive chatbot experience** to enhance usability.

## 🚀 Features
- 📄 **Extracts medical text from PDFs** using `pdfquery`
- 🔎 **Finds the most relevant information** using **cosine similarity**
- 🤖 **Generates AI-powered medical responses** via **Llama3 model**
- 🔄 **Interactive chatbot** for user queries on **diseases, symptoms, and treatments**
- 🏥 **Encourages users to seek proper medical advice**

## 🛠️ Tech Stack
- **Python** 🐍
- **pdfquery** 📄 (For PDF text extraction)
- **cosine similarity** (For information retrieval)
- **Llama3 API** 🤖 (For AI-powered responses)

## 📌 Usage
1️⃣ **Select an option:**
   - (1) Diseases and Symptoms
   - (2) Diseases and Treatments
   - (3) Terminate the program
2️⃣ **Enter your query:** (e.g., "What are the symptoms of diabetes?")
3️⃣ **Receive AI-generated medical response** 📢


## 📜 Example Query
```
>>> dizziness, nosebleeds
I'm here to help! Based on your symptoms, you might be experiencing Vasovagal Syncope. 
Seek medical attention if symptoms persist.
```

## 🎯 Future Enhancements
- ✅ **Integrate a web-based UI**
- ✅ **Expand PDF support for research papers**
- ✅ **Improve model accuracy with fine-tuning**

## 🤝 Contributing
Feel free to open issues or submit PRs to improve this project. 😊
