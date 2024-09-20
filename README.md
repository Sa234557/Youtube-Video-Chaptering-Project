# Youtube-Video-Chaptering-Project
This project extracts YouTube video transcripts, performs text cleaning, applies topic modeling to identify key topics, and detects logical chapter breaks in the video. The project utilizes the YouTube Data API for fetching video details, SpaCy for natural language processing (NLP), and Non-Negative Matrix Factorization (NMF) for topic modeling.

Features:
1.Video Transcript Extraction: Fetches and processes the transcript of a YouTube video.
2.Topic Modeling: Identifies key topics from the cleaned transcript using NMF.
3.Chapter Detection: Automatically detects and outputs video chapter points based on topic shifts.

API Key Setup:
To fetch video details from YouTube, you need to provide your own YouTube Data API v3 key.

Steps to Obtain an API Key:
1.Go to the Google Cloud Console.
2.Create a new project and enable the YouTube Data API v3.
3.Go to the Credentials section and generate an API Key.
4.Replace 'your api key' in the code with your own API key.

Project Workflow:
Input: You provide a YouTube video URL.
Transcript Extraction: The script retrieves the transcript and cleans it using SpaCy.
Topic Identification: Using NMF, it identifies dominant topics in the video.
Chaptering: The script detects logical chapter breaks based on topic transitions.
Output: It saves the transcript to a CSV file and displays the identified topics and chapters.

License:
This project is licensed under the MIT License.
