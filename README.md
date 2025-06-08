## Ethiopian Banks App Review Analysis

This project analyzes user reviews of major Ethiopian bank mobile applications to identify user sentiments and key feedback themes. The focus is on three banks: Commercial Bank of Ethiopia, Bank of Abyssinia, and Dashen Bank.

### Objectives

- Perform sentiment analysis using VADER and BERT.
- Extract and rank keywords from user reviews.
- Group keywords into high-level themes.
- Annotate reviews with sentiment scores and identified themes.
- Export structured data for further analysis or reporting.

### Features

- Cleans and processes raw review data.
- Performs sentiment classification using two models.
- Uses a keyword extraction method based on TF-IDF.
- Applies manual clustering to group related feedback into themes.
- Saves results in a structured CSV format with the following fields:
  - `review_id`
  - `review_text`
  - `sentiment_label`
  - `sentiment_score`
  - `identified_theme(s)`

### Technologies Used

- Python (pandas, scikit-learn, NLTK, transformers)
- VADER for rule-based sentiment analysis
- BERT for contextual sentiment analysis
- TF-IDF for keyword scoring

### Output

- Cleaned and annotated dataset
- Thematic insights per bank
- Exported CSV file containing all relevant fields for downstream tasks

### Usage

1. Clone the repository.
2. Install the required libraries.
3. Run the notebook or scripts step-by-step.
4. Review the output CSV file and visualizations.