# AI Risk & Mitigation Assistant for Miro

A Miro-integrated workshop assistant that helps facilitate AI risk assessment and mitigation brainstorming sessions. This tool combines structured workshop methodologies with AI-powered suggestions to help teams identify potential risks, develop mitigation strategies, and explore benefits of AI systems.

## Overview

The AI Risk & Mitigation Assistant is designed for research workshops focused on AI ethics, risk assessment, and responsible AI development. It integrates with Miro boards to facilitate two primary workshop formats:

- **Futures Wheel Workshops**: Explore cause-and-effect relationships and potential consequences
- **Empathy Mapping Workshops**: Understand stakeholder perspectives and impacts

## Key Features

### Workshop Formats
- **Futures Wheel**: Interactive brainstorming for exploring consequences and impacts
- **Empathy Mapping**: Stakeholder-focused analysis with persona-based insights
- **Free-form Brainstorming**: Flexible workshop structure based on Futures Wheel methodology

### AI Use Case Scenarios
The assistant comes with pre-configured AI scenarios for workshop activities:
- **Chatbot Companion AI** (Salieri): Emotional support and companionship system
- **Medical AI**: Autonomous organ transplant allocation system  
- **Self-driving Car AI** (Altair): Autonomous vehicle navigation system
- **AI Artist**: 3D model generation for game development

### AI-Powered Assistance
- **Risk Generation**: Automatically suggests potential risks based on EU AI Act, SDGs, and Human Rights frameworks
- **Mitigation Strategies**: Proposes practical mitigation approaches
- **Benefits Analysis**: Identifies positive impacts and opportunities
- **Personal AI Assistant**: Interactive chat interface for brainstorming support

### Integration Features
- **Miro Board Reading**: Automatically reads and analyzes Miro board content
- **Selected Item Analysis**: Focuses on specific board elements
- **Real-time Suggestions**: Provides contextual AI-powered recommendations
- **Auto-idea Generation**: Configurable timer-based suggestion system

## Technical Architecture

### Frontend
- HTML/CSS/JavaScript application
- Miro Web SDK v2 integration
- Responsive design with Inter font family
- Real-time board interaction capabilities

### AI Integration
- GPT-4 integration for content generation
- Specialized system prompts for different expert roles:
  - RiskGen: AI risk identification expert
  - Mitigation specialist
  - Benefits analyst  
  - Personal assistant with comprehensive AI ethics knowledge

### Workshop Structure
- **Group Mappings**: Supports workshops 4-13 with different AI use case combinations
- **Empathy Modes**: Persona-based analysis and impact assessment
- **Timer Controls**: Auto-suggestion intervals (default 10 minutes)

## Risk Assessment Framework

The tool uses a comprehensive framework combining:
- **EU AI Act**: Compliance requirements for high-risk AI systems
- **17 Sustainable Development Goals (SDGs)**: Global development framework
- **UN Universal Declaration of Human Rights**: 30 articles for rights-based analysis
- **DeepMind Risk Taxonomy**: 6 categories for systematic risk classification
  - Discrimination, Hate speech and Exclusion
  - Information Hazards
  - Misinformation Harms
  - Malicious Uses
  - Human-Computer Interaction Harms
  - Environmental and Socioeconomic harms

## Usage

### Setup
1. Host the application locally or on a web server
2. Configure Miro Developer Team and app permissions
3. Install the app to your Miro team
4. Configure API keys for GPT integration

### Workshop Facilitation
1. **Select Workshop Type**: Choose between Futures Wheel or Empathy Mapping
2. **Choose AI Use Case**: Select from predefined scenarios or customize
3. **Start Workshop**: Use Miro board for collaborative brainstorming
4. **Get AI Assistance**: Leverage automated suggestions and analysis
5. **Generate Content**: Use AI-powered risk, mitigation, and benefit generation

### Key Controls
- **Read Board**: Analyze all content on the current Miro board
- **Read Selected**: Focus analysis on selected board items
- **AI Suggestions**: Generate contextual recommendations
- **Workshop Toggle**: Switch between Futures Wheel and Empathy Mapping modes
- **Auto-Ideas**: Enable/disable automated suggestion timer

## File Structure

```
├── dist/
│   ├── index.html          # Miro app entry point
│   ├── app.html           # Main application interface
│   └── assets/            # Compiled assets and resources
├── empathy_mapping.html    # Standalone empathy mapping workshop
├── futures_wheel.html     # Standalone futures wheel workshop
└── README.md              # This file
```

## Research Context

This tool was developed for academic research on AI risk assessment methodologies and workshop facilitation techniques. The system supports controlled studies comparing different workshop formats and AI assistance levels.

**Note**: This codebase contains research group mappings and experimental configurations that should be reviewed and modified for production use.

## Technical Requirements

- Modern web browser with JavaScript enabled
- Miro account with Developer Team access
- GPT API access for AI-powered features
- Local web server for development/hosting

## License

This software was developed for research purposes. Please contact the research team for licensing and usage permissions.