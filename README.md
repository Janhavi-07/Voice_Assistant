# Venku - Voice Assistant 🎙️

**Venku** is a simple voice assistant built with Python that responds to voice commands and performs actions like checking the weather 🌤️, telling jokes 🤣, opening apps 🖥️, searching on the web 🌐, and more. This assistant is built using the **Tkinter** library for the graphical user interface (GUI), **pyttsx3** for text-to-speech functionality 🎧, and other libraries for speech recognition 🗣️ and web scraping.

## Features ✨
- **Weather updates**: Get real-time weather information for any city 🌍.
- **Voice commands**: Interact with the assistant using natural voice commands 🎙️.
- **Application control**: Open apps like Calculator 🧮, Notepad 📝, Excel 📊, Word 📃, etc.
- **Search on the web**: Perform Google and YouTube searches via voice 🔍.
- **Tell jokes**: Get a random joke using the `pyjokes` library 😂.
- **Time and Date**: Get current time 🕒, date 📅, and day of the week 📆.

## Technologies Used 🛠️
- **Python** 3.x 🐍
- **Tkinter**: For building the GUI 🖼️.
- **pyttsx3**: For text-to-speech functionality 🎤.
- **SpeechRecognition**: For recognizing voice commands 🗣️.
- **requests**: For fetching weather information 🌦️.
- **feedparser**: For fetching news from RSS feeds 📰.
- **pyjokes**: For generating jokes 😆.
- **Pillow**: For handling images (e.g., microphone icon 🎤).

## Installation 🏗️

1. **Clone the repository**:

    ```bash
    git clone https://github.com/yourusername/venku-voice-assistant.git
    ```

2. **Install dependencies**:

    Make sure you have Python 3.x installed, then install the required libraries using `pip`:

    ```bash
    pip install pyttsx3 requests feedparser pyjokes SpeechRecognition Pillow
    ```

## Usage 🚀

1. Navigate to the project folder where you downloaded or cloned the repository.
2. Run the main Python script to start the assistant:

    ```bash
    python main.py
    ```

3. The assistant will launch with a graphical user interface (GUI). Click the **"Start Listening"** 🎤 button and start giving voice commands like:
    - **"What's the weather in [city]?" 🌦️**
    - **"Tell me a joke." 🤣**
    - **"Open Calculator." 🧮**
    - **"Search for [query] on Google." 🔍**

## Acknowledgments 🙏
- **OpenWeatherMap** - For providing weather data via their API 🌤️.
- **pyjokes** - For providing random jokes 🤡.
- **Google News RSS** - For fetching the latest news 📰.
- **Tkinter** - For the GUI 🖼️.
- **pyttsx3** - For text-to-speech functionality 🎤.
