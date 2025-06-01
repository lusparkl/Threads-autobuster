# Threads AutoBooster 🤖

An autonomous Threads.net promotion bot that leverages AI and automation to grow your presence through smart content generation and engagement.

## Core Functionality

### 🤖 AI-Powered Content Generation
- Dynamic post creation based on user style and preferences
- Context-aware comment generation for meaningful engagement
- Natural language processing for human-like interactions
- Smart response generation with post context awareness
- Persona-based content evaluation and filtering
- Multi-style post generation with varying lengths and tones
- Ukrainian language integration for more natural content

### 📅 Automated Activities
- Multi-time post scheduling system
- Interval-based comment and follow automation
- Smart activity rate limiting and safety checks
- Real-time activity monitoring and logging
- Sleep mode with random variations for human-like behavior
- Automated response to comments on your posts
- Smart content evaluation before engagement
- Random delays between actions for natural behavior

### 🔄 Browser Automation
- Headless browser control via Playwright
- Cookie-based authentication system
- Dynamic content interaction
- Feed parsing and post extraction
- Automated user engagement
- Proxy support with health checks
- Smart post text extraction
- Comment response automation
- Activity feed monitoring

### 📊 Activity Management
- SQLite database for activity tracking
- Comprehensive logging system
- Daily statistics generation
- Rate limit enforcement
- Activity validation and safety checks
- Detailed activity reports
- Success/failure tracking
- Hourly and daily limits enforcement

## Technology Stack

### Backend
- **Python 3.11+** - Core programming language
- **Playwright** - Browser automation and interaction
- **APScheduler** - Task scheduling and management
- **OpenAI API** - AI content generation
- **SQLite** - Activity and state management
- **YAML** - Configuration management
- **Dotenv** - Environment variable management

### Control Interface
- **Telegram Bot** - Remote control and monitoring
- **Admin-only access** - Secure command interface
- **Real-time notifications** - Activity updates
- **Manual job execution** - On-demand activity control
- **Status monitoring** - Real-time bot state tracking

### Infrastructure
- **Cookie-based Auth** - Secure session management
- **Environment Variables** - Secure configuration
- **Logging System** - Activity tracking and debugging
- **Rate Limiting** - Safety and compliance
- **Proxy Support** - IP rotation and management
- **Error Recovery** - Automatic retry mechanisms
- **Sleep Mode** - Configurable rest periods

## Architecture

The bot operates through several interconnected components:
1. **Scheduler** - Manages all automated activities
2. **Browser Controller** - Handles Threads.net interactions
3. **AI Engine** - Generates content and responses
4. **Database** - Tracks activities and maintains state
5. **Telegram Interface** - Provides control and monitoring
6. **Configuration Manager** - Handles bot settings and persona
7. **Activity Monitor** - Tracks and limits interactions
8. **Proxy Manager** - Handles IP rotation and health checks

## Safety Features

- Rate limiting and activity caps
- Secure credential management
- Automated safety checks
- Activity validation
- Error handling and recovery
- Proxy health monitoring
- Sleep mode for natural behavior
- Content evaluation before engagement
- Random delays between actions
- Comprehensive error logging

## Configuration

The bot is highly configurable through `config.yaml`:
- AI model settings and prompts
- Activity limits and schedules
- Browser settings and proxy configuration
- Persona definition and content style
- Sleep mode settings
- Content evaluation criteria
- Response generation rules

---

Made with ❤️ 
