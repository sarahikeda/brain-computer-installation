# brain-computer-interface
Thoughtworks BCI project

- 1) Get credentials from Sarah for google api (it will be a JSON file)

#Speech
- 1) Navigate to speech directory
- 2) `$ virtualenv env`
- 3) `$ source env/bin/activate`
- 4) `$ pip install -r requirements.txt`
- 5) Within `speech` directory, set `export GOOGLE_APPLICATION_CREDENTIALS=` to the path of credentials. (i.e. `export GOOGLE_APPLICATION_CREDENTIALS='../art-a-hack-c0761036ca8c.json'`)
- 7) To test transcription, run `python quickstart.py`. The transcription `how old is the Brooklyn Bridge` should appear.


#Sentiment
- 1) Navigate to sentiment directory
- 2) `$ virtualenv env`
- 3) `$ source env/bin/activate`
- 4) `$ pip install -r requirements.txt`
- 5) Within `sentiment` directory, set `export GOOGLE_APPLICATION_CREDENTIALS=` to the path of credentials. (i.e. `export GOOGLE_APPLICATION_CREDENTIALS='../art-a-hack-c0761036ca8c.json'`)
- 6) To analyze sentiment, CD into `sentiment`
- 7) To test sentiment analysis, run `python sentiment_analysis.py` for a `.txt` file. For example, you can run sentiment analysis on a sample text by doing `python sentiment_analysis.py resouces/pos.txt` and the sentiment score will display in the terminal.

