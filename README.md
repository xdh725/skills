# AI Skills Collection

This repository contains my personal collection of AI CLI skills managed by [skillshare](https://github.com/runkids/skillshare).

## About skillshare

skillshare is a unified skill management system for AI CLI tools like Claude Code, Cursor, Codex, and 50+ more. It maintains a single source of truth for skills and syncs them across all your AI tools.

## Skills in This Collection

### 🎨 Design & Productivity
- **figma** - Figma integration and design workflow skills
- **screenshot** - Screenshot capture and processing skills

### 📄 Document Processing
- **pdf** - PDF parsing, analysis, and manipulation skills

### 🗣️ Speech & Audio
- **speech** - Speech-to-text and audio processing skills

### 📚 Documentation & Learning
- **openai-docs** - OpenAI documentation and API reference skills
- **learned** - Personal knowledge base and learning notes

### 🚀 Development & Deployment
- **vercel-deploy** - Vercel deployment and cloud integration skills
- **track-ai-efficiency** - AI usage tracking and efficiency metrics

### 🔧 System & Utilities
- **skillshare** - Built-in skillshare management skills
- **.system** - System utilities and helper functions

## Setup

To use these skills on your machine:

1. **Install skillshare**
   ```bash
   curl -fsSL https://raw.githubusercontent.com/runkids/skillshare/main/install.sh | sh
   ```

2. **Clone this repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git ~/.config/skillshare/skills
   ```

3. **Initialize skillshare**
   ```bash
   skillshare init --remote https://github.com/YOUR_USERNAME/YOUR_REPO.git
   ```

4. **Sync to your AI tools**
   ```bash
   skillshare sync
   ```

## Daily Workflow

### Pull latest changes
```bash
skillshare pull
```

### Add new skills
```bash
# Install from GitHub
skillshare install anthropics/skills/pdf

# Or create your own
skillshare new my-skill
```

### Push updates
```bash
skillshare push -m "Update skills"
```

## Skill Structure

Each skill follows this structure:
```
skill-name/
├── SKILL.md          # Main skill definition with frontmatter
├── skill.ts          # Implementation code
└── ...               # Additional resources
```

## Sync Targets

This repository is synced across:
- Claude Code
- Cursor
- Other AI CLI tools as configured

## Contributing

Feel free to use these skills as inspiration for your own AI tooling setup!

## License

These skills are personal tools, but feel free to adapt them for your own use.

---

*Managed with ❤️ by [skillshare](https://github.com/runkids/skillshare)*
