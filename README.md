<![CDATA[<div align="center">

<!-- Animated flowing gradient banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=220&section=header&text=Devarajan%20Maheshwaran&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=AI%20%7C%20Federated%20Learning%20%7C%20Blockchain%20%7C%20Backend%20Systems&descAlignY=58&descSize=16&animation=fadeIn" width="100%" />

<!-- Animated typing headline -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=A78BFA&center=true&vCenter=true&width=700&lines=Software+Engineer+%7C+AI+%2F+ML+%7C+Federated+Learning;Blockchain+%7C+ZK+Proofs+%7C+Smart+Contracts;Distributed+Systems+%7C+Backend+Infrastructure;3rd+Year+B.E.+CSE+%40+Chennai+Institute+of+Technology" alt="Typing SVG" />
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/devarajan-maheshwaran/)
[![GitHub](https://img.shields.io/badge/GitHub-161B22?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Devarajan-Maheshwaran)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:devarajanm.magesh@gmail.com)

</div>

---

<img align="right" src="https://github-readme-activity-graph.vercel.app/graph?username=Devarajan-Maheshwaran&theme=tokyo-night&hide_border=true&area=true&radius=8" width="420" />

### About Me

Software engineer focused on the intersection of **privacy-preserving AI**, **blockchain verification**, and **distributed systems**. I build production-grade pipelines where federated learning, zero-knowledge proofs, and on-chain logic converge into real, deployable systems.

- Currently building **BOPFL** — an asynchronous ZK-verified, blockchain-aggregated federated LoRA fine-tuning framework for 7B LLMs
- Backend Developer Intern at **VK Tutelage** on Axentra AI — a multi-modal travel intelligence platform targeting AWS deployment
- Researching the **Privacy–Integrity–Efficiency trilemma** in federated learning: TEEs, synchronous ZK-FL, and crypto-economic schemes each have fatal tradeoffs
- Studying for **GATE 2027** (targeting AIR < 500) and **JLPT N4** Japanese certification
- Open to research internships in **Federated Learning**, **ZK cryptography**, or **Distributed AI**

<br clear="right"/>

---

## Research

**BOPFL — Blockchain-Orchestrated Privacy-Preserving Federated Learning** `2025 – Present`

Formalised the trilemma in federated LoRA fine-tuning of 7B LLMs and designed four core contributions:

| Contribution | What it solves |
|---|---|
| **PoUI** — Halo2 ZK circuit, O(1) on-chain verification via recursive aggregation | Lightweight integrity proof for LoRA update arithmetic |
| **Pre-normalised ZK-Cosine** | Gradient-leak-free alignment check |
| **VRF-driven synthetic auditing** | Semantic poisoning detection without raw data exposure |
| **Asynchronous buffered aggregation** | Decouples global rounds from slow clients |

---

## Projects

<details>
<summary><b>GalleryFL — Privacy-Oriented Federated Learning Platform</b></summary>
<br/>

On-device TFLite fine-tuning pipeline across 5 Non-IID Android clients (Dirichlet α=0.25). Integrates **FedProx**, **Gaussian Differential Privacy** via Opacus, and a validation-driven commit guard to prevent model regression and data leakage.

[View Repository](https://github.com/Devarajan-Maheshwaran/GalleryFL)

</details>

<details>
<summary><b>StudyForge — Adaptive AI Study Platform</b></summary>
<br/>

Zero-API-call NLP pipeline: TF-IDF graph-centrality summariser (ROUGE-L >= 0.38), Bloom's Taxonomy difficulty classifier (F1 >= 0.60), POS-aligned MCQ distractor generator, and cosine-similarity retrieval — all from raw student notes.

[View Repository](https://github.com/Devarajan-Maheshwaran/ai-study-pal)

</details>

<details>
<summary><b>EngageX — Agentic AI Classroom Ecosystem</b></summary>
<br/>

4-crew CrewAI pipeline (Monitor, Intervention, Quiz, Report) with multimodal signal fusion — Whisper + librosa for audio, face-api.js for vision, Transformers.js for text — over FastAPI + Socket.IO delivering real-time per-student analytics and automated PDF reports.

[View Repository](https://github.com/Devarajan-Maheshwaran/EngageX-Classroom-AI)

</details>

<details>
<summary><b>MedVault — Blockchain Health Data Wallet</b></summary>
<br/>

3 Solidity contracts (PatientRegistry, HealthRecordStore, AccessController) on BSC Testnet. Client-side AES-GCM encryption via WebCrypto API, on-chain per-record access control, and an integrated fine-tuned LLM chatbot for AI-assisted record querying.

[View Repository](https://github.com/Devarajan-Maheshwaran/Health-Data-Wallet)

</details>

<details>
<summary><b>Trust-Gated AI Control for Industrial CPS</b></summary>
<br/>

On-chain verification layer (Solidity + Arduino) blocking AI-proposed control actions when dynamic trust score T — derived from misbehaviour rate M = I/N — falls below threshold or diverges from the independently computed expected safe action. Achieved zero unauthorised actuations in simulation.

[View Repository](https://github.com/Devarajan-Maheshwaran/CCP)

</details>

---

## Tech Stack

**AI / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)

**Federated Learning & ZK**

![Python](https://img.shields.io/badge/Flower_flwr-6DA5F5?style=for-the-badge)
![Opacus](https://img.shields.io/badge/Opacus_DP--SGD-EE4C2C?style=for-the-badge)
![Halo2](https://img.shields.io/badge/Halo2_ZK-302b63?style=for-the-badge)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white)

**Blockchain**

![Solidity](https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white)
![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=ethereum&logoColor=white)
![Hardhat](https://img.shields.io/badge/Hardhat-F7DC6F?style=for-the-badge)
![Ethers.js](https://img.shields.io/badge/Ethers.js-2535A0?style=for-the-badge)

**Full-Stack & Infrastructure**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

---

## GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Devarajan-Maheshwaran&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" height="160" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Devarajan-Maheshwaran&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" height="160" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Devarajan-Maheshwaran&theme=tokyonight&hide_border=true" height="160" />

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer&animation=fadeIn" width="100%" />

</div>
]]>