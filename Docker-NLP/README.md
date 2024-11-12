# NLP examples

This directory contains examples of how to use the NLP Docker image. The image is based on Guides by [Docker](https://docs.docker.com/guides/sentiment-analysis/).

## Sentiment analysis

### Running the application

1) Build the image

```bash
docker build -t basic-nlp .
```

2) Run the image

```bash
docker run -it basic-nlp 01_sentiment_analysis.py
```

3) Analyze sentiments of a sentence on the terminal

The script will prompt you to enter a sentence. Enter a sentence and press enter. The script will output the sentiment of the sentence. Type `exit` to stop the container.