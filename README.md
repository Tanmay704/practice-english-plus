# Practice English Plus 🎓

An intelligent AI-powered English learning platform that helps users master English through interactive translation exercises with real-time feedback and comprehensive analytics.

https://github.com/user-attachments/assets/e0a0712b-e873-4e41-bc10-8d18003679e2


## ✨ Features

### 🎯 Core Functionality
- **Smart Paragraph Generation**: Generate paragraphs in multiple Indian languages (Hindi, Marathi, Bengali, Kannada, Tamil)
- **Difficulty Levels**: Choose from Easy, Medium, or Hard difficulty levels
- **Real-time Translation**: Translate native language paragraphs to English
- **AI-Powered Evaluation**: Get instant feedback on grammar, vocabulary, fluency, and similarity

### 🌍 Supported Languages
- **Hindi** (हिंदी) - Devanagari script
- **Marathi** (मराठी) - Devanagari script
- **Bengali** (বাংলা) - Bengali script
- **Kannada** (ಕನ್ನಡ) - Kannada script
- **Tamil** (தமிழ்) - Tamil script

### 🔄 Translation & Validation Process

**Step 1: Generate Paragraph**
- Select your native language from the dropdown
- Choose difficulty level (Easy/Medium/Hard)
- Click "Generate" button
- System generates a paragraph in your selected language
- Original English translation is stored for comparison

**Step 2: Translate**
- Read the generated paragraph in your native language
- Type your English translation in the text area
- No time limit - take your time to craft the best translation

**Step 3: Validate**
- Click "Validate" button to submit your translation
- AI analyzes your translation against the original
- Evaluation includes:
  - **Similarity Score**: How close your translation matches the original meaning
  - **Grammar Score**: Correctness of grammar usage
  - **Vocabulary Score**: Richness and appropriateness of word choice
  - **Fluency Score**: Natural flow and readability
  - **Overall Score**: Combined performance metric

**Step 4: Review Results**
- View detailed grammar issues with suggestions
- Explore different view modes (Quick View, Progress, Detailed)
- Compare your translation with the answer key
- Track improvement areas and strengths

### 📊 Learning Analytics
- **Comprehensive Scoring**: Track similarity, grammar, vocabulary, fluency, and overall scores
- **Multiple View Modes**:
  - **Quick View**: Horizontal scrolling cards with all insights at a glance
  - **Progress Tracker**: Visual skill garden showing improvement areas
  - **Detailed Analysis**: In-depth breakdown of performance metrics
- **Grammar Issue Detection**: Identify and fix grammar mistakes with AI suggestions

### 🎨 Modern UI/UX
- **Theme Support**: Light and Dark mode with professional color schemes
- **Smooth Animations**: Framer Motion powered transitions and interactions
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Glass Morphism**: Modern backdrop blur effects and gradients
- **Professional Typography**: Inter font family with optimized weights

### 🌟 Additional Features
- **Celebration Effects**: Animated celebrations for high scores (>80%)
- **Toast Notifications**: User-friendly feedback messages
- **Resizable Containers**: Adjust paragraph view sizes
- **Answer Key**: View original English translations
- **Feedback System**: Submit suggestions, bug reports, and general feedback

## 🚀 Tech Stack

- **Frontend Framework**: React 18
- **Build Tool**: Vite
- **Routing**: React Router DOM
- **UI Components**: Material-UI (MUI)
- **Animations**: Framer Motion
- **Styling**: CSS3 with custom themes
- **HTTP Client**: Axios
- **Icons**: Material Icons, Lucide React
- **Form Handling**: FormSubmit.co

## 📦 Installation

1. **Clone the repository**
```bash
git clone <repository-url>
cd english-master-ai
```

2. **Install dependencies**
```bash
npm install
```

3. **Set up environment variables**
Create a `src/config.js` file:
```javascript
const config = {
  PARAGRAPH_API_URL: 'your-api-url/generate',
  EVALUATION_API_URL: 'your-api-url/evaluate'
};

export default config;
```

4. **Run development server**
```bash
npm run dev
```

5. **Build for production**
```bash
npm run build
```

## 🎮 Usage

1. **Select Language & Difficulty**: Choose your native language and difficulty level from the settings
2. **Generate Paragraph**: Click "Generate" to get a paragraph in your native language
3. **Translate**: Type your English translation in the provided text area
4. **Validate**: Click "Validate" to get AI-powered feedback and scores
5. **Review**: Explore different view modes to understand your performance
6. **Improve**: Use grammar suggestions and insights to enhance your skills

## 🎨 Theme Customization

The app supports two themes with professional color palettes:

**Light Theme**:
- Background: Subtle grid pattern with blue/purple gradients
- Components: White with glass morphism effects
- Text: Dark slate colors for optimal readability

**Dark Theme**:
- Background: Dark grid pattern with indigo/purple gradients
- Components: Dark slate with enhanced glass effects
- Text: Light colors with proper contrast

## 📱 Responsive Breakpoints

- **Desktop**: > 1200px
- **Tablet**: 768px - 1200px
- **Mobile**: < 768px
- **Small Mobile**: < 480px

## 🔧 Configuration

### API Endpoints
Configure your backend API endpoints in `src/config.js`:
- `PARAGRAPH_API_URL`: Endpoint for paragraph generation
- `EVALUATION_API_URL`: Endpoint for translation evaluation

### Theme Persistence
Theme preference is automatically saved to localStorage and persists across sessions.

### Language & Difficulty
User preferences for language and difficulty are stored in localStorage.

## 🌐 Pages

- **Home (/)**: Main practice interface with all learning tools
  <img width="1901" height="863" alt="image" src="https://github.com/user-attachments/assets/17794334-cd5c-47b7-aa8d-9648fa6611b6" />
  <img width="1913" height="856" alt="image" src="https://github.com/user-attachments/assets/f650a293-c55d-467e-81fa-e33a0b235a69" />

  
- **About (/about)**: Information about the platform and features
  <img width="1902" height="862" alt="image" src="https://github.com/user-attachments/assets/bf936b25-bd1e-45d5-a6b1-1ca589bd6be0" />
  
- **Feedback (/feedback)**: Submit feedback, suggestions, or bug reports
  <img width="1917" height="862" alt="image" src="https://github.com/user-attachments/assets/d639445b-8ac4-4a0e-93ca-65d2c9279fa7" />


## 🎯 Key Components

- **Header**: Navigation with theme toggle and animated logo
- **Toolbox**: Language and difficulty selection with Autocomplete
- **Scoreboard**: Real-time metrics display with progress bars
- **MainContainer**: Resizable paragraph display with typing animation
- **UserTranslation**: Text input area for translations
- **AnimatedTabs**: Tabbed interface for insights and answer key
- **InnovativeLearningHub**: Multiple view modes for learning analytics
- **HorizontalLearningView**: Scrollable cards with grammar issues
- **SkillProgressTracker**: Visual skill garden representation
- **LearningInsights**: Detailed performance breakdown

## 🎨 Design Philosophy

- **Professional**: Inspired by modern apps like GitHub, Linear, and Notion
- **Eye-friendly**: Carefully selected colors to reduce eye strain
- **Consistent**: Uniform spacing and typography throughout
- **Accessible**: High contrast ratios and readable font sizes
- **Performant**: Optimized animations and lazy loading

## 📄 License

All rights reserved © 2024 PracticeEnglishPlus

## 🤝 Contributing

This is a private project. For feedback or suggestions, please use the in-app feedback form.

## 📧 Contact

For inquiries: practiceenglishplus@gmail.com

---

**Built with ❤️ for English learners worldwide**
