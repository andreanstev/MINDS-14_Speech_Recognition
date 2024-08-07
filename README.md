# MINDS-14_Speech_Recognition

Speech recognition is a methodologies and technologies that enable the recognition and translation of spoken language into text by computers. It is also known as automatic speech recognition (ASR). ASR help human for interacting to computer by gives the machine to understand what was said and its speech patterns, speaking styles, dialects, accents and phrases.

The dataset used are from the paper by Gerz et al. termed MInDS-14. The dataset contains multilingual and cross-lingual intent detection from spoken data. The dataset includes 14 intents that were identified in a commercial e-banking system. Each intent is associated with spoken examples across 14 distinct language varieties. We limited the scope by only use 5 distinct language, i.e. "zh-CN", "ru-RU", "fr-FR", "en-US", "de-DE".

## Model Metrics
Word Error Rate (wer): Common metric of the performance of an automatic speech recognition system. Lower wer are more desired.

## Project Structure
1. Data Preparation

Covers combining array of sentences into one sentence for each "clean_article" and "clean_summary".

2. Exploratory Data Analysis

Conduct thorough analysis of the content in English transcription to understand their structure, distribution, and key features.

3. Fine Tuning

Fine tuning Whisper models for speech recognition.

4. Inference Pipeline

An end-to-end pipeline from ASR to intent classification.

