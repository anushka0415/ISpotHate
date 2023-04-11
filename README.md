# ISpotHate
A plugin that censors offensive language and removes hateful tweets.

## Project Overview
NLP model using spaCy and sklearn. 
Created a REST API using Flask so that the Google Chrome plugin is able to communicate with our NLP model.  parsed the Twitter webpage for text-only versions of visible Tweets and sent it to our NLP model to be classified. 
If the Tweet is classified as hate speech, it is hidden from the user. 
Additionally,incorporated a list of vulgar words with this Google Chrome plugin; if the tweet contains a vulgar word, it is censored.

## How to Run
1. First, run the backend NLP Flask server at `server/server.py`.

To use Google Chrome extension:
1. Go to `chrome://extensions`.
2. Turn on developer mode.
3. Click load unpacked extension.
4. Select the `chrome_ext` folder.

## Demo Video:
https://youtu.be/HHCwH0IjGiw
