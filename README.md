# NivasaAI

AI-powered real estate intelligence for Indian datasets.  
Open-source, modular, and designed for transparency and accessibility.

---

## Project Overview

NivasaAI helps users analyze, compare, and extract insights from property, infrastructure, and neighborhood data in India using free, open-source AI tools.

---

## Key Features

- **AI Reasoning:** Query and interpret real estate data with explainable AI.
- **RAG Architecture:** Combines retrieval and generation for accurate answers.
- **Feedback Loop:** Improves insights with user feedback.
- **Indian Dataset Focus:** Tailored for local property, infrastructure, and environment data.



## Architecture Summary

- **Flask UI:** Simple web interface for queries.
- **LangChain RAG:** Modular retrieval-augmented generation pipeline.
- **FAISS DB:** Fast vector search for property documents.
- **SQLite Memory:** Lightweight structured data storage.
- **Ollama Models:** Open-source LLMs (CodeLlama, Mistral) for reasoning.

---

## Tech Stack

- Python 3.10+
- Flask
- LangChain
- FAISS
- SQLite
- Ollama (CodeLlama, Mistral)
- Jupyter (optional for notebooks)

---

## Setup Instructions

```bash
# Clone the repo
git clone https://github.com/parveen-birthaliya/NivasaAI.git
cd NivasaAI

# Create Python environment
python3 -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Start Flask app
python app.py
```

---

## Dataset Sources (India)

- Government Open Data (data.gov.in)
- RERA (Real Estate Regulatory Authority)
- Housing.com, MagicBricks APIs
- CPCB (Central Pollution Control Board)
- OpenStreetMap

---

## Future Enhancements

- Self-learning AI with improved feedback integration
- Advanced retrieval and ranking
- Interactive dashboard UI
- Community-driven datasets and plugins

---

## Contributing

Fork the repo, open issues, and submit pull requests.  
All contributions are welcome!

---

## License

MIT License

---

## Contact / Credits

Created by Parveen Birthaliya  
[GitHub: parveen-birthaliya](https://github.com/parveen-birthaliya)
