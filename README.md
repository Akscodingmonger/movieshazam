# 🎬 Movie Shazam

**Movie Shazam** is a Python application that identifies movies based on short dialogue snippets — think *Shazam, but for films.*  
It uses **web scraping** to collect thousands of movie quotes and applies **Natural Language Processing (NLP)** with **spaCy** to match any user-entered dialogue to the most likely movie title.

---

## 🚀 Features
- 🧠 **Dialogue Recognition** – Input any movie quote or snippet of dialogue and get an accurate movie prediction.  
- 🌐 **Automated Web Scraping** – Gathers 1,000+ movie dialogues using BeautifulSoup, Googlesearch, and HTTP Requests.  
- 🗣️ **NLP Matching** – Tokenizes and compares text embeddings using spaCy for semantic similarity.  
- 💻 **User Interface** – Simple and modern CustomTkinter UI for a seamless user experience.  
- 🎯 **High Accuracy** – Achieves over **90% prediction accuracy** on the scraped dataset.

---

## 🧩 Tech Stack
- **Language:** Python  
- **Libraries:** BeautifulSoup, requests, googlesearch-python, spaCy, CustomTkinter, numpy  
- **Techniques:** Web Scraping, Text Tokenization, Semantic Similarity (NLP)  

---

## ⚙️ Installation

Clone the repository and install the dependencies:

```bash
git clone https://github.com/your-username/movie-shazam.git
cd movie-shazam
pip install -r requirements.txt
