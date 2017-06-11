# cbf_denver_watson_toneanalyzer

## Description
This project, written in Python, utilizes the IBM Bluemix - Watson API Tone Analyzer to analyze text input from the comand line.  This project will console log an analysis that includes the name of the emotion and the probability each emotion (anger, disgust, fear, joy and sadness) was represented within the submitted text.

From IBM: Tone Analyzer leverages cognitive linguistic analysis to identify a variety of tones at both the sentence and document level. This insight can then used to refine and improve communications. It detects three types of tones, including emotion (anger, disgust, fear, joy and sadness), social propensities (openness, conscientiousness, extroversion, agreeableness, and emotional range), and language styles (analytical, confident and tentative) from text.

#### Technologies
- IBM Bluemix / Watson API - Tone Anlayzer Service
- Python

#### Requirements
You will need to touch a .env file and add your Bluemix / Watson Tone Analyzer credentials to that file in order for the API calls to work.  Format of the .env file should be:
TONE_USERNAME="...YOUR USERNAME HERE..."
TONE_PASSWORD="...YOUR PASSWORD HERE..."