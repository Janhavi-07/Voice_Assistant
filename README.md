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

## Weather API Key 💡

- The weather feature in this project uses an API from **OpenWeatherMap**. The API key is **hardcoded** in the code (for learning purposes only) and **is subject to limited usage**.
- If you wish to **use the weather functionality**, it is recommended that you **replace the existing API key** with your own. You can get a free API key from [OpenWeatherMap](https://openweathermap.org/api).

### Steps to Replace the API Key:
1. Go to [OpenWeatherMap](https://openweathermap.org/api) and sign up for a free API key.
2. In the code, locate this line:
    ```python
    url = f"http://api.openweathermap.org/data/2.5/weather?q={city}&appid=YOUR_API_KEY&units=metric"
    ```
3. Replace `YOUR_API_KEY` with the key you received from OpenWeatherMap.
4. Save the changes and run the application.

> **Note**: The current API key is free and has a limited number of requests per minute. If you exceed the quota, the weather feature may stop working.

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
