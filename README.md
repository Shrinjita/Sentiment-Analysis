# Twitter Sentiment Analysis
### Key Features:
- **Data Preprocessing**: Reads a CSV file containing tweets and prepares the text for sentiment analysis.
- **Sentiment Analysis with BERT**: Uses the Hugging Face `transformers` library to classify tweets based on sentiment.
- **Data Visualization**: Generates a sentiment distribution plot to provide a visual summary of the analysis.
- **CSV Output**: Saves the analyzed data with sentiment labels in a new CSV file.

---

## Requirements

- Python 3.x
- Required Libraries:
  - `transformers`
  - `pandas`
  - `matplotlib`
  - `seaborn`

Install the required libraries using the following command:

```bash
pip install transformers pandas matplotlib seaborn
```

---

## Usage Instructions

1. **Clone the repository** (if applicable) or download the script and dataset.
2. **Place your dataset** (CSV file) in the same directory as the script.
3. **Edit the file path** in the script to match your dataset location.
4. **Run the script** to analyze the sentiment of tweets:
   ```bash
   python sentiment_analysis.py
   ```

---

## Files and Structure

- `sentiment_analysis.py`: Main script that performs sentiment analysis on the dataset.
- `Twitter Sentiments.csv`: The input CSV file containing tweets (replace this with your own file).
- `sentiment_analysis_results.csv`: The output CSV file with sentiment labels for each tweet.

---

## Output

- **Sentiment Analysis Results**: The script generates a new CSV file (`sentiment_analysis_results.csv`) with an added column for the sentiment of each tweet.
- **Visualization**: The sentiment distribution of the dataset is visualized using a bar plot.

---

## Example

Sample command to run the script:

```bash
python sentiment_analysis.py
```

Upon running, you'll get a new CSV file and a visualization of sentiment distribution.

---

## Future Improvements

- Support for additional sentiment categories (e.g., neutral).
- Integration with larger datasets using GPU acceleration.
- Implementation of more advanced models like RoBERTa for fine-tuned sentiment analysis.
