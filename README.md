# whatsapp-chat-analysis
A streamlit app to analyze your whatsapp chats

Demo Link: https://wca-campusx.herokuapp.com/


# WhatsApp Chat Analysis

An intuitive Python application to analyze WhatsApp chats using machine learning. Extract insights, visualize trends, and uncover hidden patterns in your conversations with ease.

## Features

- **Message Statistics**: Analyze the number of messages, word count, and average message length.
- **Participant Analysis**: Track individual user contributions and interactions.
- **Sentiment Analysis**: Discover the emotional tone of conversations using machine learning.
- **Time-Based Trends**: Visualize activity by time, day, or month.
- **Word Cloud**: Generate word clouds to visualize frequently used words.
- **Emoji Analysis**: Count and categorize emojis used in chats.
- **Exportable Results**: Save analysis results as images or CSV files.

## Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - `pandas` for data manipulation
  - `numpy` for numerical computations
  - `matplotlib` and `seaborn` for data visualization
  - `nltk` for text processing
  - `scikit-learn` for machine learning tasks (sentiment analysis)
  - `wordcloud` for generating word clouds
  - `emoji` for emoji analysis

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/whatsapp-chat-analysis.git
   cd whatsapp-chat-analysis
   ```

2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate # On Windows: venv\Scripts\activate
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Export your WhatsApp chat in `.txt` format.
2. Place the exported file in the `data/` directory.
3. Run the analysis script:
   ```bash
   python main.py
   ```
4. Follow the on-screen instructions to generate visualizations and insights.
## Project Structure

```
whatsapp-chat-analysis/
├── data/                # Folder for storing chat files
├── examples/            # Example output images
├── src/                 # Source code
│   ├── analysis.py      # Core analysis functions
│   ├── visualization.py # Visualization functions
│   └── utils.py         # Helper functions
├── requirements.txt     # Python dependencies
├── main.py              # Main application script
└── README.md            # Project README
```

## Contributing

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.

## License

This project is licensed under the MIT License.
