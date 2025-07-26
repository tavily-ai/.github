<!-- Hero Section -->

<h1 align="center">Tavily - The Web Access Layer for AI Agents</h1>


<p align="center">
  <a href="https://www.tavily.com/">
    <img src="assets/feature.gif" alt="Tavily Demo" width="100%" />
  </a>
</p>

<p align="center"><em>Search • Extract • Map • Crawl</em></p>

<div align="center">

<p>
<a href="https://www.tavily.com/">
  <img src="https://img.shields.io/badge/Trusted_by_600K%2B_Developers-ff5b6b?style=for-the-badge&logo=users&logoColor=white" alt="Trusted by 600K+ Developers"/>
</a>
<a href="https://www.npmjs.com/package/@tavily/core">
  <img src="https://img.shields.io/npm/dt/@tavily/core?style=for-the-badge&logo=npm&logoColor=white&label=NPM%20Downloads&color=ff5b6b" alt="NPM Downloads"/>
</a>
<a href="https://pepy.tech/project/tavily-python">
  <img src="https://img.shields.io/pepy/dt/tavily-python?style=for-the-badge&logo=python&logoColor=white&label=Python%20Downloads&color=ff5b6b" alt="Python Downloads"/>
</a>
</p>

<p>
<a href="https://www.linkedin.com/company/tavily">
  <img src="https://img.shields.io/badge/Follow_us_on_LinkedIn-0077B5?style=for-the-badge&logo=LinkedIn&logoColor=white" alt="Follow us on LinkedIn"/>
</a>
<a href="https://x.com/tavilyai">
  <img src="https://img.shields.io/badge/Follow_us_on_X-000000?style=for-the-badge&logo=x&logoColor=white" alt="Follow us on X"/>
</a>
<a href="https://status.tavily.com/">
  <img src="https://img.shields.io/badge/API%20Status-00d084?style=for-the-badge&logo=statuspage&logoColor=white" alt="API Status"/>
</a>
</p>

</div>

<p align="center">
  <a href="https://www.tavily.com/">
    <img src="assets/tavily.png" alt="Tavily" width="120">
  </a>
</p>

---

<div align="center">

<a href="https://github.com/tavily-ai/tavily-python">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=tavily-ai&repo=tavily-python&bg_color=0d1217&title_color=58a6ff&text_color=e6edf3&icon_color=f78166&v=2" alt="tavily-python" />
</a>
<a href="https://github.com/tavily-ai/tavily-js">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=tavily-ai&repo=tavily-js&bg_color=0d1117&title_color=58a6ff&text_color=e6edf3&icon_color=f78166&v=2" alt="tavily-js" />
</a>
<a href="https://github.com/tavily-ai/tavily-mcp">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=tavily-ai&repo=tavily-mcp&bg_color=0d1117&title_color=58a6ff&text_color=e6edf3&icon_color=f78166&v=2" alt="tavily-mcp" />
</a>

</div>


---

## ⭐ Getting Started:

<div align="center">

<a href="https://app.tavily.com/home">
  <img src="https://img.shields.io/badge/Free_API_Key-ff5b6b?style=for-the-badge&logo=gift&logoColor=white" alt="Free API Key"/>
</a>
<a href="https://app.tavily.com/playground">
  <img src="https://img.shields.io/badge/Playground-0066cc?style=for-the-badge&logo=play&logoColor=white" alt="Playground"/>
</a>
<a href="https://docs.tavily.com/welcome">
  <img src="https://img.shields.io/badge/Documentation-e7a910?style=for-the-badge&logo=book&logoColor=white" alt="Documentation"/>
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
