# Google Colab Compatible Notebooks

This folder contains all Python projects converted to Jupyter notebooks (.ipynb) that can be directly run in Google Colab.

## 🔑 API Key Setup

**IMPORTANT:** Before running any notebook, you need to:

1. Get your OpenAI API key from: https://platform.openai.com/api-keys
2. For GitHub MCP notebooks (08 & 09), create a GitHub Personal Access Token: https://github.com/settings/tokens/new
   - Required scopes: `read:user`, `public_repo`

3. Add your API keys in the designated cell:
   ```python
   # 🔐 ENTER YOUR API KEY HERE
   OPENAI_API_KEY = "sk-proj-your-actual-key-here"
   GITHUB_PAT = "ghp_your-github-token-here"  # Only for MCP notebooks
   ```

## 📚 Notebooks Overview

| # | Notebook | Description |
|---|----------|-------------|
| 01 | **Connecting_LLM** | Basic OpenAI API connection and simple request |
| 02 | **No_Memory_Chatbot** | Simple chatbot without conversation memory |
| 03 | **Memory_Chatbot** | Chatbot that remembers conversation history |
| 04 | **Audio_Generation** | Text-to-Speech using OpenAI TTS |
| 05 | **Image_Generation** | Generate images using AI |
| 06 | **Web_Search** | Using web search with chained LLM calls |
| 07 | **Web_Search_Project** | Complete shipping route analysis with web search |
| 08 | **MCP_GitHub** | Connect to GitHub using Model Context Protocol |
| 09 | **MCP_Code_Audit** | Complete code audit project using GitHub MCP |
| 10 | **Code_Interpreter** | Using code interpreter for calculations |
| 11 | **Code_Image_Output** | Generate and retrieve charts/images from code |
| 12 | **GPT_Reasoning** | Using GPT's reasoning capability for logic puzzles |
| 13 | **GPT_Reasoning_Improved** | Advanced reasoning with shipping route analysis |

## 🚀 How to Use in Google Colab

1. **Upload to Google Colab:**
   - Go to https://colab.research.google.com/
   - Click `File` → `Upload notebook`
   - Select the notebook you want to run

2. **Or use Google Drive:**
   - Upload this entire folder to your Google Drive
   - Open notebooks directly from Drive in Colab

3. **Run the notebooks:**
   - Each notebook has cells that install required packages
   - Add your API keys in the designated cell
   - Run cells sequentially from top to bottom

## 💡 Tips

- **Free tier limitations:** Google Colab free tier has resource limits. Some operations may be slower.
- **API costs:** OpenAI API calls will be charged to your OpenAI account.
- **Session persistence:** Colab sessions disconnect after inactivity. Save your work!
- **File outputs:** Generated files (images, audio, text) will be saved in the Colab session storage.

## ⚠️ Security Note

**NEVER** commit or share notebooks with your actual API keys! Always replace them with placeholders before sharing:
```python
OPENAI_API_KEY = "YOUR_API_KEY_HERE"
```

## 📖 Learning Path

**Beginners:** Start with notebooks 01 → 02 → 03 → 04 → 05

**Intermediate:** Try notebooks 06 → 07 → 10 → 11

**Advanced:** Explore notebooks 08 → 09 → 12 → 13

## 🔗 Useful Links

- OpenAI API Documentation: https://platform.openai.com/docs
- OpenAI Pricing: https://openai.com/api/pricing/
- Google Colab Guide: https://colab.research.google.com/notebooks/intro.ipynb

---

Happy Learning! 🎉
