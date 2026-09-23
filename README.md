# Hi, I'm Omar 👋

**Software engineer (B.Sc. Computer Engineering, Ain Shams University, 2026).** I build systems that process heavy, messy, real-time data: streaming backends, distributed pipelines, embedded firmware and ML, most often for brain signals (EEG/BCI).

Before engineering school I spent four years working remotely for US clients in marketing and scriptwriting, so I'm used to async work, writing things down and shipping on deadline.

## Selected work

| Project | What it shows |
|---|---|
| [**ieeg_backend**](https://github.com/omar4a/ieeg_backend) | Plugin-based Python backend that streams a **1.2 GB, 172-channel** recording in **~150 MB RAM**. ABC contracts, adapter pattern, **100% test coverage** on the core. |
| [**distributed_systems**](https://github.com/omar4a/distributed_systems) | Distributed crawler + search engine on **AWS SQS/S3**. Hot-standby master with heartbeat failover, horizontally scalable workers. |
| [**python-dhcp-server**](https://github.com/omar4a/python-dhcp-server) | DHCP server from scratch (RFC 2131/2132) with Scapy. Full message set, thread pool, **20+ req/s**. |
| [**p300-bci-speller**](https://github.com/omar4a/p300-bci-speller) | Real-time brain-typing. LSL streaming with a **synthetic sample clock** (jitter-free alignment, zero added latency), xDAWN + LDA / Riemannian MDM, Bayesian dynamic stopping, **LLM word completion** confirmed by SSVEP. |
| [**eeg-emotion-recognition**](https://github.com/omar4a/eeg-emotion-recognition) | Graduation project (**graded 4.0/4.0**). Dry-electrode EEG → per-electrode **contact-quality gating** → **ASR** artifact reconstruction → classical ML + TSception. Backed by a 10-block study on our own 180-trial dataset. |
| [**mindmetric-eeg-app**](https://github.com/omar4a/mindmetric-eeg-app) | The same pipeline running **on a phone**: Bluetooth straight to the headset, C++/Eigen ASR over JNI, ONNX TSception, and Dart DSP verified against Python by parity tests. |
| [**DEAP**](https://github.com/omar4a/DEAP) | Research framework (13 feature families, 8+ model types, nested CV, 6 deep-learning branches) behind **hundreds of experiments**. Showed a published 88–89% result falls to ~70% under subject-aware evaluation. |
| [**RTOS**](https://github.com/omar4a/RTOS) | FreeRTOS vehicle-safety firmware on ARM Cortex-M4: 5 tasks, queues, mutex, ISR → task handoff. |

<p align="center"><img src="https://raw.githubusercontent.com/omar4a/mindmetric-eeg-app/main/docs/screenshots/strip.png" width="720" alt="MindMetric app"></p>

## Stack
**Languages:** Python · C · C++ · Dart · JavaScript/Node.js · SQL
**Backend & infra:** AWS (SQS, S3) · Firebase · Express · MongoDB · WebSockets · Linux · Git
**ML & signals:** PyTorch · scikit-learn · Optuna · MNE · pyRiemann · SciPy · BrainFlow · LSL
**Embedded:** FreeRTOS · ARM Cortex-M4 (TM4C123) · register-level drivers · Keil / IAR
**Testing:** pytest (+ coverage) · Flutter widget/integration tests

## Also
- 🧠 Founder & President of **NeuroTech ASU**, the first NeuroTechX chapter in Africa & MENA (50+ members). Led 4 teams at the g.tec BR41N.IO hackathon.
- 🏅 National **Brain Bee** Champion (Egypt), International Brain Bee finalist.
- 🌍 Arabic (native) · English (fluent) · French (basic)

## Contact
[LinkedIn](https://www.linkedin.com/in/omar-abdalaal-3b7150216/) · [omar.m.abdalaal@gmail.com](mailto:omar.m.abdalaal@gmail.com) · Cairo, Egypt (remote)
