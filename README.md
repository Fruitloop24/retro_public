---

# Retro Portfolio Project
Welcome to the Retro Portfolio Project! This repository is designed as a unique, fast, and efficient e-portfolio to showcase various development projects and technical skills. With a retro-inspired look, it stands out while still focusing on functionality and accessibility.

[Explore the live e-portfolio here](https://eportkc.com)

## 🕹️ Why Retro?
The retro aesthetic was chosen to create an engaging, nostalgic experience that makes the portfolio memorable. In a world full of modern designs, this project shows versatility and creativity, proving that great work can come in all styles.

## 🚀 Project Goals
- **Compact and Efficient**: Lightweight design for quick load times and responsiveness on any device.
- **Engagement and Fun**: From the initial login screen to project showcases, the experience is interactive and different from the norm.
- **Easy to Navigate**: Simple structure that provides easy access to detailed documentation, related projects, and resources.

## 🔧 Getting Started
### 1. **Clone the Repository**
Start by cloning this repository to your local machine:
```bash
git clone git@github.com:YourUsername/retro_portfolio.git
cd retro_portfolio
```

### 2. **Customize Placeholders**
Edit the `index.html`, `css/style.css`, and `js/main.js` files to replace placeholder text and URLs with your own content:
- **index.html**: Replace `[Your Name]`, `[Your GitHub Profile URL]`, and other placeholders.
- **css/style.css**: Adjust styles if you want to personalize the look further.
- **js/main.js**: Make sure the JavaScript functions align with any added customizations.

### 3. **Deploying to Azure Static Web Apps**
- **Sign Up for Azure**: [Sign up for Azure](https://portal.azure.com/) if you're new and create a Static Web App.
- **Connect GitHub Repository**: Link this repository to your Azure account for automatic builds and deployments.
- **Configure GitHub Actions**: Ensure that your main branch triggers a GitHub Actions workflow to deploy the app.

### Using Azure Blob Storage:
- **Storage Setup**: Configure Azure Blob Storage for dynamic content like blog posts and podcast files.
- **Embed Content**: Use iframes to pull content directly from Blob Storage:
    ```html
    <iframe src="https://<your-storage-account>.blob.core.windows.net/$web/your-content.html" width="100%" height="600px" style="border:none;"></iframe>
    ```

## 🛠️ Key Features
- **AI Integration**: AI tools were used throughout the development to make debugging, testing, and enhancement seamless.
- **Related Projects**:
    - **[Blog Server](https://github.com/yourusername/blog-server)**: Automates AI-driven blog content generation.
    - **[AI Agent](https://github.com/yourusername/ai-agent)**: Provides system diagnostics and security checks.

## 🤖 Leveraging Aider and AI Tools
Aider and other AI tools bridge the gap between coding and innovation. They were used for quick debugging, testing, and refining code. To make using these tools easier:
- **Environment Variables**: Store your API keys securely in your `.bashrc` or `.bash_profile`:
    ```bash
    export OPENAI_API_KEY="your_openai_api_key"
    ```
- **Alias for Quick Access**: Set up an alias to call the AI tools easily:
    ```bash
    alias aider="path_to_aider --api-key $OPENAI_API_KEY"
    ```

---

