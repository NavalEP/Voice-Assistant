# Voice-Assistant

## Description
This project, "Blue," is a voice-controlled assistant built in Python. It uses the `speech_recognition`, `selenium`, `webbrowser`, `playsound`, `os`, `re`, `requests`, `random`, `time`, and `gtts` libraries to perform tasks like logging into Moodle, searching study materials on Google and YouTube, playing music on YouTube Music, throwing dice, and fetching weather updates.

## Features
- **Voice-activated Moodle Login**: Logs into Moodle with voice commands.
- **Search Study Materials**: Voice command search for study materials on Google and YouTube.
- **Music Playback**: Plays songs from YouTube Music based on voice commands.
- **Dice Simulator**: Simulates a dice throw.
- **Weather Updates**: Provides weather updates based on the user's location.

## Prerequisites
Before running this project, you need to have the following installed:
- Python 3
- Selenium WebDriver
- ChromeDriver (compatible with your version of Google Chrome)
- The libraries mentioned above, which can be installed using the command:

-pip install speech_recognition selenium webbrowser playsound os re requests random time gtts

## Installation
1. Clone the repository to your local machine using:

- git clone <https://github.com/NavalEP/Voice-Assistant>
2. Ensure you have ChromeDriver installed in the root directory of the project.

3. Install all required Python libraries:

-pip install -r requirements.txt

### python assistant.py
## Usage
To start the assistant, run the script from your command line:
Follow the voice prompts to interact with the assistant. You can say "exit," "quit," or "no" to stop the assistant.

## Functions
### `moodle_login()`
This function handles logging into Moodle by opening a Chrome browser session, waiting for user input for credentials, and performing the login operation.

### `search_studm()`
Asks the user for a topic, searches it on Google and YouTube, and opens the search results in the default web browser.

### `p_songs()`
Plays a song specified by the user through voice command on YouTube Music.

### `die()`
Simulates the rolling of a dice and announces the result.

### `weather()`
Fetches and announces the current weather based on the user's IP address location.








