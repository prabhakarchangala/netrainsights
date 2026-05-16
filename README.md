# NetrAI Academy - Free AI Training Institute

A complete, modern, free training institute website showcasing comprehensive AI and Machine Learning courses with detailed syllabi and learning content.

## 🎯 Project Overview

This is a **fully functional training institute website** featuring:
- ✅ **10+ Free AI Courses** with complete syllabi
- ✅ **Expandable Architecture** - Easy to add more courses  
- ✅ **Professional Design** - Modern, responsive UI
- ✅ **Free Access** to all course content and syllabi
- ✅ **Search & Filtering** - Filter courses by category
- ✅ **SEO Optimized** - Proper meta tags and structure

## 📁 Project Structure

```
netrAI/
├── index.html                          # Main homepage with course catalog
├── logo.png                            # Institute logo
├── favicon.svg                         # Browser favicon
│
└── courses/                            # Individual course pages
    ├── agentic-ai.html                 # 🤖 Agentic AI & LLMs (40h)
    ├── ml-fundamentals.html            # 📊 Machine Learning Fundamentals (35h)
    ├── deep-learning.html              # 🧠 Deep Learning Essentials (45h)
    ├── nlp.html                        # 📝 Natural Language Processing (40h)
    ├── computer-vision.html            # 👁️ Computer Vision (40h)
    ├── reinforcement-learning.html     # 🎮 Reinforcement Learning (45h)
    ├── prompt-engineering.html         # ✍️ Prompt Engineering & Fine-tuning (25h)
    ├── mlops.html                      # ⚙️ MLOps & Model Deployment (30h)
    ├── time-series.html                # 📈 Time Series & Forecasting (35h)
    └── generative-ai.html              # 🎨 Generative AI & Diffusion Models (40h)
```

## 🚀 Features

### Home Page (index.html)
- **Hero Section** - Eye-catching introduction with call-to-action
- **Statistics** - Display of impressive course metrics
- **Course Catalog** - Grid layout showing all 10 courses
- **Filter System** - Filter courses by:
  - All Courses
  - Machine Learning
  - Deep Learning
  - NLP
  - Computer Vision
  - AI Fundamentals
- **Professional Footer** - Links, policies, and contact info

### Individual Course Pages
Each course includes:
- **Course Header** - Title, subtitle, and gradient background
- **Course Meta** - Level, duration, format, and cost
- **Course Overview** - Description and learning objectives
- **Detailed Syllabus** - Expandable modules with:
  - Topic breakdown
  - Learning subtopics
  - Resource links (Reading, Videos, Notebooks, Projects)
- **Learning Outcomes** - Clear list of what students will learn
- **Prerequisites** - Required knowledge
- **Tools & Libraries** - Technologies used
- **Call-to-Action** - Back to courses button

## 📚 Course Catalog

### 1. **Agentic AI & LLMs** (40 hours) - 🤖 Advanced
Building autonomous agents using LLMs, prompt engineering, and agent frameworks.
- LLM Fundamentals
- Prompt Engineering Mastery
- Agent Foundations
- Tools & Function Calling
- Memory & Context Management
- Building Real Agents
- Multi-Agent Systems
- Production & Safety
- Capstone Projects

### 2. **Machine Learning Fundamentals** (35 hours) - 📊 Beginner
Master supervised learning, unsupervised learning, and practical ML implementation.
- ML Foundations & Concepts
- Data Preprocessing & Feature Engineering
- Supervised Learning - Regression
- Supervised Learning - Classification
- Unsupervised Learning
- Model Evaluation & Validation
- Practical ML Projects & Deployment

### 3. **Deep Learning Essentials** (45 hours) - 🧠 Intermediate
Neural Networks, CNNs, RNNs, Transformers & Modern Architectures.
- Neural Network Fundamentals
- Convolutional Neural Networks (CNNs)
- Recurrent Neural Networks (RNNs)
- Attention & Transformers
- Generative Models
- Advanced Topics & Optimization
- Practical Projects & Production

### 4. **Natural Language Processing** (40 hours) - 📝 Intermediate
Processing, understanding & generating human language with AI.
- NLP Fundamentals & Text Processing
- Word Embeddings & Representations
- Text Classification & Sentiment Analysis
- Named Entity Recognition & POS Tagging
- Sequence Models & RNNs for NLP
- Transformers & Large Language Models
- Advanced NLP & Capstone Projects

### 5. **Computer Vision** (40 hours) - 👁️ Intermediate
Image processing, object detection & real-world vision applications.
- Image Fundamentals & Processing
- Feature Extraction & Descriptors
- Object Detection & Localization
- Image Segmentation
- Pose Estimation & Action Recognition
- Advanced Topics
- Projects & Deployment

### 6. **Reinforcement Learning** (45 hours) - 🎮 Advanced
Learning through interaction - MDPs, Q-Learning & Policy Gradient.
- RL Fundamentals
- Markov Decision Processes (MDPs)
- Reward Functions & Discounting
- Value Functions & Bellman Equations
- Q-Learning & Temporal Difference
- Deep Q-Networks (DQN)
- Policy Gradient Methods
- Actor-Critic Methods
- Game Playing Agents

### 7. **Prompt Engineering & Fine-tuning** (25 hours) - ✍️ Intermediate
Master advanced LLM interactions & model customization.
- Prompt Structure & Components
- Few-shot Learning Techniques
- Chain-of-Thought Prompting
- Fine-tuning Fundamentals
- LoRA & Parameter-Efficient Fine-tuning
- Production Prompt Management

