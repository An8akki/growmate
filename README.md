# GrowMate AI – Digital Marketing Co-Pilot for Bharat 🇮🇳

## 🌍 Vision
To empower Indian small businesses, creators, and startups with an AI-driven marketing assistant that creates content, designs visuals, builds strategy, predicts engagement, and automates planning—all in one intelligent platform.

GrowMate is not just a content generator. It is a **Marketing Decision Engine**.

## 🚀 Core Features

### 1️⃣ AI Content Generator
- Platform-optimized content for Instagram, LinkedIn, X (Twitter)
- Hook lines, captions, CTAs, hashtags with 3 variations
- Brand voice preservation and cultural adaptation

### 2️⃣ AI Post Hit Prediction Engine
- Multi-dimensional analysis: hook strength, CTA clarity, hashtag quality
- **Hit Score (0-100)** with engagement predictions
- Improvement suggestions for low-scoring posts

### 3️⃣ Smart Positioning Engine
- Platform, timing, and format recommendations
- Marketing funnel stage classification
- A/B testing recommendations with predicted outcomes

### 4️⃣ AI Marketing Strategy Planner
- Content pillars and campaign concepts
- 7-day and 30-day content calendars
- Industry-best content mix (40% educational, 30% engagement, 20% promotional, 10% community)

### 5️⃣ Professional Visual Generator
- Clean product images and promotional banners
- Platform-optimized layouts with human design aesthetics
- Brand guideline compliance with 3-5 design variations

### 6️⃣ Reel Builder (Professional Marketing Style)
- 6-10 second marketing reels from generated assets
- Clean text overlays with smooth transitions
- Music synchronization and platform-optimized exports

### 7️⃣ Bharat Mode – Multilingual Support 🇮🇳
- Content generation in English, Hindi, Tamil, Hinglish
- Cultural adaptation with festival references
- UI localization in English and Hindi

### 8️⃣ Automation & Scheduling
- Intelligent scheduling based on positioning recommendations
- Approval workflows with 24-hour advance notice
- Batch scheduling and social media API integration

## 🏗 Technical Architecture

### Frontend
- **React 18+** with TypeScript
- **Tailwind CSS** with custom design system
- **ShadCN/Radix UI** components
- Responsive design for desktop and mobile

### Backend
- **Python 3.11+** with FastAPI
- **PostgreSQL** database with structured schema
- **Redis** for caching and message queues
- **n8n** for workflow automation

### AI Integration
- **LLM APIs**: OpenAI GPT-4, Anthropic Claude, Google Gemini
- **Image Generation**: Commercial APIs with brand compliance
- **Video Processing**: FFmpeg/moviepy for reel creation

## 📋 Specification Documents

The project follows a comprehensive specification-driven development approach:

### [Requirements Document](.kiro/specs/growmate-ai-digital-marketing-copilot/requirements.md)
- **17 requirements** with 100+ acceptance criteria
- Clear user stories and success metrics
- UI/UX design system specifications

### [Design Document](.kiro/specs/growmate-ai-digital-marketing-copilot/design.md)
- **System architecture** and component interfaces
- **55 correctness properties** for property-based testing
- **Comprehensive UI/UX design system** with:
  - Color palette: GrowMate Green (#10B981), Confidence Blue (#3B82F6), Energy Orange (#F59E0B)
  - Typography: Inter font family with complete hierarchy
  - Responsive grid system and component specifications
  - Cultural adaptations for the Indian market
  - WCAG 2.1 AA accessibility compliance

### [Implementation Plan](.kiro/specs/growmate-ai-digital-marketing-copilot/tasks.md)
- **20 main tasks** with 100+ sub-tasks
- Incremental development with checkpoints
- Property-based testing integration
- Performance and security requirements

## 🎯 Target Users
- **Small business owners** in tier 2/3 cities
- **Influencers** and content creators
- **Freelancers** and marketing beginners
- **Local shops** and regional brands
- **Students** and aspiring entrepreneurs

## 🏆 Hackathon Strength
GrowMate delivers:
- **AI-driven creativity** with data-backed decision support
- **Visual content generation** that looks professional, not "AI-styled"
- **Complete marketing workflow** from strategy to publication
- **Multilingual inclusion** for the Indian market
- **Real-world business impact** with measurable results

## 🔄 User Workflow
1. **User selects business type** → AI generates strategy
2. **AI creates content** → AI generates visuals
3. **AI builds reel** → Post gets hit score
4. **Platform & time suggested** → Content scheduled
5. **User approves** → Content published

Everything in one unified dashboard.

## 📊 Success Metrics
- **Content accuracy**: 85% of generated content requires minimal editing
- **Prediction accuracy**: Hit_Score predictions within ±15% of actual engagement
- **User adoption**: 70% trial-to-paid conversion within 30 days
- **System performance**: 95% of interactions complete within 2 seconds
- **Accessibility**: 100% WCAG 2.1 AA compliance

## 🚀 Getting Started

### Prerequisites
- Python 3.11+
- Node.js 18+
- PostgreSQL 14+
- Redis 7+

### Installation
```bash
# Clone the repository
git clone https://github.com/An8akki/growmate
cd growmate

# Install backend dependencies
pip install -r requirements.txt

# Install frontend dependencies
cd frontend
npm install

# Set up environment variables
cp .env.example .env
```

### Development
```bash
# Start backend server
uvicorn app.main:app --reload

# Start frontend development server
cd frontend
npm run dev
```

## 📄 License
MIT License - see [LICENSE](LICENSE) file for details

## 🤝 Contributing
Contributions are welcome! Please read our [Contributing Guidelines](CONTRIBUTING.md) for details.

## 📞 Contact
For questions or support, please open an issue in the GitHub repository.

---

**One-Line Pitch**: GrowMate AI is an intelligent digital marketing co-pilot that creates content, designs visuals, predicts engagement, and automates planning — helping Indian businesses grow smarter online.