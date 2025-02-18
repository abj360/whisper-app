# Whisper: AI-Powered Disaster Tweet Classification

## Description
Whisper is an AI system that harnesses natural language processing (NLP) to classify disaster-related tweets, enhancing situational awareness and expediting emergency response during crises. By leveraging deep learning, Whisper helps organizations and first responders analyze social media in real time to prioritize actions effectively.

---

## Features
✅ AI-driven classification of disaster-related tweets  
✅ Real-time situational awareness from social media  
✅ Helps prioritize emergency response efforts  
✅ High accuracy using NLP and deep learning models  
✅ User-friendly interface for analysts and responders  
✅ Secure and privacy-focused data handling  

---

## How It Works
1. **Tweet Input** – Users provide a tweet or dataset of tweets.  
2. **NLP Analysis** – The deep learning model processes the text and classifies it as disaster-related or not.  
3. **Classification Output** – The app provides a probability score and disaster category.  

---

## Tech Stack
- **Frontend:** Streamlit  
- **Backend:** N/A (Only Google Colab for model execution)  
- **AI Model:** PyTorch (Fine-tuned NLP model for disaster classification)  
- **Dataset:** [Disaster Relief Dataset](https://storage.googleapis.com/inspirit-ai-data-bucket-1/Data/AI%20Scholars/Sessions%206%20-%2010%20(Projects)/Project%20-%20Disaster%20Relief/disaster_data.csv)  
- **Word Embeddings:** [GloVe 300D](http://nlp.uoregon.edu/download/embeddings/glove.6B.300d.txt)  

---

## Installation & Setup
### Prerequisites
- Python (3.8+)
- PyTorch
- Streamlit

### Clone the Repository
```bash
git clone https://github.com/abj360/whisper-app.git
cd whisper-app
```

---

## Usage
1. Open the Google Colab notebook in the repository.
2. Run the notebook to execute the AI model.
3. Input a tweet or a dataset of tweets.
4. Wait for the AI model to classify the tweets.
5. Receive a classification report with insights.  

---

## Model Training (For Developers)
To train the AI model:
```bash
python train.py --epochs [number] --batch_size [size]
```
- Dataset: [Disaster Relief Dataset](https://storage.googleapis.com/inspirit-ai-data-bucket-1/Data/AI%20Scholars/Sessions%206%20-%2010%20(Projects)/Project%20-%20Disaster%20Relief/disaster_data.csv)  
- Word Embeddings: [GloVe 300D](http://nlp.uoregon.edu/download/embeddings/glove.6B.300d.txt)  
- Training parameters: Fine-tuned PyTorch NLP model for disaster tweet classification  

---

## Deployment
Since Whisper currently runs in Google Colab, deployment is not applicable. Future iterations may integrate deployment via Streamlit Cloud or a dedicated server.

---

## Contributing
Pull requests are welcome! Follow these steps:
1. Fork the repo.
2. Create a new branch (`git checkout -b feature-name`).
3. Commit changes (`git commit -m "Added feature X"`).
4. Push to your branch (`git push origin feature-name`).
5. Open a PR.

---

## License
This project is licensed under the **MIT License**. See `LICENSE.md` for details.

---

## Contact
For questions or collaborations:  
📧 Email: oluwatoyosi.abolaji25@gmail.com  
