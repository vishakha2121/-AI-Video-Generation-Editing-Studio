# 🎬 AI Video Generation & Editing Studio

> An AI-powered video generation and editing platform that transforms text prompts into professional videos with automated subtitles, voiceovers, and marketing content.

[![GitHub](https://img.shields.io/badge/GitHub-Repository-blue?style=for-the-badge&logo=github)](https://github.com/vishakha2121/-AI-Video-Generation-Editing-Studio)
[![React](https://img.shields.io/badge/React-18.2.0-61DAFB?style=for-the-badge&logo=react)](https://reactjs.org/)
[![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=for-the-badge&logo=python)](https://python.org/)
[![Flask](https://img.shields.io/badge/Flask-2.3.3-000000?style=for-the-badge&logo=flask)](https://flask.palletsprojects.com/)
[![SQLite](https://img.shields.io/badge/SQLite-3.0-003B57?style=for-the-badge&logo=sqlite)](https://sqlite.org/)
[![Tailwind](https://img.shields.io/badge/Tailwind-3.3.5-06B6D4?style=for-the-badge&logo=tailwindcss)](https://tailwindcss.com/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

---

## 📋 Table of Contents

- [🎯 Overview](#-overview)
- [✨ Features](#-features)
- [🛠️ Tech Stack](#️-tech-stack)
- [📁 Project Structure](#-project-structure)
- [🚀 Quick Start](#-quick-start)
- [📦 Installation](#-installation)
- [🔧 Configuration](#-configuration)
- [🏃 Running the Application](#-running-the-application)
- [📊 Database Setup](#-database-setup)
- [🧪 Testing](#-testing)
- [📚 API Documentation](#-api-documentation)
- [🎨 UI Components](#-ui-components)
- [🤖 AI Services](#-ai-services)
- [📈 Performance Optimization](#-performance-optimization)
- [🐛 Troubleshooting](#-troubleshooting)
- [📝 Contributing](#-contributing)
- [📄 License](#-license)
- [👨‍💻 Author](#-author)
- [🙏 Acknowledgments](#-acknowledgments)

---

## 🎯 Overview

**AI Video Generation & Editing Studio** is a comprehensive web application that democratizes video content creation using cutting-edge artificial intelligence. Built for content creators, educators, marketers, and businesses, this platform enables users to generate professional-quality videos from simple text descriptions without requiring any video editing expertise.

### 🎬 What Makes This Project Special?

- **⚡ Speed**: Generate videos in minutes, not days
- **🎯 Accessibility**: No technical skills required
- **🤖 AI-Powered**: Leverages state-of-the-art AI models
- **💰 Cost-Effective**: Eliminates expensive software and hardware
- **🔄 Versatile**: Supports multiple content types and use cases

### 📊 Use Cases

| Industry | Application |
|----------|-------------|
| **Marketing** | Product demos, social media ads, promotional videos |
| **Education** | Online courses, training videos, explainer animations |
| **E-commerce** | Product showcases, review videos, unboxing content |
| **Corporate** | Internal communications, presentations, reports |
| **Content Creation** | YouTube videos, TikTok content, Instagram reels |

---

## ✨ Features

### 🚀 Core Features

#### 1. **AI Video Generation**
- ✅ Transform text prompts into full videos
- ✅ 10+ visual styles (cinematic, animated, minimalist, corporate, 3D, etc.)
- ✅ Customizable duration (5-60 seconds)
- ✅ Multiple resolutions (480p, 720p, 1080p)
- ✅ Scene-by-scene generation with smooth transitions
- ✅ Real-time generation progress tracking

#### 2. **Smart Video Editing**
- ✅ Automated scene detection and trimming
- ✅ 20+ transition effects
- ✅ AI-powered filters and color grading
- ✅ Interactive timeline editor
- ✅ Crop, rotate, and resize tools
- ✅ Export in multiple formats (MP4, AVI, MOV)

#### 3. **Automated Subtitle Generation**
- ✅ Speech-to-text using OpenAI's Whisper
- ✅ 50+ language support
- ✅ Interactive subtitle editor with timing controls
- ✅ Auto-sync with video timeline
- ✅ Export SRT, VTT, and TXT formats
- ✅ Style customization (font, size, color, position)

#### 4. **AI Voiceover Generation**
- ✅ Natural-sounding TTS with 30+ voices
- ✅ Multiple languages and accents
- ✅ Speed and pitch customization
- ✅ Emotion and emphasis controls
- ✅ Background noise reduction
- ✅ Audio mixing capabilities

#### 5. **Marketing Content Generator**
- ✅ AI-powered video descriptions
- ✅ Social media optimized captions
- ✅ SEO-friendly titles and tags
- ✅ Auto-generated thumbnails
- ✅ Content calendar planning
- ✅ Performance analytics

#### 6. **Educational Video Creator**
- ✅ Automated lesson planning
- ✅ Interactive quiz creation
- ✅ Animated explainer videos
- ✅ Module-based content structuring
- ✅ Student engagement analytics
- ✅ Assessment and grading tools

### 🎨 UI/UX Features

- ✅ **Modern Design**: Glassmorphism with animated transitions
- ✅ **Dark/Light Mode**: Eye-friendly theme switching
- ✅ **Responsive**: Works on desktop, tablet, and mobile
- ✅ **Real-time Updates**: Live progress tracking
- ✅ **Drag & Drop**: Easy file uploads
- ✅ **Keyboard Shortcuts**: Quick actions for power users
- ✅ **Toast Notifications**: Friendly feedback system

---

## 🛠️ Tech Stack

### Frontend
| Technology | Version | Purpose |
|------------|---------|---------|
| **React.js** | 18.2.0 | UI Framework |
| **React Router** | 6.18.0 | Navigation |
| **Tailwind CSS** | 3.3.5 | Styling |
| **DaisyUI** | 3.9.2 | UI Components |
| **Framer Motion** | 10.16.4 | Animations |
| **Axios** | 1.6.0 | HTTP Client |
| **React Query** | 3.39.3 | Data Fetching |
| **React Hook Form** | 7.47.0 | Form Handling |
| **Yup** | 1.3.3 | Validation |
| **React Player** | 2.13.0 | Video Playback |
| **Wavesurfer.js** | 7.4.2 | Audio Visualization |
| **React Icons** | 4.11.0 | Icons |
| **Recharts** | 2.8.0 | Charts |

### Backend
| Technology | Version | Purpose |
|------------|---------|---------|
| **Python** | 3.9+ | Programming Language |
| **Flask** | 2.3.3 | Web Framework |
| **Flask-SQLAlchemy** | 3.0.5 | ORM |
| **Flask-JWT** | 4.5.3 | Authentication |
| **Celery** | 5.3.4 | Task Queue |
| **Redis** | 5.0.0 | Message Broker |
| **SQLite** | 3.0 | Database |
| **Gemini API** | Latest | AI Integration |
| **OpenAI Whisper** | Latest | Speech Recognition |
| **gTTS** | 2.3.2 | Text-to-Speech |
| **MoviePy** | 1.0.3 | Video Processing |
| **OpenCV** | 4.8.1 | Image Processing |
| **NumPy** | 1.24.3 | Numerical Operations |

### DevOps & Tools
| Technology | Purpose |
|------------|---------|
| **Git** | Version Control |
| **Docker** | Containerization |
| **Docker Compose** | Multi-container Setup |
| **Vite** | Build Tool |
| **ESLint** | Code Linting |
| **Prettier** | Code Formatting |
| **Pytest** | Testing |
| **Black** | Python Code Formatter |

---

## 📁 Project Structure

---

## 🚀 Quick Start

### Prerequisites

| Requirement | Version |
|-------------|---------|
| **Node.js** | 16.0.0 or higher |
| **npm** | 8.0.0 or higher |
| **Python** | 3.9 or higher |
| **pip** | Latest version |
| **Git** | Latest version |
| **SQLite** | 3.x |

### One-Line Setup (Linux/Mac)
```bash
curl -s https://raw.githubusercontent.com/vishakha2121/-AI-Video-Generation-Editing-Studio/main/setup.sh | bash

# Clone repository
git clone https://github.com/vishakha2121/-AI-Video-Generation-Editing-Studio.git
cd ai-video-studio

# Setup backend
cd backend
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt

# Setup frontend
cd ../frontend
npm install

# Setup database
cd ../database
sqlite3 video_studio.db < migrations/001_initial_schema.sql

# Configure environment
cp ../.env.example ../.env
# Edit .env with your API keys

# Run the application
# Terminal 1 - Backend
cd ../backend
python run.py

# Terminal 2 - Frontend
cd ../frontend
npm run dev