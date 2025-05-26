# 🧠 Spotify Genre Tagger – Zero-Shot Classification with DistilBERT
This project demonstrates a lightweight zero-shot genre classification system using Hugging Face’s transformers library. It classifies music-related text (like lyrics, song summaries, or tags) into Spotify-style genres such as Pop, Hip-Hop, Rock, and Latin—without requiring model fine-tuning.

# 📌 Features
•	Zero-shot classification using typeform/distilbert-base-uncased-mnli
•	No training required — just inference on real lyric samples
•	Classifies into multiple genres based on semantic understanding
•	Includes evaluation via precision, recall, F1-score
•	Visualizes results with a confusion matrix


# 📊 Results
•	Achieved 100% precision, recall, and F1-score on a 3-sample test
•	Model successfully predicted correct genres for lyric-based prompts


# 🧠 Technologies & Dependencies
# Tool/Library	Purpose
transformers	Zero-shot classification pipeline
pandas	DataFrame for lyric & genre data
scikit-learn	Model evaluation (metrics, confusion matrix)
seaborn + matplotlib	Visualization
jupyter	Notebook execution and documentation

# 💻 How to Run

# Install dependencies
pip install -r requirements.txt

# Launch the notebook
jupyter notebook spotify_genre_tagger.ipynb

# 🧪 Folder Contents

spotify_genre_tagger.ipynb     # Fully documented notebook
README.md                            # Project overview
requirements.txt                     # Required libraries

# 🔭 Potential Future Improvements
•	Use the Spotify API to fetch real artist/track metadata
•	Fine-tune genre classification on a custom dataset
•	Deploy via Streamlit for interactive song-to-genre prediction
