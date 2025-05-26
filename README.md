# 🧠 Spotify Genre Tagger

This project uses a pre-trained transformer model (`facebook/bart-large-mnli`) to classify song lyrics or text into Spotify-style genres like Pop, Rock, Hip-Hop, and Latin.

## Features
- Zero-shot classification
- Real lyrics-based examples
- Evaluation using classification report and confusion matrix

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook spotify_genre_tagger.ipynb
```

## Future Improvements
- Fine-tune on a custom dataset with Spotify metadata
- Add Streamlit web interface
- Integrate with Spotify API for real-time classification
