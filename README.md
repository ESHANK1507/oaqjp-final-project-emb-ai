# Final Project: Emotion Detection Web Application

## Project Overview

This web application detects emotions from user-submitted text using the Watson NLP library and IBM Watson EmotionPredict service. The application is packaged as a reusable Python package (`EmotionDetection`) and deployed as a web interface using Flask.

## Features

- **Emotion Detection:** Analyzes input statements and scores 5 key emotions: `anger`, `disgust`, `fear`, `joy`, and `sadness`.
- **Dominant Emotion Identification:** Identifies the primary emotion with the highest score.
- **Robust Error Handling:** Detects blank or invalid statements (HTTP status 400) and returns `'Invalid text! Please try again!'` without server crashes.
- **Unit Testing:** Comprehensive test coverage via Python's `unittest` framework (`test_emotion_detection.py`).
- **Clean Code Quality:** Passes static code analysis with a perfect **10.00/10** score via `pylint`.
