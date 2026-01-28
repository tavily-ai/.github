<!-- Hero Section -->


<p align="center">
  <a href="https://www.tavily.com/">
    <img src="assets/tavily_logo_v2.png" alt="Tavily" width="120">
  </a>
</p>

<div align="center">


</div>

## ⭐ Getting Started:

<div align="center">

<a href="https://app.tavily.com/home">
  <img src="https://img.shields.io/badge/Free_API_Key-70a790?style=for-the-badge&logo=gift&logoColor=white" alt="API Key"/>
</a>
<a href="https://app.tavily.com/playground">
  <img src="https://img.shields.io/badge/Playground-70a790?style=for-the-badge&logo=play&logoColor=white" alt="Playground"/>
</a>
<a href="https://docs.tavily.com/welcome">
  <img src="https://img.shields.io/badge/Documentation-70a790?style=for-the-badge&logo=book&logoColor=white" alt="Documentation"/>
</a>

</div>

### Python:

```bash
pip install tavily-python
```

```python
from tavily import TavilyClient

tavily_client = TavilyClient(api_key="tvly-YOUR_API_KEY")
response = tavily_client.search("Who is Leo Messi?")

print(response)
```

### JavaScript / TypeScript:

```bash
npm install @tavily/core
```

```javascript
const { tavily } = require("@tavily/core");

const tvly = tavily({ apiKey: "tvly-YOUR_API_KEY" });
const response = await tvly.search("Who is Leo Messi?");

console.log(response);
```

For full API reference & guides: **[docs](https://docs.tavily.com)** .

---

<h2 align="center">What is Tavily?</h2>

**The web access layer for AI applications.** Tavily provides fast, reliable APIs that let developers easily:

### 🔍 **Search** the web
Optimized for relevancy and low latency. Get real-time, contextual information from across the web with intelligent content extraction and ranking that prioritizes the most relevant results for your AI applications.

### 📄 **Extract** structured data from URLs  
Supporting summaries, Markdown, or cleaned text. Transform any webpage into LLM-ready data with automatic content cleaning, format conversion, and text extraction that preserves structure and meaning.

### 🕸️ **Crawl** entire domains at scale
Optimized for intelligent URL decisions and results. Navigate complex websites with smart crawling strategies that respect robots.txt, handle dynamic content, and efficiently discover all accessible pages.

Built specifically for **AI agents** and **RAG workflows**.
