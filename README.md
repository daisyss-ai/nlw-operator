# ClipMaker 🎬

## Project Overview

**ClipMaker** is an intelligent web application that automatically extracts and generates short, viral-worthy clips from long-form videos. The app uses AI to analyze video transcriptions and identify the most engaging moments, making it easy to repurpose content for social media.

## Purpose

The purpose of this project is to solve a common content creator problem: finding the best moments in long videos. Instead of manually reviewing hours of footage, ClipMaker automates this process by:

1. Uploading videos to the cloud
2. Transcribing the audio
3. Analyzing the transcription with AI to find viral-worthy moments
4. Creating a modern interface to browse and select these moments

## Why I'm Building This

This project is part of the **Next Level Week Operator** (22nd edition - March 12-16, 2026) beginner track by **Rocketseat**. It serves as a practical introduction to:
- Web development fundamentals (HTML, CSS, JavaScript)
- API integration
- Working with AI (Google Gemini)
- Cloud services (Cloudinary)
- Real-world problem-solving through code

The project teaches how JavaScript can interact with HTML elements, handle asynchronous operations, and integrate external services to create a functional web application.

## Technology Stack

### Frontend
- **HTML** - Structure and markup
- **CSS** (with Tailwind) - Styling
- **JavaScript** - Interactivity and logic

### APIs & Services
- **Google Gemini API** - AI analysis of video transcriptions to identify viral moments
- **Cloudinary** - Video upload, storage, and transcription services

### Key Features
- Video upload widget powered by Cloudinary
- Automatic transcription processing
- AI-powered moment detection and analysis
- Real-time interface updates

## What I've Already Done

### Completed
✅ Set up the HTML structure with Cloudinary upload widget  
✅ Configured Cloudinary integration (cloudName: `dcq0maxgt`, uploadPreset: `upload_nlw`)  
✅ Created the app object with core methods:
   - `waitForTranscription()` - Polls Cloudinary to check if transcription is ready
   - `getTranscription()` - Retrieves the transcription
   - `getViralMoment()` - Uses Gemini API to analyze transcription and find viral moments  
✅ Implemented upload event handling  
✅ Set up the basic JavaScript architecture for async operations  

### In Progress / To Do
- [ ] Build the UI to display video information after upload
- [ ] Implement real-time clip preview
- [ ] Create the interface to display viral moments found by Gemini
- [ ] Add styling and polish the user experience
- [ ] Set up environment variables for API keys
- [ ] Test end-to-end workflow
- [ ] Deploy the application

## Project Structure

```
nlw/
├── README.md
├── trilha fullstack/          # Full-stack track materials
├── trilha iniciante/          # Beginner track materials
│   ├── index.html            # Main application file
│   ├── main.css              # Styling
│   └── main.js               # JavaScript logic
```

## Getting Started

1. Clone or access the project
2. Configure your Gemini API key in the code
3. Open `index.html` in your browser
4. Upload a video using the Cloudinary widget
5. Wait for transcription to complete
6. AI will analyze and extract viral moments

## API Integration Notes

### Cloudinary
- Used for secure video upload and storage
- Provides automatic transcription services
- Generates video URLs with version tags for tracking

### Google Gemini
- Analyzes video transcriptions
- Identifies engaging moments and generates timestamps
- Provides context about why moments are viral-worthy

## Learning Outcomes

Through building ClipMaker, I'm learning:
- DOM manipulation with JavaScript
- Asynchronous programming (async/await)
- HTTP requests and API consumption
- Error handling and retry logic
- Integration of multiple services
- Building user-friendly interfaces

---

**Instructor:** Mayk Brito  
**Event:** Next Level Week Operator (22nd Edition)   
**Track:** Beginner - Learn to Program with AI  
**Made with ❤️ by Rocketseat**
