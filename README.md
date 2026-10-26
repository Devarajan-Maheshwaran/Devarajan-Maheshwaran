<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d0221,40:0d1b2a,100:00d4ff&height=150&section=header&animation=fadeIn" width="100%" alt="Animated blue header" />
</div>

<h1 align="center">Devarajan Maheshwaran</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=17&pause=1200&color=00D4FF&center=true&vCenter=true&width=750&lines=Privacy-preserving+ML;Agentic+AI;Edge+%26+on-device+intelligence;Federated+Learning+%26+Differential+Privacy" alt="Animated research interests" />
</p>

<p align="center">
  <b>Privacy-preserving ML · Agentic AI · Edge &amp; on-device intelligence</b><br/>
  B.E. Computer Science and Engineering (2024–2028) · Chennai Institute of Technology
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/devarajan-maheshwaran/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  &nbsp;
  <a href="mailto:devarajanmaheswaran.cse2024@citchennai.net">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  &nbsp;
  <a href="https://github.com/Devarajan-Maheshwaran">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  &nbsp;
  <a href="https://www.linkedin.com/in/devarajan-maheshwaran/">
    <img src="https://img.shields.io/badge/Open%20to-Internships%20%26%20Research-2ea44f?style=for-the-badge" alt="Open to Internships and Research"/>
  </a>
</p>

---

## About

I build machine learning systems that have to be **trustworthy by design**: models that learn without centralising private data, agents that act within enforceable limits, and pipelines whose results can be checked rather than assumed.

My research and development interests span the full lifecycle of AI systems — from model improvement and inference optimization to real-time deployment, edge AI and on-device intelligence. Through my projects, I have explored federated learning, differential privacy and gradient security, alongside computer vision, perception pipelines and agentic workflows. I am particularly interested in bridging the gap between capable models and efficient, reliable real-world systems through intelligent inference, practical deployment and continuous evaluation.

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
| [**EngageX**](https://github.com/Devarajan-Maheshwaran/EngageX-Classroom-AI) *(team fork)* | Four-agent classroom pipeline (Monitor, Intervention, Quiz, Report) fed by audio and vision signals, with real-time per-student analytics. <br/><em>My contribution: [describe exactly what you built].</em> | CrewAI · Whisper · librosa · face-api.js · FastAPI · Socket.IO | Prototype, known bugs |
| [**AutoCorp**](https://github.com/Devarajan-Maheshwaran/AutoCorp) | Agent swarm that runs micro-enterprises on-chain, with Solidity contracts enforcing spending limits and dissolution conditions so the AI operates inside hard bounds. | CrewAI · Solidity · ethers.js · FastAPI · Next.js | Prototype, known bugs |
| [**Trust-gated AI Control for CPS**](https://github.com/Devarajan-Maheshwaran/Blockchain_Trustgated_AI_Control_for_Cyber_Physical_Systems) | An AI orchestrator monitors simulated edge hardware (Arduino Uno) for behavioural anomalies, and Ethereum/Hardhat contracts gate control actions on verified trust. | Python · Hardhat · Solidity | Proof of concept - Simulated |

<details>
<summary><b>More projects</b></summary>

<br/>

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

- **Deep learning:** building and training models from scratch in PyTorch, with a focus on vision and multimodal architectures, and on understanding why they work rather than only using pretrained ones
- **Reinforcement learning:** policy-gradient and actor-critic methods (PPO), reward design, and learned locomotion policies trained in simulation, including the sim-to-real transfer problem
- **Physical AI:** models that perceive, decide and act in the real world, including vision-language-action (VLA) ideas, with simulation (Gazebo / Isaac Sim) and ROS 2 as the testing ground
- **Edge deployment:** compressing and exporting trained models (ONNX, TFLite, quantization) to run on low-power devices
- **Agentic pipelines:** turning raw sensor data into structured, verifiable reports with LLM/VLM tool use
- **Engineering rigour:** adding tests, CI and reproducible setups to my existing projects

---

## Let's collaborate

I'm looking for **internships and research collaborations** in privacy-preserving ML, agentic systems, edge AI and robotics. The best way to reach me is on [LinkedIn](https://www.linkedin.com/in/devarajan-maheshwaran/).


<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d0221,50:0d1b2a,100:00d4ff&height=100&section=footer&animation=fadeIn" width="100%" alt="Animated blue footer" />
</div>
