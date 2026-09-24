<!-- Header -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Yashwanth%20Sai%20Nallapuneni&fontSize=42&fontColor=ffffff&fontAlignY=36&desc=AI%20Engineer%20%E2%80%A2%20M.S.%20CS%20%40%20Columbia&descSize=17&descAlignY=58" width="100%"/>

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=3200&pause=900&color=5FB3C9&center=true&vCenter=true&width=620&lines=I+build+LLM+systems+that+can+be+trusted.;Agents+%E2%80%A2+RAG+%E2%80%A2+LLM+evaluation;From+prototype+to+production%2C+with+the+tests+to+prove+it." alt="typing intro"/>

<p>
  <a href="mailto:yn2509@columbia.edu"><img src="https://img.shields.io/badge/Email-yn2509%40columbia.edu-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/yashwanth-nallapuneni/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://arxiv.org/abs/2510.13202"><img src="https://img.shields.io/badge/arXiv-2510.13202-B31B1B?style=for-the-badge&logo=arxiv&logoColor=white"/></a>
</p>

</div>

---

## 👋 About me

I'm an **AI engineer** doing my M.S. in Computer Science at **Columbia University** (Fall 2026 to Dec 2027). Before that, I did my B.Tech in CSE (Blockchain Technology) at **VIT Vellore**, graduating with a 9.15 CGPA and ranked 6th in my program.

I build applications on top of large language models: agent workflows, retrieval pipelines, and the evaluation harnesses that show whether they actually work. I care most about the unglamorous part, making LLM output **reliable, measurable, and safe to ship**.

```python
yashwanth = {
    "role":       "AI Engineer",
    "now":        "M.S. CS @ Columbia University",
    "building":   ["LLM agents", "RAG pipelines", "LLM evaluation",
                   "LLM infrastructure"],
    "stack":      ["Python", "LangGraph", "LangChain", "FastAPI", "Docker"],
    "ask_me_about": ["LangGraph agents", "LLM evals", "synthetic data quality"],
}
```

---

## 💼 Experience

**AI Research Intern** · Jio Institute, Navi Mumbai · *Jun 2026 to Jul 2026*
- Built automated LLM experiment pipelines with **LangChain, LangGraph and the OpenRouter API**, running controlled evaluations on GSM8K and Visual7W
- Engineered a multi-turn Solver–Prober setup to test whether LLMs stay consistent under adversarial questioning, across different prompting tones
- Extended multiple-choice evaluation experiments to vision-language models by building visual reasoning benchmarks

**Undergraduate Research Assistant** · VIT Vellore · Advisor: Prof. Gopichand G · *Jul 2025 to May 2026*
- Built LLM-guided data augmentation to reduce bias in AI systems, with checks on semantic fidelity, safety and statistical validity
- Designed experiments measuring fairness and subgroup performance gaps; contributed to an IEEE-published paper

---

## 📄 Publication

**LGSA: LLM-Guided Synthetic Augmentation for Mitigating Bias in AI Systems**<br/>
IEEE ICoECIT 2026 · [arXiv:2510.13202](https://arxiv.org/abs/2510.13202)<br/>
<sub>Uses an LLM to generate label-consistent counterfactual samples for underrepresented groups, validated in multiple stages. Narrows subgroup performance gaps without hurting overall accuracy.</sub>

---

## 🚀 Projects

<table>
<tr>
<td width="50%" valign="top">

### 📚 [ragpipe](https://github.com/Yashwanth-Nallapuneni/rag)
**Production RAG with enforced citations.** Answers questions over 40 arXiv papers, and every claim must trace to a retrieved passage, or the system refuses. Hybrid BM25 + dense retrieval, cross-encoder reranking, a LangGraph pipeline, and a RAGAS quality gate on every pull request.

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white"/>
<img src="https://img.shields.io/badge/ChromaDB-FF6446?style=flat-square"/>
<img src="https://img.shields.io/badge/RAGAS-6E40C9?style=flat-square"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>

</td>
<td width="50%" valign="top">

### ⚡ [llm-gateway](https://github.com/Yashwanth-Nallapuneni/llm-gateway)
**Async rate-limit layer for LLM APIs**, published on PyPI as [`aiollm-gateway`](https://pypi.org/project/aiollm-gateway/). Paces requests under provider limits, retries what's worth retrying, batches prompts, and fails over with a circuit breaker. Zero runtime dependencies.

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/asyncio-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/PyPI-3775A9?style=flat-square&logo=pypi&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧪 [Synthetic Data Quality Validator](https://github.com/Yashwanth-Nallapuneni/synthetic-data-quality-validator)
Scores synthetic tabular data on fidelity, utility, privacy, diversity and calibration, detecting numeric and categorical features automatically. FastAPI backend in Docker, Streamlit front end.

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/>

</td>
<td width="50%" valign="top">

### 🔍 [AI Hallucination Taxonomy Explorer](https://github.com/Yashwanth-Nallapuneni/AI-Hallucination-Taxonomy)
Detects and categorizes LLM hallucinations with heuristic and LLM-based pipelines. Measures prompt–output drift with sentence embeddings, and its taxonomy refines itself as new cases come in.

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/Sentence%20Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/>
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/>

</td>
</tr>
</table>

---

## 🛠️ Tech stack

<table>
<tr><td><b>Languages</b></td><td><img src="https://skillicons.dev/icons?i=python,cpp,js,html&theme=dark" /></td></tr>
<tr><td><b>LLM & AI</b></td><td>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
<img src="https://img.shields.io/badge/ChromaDB-FF6446?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white"/>
</td></tr>
<tr><td><b>Data</b></td><td>
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
</td></tr>
<tr><td><b>Engineering</b></td><td><img src="https://skillicons.dev/icons?i=fastapi,docker,git,githubactions,linux,bash&theme=dark" /></td></tr>
</table>

<sub>Also: retrieval-augmented generation, prompt engineering, LLM evaluation, synthetic data.</sub>

---

## 📊 GitHub stats

<div align="center">
<img height="165" src="https://github-readme-stats.vercel.app/api?username=Yashwanth-Nallapuneni&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&count_private=true"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Yashwanth-Nallapuneni&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&langs_count=6"/>
<br/>
<img src="https://streak-stats.demolab.com?user=Yashwanth-Nallapuneni&theme=github-dark-blue&hide_border=true&background=0d1117" />
</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=110&section=footer" width="100%"/>
