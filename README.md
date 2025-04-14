## 🎤 AI Voice Recorder App with Web Integration
## 🎤 Voice-to-Text Summariser App

A small personal project built with React Native and TypeScript.
A project that delivers an AI-powered voice recorder as a mobile application by integrating a web service.
The app is still a work in progress, and I plan to continue improving its functionality and UI.

### Core Features (Web service - Next.js)
- Voice recording and transcription  
- Summerisation from transcription

### ✨ New Features Introduced

- **Camera Capture During Recording**: Users can take photos while recording audio  
- **Script History Saving**: Stores transcription history for later reference  

---

### 🔧 Technical Overview

#### 0. Web Component (Next.js)  
[Git Repository](https://github.com/sunikko/ai-recording-web)  
- Voice recording feature  
- Audio-to-script conversion  
- Summarisation using OpenAI API  

#### 1. App Integration via WebView  
- Loads the web component inside the app using a WebView  
- Ensures consistent UI/UX across platforms  

#### 2. Native Recording Functionality  
- Uses the app's native recording API (rather than web recording) for better device compatibility  

#### 3. Additional Feature: Camera Support  
- Integrated native camera API to allow photo capture during recordings  

#### 4. Additional Feature: History Storage  
- Saves data locally on the device  
- Displays a list of past recordings and transcriptions  

