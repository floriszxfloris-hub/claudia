# Claudia

A Claude Code-style AI chat interface with orange branding, dark theme, sidebar navigation, and skill selection.

## Features

- **Dark theme** with orange accents (Claude colors)
- **Sidebar** with pinned/recent conversations
- **Skill selector** dropdown (design-taste-frontend, brandkit, etc.)
- **Streaming-capable** API integration
- **LocalStorage persistence** for conversations
- **Responsive** mobile layout
- **Code syntax highlighting** for responses

## Configuration

Edit `config.json` to customize:

```json
{
  "api": {
    "baseUrl": "https://api.tokenlayer.net/",
    "apiKey": "your-api-key-here",
    "model": "claude-opus-4-8"
  },
  "skills": ["your", "skill", "list"],
  "theme": {
    "accentColor": "#e85d04",
    "accentColorHover": "#f48c06",
    "modelBadge": "your-model-name"
  }
}
```

## Tech Stack

- Vanilla HTML/CSS/JS (no build step required)
- Geist font family
- Custom dark theme

## Usage

Open `index.html` directly in a browser, or serve with any static server:

```bash
# Python
python -m http.server 8000

# Node
npx serve
```

## Skills

Available skills that can be activated:

| Skill | Description |
|-------|-------------|
| design-taste-frontend | Anti-slop frontend design patterns |
| design-taste-frontend-v1 | High-agency frontend skill |
| brandkit | Brand design consistency |
| full-output-enforcement | Complete code delivery |
| gpt-taste | Design taste patterns |
| high-end-visual-design | Premium visual design |
| image-to-code | Image to code conversion |
| industrial-brutalist-ui | Brutalist design aesthetic |
| minimalist-ui | Minimalist interface design |
| redesign-existing-projects | Project redesign patterns |
| stitch-design-taste | Design stitching techniques |

## Files

```
claudia/
├── index.html      # Main application
├── config.json     # Configuration
└── README.md       # This file
```
