# Stock signal based on fundamental and technical indicators
## Desired Outcomes
I hope to ingest Yahoo news articles from Yahoo API for sentiment analysis and track recent % changes or technical indicators in top stocks in major industries and feed into an LSTM model which I will train in general over a years worth of data (Industry specific). The focus is to showcase and practice data and software architecture patterns. 
I intend to use a local docker app to run the Kafka cluster and possibly ingest such data to BigTable (if we want to store the news article) or BigQuery (if we analyze sentiment during stream).
Hope to use TKinter to have a simple UI that can return the result. 
If the project goes well I can migrate the application to cloud and view the results on an interactive looker dashboard. 

## Technical Goals
1. Build an end to end pipe that works.
2. **Kafka configured to scale with correct configurations.**
3. Use a model like LSTM to suggest price movement. Can bucket ranges of price movements to avoid overcomplex features.
4. Store feature data in BigQuery with the correct partitioning and clustering technique.
5. **Debugging - Test Driven Development.**

## References - I hope to use
1. Kafka: A definitive guide
2. I heart logs
3. AI book
4. Any similar ML pipes on stock performance.
