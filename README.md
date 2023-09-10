# Python-Speak-Command
Control ypur system through your own voice using python
Welcome to the Voice-Controlled Application Launcher! This Python script allows you to open various applications using your voice commands. It utilizes the power of speech recognition and text-to-speech synthesis to create a hands-free experience.

# Features

- Launch popular applications like Google Chrome, Notepad, Brave Browser, Paint, Microsoft Word, Microsoft Excel, File Explorer (Windows Explorer), and Calculator.
- Provides an interactive voice-based interface.


# Preview:

Here's a quick demo of the Voice-Controlled Application Launcher in action:
https://github.com/neelay-16/Python-Speak-Command/assets/135517502/17af1c18-35da-450f-a1a9-61d23da9744e


# Installation

Before you get started, make sure you have the following installed:
- Python 3.x installed.
- Required Python libraries:
  - webbrowser
  - os
  - speech_recognition
  - pyttsx3
 
    
![image](https://github.com/neelay-16/Python-Speak-Command/assets/135517502/e1fc5de5-a513-4bf1-9752-045a42ba948a)

Luckily,we get the webbrowser and os module already installed in the python standard library while installing the anaconda. For the remaining libraries,you can either install it from your cmd or from your jupyter notebook itself:


![image](https://github.com/neelay-16/Python-Speak-Command/assets/135517502/8d69af87-69af-4739-9e96-c8de4ce63f83)
![image](https://github.com/neelay-16/Python-Speak-Command/assets/135517502/aca8c382-7f26-4262-a7cc-06dc3b413267)

# Description

There are three functions speak(),open_url(),open_application()

Through speak() we are able to communicate with the program where we initialised pyttsx3

![image](https://github.com/neelay-16/Python-Speak-Command/assets/135517502/00ae7190-2cf5-4f54-848b-9b354ee47c35)

Through open_url() we are able to open the url on the browser

![image](https://github.com/neelay-16/Python-Speak-Command/assets/135517502/0b497b96-68fe-4e7e-80d6-f61866d9fb22)

And in the open_application() I am using exception handling because this function I have designed in such a way that I want to open the applications using their respective commands i.e the way we open application from CLI but I dont know what all applications I am having on my system that's why I am using exception handling

![image](https://github.com/neelay-16/Python-Speak-Command/assets/135517502/2728aaa0-e196-4c5b-abeb-42bb164496f4)

Further,I am telling my program to speak something so that I understand what exactly my program wants from me:

![image](https://github.com/neelay-16/Python-Speak-Command/assets/135517502/70c042a3-3455-4856-be2b-4cca3f875395)

Using the Recognizer(),my program is able to understand that what am I speaking. In python using the speech_recogniton library and using Recognizer(), we can make our program capable enough to understand our language

![image](https://github.com/neelay-16/Python-Speak-Command/assets/135517502/8a005aed-b32d-4f03-a0f0-36299fee1ef0)

Next,I am making my program capable to listen to my voice:

![image](https://github.com/neelay-16/Python-Speak-Command/assets/135517502/8c0ea236-b6a8-4074-a9a6-0d870c41dd24)

Again,by using exception handling I am telling my program to recognize my voice and perform the respective action as per my voice command: 

![image](https://github.com/neelay-16/Python-Speak-Command/assets/135517502/56a4f52a-670f-49fd-a649-0027a73493df)


# Customization
You can easily customize this script by adding more application options or changing the voice commands. Simply update the if statements in the code accordingly.

![image](https://github.com/neelay-16/Python-Speak-Command/assets/135517502/5cee3356-4118-4b77-8179-ff1acf93abac)


# Troubleshooting
If you encounter any issues or errors while using the script, please make sure you have the required dependencies installed and your microphone is properly configured.




Thank you for using the Voice-Controlled Application Launcher! If you have any questions, suggestions, or contributions, please feel free to open an issue or submit a pull request.
















