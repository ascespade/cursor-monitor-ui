# Cursor Monitor - AI-Powered Development Platform

A modern, full-featured AI development platform interface built with HTML, CSS, and JavaScript. This is the frontend UI that provides a comprehensive dashboard for managing cloud agents, orchestrations, and AI-powered development workflows.

## 🌟 Features

### Core Features
- **Dashboard** - Real-time statistics and analytics
- **Cloud Agents** - Browse and manage AI agents
- **Orchestrations** - Create and monitor complex AI workflows
- **Repository Profiles** - Manage project-specific settings
- **Prompt Templates** - Reusable AI prompt templates
- **Settings** - Complete API key and preference management

### UI Features
- **Dark Mode** - Beautiful dark theme optimized for developers
- **Responsive Design** - Works on desktop and mobile
- **Smooth Animations** - Polished micro-interactions
- **SPA Architecture** - Seamless page transitions

## 📁 Project Structure

```
ui-demo/
├── index.html          # Main application (SPA)
├── dashboard.html      # Dashboard page (legacy)
├── cloud-agents.html   # Cloud agents page (legacy)
├── orchestrate.html    # Create orchestration page (legacy)
├── orchestrations.html # Orchestrations list page (legacy)
├── orchestration-detail.html  # Orchestration details (legacy)
├── prompt-templates.html      # Prompt templates (legacy)
├── repository-profiles.html   # Repository profiles (legacy)
├── settings.html       # Settings page (legacy)
└── login.html          # Authentication page (legacy)
```

## 🚀 Getting Started

### Local Development
Simply open `index.html` in your browser:

```bash
# Using a simple HTTP server
npx serve .

# Or using Python
python -m http.server 8000
```

Then visit `http://localhost:8000`

## 🔧 Technology Stack

- **HTML5** - Semantic markup
- **CSS3** - Custom properties, Flexbox, Grid
- **JavaScript (ES6+)** - Vanilla JS for interactions
- **Google Fonts** - Inter font family

## 📋 Pages Overview

### Home
Landing page with feature highlights and CTA buttons.

### Dashboard
Main dashboard showing:
- Statistics cards (Agents, Orchestrations, Success Rate, Duration)
- Activity chart
- Recent activity feed
- Quick actions

### Cloud Agents
Browse available AI agents:
- Coding agents
- Debugging agents
- Testing agents
- Documentation agents
- Research agents

### Orchestrations
Manage your AI workflows:
- View all orchestrations
- Create new orchestration
- Monitor progress
- View task details and logs

### Create Orchestration
Form to create new orchestrations with:
- Repository URL input
- Model selection (Claude, GPT, Gemini)
- Execution mode (Auto, Single Agent, Pipeline, Batch)
- Advanced options

### Repository Profiles
Manage project-specific settings:
- Safety policies
- Code style configurations
- Preferred agents

### Prompt Templates
Reusable AI prompt templates:
- Feature development templates
- Bug fix workflows
- Code refactoring templates
- Documentation templates

### Settings
Complete configuration:
- Profile management
- API Keys management for:
  - AI Models (Claude, OpenAI, Gemini, HuggingFace)
  - Development (GitHub, GitLab, Bitbucket)
  - Web Search (Serper, Tavily, Jina AI)
  - Browser Automation (Browserbase, ScrapeOps)
  - Webhooks (Slack, Discord, Custom)
- Notification preferences
- Security settings (2FA, Sessions, Password)

### Login
Authentication page with:
- Email magic link login
- GitHub OAuth
- Google OAuth

## 🔐 API Keys Configuration

The system supports multiple API providers for maximum flexibility:

### AI Models
- Anthropic Claude API
- OpenAI GPT API
- Google Gemini API
- HuggingFace Models

### Development Tools
- GitHub Personal Access Token
- GitLab Token
- Bitbucket Token

### Web Research
- Serper (Google Search API)
- Tavily (Research API)
- Jina AI (Content Extraction)

### Browser Automation
- Browserbase
- ScrapeOps

### Notifications
- Slack Webhooks
- Discord Webhooks
- Custom Webhooks

## 🎨 Design System

### Colors
- Primary: `#FFC107` (Amber)
- Secondary: `#D946EF` (Fuchsia)
- Background: `#0E0B16` (Deep purple)
- Surface: `#211D2B` (Dark purple)

### Typography
- **Font**: Inter
- **Monospace**: JetBrains Mono (for code)

## 📱 Responsive Breakpoints

- **Desktop**: > 1024px
- **Tablet**: 768px - 1024px
- **Mobile**: < 768px

## 🛠️ Development

To modify the UI:

1. Edit `index.html` for main application structure
2. CSS styles are embedded in `<style>` tags
3. JavaScript is embedded in `<script>` tags
4. Use browser DevTools for debugging

## 📄 License

MIT License - Feel free to use for personal or commercial projects.

---

**Built with ❤️ for AI-Powered Development**
