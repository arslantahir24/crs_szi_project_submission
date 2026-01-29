# 🚀 Content Generator

AI-powered multi-platform content generation tool that transforms a single keyword into professional content for 5 different platforms.

## ✨ Features

- **📝 Blog Posts** - Complete, SEO-optimized articles
- **🐦 Twitter Threads** - Engaging 6-8 tweet threads  
- **💼 LinkedIn Posts** - Professional content for business audiences
- **📘 Facebook Posts** - Conversational, shareable content
- **📸 Instagram Captions** - Visual-first social media content

## 🎯 Live Demo

**[Try it here →](https://YOUR-USERNAME.github.io/content-generator/)**

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript (Vanilla)
- **Automation**: n8n workflow
- **AI**: OpenAI GPT-4o-mini
- **Database**: Airtable
- **Hosting**: GitHub Pages

## 📖 How It Works

1. Enter a keyword or topic
2. Click "Generate Content"
3. Wait 30-60 seconds for AI generation
4. Get 5 pieces of platform-specific content
5. Copy and use anywhere

## 🚀 Quick Start

### For Users

Simply visit the [live site](https://YOUR-USERNAME.github.io/content-generator/) and start generating content!

### For Developers

1. Clone this repository:
```bash
git clone https://github.com/YOUR-USERNAME/content-generator.git
```

2. Update the webhook URL in `index.html`:
```javascript
const N8N_WEBHOOK_URL = 'your-n8n-webhook-url';
```

3. Open `index.html` in your browser

## 🔧 Configuration

The tool requires an n8n workflow with:
- Webhook trigger endpoint
- Company profile integration (Airtable)
- AI content generation nodes
- Response formatting

See `SETUP_GUIDE.md` for detailed setup instructions.

## 📱 Platforms Supported

| Platform | Content Type | Optimized For |
|----------|-------------|---------------|
| Blog | Long-form articles | SEO & readability |
| Twitter/X | Threaded tweets | Engagement & viral reach |
| LinkedIn | Professional posts | B2B & networking |
| Facebook | Social updates | Sharing & conversation |
| Instagram | Caption + hashtags | Visual storytelling |

## 🔒 Security

- No sensitive data stored in frontend
- Webhook handles authentication
- Rate limiting on backend
- HTTPS enabled

## 📊 Features

- ✅ Clean, modern UI
- ✅ Responsive design (mobile-friendly)
- ✅ Real-time generation
- ✅ One-click copy to clipboard
- ✅ Character/word count display
- ✅ Loading animations
- ✅ Error handling

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest features
- Submit pull requests

## 📄 License

MIT License - feel free to use this for your own projects!

## 👨‍💻 Author

Created with ❤️ for efficient content creation

## 🙏 Acknowledgments

- n8n for workflow automation
- OpenAI for AI capabilities
- Airtable for data storage
- GitHub Pages for hosting

---

**⭐ Star this repo if you find it useful!**