### 8. **MLOps & Model Deployment** (30 hours) - ⚙️ Advanced
Production ML systems, CI/CD & enterprise best practices.
- ML Development Lifecycle
- Model Versioning & Tracking
- Docker & Containerization
- Kubernetes Basics
- CI/CD for ML
- Model Serving & Inference
- Monitoring & Observability

### 9. **Time Series & Forecasting** (35 hours) - 📈 Intermediate
Predictive analytics for temporal data.
- Time Series Fundamentals
- Stationarity & Trend Analysis
- ARIMA Models
- Exponential Smoothing
- Prophet for Forecasting
- LSTM Networks for Time Series
- Anomaly Detection

### 10. **Generative AI & Diffusion Models** (40 hours) - 🎨 Advanced
Creating with AI - GANs, VAEs, Diffusion & Text-to-Image.
- Generative Models Fundamentals
- Autoencoders & VAE
- Generative Adversarial Networks (GANs)
- Diffusion Models
- Text-to-Image Generation
- Image Inpainting & Super-resolution
- Real-world Applications

## 🎨 Design Features

### Visual Design
- **Modern Color Scheme** - Gradient backgrounds with brand colors
- **Responsive Layout** - Works on desktop, tablet, and mobile
- **Interactive Elements** - Expandable course modules with animations
- **Professional Typography** - Inter font family for clean, modern look
- **Accessibility** - Proper contrast ratios and semantic HTML

### Technical Features
- **Pure HTML/CSS/JavaScript** - No external frameworks (except fonts)
- **Zero Dependencies** - Self-contained, no npm/build required
- **Performance Optimized** - Fast loading, minimal CSS
- **SEO Friendly** - Proper meta tags and semantic structure
- **Mobile First** - Responsive design with media queries

## 🔧 Customization Guide

### Add a New Course

1. **Create Course Page** (`courses/your-course.html`)
   - Copy template from existing course
   - Update header gradient color
   - Fill in course details and modules

2. **Update Main Index** (edit `index.html`)
   ```javascript
   const courses = [
       // Add new course object:
       {
           id: 'new-course',
           title: 'Course Title',
           subtitle: 'Subtitle here',
           category: 'ml', // or 'dl', 'nlp', 'cv', 'ai'
           level: 'Beginner', // or Intermediate, Advanced
           hours: 30,
           emoji: '🎓',
           description: 'Course description...',
           url: 'courses/new-course.html'
       }
   ];
   ```

### Change Colors

Edit CSS variables in `index.html`:
```css
:root {
    --primary: #6366f1;      /* Main brand color */
    --accent: #06b6d4;       /* Accent color */
    --green: #10b981;        /* Success/positive */
    --orange: #f59e0b;       /* Warning/attention */
    /* ... */
}
```

### Update Course Category Colors

Each category has unique gradients in `.course-card` styles:
```css
.course-card.ml .course-header { 
    background: linear-gradient(135deg, #8b5cf6 0%, #ec4899 100%); 
}
```

## 📊 Statistics

- **10+ Courses** covering all AI specializations
- **200+ Hours** of comprehensive content
- **100% Free** - No hidden costs
- **50+ Resources** - Reading, videos, code, projects

## 🌐 Deployment

### Local Development
1. Simply open `index.html` in a modern web browser
2. All courses load from local `courses/` directory
3. No server required

### Web Deployment
1. Upload all files to web server
2. Ensure file structure is preserved
3. Works on any static hosting (GitHub Pages, Netlify, Vercel, etc.)

### GitHub Pages Deployment
```bash
# Push to GitHub
git add .
git commit -m "Add NetrAI Academy website"
git push origin main

# Enable Pages in repository settings
# Choose main branch as source
```

## 🔗 File Links in Courses

Each course card displays:
- **View Course** - Links to course detail page
- **Syllabus** - Same page with syllabus parameter

Resource links placeholder format:
```html
<a href="#" class="resource-link">📚 Reading</a>
<a href="#" class="resource-link">🎥 Videos</a>
<a href="#" class="resource-link">💻 Code</a>
```

Replace `#` with actual URLs:
- YouTube playlists
- GitHub repos
- Documentation links
- Dataset URLs

## 💡 Content Expansion Ideas

1. **Add Discussion Forums**
   - Community interaction
   - Q&A sections

2. **Student Progress Tracking**
   - Login system
   - Course completion tracking
   - Certificates

3. **Live Sessions**
   - Webinar schedule
   - Office hours
   - Guest lectures

4. **Certification Path**
   - Micro-credentials
   - Professional certificates
   - Skill badges

5. **Content Library**
   - Downloadable resources
   - Code templates
   - Dataset links

6. **Interactive Quizzes**
   - Auto-grading
   - Knowledge checks
   - Progress assessment

## 📄 License

This training institute website is **free to use and modify** for educational purposes.

## ✅ Quick Start

1. Open `index.html` in your browser
2. Click on any course to view details
3. Expand modules to see curriculum
4. Click resource links to access content
5. Filter courses by category using top buttons

## 🎓 For Instructors

To customize for your institution:
1. Update logos and branding
2. Add your course content and resources
3. Update contact information
4. Add custom color schemes
5. Expand course catalog

## 📞 Support Resources

- View course syllabus: Click "Syllabus" button on course cards
- Expand course modules: Click any module title to see details
- Filter courses: Use category buttons at top
- Navigate: Use "Back to Courses" link on each course page

---

**Build amazing learning experiences with NetrAI Academy!** 🚀

Created with ❤️ for AI Enthusiasts | Free & Open for Everyone
