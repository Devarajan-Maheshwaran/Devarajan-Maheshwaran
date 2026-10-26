<h1 align="center">Devarajan Maheshwaran</h1>

<p align="center">
  <b>Privacy-preserving ML · Agentic AI · Edge &amp; on-device intelligence</b><br/>
  B.E. Computer Science and Engineering (2024–2028) · Chennai Institute of Technology
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/devarajan-maheshwaran/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:YOUR_EMAIL_HERE"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <img src="https://img.shields.io/badge/Open%20to-Internships%20%26%20Research-2ea44f?style=for-the-badge"/>
</p>

---

## About

I build machine learning systems that have to be **trustworthy by design**: models that learn without centralising private data, agents that act within enforceable limits, and pipelines whose results can be checked rather than assumed.

My research focus is **federated learning, differential privacy and gradient security**, and I am extending it toward **autonomous systems that perceive, decide and report in the real world** (perception, edge deployment and agent workflows).

Most of my work is developed and trained on a CPU-only laptop with free-tier tooling. That constraint is why I lean toward small models, LoRA fine-tuning, DP-SGD and ONNX/edge deployment instead of brute-force compute.

---

## Research

**BOPFL: Blockchain-Orchestrated Privacy-Preserving Federated Learning** *(ongoing)*

How can a federated model update be verified without exposing the gradient behind it? I study the privacy / trust / efficiency trade-offs in current approaches to fine-tuning LLMs across distributed clients.

`Federated Learning` · `Differential Privacy` · `ZK Proofs` · `LLM Fine-tuning` · `On-chain Verification`

---

## Featured projects

| Project | What it demonstrates | Key techniques | Status |
|---|---|---|---|
| [**Pvt-FL-LoRA**](https://github.com/Devarajan-Maheshwaran/Pvt-FL-LoRA) | Attack-then-defend privacy evaluation: a gradient-inversion attack (iDLG) is reproduced, then mitigated with DP-SGD. 5 non-IID simulated clients, experiments tracked in W&B, final model exported to ONNX. | Flower · PEFT/LoRA · Opacus · W&B · ONNX | ✅ Working |
| [**GalleryFL**](https://github.com/Devarajan-Maheshwaran/GalleryFL) | On-device federated learning across non-IID Android clients: photos never leave the device. A validation-driven commit guard prevents a bad round from regressing the global model. | FedProx · Gaussian DP (Opacus) · TFLite · Kotlin · Dirichlet partitioning | ✅ Working |
| [**WebPulse**](https://github.com/Devarajan-Maheshwaran/WebPulse) | Contact-free stress estimation from a webcam: 3-region rPPG fusion, a WESAD-trained HRV/stress classifier, and live voice-valence fusion. No wearable needed. | EfficientPhys · ONNX Runtime · OpenCV · MediaPipe | ✅ Working |

### Agentic and systems prototypes

These are exploratory builds. They are public so the design is visible, but they are **not production-ready**, and the known issues are being worked through.

| Project | Idea | Stack | Status |
|---|---|---|---|
| [**EngageX**](https://github.com/Devarajan-Maheshwaran/EngageX-Classroom-AI) *(team fork)* | Four-agent classroom pipeline (Monitor, Intervention, Quiz, Report) fed by audio and vision signals, with real-time per-student analytics. <br/>*My contribution: [describe exactly what you built].* | CrewAI · Whisper · librosa · face-api.js · FastAPI · Socket.IO | 🚧 Prototype, known bugs |
| [**AutoCorp**](https://github.com/Devarajan-Maheshwaran/AutoCorp) | Agent swarm that runs micro-enterprises on-chain, with Solidity contracts enforcing spending limits and dissolution conditions so the AI operates inside hard bounds. | CrewAI · Solidity · ethers.js · FastAPI · Next.js | 🚧 Prototype, known bugs |
| [**Trust-gated AI Control for CPS**](https://github.com/Devarajan-Maheshwaran/Blockchain_Trustgated_AI_Control_for_Cyber_Physical_Systems) | An AI orchestrator monitors simulated edge hardware (Arduino Uno) for behavioural anomalies, and Ethereum/Hardhat contracts gate control actions on verified trust. | Python · Hardhat · Solidity | 🧪 Proof of concept |

<details>
<summary><b>More projects</b></summary>

- [**Health-Data-Wallet**](https://github.com/Devarajan-Maheshwaran/Health-Data-Wallet): patient-controlled health records on Stellar with client-side AES-GCM encryption, on-chain per-record access control and AI-assisted querying. *(TypeScript, Stellar, Solidity, WebCrypto)*
- [**RescueMeshAI**](https://github.com/Devarajan-Maheshwaran/RescueMeshAI): infrastructure-free peer-to-peer mesh communication for disaster scenarios. *(Java, Android, Briar)*

</details>

---

## How I work

- **Evaluate, don't assume.** I reproduce the attack before claiming a defence, track runs, and add guards so a change can't silently make a model worse.
- **Specify first, then build.** I write down the problem and success criteria before generating or writing code, and I review AI-generated code as critically as a colleague's.
- **Honest status.** Every project above is labelled with where it really stands.
- **Reproducibility.** Projects aim to ship with setup instructions, pinned dependencies and a way to re-run the experiments.

---

## Tech stack

| Area | Tools |
|---|---|
| **Deep learning** | PyTorch · Hugging Face (PEFT/LoRA) · ONNX / ONNX Runtime · TFLite · OpenCV · MediaPipe |
| **Federated learning and privacy** | Flower · Opacus (DP-SGD) · FedProx · gradient-inversion attacks (iDLG) · W&B |
| **Agents and LLM apps** | CrewAI · Whisper · tool use and workflow orchestration · FastAPI · Socket.IO |
| **Blockchain** | Solidity · Hardhat · ethers.js · Stellar |
| **Engineering** | Python · TypeScript · Kotlin · Java · Docker · Git · Linux |

---

## Currently learning and building

- Robotics software: **ROS 2, Nav2 and simulation** (Gazebo / Isaac Sim), the foundation for autonomous perception and navigation
- LiDAR and point-cloud processing (Open3D)
- Agent pipelines that turn raw sensor data into structured, verifiable reports
- Hardening existing prototypes: tests, CI and reproducible setups

---

## Let's collaborate

I'm looking for **internships and research collaborations** in privacy-preserving ML, agentic systems, edge AI and robotics.
The best way to reach me is on [LinkedIn](https://www.linkedin.com/in/devarajan-maheshwaran/).

<!--
OPTIONAL: add after your repos are cleaned up, if you want live stats
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Devarajan-Maheshwaran&layout=compact&hide_border=true" />
</p>
-->
