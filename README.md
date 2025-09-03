# Smart_Desktop_Assistant

## Overview
This project is a smart AI-powered desktop assistant that monitors your **face, voice, and typing patterns** in real time to detect your **mental state** (confused, tired, focused, bored).  
Based on the detected state, it provides **personalized study tips, motivational nudges, or break reminders** to enhance productivity and learning efficiency.  

The assistant uses computer vision, voice analysis, and keystroke dynamics to create a multimodal understanding of the user’s current cognitive and emotional state.  

---

## Features
- Detects user’s **mental state**: Focused, Confused, Tired, or Bored.  
- **Face monitoring** (via webcam): eye strain, yawning, gaze tracking.  
- **Voice monitoring** (via mic): tone, pitch, hesitation analysis.  
- **Typing behavior monitoring**: speed, error rate, pauses.  
- Provides **personalized interventions**:
  - Study tips when confused  
  - Break reminders when tired  
  - Motivational nudges when bored  
  - Silent support when focused  
- Privacy-first: all processing can be done locally.  

---

## Installation

Clone the repository:
```bash
git clone https://github.com/username/smart-desktop-assistant.git
cd smart-desktop-assistant
python3 -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate
pip install -r requirements.txt
