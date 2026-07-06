# Intelligent AI Attendance System

## Overview
An AI-powered attendance management system built with Python and Streamlit that supports **face recognition** and **voice recognition** based attendance, subject management, student enrollment, and attendance reporting.

## Features
- Face Recognition Attendance
- Voice Recognition Attendance
- Student Enrollment
- Auto Face Enrollment
- Subject Creation & Sharing
- Teacher & Student Dashboards
- Attendance Reports
- Supabase Database Integration
- Modular AI Pipelines

## Tech Stack
- Python
- Streamlit
- OpenCV
- Face Recognition
- Speech/Voice Recognition
- Supabase

## Project Structure

```text
src/
├── components/
├── database/
├── pipelines/
├── screens/
├── ui/
├── app.py
README.md
requirements.txt
```

## Components

### components/
Contains reusable UI dialogs:
- Add Photo
- Face Enrollment
- Voice Attendance
- Subject Management
- Attendance Results
- Header/Footer

### pipelines/
- face_pipeline.py
- voice_pipeline.py

### database/
- config.py
- db.py

### screens/
- Home
- Teacher
- Student

### ui/
Base layout shared across screens.

## Installation

```bash
git clone <repo-url>
cd project
pip install -r requirements.txt
streamlit run src/app.py
```

## Future Enhancements
- Anti-spoofing
- Mobile App
- Analytics Dashboard
- Multi-factor Authentication


