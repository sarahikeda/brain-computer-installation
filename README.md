# brain-computer-interface
Thoughtworks BCI project

- 1) Get credentials from Sarah for google api (it will be a JSON file)

#Speech
-   Navigate to speech directory
-  `$ virtualenv env`
-  `$ source env/bin/activate`
-  `$ pip install -r requirements.txt`
-  `$ brew install portaudio`
-  `$ pip install pyAudio`
-  Within `speech` directory, set `export GOOGLE_APPLICATION_CREDENTIALS=` to the path of credentials. (i.e. `export GOOGLE_APPLICATION_CREDENTIALS='../art-a-hack-c0761036ca8c.json'`)
-  To test transcription, run `python transcribe_streaming_mic.py`. 
-  Navigate to `http://127.0.0.1:5000/`
-  Make sure computer's microphone is functional and say a phrase
-  Browser will render sentiment analysis results and data viz

 
