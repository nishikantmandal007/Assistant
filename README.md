
# VocAssistant

**VocAssistant** is a personal voice assistant built with Python that uses speech recognition and natural language processing to understand and execute user commands. It offers functionalities like web searches, weather updates, music playback, reminders, email messaging, and calendar management, all through voice interactions.

## Features

- **Voice Command Recognition**: Recognizes and interprets spoken commands.
- **Natural Language Processing**: Understands the intent behind user queries.
- **Web Search**: Performs searches and retrieves information.
- **Weather Updates**: Provides real-time weather for any location.
- **Music Playback**: Plays music via voice commands.
- **Reminders & Alarms**: Sets reminders and alarms.
- **Email & Messaging**: Sends emails or messages using voice instructions.
- **Calendar Management**: Manages events and schedules.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/nishikantmandal007/Seraphina.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd Assistant
   ```
3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
4. **Install PyAudio:**
   - **Windows**: Download the appropriate PyAudio wheel file and install using `pip`.
   - **Linux**: Install `portaudio` via your package manager, then `pip install pyaudio`.
   - **macOS**: Use Homebrew `brew install portaudio` and then `pip install pyaudio`.

## Running VocAssistant

Start the assistant with:
```bash
python assist.py
```

## Usage

1. Launch `assist.py`.
2. Wait for the initialization greeting.
3. Speak your command clearly after the prompt.
4. VocAssistant will process and respond accordingly.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for suggestions or improvements.

## License

This project is licensed under the MIT License.
