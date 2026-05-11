# emotions-detection-from-text
AI-powered web app that detects emotions from text using Claude API — with real-time probability charts.
# Text Emotion Detection

A lightweight, AI-powered web application that analyzes any text input and identifies 
the underlying emotion it carries — built with vanilla HTML/CSS/JS and the Anthropic Claude API.

## Features
- Detects 8 emotions: Joy, Anger, Sadness, Fear, Disgust, Surprise, Shame, Neutral
- Real-time confidence score with visual progress bar
- Color-coded probability bar chart for all emotion categories
- One-sentence AI explanation for each prediction
- Sample phrases to try instantly
- Zero dependencies — single HTML file, runs in any browser

## How It Works
1. User types or pastes any text into the input area
2. The text is sent to Claude (claude-sonnet-4) via the Anthropic API
3. Claude returns emotion scores, confidence, and a brief analysis
4. Results are displayed with a bar chart and prediction card

## Tech Stack
- HTML / CSS / JavaScript (vanilla)
- Anthropic Claude API (claude-sonnet-4)
- Chart.js for probability visualization
- Google Fonts — DM Sans + DM Serif Display

## Getting Started
1. Clone the repo
2. Open `emotion_detection.html` in your browser
3. Make sure your Anthropic API key is configured
4. Type any text and click Submit

## Topics / Tags
`emotion-detection` `nlp` `sentiment-analysis` `claude-api` `anthropic` 
`javascript` `chartjs` `ai` `text-classification` `single-page-app`
