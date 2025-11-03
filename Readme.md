# 📝 Free-Readme-and-License-Generator  

A lightweight, AI-powered solution to instantly generate polished GitHub README.md files and ready-to-use LICENSE files for your repositories. This tool combines repository analysis, OpenRouter/OpenAI summarization, and customizable licensing templates into an intuitive Gradio web interface.

![Project Banner](https://img.shields.io/badge/Project-Free%20README%20Generator-blueviolet)  
![AI Powered](https://img.shields.io/badge/AI-Enhanced-orange)  
![Open Source](https://img.shields.io/badge/License-MIT-yellow)  
![Gradio](https://img.shields.io/badge/Built%20with-Gradio-ff69b4)  
![Python](https://img.shields.io/badge/Code%20Language-Python-success)  
![GitHub](https://img.shields.io/badge/Platform-GitHub-green)

---

## ✨ Features

- 🤖 **AI-Enhanced Summarization**: Leverages OpenAI via OpenRouter for intelligent repository analysis
- 📊 **GitHub Repository Analysis**: Automatically scans and analyzes your repository structure
- 📝 **Customizable README Generation**: Creates professional README.md files with your project's details
- 📜 **Ready-to-Use Licenses**: Generates MIT, Apache 2.0, GPL, and other popular licenses
- 🎨 **Beautiful UI**: Clean and intuitive Gradio web interface for easy use
- ⚙️ **Flexible Configuration**: Customize content style and license terms
- 🌐 **Multi-Language Support**: Works with repositories in any programming language
- 📈 **Repository Insights**: Highlights key project metrics and documentation gaps

---

## 🚀 Installation

### Prerequisites

- Python 3.8+
- Git
- OpenRouter API key ([Get your free key](https://openrouter.ai/))

### Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/Pranesh-2005/Free-Readme-and-License-Generator.git
cd Free-Readme-and-License-Generator
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Set up environment variables:
```bash
# Create .env file
echo "KEY=YOUR_OPENROUTER_API_KEY" > .env
```

4. Install frontend dependencies (optional):
```bash
cd front
npm install
```

---

## 🛠️ Usage

### Running the Application

1. Start the Gradio interface:
```bash
python app.py
```

2. Open your browser and navigate to the local URL (typically http://localhost:7860)

3. Enter your repository details:
   - **Repository URL**: Enter your GitHub repository URL
   - **Username**: Your GitHub username
   - **License Type**: Select desired license (MIT, Apache 2.0, GPL, etc.)

4. Click "Generate" to create your README and LICENSE files

### Example

```bash
python app.py
# Visit http://localhost:7860
```

---

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/AmazingFeature`)
3. **Commit your changes** (`git commit -m 'Add some AmazingFeature'`)
4. **Push to the branch** (`git push origin feature/AmazingFeature`)
5. **Open a Pull Request**

### Development Guidelines

- Follow PEP 8 style guidelines
- Add tests for new features
- Update documentation as needed
- Use descriptive commit messages

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🌟 Star History

![Star History Chart](https://api.star-history.com/svg?repos=Pranesh-2005/Free-Readme-and-License-Generator&type=Date)

---

<div align="center">
  <strong>Give this project a ⭐ if it helped simplify your documentation workflow!</strong>
</div>

## License
This project is licensed under the **MIT** License.

---
🔗 GitHub Repo: https://github.com/Pranesh-2005/Free-Readme-and-License-Generator