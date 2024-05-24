# EVA: Enhanced Virtual Assistant

## Overview
EVA (Enhanced Virtual Assistant) is a Python-based personal assistant application that leverages speech recognition and text-to-speech technology to provide a hands-free user experience. EVA can greet you based on the time of day, perform web searches, open applications, and execute various commands based on your voice input.

## Features
- **Voice Recognition**: EVA listens to your commands using the microphone and processes them using Google's speech recognition.
- **Text-to-Speech**: EVA can speak responses and provide auditory feedback for the actions it performs.
- **Greetings**: EVA greets you with an appropriate message based on the time of day (morning, afternoon, evening).
- **Wikipedia Search**: EVA can search Wikipedia and read a summary of the results.
- **Open Applications**: EVA can open Notepad and Windows Media Player, and close Notepad.
- **Web Navigation**: EVA can open popular websites like YouTube, Google, Gmail, and Facebook.
- **Music Playback**: EVA can launch the default music player.
- **Exit Command**: EVA can gracefully exit the application upon your command.

## Usage
- **Greeting**: EVA will greet you when the application starts, according to the time of day.
- **Voice Command Recognition**: Say commands like "hello", "wikipedia", "open notepad", "close notepad", "open YouTube", "open Google", "play music", "open mail", "open fb", and "exit".
  - **Wikipedia Search**: Trigger a search by saying "wikipedia" followed by the search term. EVA will read a summary of the Wikipedia article.
  - **Open Notepad**: Say "open notepad" to launch Notepad.
  - **Close Notepad**: Say "close notepad" to close Notepad.
  - **Open YouTube**: Say "open YouTube" to launch YouTube in the default web browser.
  - **Open Google**: Say "open Google" to launch Google in the default web browser.
  - **Play Music**: Say "play music" to open the default music player.
  - **Open Mail**: Say "open mail" to launch Gmail in the default web browser.
  - **Open Facebook**: Say "open fb" to open Facebook in the default web browser.
  - **Exit Application**: Say "exit" to close the assistant.

## Error Handling
- EVA gracefully handles errors by catching exceptions and providing feedback.
- In case of unrecognized voice commands, EVA will inform the user that it was unable to recognize the voice input.

## Conclusion
EVA is a versatile and user-friendly virtual assistant designed to make routine tasks easier through voice commands. It is ideal for users who prefer hands-free operation of their computer for basic tasks such as searching the web, opening applications, and managing media playback.
