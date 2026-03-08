# LearnSign 🤟

<div align="center">
  <img src="public/assets/imgs/image.png" alt="LearnSign Logo" width="300"/>

  **"Duolingo for Sign Language" — AI-Powered Indian Sign Language Learning & Translation Platform**

  *Empowering children with innovative sign language education*

  [![GitHub](https://img.shields.io/badge/GitHub-LearnSign-blue?logo=github)](https://github.com/amithkm9/LearnSign_pro)
  [![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
  [![Node.js](https://img.shields.io/badge/Node.js-18.x-brightgreen?logo=node.js)](https://nodejs.org/)
  [![AWS](https://img.shields.io/badge/AWS-Powered-orange?logo=amazonaws)](https://aws.amazon.com/)
  [![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow)](https://www.tensorflow.org/)

  ---

  > 🏆 **Submitted to the AWS AI for Bharat Hackathon**
  >
  > **Team Name:** LearnSign &nbsp;|&nbsp; **Team Leader:** Amith K M
  >
  > **Problem Statement:** Build an AI-powered solution that improves access to information, resources, or opportunities for communities and public systems.

</div>

---

## 📖 Table of Contents

- [About](#-about)
- [Why AI?](#-why-ai-is-required)
- [Key Innovations](#-key-innovations)
- [AI Value to Users](#-what-value-the-ai-layer-adds)
- [Features](#-features)
- [Screenshots](#-screenshots)
- [AWS Architecture](#-aws-architecture)
- [Tech Stack](#-tech-stack)
- [User Journey](#-user-journey--system-interaction-flow)
- [Sign Recognition System](#-sign-recognition-system)
- [AI Tutor – SignMentor](#-ai-tutor-system-signmentor)
- [Parent Report System](#-parent-report-system)
- [Getting Started](#-getting-started)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [API Documentation](#-api-documentation)
- [Project Structure](#-project-structure)
- [Roadmap](#-roadmap)
- [Contributing](#-contributing)
- [Team](#-team)
- [License](#-license)
- [Contact](#-contact)
- [Acknowledgments](#-acknowledgments)

---

## 🎯 About

**LearnSign** is the **"Duolingo for Sign Language"** — a comprehensive, AI-powered Indian Sign Language (ISL) learning and translation platform designed for children ages 1–15+. The platform uses a **webcam + computer vision** to detect signs in real time and deliver instant AI feedback, making sign language education interactive, personalized, and accessible to all.

### Mission

To bridge communication gaps and empower deaf and hard-of-hearing children through innovative, accessible, and engaging sign language education.

### Vision

Create an inclusive world where every child can communicate effectively through sign language, breaking down barriers and fostering understanding across communities.

---

## 🤖 Why AI Is Required

LearnSign's core experience is only possible because of AI:

- **Real-time sign language recognition** using computer vision directly from webcam input.
- **Detects hand gestures and facial cues** to understand Indian Sign Language accurately.
- **Instant feedback system** tells users whether a sign is correct or incorrect.
- **Personalized learning** by analyzing mistakes and adapting difficulty levels.
- **Automates evaluation and progress tracking**, which is impossible with traditional video-based learning.

---

## 💡 Key Innovations

1. **Webcam-Based Quizzes** — Interactive assessments where learners perform signs live in front of their camera.
2. **Understands Signs in Real-Time** — AI-powered computer vision detects hand gestures (and facial cues) instantly.
3. **Provides Instant AI Feedback** — Immediate results: Correct / Incorrect + actionable improvement tips + score.
4. **Age-Tailored Courses** — Structured content designed for: 1–5 years, 6–10 years, and 10–15 years.
5. **Video Lessons** — Expert-led sign demonstrations for step-by-step learning.
6. **Progress Tracking** — Tracks learning milestones, quiz performance, and skill growth over time.

---

## 🌟 What Value the AI Layer Adds

1. **Interactive learning** with real-time sign detection through webcam.
2. **Instant AI feedback** improves accuracy and learning speed.
3. **Personalized recommendations** based on user performance.
4. **AI-powered dashboard & report generation** showing progress and analytics.
5. **Accessible communication** by converting sign language into text for real-world use.

---

# 🎥 LearnSign Demo

https://github.com/user-attachments/assets/35933fd6-315e-4785-87b2-b8a1e793f8ec


## ✨ Features

### 🎓 Comprehensive Course Catalog

- **Age-Appropriate Learning Paths**
  - Early Learners (Ages 1–4): Foundational signs through play
  - Young Explorers (Ages 5–10): Vocabulary building and conversations
  - Advanced Learners (Ages 10–15+): Complex communication and cultural context

- **Structured Curriculum**
  - 50+ interactive lessons
  - Video demonstrations for every sign
  - Quizzes and assessments
  - Progress tracking per course

### 🤖 AI-Powered Real-Time Sign Recognition

- **Live webcam-based sign detection** with instant accuracy feedback
- **Support for 350+ common ISL signs**

- **Three Recognition Modes**
  1. **Alphabet Recognition** — Learn A–Z fingerspelling
  2. **Number Recognition** — Master numbers 0–9
  3. **Word Recognition** — Common words and phrases

- **Advanced ML Pipeline**
  - MediaPipe hand landmark detection
  - LSTM neural network for sequence recognition
  - 95%+ accuracy on trained signs
  - Real-time pose estimation

### 📊 Analytics & Progress Tracking (Gamified Dashboard)

- **Gamified Dashboard**
  - Overall learning progress percentage
  - Lessons completed counter
  - Total time spent learning
  - Last activity tracking

- **Visual Analytics**
  - Weekly activity charts
  - Progress by category (pie charts)
  - Achievement metrics and badges
  - Performance trends over time

- **AI-Generated Reports (Parent Reporting)**
  - AI-powered personalized learning summary
  - Strengths and growth areas analysis
  - Weekly goals and recommendations
  - Actionable tips for parents
  - Download as PDF / Print-friendly format

### 🤖 AI Tutor – SignMentor

Your personal AI-powered sign language tutor:

- **Smart Chat Interface**
  - Natural language conversations about sign language
  - Ask about any sign and get video demonstrations
  - Step-by-step learning guides with practice exercises
  - Related signs and vocabulary suggestions

- **Voice Interaction** (Amazon Transcribe + Amazon Polly)
  - 🎤 Voice input — speak naturally in your language
  - 🔊 Voice responses — hear pronunciations and instructions
  - Multi-language support: English, Hindi (हिंदी), Kannada (ಕನ್ನಡ), Telugu (తెలుగు)

- **Intelligent Video Sequences**
  - Automatic sentence-to-sign video playback
  - Word-by-word progress indicators
  - Pause, replay, and slow-motion controls
  - Click any word to jump to its sign

### 🔤 Sign Language Translator

- Type any word or sentence to see its ISL sign
- Video demonstrations with loop functionality
- Quick example phrases
- Search through 350+ sign database
- Real-world text ↔ sign language conversion

### 👨‍👩‍👧‍👦 Community & Inspiring Journeys

- Success stories from deaf achievers
- Role models and inspirational figures
- Real-world impact stories

---

## 📸 Screenshots

### Home Page
<div align="center">
  <img src="docs/screenshots/home.png" alt="Home Page" width="800"/>
  <p><i>Beautiful landing page with mission statement and call-to-action</i></p>
</div>

### Course Catalog
<div align="center">
  <img src="docs/screenshots/courses.png" alt="Courses" width="800"/>
  <p><i>Age-appropriate learning paths with progress indicators</i></p>
</div>

### Sign Language Translator
<div align="center">
  <img src="docs/screenshots/translator.png" alt="Translator" width="800"/>
  <p><i>Real-time sign language recognition and demonstration</i></p>
</div>

### Dashboard & Progress Tracking
<div align="center">
  <img src="docs/screenshots/dashboard.png" alt="Dashboard" width="800"/>
  <p><i>Gamified analytics and progress visualization</i></p>
</div>

### Community Section
<div align="center">
  <img src="docs/screenshots/community.png" alt="Community" width="800"/>
  <p><i>Inspiring stories from successful deaf individuals</i></p>
</div>


---

## ☁️ AWS Architecture

LearnSign is built on a fully **serverless AWS architecture** designed for real-time tracking, scalability, and reliability.

### AWS Services Used

| AWS Service | Role in LearnSign |
|---|---|
| **Amazon API Gateway** | Handles all backend REST APIs via serverless architecture |
| **AWS Lambda** | Serverless orchestration layer — processes requests, coordinates services |
| **Amazon Cognito** | Manages secure user authentication and login |
| **Amazon SageMaker** | Hosts the AI/ML model for real-time ISL sign recognition inference |
| **Amazon DynamoDB** | Stores user progress data, quiz results, and app state |
| **Amazon S3** | Stores datasets, sign videos, and media files |
| **Amazon Bedrock** | Powers the AI Tutor (SignMentor) — GenAI conversations and recommendations |
| **Amazon Transcribe** | Speech-to-text for voice input in the AI Tutor |
| **Amazon Polly** | Text-to-speech for voice responses from the AI Tutor |
| **Amazon CloudWatch** | System monitoring, logging, and model latency tracking |

### Architecture Diagram

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                         LearnSign: AWS Serverless Architecture               │
├────────────────┬────────────────────────────┬───────────────────────────────┤
│  Client Layer  │   API & Auth Layer          │   AI, ML & Data Layer         │
│  (Frontend)    │                             │                               │
│                │  ┌──────────────────────┐   │  ┌─────────────────────────┐ │
│  User          │  │  Amazon API Gateway  │   │  │  Serverless Storage     │ │
│  (Student /    │──►  + Amazon Cognito    │   │  │  Amazon DynamoDB        │ │
│   Parent)      │  └──────────┬───────────┘   │  │  Amazon S3 Bucket       │ │
│                │             │               │  └─────────────────────────┘ │
│  Web App       │             ▼               │                               │
│  (React/EJS)   │  ┌──────────────────────┐   │  ┌─────────────────────────┐ │
│                │  │  Serverless          │───►  │  Core AI (Sign Det.)    │ │
│  Webcam Input  │  │  Orchestration       │   │  │  Amazon SageMaker       │ │
│                │  │  AWS Lambda          │◄──┤  │  Endpoint               │ │
│  Microphone    │  └──────────┬───────────┘   │  └─────────────────────────┘ │
│  Input         │             │               │                               │
│                │             ▼               │  ┌─────────────────────────┐ │
│                │  ┌──────────────────────┐   │  │  AI Tutor (SignMentor)  │ │
│                │  │  Monitoring &        │   │  │  Amazon Bedrock         │ │
│                │  │  Logging             │   │  └─────────────────────────┘ │
│                │  │  Amazon CloudWatch   │   │                               │
│                │  └──────────────────────┘   │  ┌─────────────────────────┐ │
│                │                             │  │  Voice Services         │ │
│                │                             │  │  Amazon Transcribe      │ │
│                │                             │  │  Amazon Polly           │ │
│                │                             │  └─────────────────────────┘ │
└────────────────┴────────────────────────────┴───────────────────────────────┘
```

---

## 🛠 Tech Stack

### Frontend
- **React.js / EJS** — UI framework and server-side templating
- **HTML5 / CSS3 / JavaScript (ES6+)** — Semantic markup, responsive design, interactive features

### Backend
- **Node.js** (v18+) — Runtime environment
- **Express.js** — Web application framework
- **Amazon DynamoDB** — NoSQL database for user data and progress
- **Amazon S3** — Media and dataset storage

### AI / ML
- **MediaPipe** — Hand tracking and landmark detection
- **LSTM / Random Forest Classifier** — Sign classification model
- **Python 3.12** — ML runtime
- **TensorFlow 2.x / Keras** — Deep learning framework
- **OpenCV** — Computer vision processing

### AWS Cloud Services
- **Amazon API Gateway** — REST API management
- **AWS Lambda** — Serverless compute
- **Amazon Cognito** — Authentication and user management
- **Amazon SageMaker** — ML model hosting and inference
- **Amazon Bedrock** — GenAI-powered AI Tutor (SignMentor)
- **Amazon Transcribe** — Speech-to-text
- **Amazon Polly** — Text-to-speech
- **Amazon CloudWatch** — Monitoring and logging

### Development Tools
- **Nodemon** — Auto-restart development server
- **Concurrently** — Run multiple processes
- **dotenv** — Environment variable management
- **html2pdf.js** — PDF report generation

---

## 🗺 User Journey & System Interaction Flow

```
Student Flow:
  Login/Sign-up
    └─► Choose Activity
          └─► Select Lesson & Practice
                └─► Watch Video & Use Webcam
                      └─► Real-Time Sign Recognition (MediaPipe / LSTM)
                            ├─► Correct  → Next Lesson & Track Progress
                            └─► Incorrect → Retry with Feedback

AI Tutor Flow:
  Ask AI Tutor
    └─► Voice / Text Query
          └─► AI Processing (Transcribe, Bedrock, Video Retrieval)
                └─► Receive Response (Voice & Video)

Parent Flow:
  Parent Login
    └─► View Dashboard
          └─► Receive Weekly Progress Report (AI-Generated PDF)
```

---

## 🧠 Sign Recognition System

### How It Works

1. **Webcam captures** a live video frame from the user's device.
2. **MediaPipe** processes the frame to extract 21 hand landmarks per hand, plus facial cues.
3. **LSTM model** classifies the gesture sequence and outputs a predicted sign.
4. **SageMaker endpoint** handles inference at scale.
5. **Instant feedback** is sent back to the frontend: Correct / Incorrect + improvement tips.

### Supported Sign Categories

- **Alphabet** — A to Z (ISL fingerspelling)
- **Numbers** — 0 to 9
- **Words** — 350+ common ISL words and phrases

---

## 🤖 AI Tutor System – SignMentor

SignMentor is powered by **Amazon Bedrock** and provides:

- Natural language Q&A about any ISL sign
- Video demonstrations fetched from the sign database
- Personalized practice exercises based on quiz performance
- Voice interaction via Amazon Transcribe (input) + Amazon Polly (output)
- Multi-language support: English, Hindi, Kannada, Telugu

---

## 📄 Parent Report System

After each learning session, LearnSign automatically:

1. Updates the student's profile and stats via Lambda + DynamoDB.
2. Uses Amazon Bedrock to generate an AI-powered weekly progress report.
3. Sends the report to the parent dashboard.
4. Allows parents to download the report as a PDF.

Report contents include: learning summary, strengths, growth areas, quiz trends, and weekly goals.

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v18+)
- Python 3.12+
- AWS account with the following services enabled:
  - API Gateway, Lambda, Cognito, SageMaker, DynamoDB, S3, Bedrock, Transcribe, Polly, CloudWatch
- Webcam (for sign recognition features)

### Installation

```bash
# Clone the repository
git clone https://github.com/amithkm9/LearnSign_pro.git
cd LearnSign_pro

# Install Node.js dependencies
npm install

# Set up Python ML environment
cd sign_recognition
pip install -r requirements.txt
cd ..
```

### Configuration

```bash
# Copy the environment template
cp .env.example .env
```

Edit `.env` and fill in your AWS credentials and configuration:

```env
# AWS Configuration
AWS_REGION=ap-south-1
AWS_ACCESS_KEY_ID=your_access_key
AWS_SECRET_ACCESS_KEY=your_secret_key

# Amazon Cognito
COGNITO_USER_POOL_ID=your_user_pool_id
COGNITO_CLIENT_ID=your_client_id

# Amazon DynamoDB
DYNAMODB_TABLE_USERS=learnsign-users
DYNAMODB_TABLE_PROGRESS=learnsign-progress

# Amazon S3
S3_BUCKET_NAME=learnsign-media

# Amazon SageMaker
SAGEMAKER_ENDPOINT_NAME=learnsign-sign-recognition

# Amazon Bedrock
BEDROCK_MODEL_ID=anthropic.claude-v2

# App Config
PORT=3000
SESSION_SECRET=your_session_secret
```

### Usage

```bash
# Start the Node.js application server
npm start

# In a separate terminal, start the Python ML API
cd sign_recognition
python main.py
```

Open `http://localhost:3000` in your browser. Make sure your webcam is enabled for sign recognition features.

---

## 📡 API Documentation

### Node.js Endpoints

#### Authentication
```http
POST /api/auth/register
POST /api/auth/login
POST /api/auth/logout
GET  /api/auth/profile
```

#### Courses & Progress
```http
GET  /api/courses
GET  /api/courses/:id
POST /api/progress/update
GET  /api/progress/:userId
```

#### Quizzes
```http
GET  /api/quizzes/:courseId
POST /api/quizzes/submit
GET  /api/quizzes/results/:userId
```

#### AI Tutor (SignMentor)
```http
POST /api/tutor/chat
GET  /api/tutor/profile/:userId
```

#### Voice Services
```http
POST /api/voice/chat
POST /api/voice/text-to-speech
```

#### Parent Reports
```http
GET /api/report/generate/:userId
```

### Python ML API Endpoints

#### Sign Recognition
```http
POST /recognize
POST /translate
POST /validate-sign
GET  /supported-signs
GET  /model-info
```

---

## 📁 Project Structure

```
LearnSign/
├── config/
│   ├── config.js              # Application configuration
│   └── aws.js                 # AWS SDK configuration
├── models/
│   ├── User.js                # User schema (DynamoDB)
│   ├── Course.js              # Course schema
│   ├── UserProgress.js        # Progress tracking schema
│   ├── QuizAttempt.js         # Quiz results schema
│   └── LearningEvent.js       # Activity logging schema
├── views/
│   ├── partials/
│   │   ├── head.ejs
│   │   ├── header.ejs
│   │   └── footer.ejs
│   ├── home.ejs               # Landing page
│   ├── courses.ejs            # Course catalog
│   ├── dashboard.ejs          # Gamified user dashboard
│   ├── translate.ejs          # Sign translator
│   ├── tutor.ejs              # AI Tutor (SignMentor)
│   ├── report.ejs             # Parent Report
│   ├── about.ejs              # About page
│   └── community.ejs          # Community section
├── public/
│   ├── css/
│   │   ├── home.css
│   │   ├── dashboard.css
│   │   ├── courses.css
│   │   ├── translate.css
│   │   ├── tutor.css
│   │   └── report.css
│   ├── js/
│   │   ├── auth.js
│   │   ├── translate.js
│   │   ├── quiz.js
│   │   ├── heartbeat.js
│   │   ├── tutor.js
│   │   └── report.js
│   └── assets/
│       ├── imgs/
│       └── videos/
│           ├── signs/         # 350+ ISL sign videos
│           └── courses/       # Course videos
├── sign_recognition/
│   ├── models/
│   │   └── sign_language_numbers_letters.h5
│   ├── training_data/
│   ├── main.py                # Primary ML API
│   ├── translate_api.py       # Translation service
│   ├── numbers_letters_api.py # Alphabet/numbers recognition
│   ├── train.py               # Model training script
│   ├── collect_data.py        # Data collection utility
│   └── requirements.txt       # Python dependencies
├── seeds/
│   └── seedData.js            # Database seeding
├── index.js                   # Main application
├── api.js                     # API server
├── package.json               # Node dependencies
├── .env.example               # Environment template
├── .gitignore
├── DEPLOYMENT.md
└── README.md
```

---

## 🗺 Roadmap

### Phase 1: Core Platform ✅ Completed
- [x] User authentication (Amazon Cognito)
- [x] Course catalog with age-grouped learning paths
- [x] Video lessons
- [x] Progress tracking (DynamoDB)
- [x] Basic sign translator

### Phase 2: AI Integration ✅ Completed
- [x] Hand tracking with MediaPipe
- [x] LSTM model training and deployment (SageMaker)
- [x] Real-time ISL recognition (Alphabet, Numbers, Words)
- [x] Webcam-based quiz assessments

### Phase 3: Enhanced Features ✅ Completed
- [x] AI Tutor – SignMentor (Amazon Bedrock)
- [x] Voice input (Amazon Transcribe)
- [x] Voice output (Amazon Polly)
- [x] Multi-language support (English, Hindi, Kannada, Telugu)
- [x] Parent Report Dashboard with AI-generated PDF export
- [x] Gamified dashboard and analytics

### Phase 4: Scaling 📋 Planned
- [ ] Mobile responsive design
- [ ] Teacher portal
- [ ] Mobile apps (iOS / Android)
- [ ] Offline mode
- [ ] Advanced analytics and reporting

### Phase 5: Innovation 🔮 Future
- [ ] AR/VR integration for immersive learning
- [ ] Voice-to-sign and Sign-to-voice translation
- [ ] Community features and peer learning
- [ ] Third-party API integrations

---

## 🤝 Contributing

We welcome contributions from the community!

1. **Fork the repository**
```bash
git clone https://github.com/YOUR_USERNAME/LearnSign_pro.git
```

2. **Create a feature branch**
```bash
git checkout -b feature/amazing-feature
```

3. **Commit with clear messages**
```bash
git commit -m "Add: New sign recognition feature"
```

4. **Push and open a Pull Request**
```bash
git push origin feature/amazing-feature
```

**Areas for Contribution:** UI/UX improvements, ML model enhancements, new ISL signs, internationalization, documentation, bug fixes, testing.

---

## 📊 Project Stats

| Metric | Value |
|---|---|
| Sign Language Videos | 354+ |
| ISL Signs Supported | 350+ |
| Age Groups | 3 (1–5, 6–10, 10–15) |
| ML Model Accuracy | 95%+ |
| API Endpoints | 30+ |
| Voice Languages | 4 (English, Hindi, Kannada, Telugu) |
| AWS Services Integrated | 10 |
| Contributors | 5+ |

---

## 👥 Team

| Name | Role |
|---|---|
| **Amith K M** | Team Leader, Lead Developer & ML Engineer |
| **Adarsh** | Backend Developer |
| **Prajwal** | Frontend Developer |
| **Bindu** | UI/UX Designer |
| **Chandana** | Content Creator |

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

## 📞 Contact

- **Email:** learnsign.support@gmail.com
- **Phone:** +91 7022955705
- **GitHub:** [@amithkm9](https://github.com/amithkm9)
- **Issues:** [Report Issues](https://github.com/amithkm9/LearnSign_pro/issues)

---

## 🙏 Acknowledgments

- **AWS** — Cloud infrastructure powering the entire LearnSign platform
- **Amazon Bedrock / SageMaker / Polly / Transcribe / Cognito** — Core AI and cloud services
- **MediaPipe Team** — Hand tracking technology
- **TensorFlow / Keras Team** — Deep learning framework
- **Deaf community** — For inspiration, feedback, and purpose
- **AI for Bharat Hackathon (H2S × AWS × YourStory)** — For the platform and opportunity

---

<div align="center">

**Made with ❤️ for the deaf and hard-of-hearing community**

*Breaking barriers, one sign at a time* 🤟

[⬆ Back to Top](#learnsign-)

</div>
