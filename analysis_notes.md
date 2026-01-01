# Analysis Notes – Student Event Feedback

## Data Inspection
- The dataset contains 100 rows and 3 columns.
- No missing or null values were found.
- Data types are appropriate for analysis:
  - Rating: Integer
  - Feedback: Text

## Rating Analysis
- Ratings are distributed across the 1–5 scale.
- Higher ratings (4 and 5) appear more frequently, indicating overall satisfaction.
- Lower ratings point toward areas needing improvement.

## Sentiment Analysis
- Sentiment polarity was calculated using TextBlob.
- Feedback was classified into:
  - Positive
  - Neutral
  - Negative
- The majority of feedback falls into the positive category.

## Visualization Insights
- Bar charts show a clear dominance of positive sentiment.
- Pie chart highlights sentiment proportions at a glance.
- Word cloud reveals frequently used words such as:
  - “informative”
  - “engaging”
  - “organized”
  - “interactive”

These terms indicate what students value most in events.

## Key Observations
- Students appreciate well-structured and engaging sessions.
- Negative feedback commonly relates to:
  - Event duration
  - Pacing
  - Organization

## Recommendations
- Improve time management and scheduling
- Increase interactive and hands-on activities
- Address logistical issues raised in negative feedback

## Limitations
- Dataset is synthetically generated
- Sentiment analysis is rule-based and may not capture complex emotions

## Final Remark
Despite limitations, this analysis successfully demonstrates how NLP and data visualization can be used to extract meaningful insights from feedback data.
