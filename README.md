<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,50:16213e,100:0f3460&height=250&section=header&text=Yashwanth%20Sai%20Nallapuneni&fontSize=48&fontColor=ffffff&fontAlignY=38&desc=AI%20Engineer%20%E2%80%A2%20LLM%20Systems%20%E2%80%A2%20MSCS%20%40%20Columbia&descSize=17&descAlignY=58&animation=twinkling" width="100%"/>

<p align="center">
  <a href="mailto:yn2509@columbia.edu"><img src="https://img.shields.io/badge/Email-0f3460?style=for-the-badge&logo=gmail&logoColor=white"/></a>&nbsp;<a href="https://www.linkedin.com/in/yashwanth-nallapuneni/"><img src="https://img.shields.io/badge/LinkedIn-0f3460?style=for-the-badge&logo=linkedin&logoColor=white"/></a>&nbsp;<a href="https://arxiv.org/abs/2510.13202"><img src="https://img.shields.io/badge/arXiv-0f3460?style=for-the-badge&logo=arxiv&logoColor=white"/></a>&nbsp;<a href="https://pypi.org/project/aiollm-gateway/"><img src="https://img.shields.io/badge/PyPI-0f3460?style=for-the-badge&logo=pypi&logoColor=white"/></a>
</p>

<h3 align="center">I build LLM systems that are reliable, measurable, and safe to ship.</h3>

<br/>

## 👋 About me

🎓 &nbsp;**M.S. Computer Science** · Columbia University <sub>(2026 – 2027)</sub><br/>
🏛️ &nbsp;**B.Tech CSE** · VIT Vellore <sub>(9.15 CGPA · ranked 6th in program)</sub><br/>
🛠️ &nbsp;Building **LLM agents, RAG pipelines and evaluation harnesses**<br/>
📦 &nbsp;Shipped [`aiollm-gateway`](https://pypi.org/project/aiollm-gateway/) on PyPI<br/>
📄 &nbsp;Published at **IEEE ICoECIT 2026**<br/>
💬 &nbsp;Ask me about **LangGraph, LLM evals, synthetic data**

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

