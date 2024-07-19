# Voicebot-with-flask 
It is a voice assistant that uses OpenAI and IBM Watson Speech Library. This web project take voice input, convert it to text using speech-to-text technology, send the text to open ai's gpt-3 model, recieve a response , convert it back to text & voice to playit back to the user. 

# Prerequest
-you need to create an account for watson use the free version and copy the api key.
- create a folder inside this project name it certs. create a file named rootCA.crt paste the generated key inside this file.
- install docker

# Steps 
- clone the project : 'git clone '
- finish the above pre-requests.
- start the docker.
- buid the project : 'docker build . -t name-of-your-project'
- run the project : 'docker run -p 8000:8000 name-of-your-project'

# Screenrecord 
![Watch the video](demo-video/voice-assistant.mp4)
