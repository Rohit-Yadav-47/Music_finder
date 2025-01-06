# 🎵 SONG RADAR

A powerful music discovery and identification app that combines audio recognition, lyrics search, and AI-powered music recommendations.

## ✨ Features

### 1. 🎤 Record & Identify
- **Live Audio Recording**: Record song snippets directly through your browser
- **Advanced Song Recognition**: Powered by ACRCloud's audio fingerprinting technology
- **Rich Song Details**:
  - Album artwork and track information
  - Genre, release date, and duration
  - Streaming links (Spotify, YouTube, Apple Music)
  - Audio preview when available
  - Full and synchronized lyrics

### 2. 🔎 Song Search
- **Comprehensive Search**: Find songs by name, artist, or album
- **Detailed Results**:
  - High-quality album artwork
  - Complete track metadata
  - Direct streaming links
  - Audio previews
  - Genre and release information

### 3. 📝 Lyrics Search
- **Advanced Lyrics Search**: Find songs by their lyrics
- **Multiple Display Options**:
  - Plain text lyrics
  - Synchronized lyrics (when available)
  - Support for instrumental track identification

### 4. 🤖 AI Music Expert
- **Interactive Music Chat**: Powered by Groq's Mixtral-8x7B model
- **Expert Knowledge**:
  - Song recommendations
  - Artist information
  - Music history and theory
  - Playlist creation
  - Genre analysis
  - Musical instruments
  
### 5. 🎨 Beautiful UI
- **Modern Design**: Clean and responsive interface
- **Animated Elements**: Smooth transitions and loading states
- **Dark Mode**: Easy on the eyes
- **Interactive Components**: Dynamic music visualizations

## 🚀 Getting Started

### Prerequisites
```bash
python 3.8+
streamlit
groq
requests
audio-recorder-streamlit
```

### Installation
1. Clone the repository:
```bash
git clone https://github.com/yourusername/song-radar.git
cd song-radar
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Set up your API keys in `.env`:
```env
ACCESS_KEY=your_acrcloud_access_key
ACCESS_SECRET=your_acrcloud_access_secret
GROQ_API_KEY=your_groq_api_key
```

4. Run the app:
```bash
streamlit run main.py
```

## 🔧 Technology Stack

- **Frontend**: Streamlit
- **Audio Processing**: ACRCloud API
- **Lyrics**: LRCLIB API
- **AI Chat**: Groq API (Mixtral-8x7B)
- **Music Metadata**: ACRCloud Metadata API

## 🎯 Usage Examples

### Recording a Song
1. Click the "Record & Identify" tab
2. Press the record button
3. Play your song for 5-10 seconds
4. Wait for identification results

### Searching by Lyrics
1. Navigate to "Lyrics Search"
2. Enter any part of the song lyrics
3. View matching songs with full lyrics

### AI Music Expert
Example questions:
- "Recommend some relaxing jazz for studying"
- "Explain the difference between blues and jazz"
- "Create a workout playlist with 90s rock songs"
- "Tell me about the history of electronic music"

## 📝 API Credits
- ACRCloud for audio recognition
- LRCLIB for lyrics database
- Groq for AI conversations

## 🤝 Contributing
Contributions are welcome! Please feel free to submit pull requests.

## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.