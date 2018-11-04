# (to be updated with-in next couple of days)
# KT-Speech-Crawler: Automatic Dataset Construction for Speech Recognition from YouTube Videos

## Web demo
http://emnlp-demo.lakomkin.me/


## Installation
```
git clone https://github.com/EgorLakomkin/KTSpeechCrawler
pip install webvtt-py SpeechRecognition path.py flask python-Levenshtein tqdm unicodedata
```

## Docker
TODO:

## Running crawler
```
sh ./crawler/en_corpus.sh <dir_with_intermediate_results> <dir_for_resulting_samples>
```
## Browsing samples
```
python server.py --corpus <dir_for_resulting_samples>
Goto: http://localhost:8888/
```
