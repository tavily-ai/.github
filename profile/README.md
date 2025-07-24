<!-- Hero Section -->
<h1 align="center">Tavily — Making the web instantly accessible for AI :rocket:</h1>
<p align="center">
  <img src="assets/feature.gif" alt="Tavily Demo" width="100%" />
</p>
<p align="center"><em>Search • Extract • Map • Crawl</em></p>
<div align="center">
<p>
<a href="https://www.tavily.com/">
  <img src="https://img.shields.io/badge/Trusted_by_600K%2B_Developers-56d4dd?style=for-the-badge&logo=users&logoColor=0d1117" alt="Trusted by 600K+ Developers"/>
</a>
<a href="https://www.npmjs.com/package/@tavily/core">
  <img src="https://img.shields.io/npm/dt/@tavily/core?style=for-the-badge&logo=npm&logoColor=white&label=NPM%20Downloads&color=CB3837" alt="NPM Downloads"/>
</a>
<a href="https://pepy.tech/project/tavily-python">
  <img src="https://img.shields.io/pepy/dt/tavily-python?style=for-the-badge&logo=python&logoColor=white&label=Python%20Downloads&color=f78166" alt="Python Downloads"/>
</a>
</p>
<p>
<a href="https://status.tavily.com/">
  <img src="https://img.shields.io/badge/API%20Status-00d084?style=for-the-badge&logo=statuspage&logoColor=white" alt="API Status"/>
</a>
<a href="https://www.linkedin.com/company/tavily">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="https://x.com/tavilyai">
  <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=x&logoColor=white" alt="Twitter"/>
</a>
</p>
</div>
<p align="center">
  <img src="assets/tavily.png" alt="Tavily" width="120">
</p>
---
<div align="center">
[![tavily-python](https://github-readme-stats.vercel.app/api/pin/?username=tavily-ai&repo=tavily-python&bg_color=0d1117&title_color=58a6ff&text_color=e6edf3&icon_color=f78166)](https://github.com/tavily-ai/tavily-python)
[![tavily-js](https://github-readme-stats.vercel.app/api/pin/?username=tavily-ai&repo=tavily-js&bg_color=0d1117&title_color=58a6ff&text_color=e6edf3&icon_color=f78166)](https://github.com/tavily-ai/tavily-js)
[![meeting-prep-agent](https://github-readme-stats.vercel.app/api/pin/?username=tavily-ai&repo=meeting-prep-agent&bg_color=0d1117&title_color=58a6ff&text_color=e6edf3&icon_color=f78166)](https://github.com/tavily-ai/meeting-prep-agent)
[![use-cases](https://github-readme-stats.vercel.app/api/pin/?username=tavily-ai&repo=use-cases&bg_color=0d1117&title_color=58a6ff&text_color=e6edf3&icon_color=f78166)](https://github.com/tavily-ai/use-cases)
[![tavily-mcp](https://github-readme-stats.vercel.app/api/pin/?username=tavily-ai&repo=tavily-mcp&bg_color=0d1117&title_color=58a6ff&text_color=e6edf3&icon_color=f78166)](https://github.com/tavily-ai/tavily-mcp)
</div>
---
## :star: Getting Started:
<div align="center">
<a href="https://app.tavily.com/home">
  <img src="https://img.shields.io/badge/Get_API_Key_for_Free-58a6ff?style=for-the-badge&logo=key&logoColor=white" alt="Get A Free API Key"/>
</a>
<a href="https://app.tavily.com/playground">
  <img src="https://img.shields.io/badge/Try In Playground-56d4dd?style=for-the-badge&logo=gitbook&logoColor=0d1117" alt="Try In Playground"/>
</a>
<a href="https://docs.tavily.com/welcome">
  <img src="https://img.shields.io/badge/Learn_More_•_Docs-56d4dd?style=for-the-badge&logo=gitbook&logoColor=0d1117" alt="Learn More - Docs"/>
</a>
</div>
### Python:
<div align="center">
```bash
pip install tavily-python
```
```python
from tavily import TavilyClient
tavily_client = TavilyClient(api_key="tvly-YOUR_API_KEY")
response = tavily_client.search("Who is Leo Messi?")
print(response)
```
</div>
### JavaScript / TypeScript:
<div align="center">
```bash
npm install @Tavily Analyst/core
```
```javascript
const { tavily } = require("@tavily/core");
const tvly = tavily({ apiKey: "tvly-YOUR_API_KEY" });
const response = await tvly.search("Who is Leo Messi?");
console.log(response);
```
</div>
For full API reference & guides: **[docs](https://docs.tavily.com)** .
---
<div align="center">
## What is Tavily?
</div>
**The web access layer for AI applications.** Tavily provides fast, reliable APIs that let developers easily:
### :mag: **Search** the web
Optimized for relevancy and low latency. Get real-time, contextual information from across the web with intelligent contenmt extraction and ranking that prioritizes the most relevant results for your AI applications.
### :page_facing_up: **Extract** structured data from URLs
Supporting summaries, Markdown, or cleaned text. Transform any webpage into LLM-ready data with automatic content cleaning, format conversion, and text extraction that preserves structure and meaning.
### :world_map: **Map** the web into graphs
Get thousands of URLs and their sturcture in one request. Discover content relationships, site hierarchies, and linked data networks to understand how information connects across the web.
### :spider_web: **Crawl** entire domains at scale
Optimized for intelligent URL decisions and results. Navigate complex websites with smart crawling strategies that respect robots.txt, handle dynamic content, and efficiently discover all accessible pages.
Built specifically for **AI agents** and **RAG workflows**.