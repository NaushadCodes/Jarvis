=>LIBRARIES USED 
    
    1 speech_recognition 
    
    2 webbrowser 
    
    3 pyttsx3 
    
    4 musicLibrary 
    
    5 requests 
    
    6 openai 
    
    7 gTTS 
    
    8 pygame 
    
    9 os

=>FEATURES 
    
    1 Voice Recognition 
    
    2 Utilizes the speech_recognition library to listen for and recognize voice commands. 
    
    3 Activates upon detecting the wake word "Jarvis." 
    
    4 Converts text to speech using pyttsx3 for local conversion. 
    
    5 Uses gTTS (Google Text-to-Speech) and pygame for playback. 
    
    6 Web Browsing. 
    7 Opens websites like Google, Facebook, YouTube, and LinkedIn based on voice commands. 
    
    8 Music Playback 
    9 Interfaces with a musicLibrary module to play songs via web links. 
    
    10 News Fetching 
    11 Fetches and reads the latest news headlines using NewsAPI. 
    
    12 OpenAI Integration 
    13 Handles complex queries and generates responses using OpenAI's GPT-3.5-turbo. 
    
    14 Acts as a general virtual assistant similar to Alexa or Google Assistant

=> WORKFLOW
  1. Initialization
  2. Greets the user with "Initializing Jarvis...."
  4. Listens for the wake word "Jarvis."
  5. Acknowledges activation by saying "Ya."
  6. Command Processing.
  7. Processes commands to determine actions such as opening a website, playing music, fetching news, or generating a response via OpenAI.
  8. Speech Output. 
  9. Provides responses using speak function with either pyttsx3 or gTTS.
  10. Greets the user with "Initializing Jarvis...."
  11. Wake Word Detection
  12. Acknowledges activation by saying "Ya."
