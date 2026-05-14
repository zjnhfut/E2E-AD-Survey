# E2E-AD-Survey
Our paper "Development of End-to-end Autonomous Driving: A Survey"  🚗🚗🚗
## 🗂️ Datasets & Benchmarks

> Modalities are simplified for readability. Please check each official page for licensing and download requirements.

| Year | Dataset / Benchmark | Modality | Scale | Main Focus | Paper | Data / Project |
|:---:|---|---|---|---|:---:|:---:|
| 2018 | **Apolloscape** | Camera / Video / Map-BEV | 140K frames; 1.2K scenes | Large-scale perception; detection / tracking / segmentation | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=The%20apolloscape%20open%20dataset%20for%20autonomous%20driving%20and%20its%20application) | [![Website][website-badge]](https://apolloscape.auto/) |
| 2018 | **BDD100K-Driving** | Video / Action-state | 100K videos | Real driving videos; action / behavior labels | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=Bdd100k%3A%20A%20diverse%20driving%20dataset%20for%20heterogeneous%20multitask%20learning) | [![Website][website-badge]](https://bdd-data.berkeley.edu/) |
| 2019 | **nuScenes** | Camera / Video / Radar / Map-BEV | 1K scenes | Multi-sensor perception; E2E extensions | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=nuscenes%3A%20A%20multimodal%20dataset%20for%20autonomous%20driving) | [![Website][website-badge]](https://www.nuscenes.org/) |
| 2019 | **Waymo Open** | Camera / Video | 1,150 segments | Large-scale perception; 3D detection / tracking | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=Scalability%20in%20perception%20for%20autonomous%20driving%3A%20Waymo%20open%20dataset) | [![Website][website-badge]](https://waymo.com/open/) |
| 2022 | **nuPlan** | Action-state / Map-BEV | 1,600+ hours | Planning benchmark; imitation / RL; closed-loop | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2106.11810) | [![Website][website-badge]](https://www.nuscenes.org/nuplan) |
| 2023 | **CARLA** | Simulation / Camera / Video / Action-state | Simulation benchmark | Closed-loop simulation; route / control evaluation | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=Carla%3A%20An%20open%20urban%20driving%20simulator) | [![Website][website-badge]](https://carla.org/) |
| 2023 | **NuScenes-QA** | Camera / Language | 34K QA pairs | Driving-language reasoning; scene QA | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=Nuscenes-qa%3A%20A%20multi-modal%20visual%20question%20answering%20benchmark%20for%20autonomous%20driving%20scenario) | [![GitHub][github-badge]](https://github.com/qiantianwen/NuScenes-QA) |
| 2023 | **DriveLM** | Camera / Language | 847 scenarios | Full-stack reasoning; graph QA; planning | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=Drivelm%3A%20Driving%20with%20graph%20visual%20question%20answering) | [![GitHub][github-badge]](https://github.com/OpenDriveLab/DriveLM) |
| 2023 | **DRAMA** | Video / Language / Action-state | 2.1K clips; 12K frames | Risk reasoning; event / attention annotation | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=Drama%3A%20Joint%20risk%20localization%20and%20captioning%20in%20driving) | [![Website][website-badge]](https://usa.honda-ri.com/drama) |
| 2024 | **Bench2Drive** | Simulation / Camera / Video | 13,638 clips | Closed-loop benchmark; multi-ability evaluation | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=Bench2drive%3A%20Towards%20multi-ability%20benchmarking%20of%20closed-loop%20end-to-end%20autonomous%20driving) | [![GitHub][github-badge]](https://github.com/Thinklab-SJTU/Bench2Drive) |
| 2024 | **WOMD-Reasoning** | Video / Map-BEV / Language | 2.94M QA pairs | Interaction reasoning; motion-centric QA | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2407.04281) | [![GitHub][github-badge]](https://github.com/jiachenli94/WOMD-Reasoning) |
| 2024 | **NAVSIM** | Map-BEV / Action-state | 4,164 synthetic observations | Planning benchmark; open-loop evaluation | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=Navsim%3A%20Datadriven%20non-reactive%20autonomous%20vehicle%20simulation%20and%20benchmarking) | [![GitHub][github-badge]](https://github.com/autonomousvision/navsim) |
| 2024 | **NuInstruct** | Video / Language | 91K QA pairs | Multi-task instruction; BEV-aware reasoning | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=Holistic%20autonomous%20driving%20understanding%20by%20bird%E2%80%99s-eye-view%20injected%20multimodal%20large%20models) | — |
| 2024 | **DriveCoT** | Camera / Ego-state / Language | 1,058 scenarios | CoT reasoning; difficult driving scenes | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2403.16996) | — |
| 2025 | **WOD-E2E** | Camera / Ego-state / Map-BEV | 4,021 clips | Long-tail events; open-loop planning evaluation | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2510.26125) | [![Website][website-badge]](https://waymo.com/open/) |
| 2025 | **Physical AI Dataset** | Simulation / Map-BEV / Action-state | 15 TB data; 320K+ trajectories | Synthetic physical-AI data; WM pretraining | — | — |
| 2025 | **Dongfeng E2E Dataset** | Camera / Video / Action-state | 1.25M pairs | Real complex scenes; action labels | — | — |
| 2025 | **Impromptu-VLA** | Video / Language / Action-state | 80K clips | Unstructured scenes; VLA policy data | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2505.23757) | — |
| 2025 | **StyleDrive** | Camera / Video / Action-state | 30K scenarios | Driving-style supervision; personalized planning | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2506.23982) | — |
| 2025 | **DriveQA** | Language | 474K samples | Driving knowledge QA; reasoning | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2508.21824) | — |
| 2025 | **DriveAction** | Language / Action-state | 16,185 QA pairs | Action-oriented VLA; decision QA | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2506.05667) | — |

## 📚 Paper Taxonomy

This section follows the architectural taxonomy of the survey: **Classical E2E**, **World-Model-based E2E**, and **VLA-based E2E**. Papers inside each category are sorted by year.

### 🚗 Classical End-to-end Autonomous Driving

<details open>
<summary><b>Single-stage approach</b></summary>

| Year | Model | Title | Paper | Code |
|:---:|---|---|:---:|:---:|
| 1988 | **ALVINN** | ALVINN: An Autonomous Land Vehicle in a Neural Network | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=ALVINN%3A%20An%20Autonomous%20Land%20Vehicle%20in%20a%20Neural%20Network) | — |
| 2016 | **DAVE-2** | End to End Learning for Self-Driving Cars | [![arXiv][arxiv-badge]](https://arxiv.org/abs/1604.07316) | — |
| 2018 | **CIL** | End-to-end Driving via Conditional Imitation Learning | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=End-to-end%20Driving%20via%20Conditional%20Imitation%20Learning) | [![GitHub][github-badge]](https://github.com/felipecode/coiltraine) |
| 2019 | **Learning to Drive in a Day** | Learning to Drive in a Day | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=Learning%20to%20Drive%20in%20a%20Day) | — |
| 2020 | **Data Aggregation** | Exploring Data Aggregation in Policy Learning for Vision-Based Urban Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=Exploring%20Data%20Aggregation%20in%20Policy%20Learning%20for%20Vision-Based%20Urban%20Autonomous%20Driving) | — |
| 2020 | **LBC** | Learning by Cheating | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=Learning%20by%20Cheating) | [![GitHub][github-badge]](https://github.com/dotchen/LearningByCheating) |
| 2021 | **NEAT** | NEAT: Neural Attention Fields for End-to-End Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=NEAT%3A%20Neural%20Attention%20Fields%20for%20End-to-End%20Autonomous%20Driving) | [![GitHub][github-badge]](https://github.com/autonomousvision/neat) |
| 2021 | **TransFuser** | Multi-Modal Fusion Transformer for End-to-End Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=Multi-Modal%20Fusion%20Transformer%20for%20End-to-End%20Autonomous%20Driving) | [![GitHub][github-badge]](https://github.com/autonomousvision/transfuser) |
| 2022 | **TCP** | Trajectory-Guided Control Prediction for End-to-End Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=Trajectory-Guided%20Control%20Prediction%20for%20End-to-End%20Autonomous%20Driving) | [![GitHub][github-badge]](https://github.com/OpenPerceptionX/TCP) |
| 2024 | **EfficientFuser** | Efficient Fusion and Task Guided Embedding for End-to-End Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=Efficient%20Fusion%20and%20Task%20Guided%20Embedding%20for%20End-to-End%20Autonomous%20Driving) | — |
| 2024 | **DRAMA** | DRAMA: An Efficient End-to-End Motion Planner for Autonomous Driving with Mamba | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2408.03601) | — |
| 2025 | **GMF-Drive** | GMF-Drive: Gated Mamba Fusion with Spatial-Aware BEV Representation for End-to-End Autonomous Driving | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2508.06113) | — |
| 2025 | **GoalFlow** | GoalFlow: Goal-Driven Flow Matching for Multimodal Trajectories Generation in End-to-End Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=GoalFlow%3A%20Goal-Driven%20Flow%20Matching%20for%20Multimodal%20Trajectories%20Generation%20in%20End-to-End%20Autonomous%20Driving) | — |
| 2025 | **TransDiffuser** | TransDiffuser: End-to-End Trajectory Generation with Decorrelated Multi-Modal Representation for Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=TransDiffuser%3A%20End-to-End%20Trajectory%20Generation%20with%20Decorrelated%20Multi-Modal%20Representation%20for%20Autonomous%20Driving) | — |

</details>

<details>
<summary><b>Modular approach</b></summary>

| Year | Model | Title | Paper | Code |
|:---:|---|---|:---:|:---:|
| 2020 | **P3** | Perceive, Predict, and Plan: Safe Motion Planning Through Interpretable Semantic Representations | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=Perceive%2C%20Predict%2C%20and%20Plan%3A%20Safe%20Motion%20Planning%20Through%20Interpretable%20Semantic%20Representations) | — |
| 2021 | **MP3** | MP3: A Unified Model to Map, Perceive, Predict and Plan | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=MP3%3A%20A%20Unified%20Model%20to%20Map%2C%20Perceive%2C%20Predict%20and%20Plan) | — |
| 2022 | **ST-P3** | ST-P3: End-to-End Vision-Based Autonomous Driving via Spatial-Temporal Feature Learning | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=ST-P3%3A%20End-to-End%20Vision-Based%20Autonomous%20Driving%20via%20Spatial-Temporal%20Feature%20Learning) | [![GitHub][github-badge]](https://github.com/OpenDriveLab/ST-P3) |
| 2023 | **UniAD** | Planning-Oriented Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=Planning-Oriented%20Autonomous%20Driving) | [![GitHub][github-badge]](https://github.com/OpenDriveLab/UniAD) |
| 2023 | **VAD** | VAD: Vectorized Scene Representation for Efficient Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=VAD%3A%20Vectorized%20Scene%20Representation%20for%20Efficient%20Autonomous%20Driving) | [![GitHub][github-badge]](https://github.com/hustvl/VAD) |
| 2023 | **FusionAD** | FusionAD: Multi-Modality Fusion for Prediction and Planning Tasks of Autonomous Driving | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2308.01006) | — |
| 2023 | **ReasonNet** | ReasonNet: End-to-End Driving with Temporal and Global Reasoning | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=ReasonNet%3A%20End-to-End%20Driving%20with%20Temporal%20and%20Global%20Reasoning) | — |
| 2024 | **SparseDrive** | SparseDrive: End-to-End Autonomous Driving via Sparse Scene Representation | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=SparseDrive%3A%20End-to-End%20Autonomous%20Driving%20via%20Sparse%20Scene%20Representation) | [![GitHub][github-badge]](https://github.com/swc-17/SparseDrive) |
| 2024 | **SparseAD** | SparseAD: Sparse Query-Centric Paradigm for Efficient End-to-End Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=SparseAD%3A%20Sparse%20Query-Centric%20Paradigm%20for%20Efficient%20End-to-End%20Autonomous%20Driving) | — |
| 2024 | **DualAD** | DualAD: Disentangling the Dynamic and Static World for End-to-End Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=DualAD%3A%20Disentangling%20the%20Dynamic%20and%20Static%20World%20for%20End-to-End%20Driving) | — |
| 2024 | **GraphAD** | GraphAD: Interaction Scene Graph for End-to-End Autonomous Driving | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2403.19098) | — |
| 2024 | **PPAD** | PPAD: Iterative Interactions of Prediction and Planning for End-to-End Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=PPAD%3A%20Iterative%20Interactions%20of%20Prediction%20and%20Planning%20for%20End-to-End%20Autonomous%20Driving) | — |
| 2024 | **PARA-Drive** | PARA-Drive: Parallelized Architecture for Real-Time Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=PARA-Drive%3A%20Parallelized%20Architecture%20for%20Real-Time%20Autonomous%20Driving) | — |
| 2025 | **BridgeAD** | Bridging Past and Future: End-to-End Autonomous Driving with Historical Prediction and Planning | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=Bridging%20Past%20and%20Future%3A%20End-to-End%20Autonomous%20Driving%20with%20Historical%20Prediction%20and%20Planning) | — |
| 2025 | **UncAD** | UncAD: Towards Safe End-to-End Autonomous Driving via Online Map Uncertainty | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=UncAD%3A%20Towards%20Safe%20End-to-End%20Autonomous%20Driving%20via%20Online%20Map%20Uncertainty) | — |
| 2025 | **HiP-AD** | HiP-AD: Hierarchical and Multi-Granularity Planning with Deformable Attention for Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=HiP-AD%3A%20Hierarchical%20and%20Multi-Granularity%20Planning%20with%20Deformable%20Attention%20for%20Autonomous%20Driving) | — |
| 2025 | **DiffAD** | DiffAD: A Unified Diffusion Modeling Approach for Autonomous Driving | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2503.12170) | — |
| 2025 | **DiffusionDrive** | DiffusionDrive: Truncated Diffusion Model for End-to-End Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=DiffusionDrive%3A%20Truncated%20Diffusion%20Model%20for%20End-to-End%20Autonomous%20Driving) | [![GitHub][github-badge]](https://github.com/hustvl/DiffusionDrive) |
| 2025 | **DiffE2E** | DiffE2E: Rethinking End-to-End Driving with a Hybrid Action Diffusion and Supervised Policy | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2505.19516) | — |
| 2025 | **ARTEMIS** | ARTEMIS: Autoregressive End-to-End Trajectory Planning with Mixture of Experts for Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=ARTEMIS%3A%20Autoregressive%20End-to-End%20Trajectory%20Planning%20with%20Mixture%20of%20Experts%20for%20Autonomous%20Driving) | — |
| 2025 | **DMAD** | Divide and Merge: Motion and Semantic Learning in End-to-End Autonomous Driving | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2502.07631) | — |
| 2025 | **TTOG** | Two Tasks, One Goal: Uniting Motion and Planning for End-to-End Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=Two%20Tasks%2C%20One%20Goal%3A%20Uniting%20Motion%20and%20Planning%20for%20End-to-End%20Autonomous%20Driving) | — |
| 2025 | **CogAD** | CogAD: Cognitive-Hierarchy Guided End-to-End Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=CogAD%3A%20Cognitive-Hierarchy%20Guided%20End-to-End%20Autonomous%20Driving) | — |
| 2026 | **VADv2** | VADv2: End-to-End Vectorized Autonomous Driving via Probabilistic Planning | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=VADv2%3A%20End-to-End%20Vectorized%20Autonomous%20Driving%20via%20Probabilistic%20Planning) | [![GitHub][github-badge]](https://github.com/hustvl/VAD) |

</details>

### 🌍 World-Model-based Autonomous Driving

<details>
<summary><b>Scenario Prediction and Data Generation / Diffusion-Based</b></summary>

| Year | Model | Title | Paper | Code |
|:---:|---|---|:---:|:---:|
| 2023 | **Copilot4D** | Copilot4D: Learning Unsupervised World Models for Autonomous Driving via Discrete Diffusion | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2311.01017) | — |
| 2023 | **DriveDreamer** | DriveDreamer: Towards Real-World-Drive World Models for Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=DriveDreamer%3A%20Towards%20Real-World-Drive%20World%20Models%20for%20Autonomous%20Driving) | [![GitHub][github-badge]](https://github.com/JeffWang987/DriveDreamer) |
| 2023 | **MagicDrive** | MagicDrive: Street View Generation with Diverse 3D Geometry Control | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2310.02601) | [![GitHub][github-badge]](https://github.com/cure-lab/MagicDrive) |
| 2023 | **BEVControl** | BEVControl: Accurately Controlling Street-View Elements with Multi-Perspective Consistency via BEV Sketch Layout | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2308.01661) | — |
| 2023 | **ADriver-I** | ADriver-I: A General World Model for Autonomous Driving | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2311.13549) | — |
| 2024 | **BEVWorld** | BEVWorld: A Multimodal World Simulator for Autonomous Driving via Scene-Level BEV Latents | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2407.05679) | — |
| 2024 | **DrivingDiffusion** | DrivingDiffusion: Layout-Guided Multi-View Driving Scenarios Video Generation with Latent Diffusion Model | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=DrivingDiffusion%3A%20Layout-Guided%20Multi-View%20Driving%20Scenarios%20Video%20Generation%20with%20Latent%20Diffusion%20Model) | — |
| 2024 | **WoVoGen** | WoVoGen: World Volume-Aware Diffusion for Controllable Multi-Camera Driving Scene Generation | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=WoVoGen%3A%20World%20Volume-Aware%20Diffusion%20for%20Controllable%20Multi-Camera%20Driving%20Scene%20Generation) | [![GitHub][github-badge]](https://github.com/fudan-zvg/WoVoGen) |
| 2024 | **CoGen** | CoGen: 3D Consistent Video Generation via Adaptive Conditioning for Autonomous Driving | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2503.22231) | — |
| 2024 | **InfiniCube** | InfiniCube: Unbounded and Controllable Dynamic 3D Driving Scene Generation with World-Guided Video Models | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=InfiniCube%3A%20Unbounded%20and%20Controllable%20Dynamic%203D%20Driving%20Scene%20Generation%20with%20World-Guided%20Video%20Models) | — |
| 2024 | **OccSora** | OccSora: 4D Occupancy Generation Models as World Simulators for Autonomous Driving | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2405.20337) | [![GitHub][github-badge]](https://github.com/wzzheng/OccSora) |
| 2024 | **DOME** | DOME: Taming Diffusion Model into High-Fidelity Controllable Occupancy World Model | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2410.10429) | — |
| 2024 | **Vista** | Vista: A Generalizable Driving World Model with High Fidelity and Versatile Controllability | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=Vista%3A%20A%20Generalizable%20Driving%20World%20Model%20with%20High%20Fidelity%20and%20Versatile%20Controllability) | [![GitHub][github-badge]](https://github.com/OpenDriveLab/Vista) |
| 2024 | **Mila** | Mila: Multi-View Intensive-Fidelity Long-Term Video Generation World Model for Autonomous Driving | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2503.15875) | — |
| 2024 | **GAIA-2** | GAIA-2: A Controllable Multi-View Generative World Model for Autonomous Driving | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2503.20523) | — |
| 2024 | **GenAD** | GenAD: Generalized Predictive Model for Autonomous Driving | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2403.09630) | [![GitHub][github-badge]](https://github.com/OpenDriveLab/GenAD) |
| 2024 | **DrivePhysica** | Physical Informed Driving World Model | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2412.08410) | — |
| 2024 | **DIVE** | DIVE: Efficient Multi-View Driving Scenes Generation Based on Video Diffusion Transformer | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2504.19614) | — |
| 2024 | **SimGen** | SimGen: Simulator-Conditioned Driving Scene Generation | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=SimGen%3A%20Simulator-Conditioned%20Driving%20Scene%20Generation) | — |
| 2024 | **ReconDreamer** | ReconDreamer: Crafting World Models for Driving Scene Reconstruction via Online Restoration | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=ReconDreamer%3A%20Crafting%20World%20Models%20for%20Driving%20Scene%20Reconstruction%20via%20Online%20Restoration) | — |
| 2024 | **DriveDreamer4D** | DriveDreamer4D: World Models Are Effective Data Machines for 4D Driving Scene Representation | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=DriveDreamer4D%3A%20World%20Models%20Are%20Effective%20Data%20Machines%20for%204D%20Driving%20Scene%20Representation) | — |
| 2024 | **Delphi** | Unleashing Generalization of End-to-End Autonomous Driving with Controllable Long Video Generation | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2406.01349) | — |
| 2024 | **X-DRIVE** | X-DRIVE: Cross-Modality Consistent Multi-Sensor Data Synthesis for Driving Scenarios | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2411.01123) | — |
| 2025 | **DriveDreamer-2** | DriveDreamer-2: LLM-Enhanced World Models for Diverse Driving Video Generation | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=DriveDreamer-2%3A%20LLM-Enhanced%20World%20Models%20for%20Diverse%20Driving%20Video%20Generation) | — |
| 2025 | **DriVerse** | DriVerse: Navigation World Model for Driving Simulation via Multimodal Trajectory Prompting and Motion Alignment | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=DriVerse%3A%20Navigation%20World%20Model%20for%20Driving%20Simulation%20via%20Multimodal%20Trajectory%20Prompting%20and%20Motion%20Alignment) | — |
| 2025 | **LiDARCrafter** | LiDARCrafter: Dynamic 4D World Modeling from LiDAR Sequences | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2508.03692) | — |
| 2025 | **Epona** | Epona: Autoregressive Diffusion World Model for Autonomous Driving | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2506.24113) | — |
| 2025 | **LidarDM** | LidarDM: Generative LiDAR Simulation in a Generated World | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=LidarDM%3A%20Generative%20LiDAR%20Simulation%20in%20a%20Generated%20World) | [![GitHub][github-badge]](https://github.com/vzyrianov/lidardm) |
| 2025 | **UniScene** | UniScene: Unified Occupancy-Centric Driving Scene Generation | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=UniScene%3A%20Unified%20Occupancy-Centric%20Driving%20Scene%20Generation) | — |
| 2025 | **Veila** | Veila: Panoramic LiDAR Generation from a Monocular RGB Image | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2508.03690) | — |

</details>

<details>
<summary><b>Scenario Prediction and Data Generation / Autoregressive-Based</b></summary>

| Year | Model | Title | Paper | Code |
|:---:|---|---|:---:|:---:|
| 2022 | **TrafficGen** | TrafficGen: Learning to Generate Diverse and Realistic Traffic Scenarios | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2210.06609) | — |
| 2023 | **GAIA-1** | GAIA-1: A Generative World Model for Autonomous Driving | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2309.17080) | — |
| 2024 | **DrivingWorld** | DrivingWorld: Constructing World Model for Autonomous Driving via Video GPT | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2412.19505) | — |
| 2024 | **Bench2Drive-R** | Bench2Drive-R: Turning Real World Data into Reactive Closed-Loop Autonomous Driving Benchmark by Generative Model | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2412.09647) | — |
| 2024 | **HoloDrive** | HoloDrive: Holistic 2D-3D Multi-Modal Street Scene Generation for Autonomous Driving | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2412.01407) | — |
| 2024 | **OccLLaMA** | OccLLaMA: An Occupancy-Language-Action Generative World Model for Autonomous Driving | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2409.03272) | — |
| 2024 | **DriveGPT** | DriveGPT: Scaling Autoregressive Behavior Models for Driving | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2412.14415) | — |
| 2024 | **Carformer** | Carformer: Self-Driving with Learned Object-Centric Representations | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=Carformer%3A%20Self-Driving%20with%20Learned%20Object-Centric%20Representations) | — |
| 2024 | **DOE-1** | DOE-1: Closed-Loop Autonomous Driving with Large World Model | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2412.09627) | — |
| 2024 | **Street-View Image Generation** | Street-View Image Generation from a Bird’s-Eye View Layout | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=Street-View%20Image%20Generation%20from%20a%20Bird%E2%80%99s-Eye%20View%20Layout) | — |
| 2024 | **X-Driver** | X-Driver: A General World Model for Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=X-Driver%3A%20A%20General%20World%20Model%20for%20Driving) | — |
| 2025 | **OccWorld** | OccWorld: Learning a 3D Occupancy World Model for Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=OccWorld%3A%20Learning%20a%203D%20Occupancy%20World%20Model%20for%20Autonomous%20Driving) | — |
| 2025 | **RenderWorld** | RenderWorld: World Model with Self-Supervised 3D Occupancy Rendering | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=RenderWorld%3A%20World%20Model%20with%20Self-Supervised%203D%20Occupancy%20Rendering) | — |
| 2025 | **DriveOccWorld** | Driving in the Occupancy World: Vision-Centric 4D Occupancy Forecasting and Planning via World Models | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=Driving%20in%20the%20Occupancy%20World%3A%20Vision-Centric%204D%20Occupancy%20Forecasting%20and%20Planning%20via%20World%20Models) | — |

</details>

<details>
<summary><b>Enhancing E2E-AD Capabilities</b></summary>

| Year | Model | Title | Paper | Code |
|:---:|---|---|:---:|:---:|
| 2024 | **UniWorld** | UniWorld: Autonomous Driving Pre-Training via World Models | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=UniWorld%3A%20Autonomous%20Driving%20Pre-Training%20via%20World%20Models) | — |
| 2024 | **LAW** | Learning Autonomous Driving World Models | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=Learning%20Autonomous%20Driving%20World%20Models) | — |
| 2024 | **SSR** | SSR: Navigation-Guided Sparse Scene Representation for Efficient End-to-End Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=SSR%3A%20Navigation-Guided%20Sparse%20Scene%20Representation%20for%20Efficient%20End-to-End%20Autonomous%20Driving) | — |
| 2024 | **Panacea** | Panacea: Panoramic and Controllable Video Generation for Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=Panacea%3A%20Panoramic%20and%20Controllable%20Video%20Generation%20for%20Autonomous%20Driving) | — |
| 2025 | **DriveScape** | DriveScape: Towards High-Fidelity Full-Stack Driving World Model | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=DriveScape%3A%20Towards%20High-Fidelity%20Full-Stack%20Driving%20World%20Model) | — |
| 2025 | **SimWorld** | SimWorld: Simulator-Augmented World Model for Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=SimWorld%3A%20Simulator-Augmented%20World%20Model%20for%20Autonomous%20Driving) | — |
| 2025 | **Cosmos-Drive-Dreams** | Cosmos-Drive-Dreams: Foundation World Models for Controllable Driving Data Generation | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=Cosmos-Drive-Dreams%3A%20Foundation%20World%20Models%20for%20Controllable%20Driving%20Data%20Generation) | — |

</details>

<details>
<summary><b>Driving Decision Making</b></summary>

| Year | Model | Title | Paper | Code |
|:---:|---|---|:---:|:---:|
| 2022 | **MILE** | Model-Based Imitation Learning for Urban Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=Model-Based%20Imitation%20Learning%20for%20Urban%20Driving) | — |
| 2023 | **OccWorld** | OccWorld: Learning a 3D Occupancy World Model for Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=OccWorld%3A%20Learning%20a%203D%20Occupancy%20World%20Model%20for%20Autonomous%20Driving) | — |
| 2024 | **Think2Drive** | Think2Drive: Efficient Reinforcement Learning by Thinking in Latent World Model for Quasi-Realistic Autonomous Driving | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2402.16720) | [![GitHub][github-badge]](https://github.com/Thinklab-SJTU/Think2Drive) |
| 2024 | **PIWM** | Physical Interaction World Model for Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=Physical%20Interaction%20World%20Model%20for%20Autonomous%20Driving) | — |
| 2024 | **WoTE** | World Models for Online Trajectory Evaluation in Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=World%20Models%20for%20Online%20Trajectory%20Evaluation%20in%20Autonomous%20Driving) | — |
| 2024 | **CarFormer** | CarFormer: Self-Driving with Learned Object-Centric Representations | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=CarFormer%3A%20Self-Driving%20with%20Learned%20Object-Centric%20Representations) | — |
| 2024 | **GeoDrive** | GeoDrive: Geometry-Aware Driving World Model for Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=GeoDrive%3A%20Geometry-Aware%20Driving%20World%20Model%20for%20Autonomous%20Driving) | — |
| 2024 | **NeMo** | NeMo: Neural Map-Guided World Model for Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=NeMo%3A%20Neural%20Map-Guided%20World%20Model%20for%20Autonomous%20Driving) | — |
| 2024 | **KARNet** | KARNet: Kalman-Augmented Recurrent Network for Robust Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=KARNet%3A%20Kalman-Augmented%20Recurrent%20Network%20for%20Robust%20Autonomous%20Driving) | — |
| 2024 | **ADAWM** | ADAWM: Adaptive Driving Agent with World Model | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=ADAWM%3A%20Adaptive%20Driving%20Agent%20with%20World%20Model) | — |
| 2024 | **AdaptiveDriver** | AdaptiveDriver: Adaptive World-Model-Based Driving Policy | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=AdaptiveDriver%3A%20Adaptive%20World-Model-Based%20Driving%20Policy) | — |
| 2024 | **TrafficBots** | TrafficBots: Towards World Models for Multi-Agent Traffic Simulation and Planning | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=TrafficBots%3A%20Towards%20World%20Models%20for%20Multi-Agent%20Traffic%20Simulation%20and%20Planning) | — |
| 2024 | **DrivingGPT** | DrivingGPT: Unifying Environment Modeling and Planning for Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=DrivingGPT%3A%20Unifying%20Environment%20Modeling%20and%20Planning%20for%20Autonomous%20Driving) | — |
| 2024 | **World4Drive** | World4Drive: End-to-End Autonomous Driving via Intention-Aware World Modeling | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=World4Drive%3A%20End-to-End%20Autonomous%20Driving%20via%20Intention-Aware%20World%20Modeling) | — |
| 2025 | **AD-R1** | AD-R1: Closed-Loop Reinforcement Learning with Counterfactual World Models | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=AD-R1%3A%20Closed-Loop%20Reinforcement%20Learning%20with%20Counterfactual%20World%20Models) | — |
| 2025 | **MapWorld** | MapWorld: Map-Guided World Model for Safe Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=MapWorld%3A%20Map-Guided%20World%20Model%20for%20Safe%20Autonomous%20Driving) | — |
| 2025 | **DriveX** | DriveX: Learning General Driving Knowledge through Full-Scene World Modeling | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=DriveX%3A%20Learning%20General%20Driving%20Knowledge%20through%20Full-Scene%20World%20Modeling) | — |
| 2025 | **L3P** | L3P: Large-Scale Learned Planning with World Models | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=L3P%3A%20Large-Scale%20Learned%20Planning%20with%20World%20Models) | — |
| 2025 | **VAVIM / VAVAM** | Learning Action-Environment Mappings through Video Generation Models | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=Learning%20Action-Environment%20Mappings%20through%20Video%20Generation%20Models) | — |
| 2025 | **SEM2** | SEM2: Scene Evolution Modeling for Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=SEM2%3A%20Scene%20Evolution%20Modeling%20for%20Autonomous%20Driving) | — |
| 2025 | **DriveWM** | DriveWM: Robust World Modeling for Autonomous Driving under Occlusion | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=DriveWM%3A%20Robust%20World%20Modeling%20for%20Autonomous%20Driving%20under%20Occlusion) | — |

</details>

### 🤖 Vision-Language-Action-based Autonomous Driving

<details>
<summary><b>Auxiliary VLA / Explainability-Oriented Assistance</b></summary>

| Year | Model | Title | Paper | Code |
|:---:|---|---|:---:|:---:|
| 2023 | **DriveGPT4** | DriveGPT4: Interpretable End-to-End Autonomous Driving via Large Language Model | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2310.01412) | [![GitHub][github-badge]](https://github.com/PJLab-ADG/DriveGPT4) |
| 2023 | **DriveLM** | DriveLM: Driving with Graph Visual Question Answering | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=DriveLM%3A%20Driving%20with%20Graph%20Visual%20Question%20Answering) | [![GitHub][github-badge]](https://github.com/OpenDriveLab/DriveLM) |
| 2024 | **NLE-DM** | Natural Language Explanation for Driving Decision Making | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=Natural%20Language%20Explanation%20for%20Driving%20Decision%20Making) | — |
| 2024 | **ReasonPlan** | ReasonPlan: Unified Scene Prediction and Decision-Chain Reasoning for Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=ReasonPlan%3A%20Unified%20Scene%20Prediction%20and%20Decision-Chain%20Reasoning%20for%20Autonomous%20Driving) | — |
| 2024 | **OmniDrive** | OmniDrive: A Holistic LLM-Agent Framework for Autonomous Driving with 3D Perception, Reasoning and Planning | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2405.01533) | — |
| 2024 | **X-Driver** | X-Driver: Explainable Autonomous Driving with Chain-of-Thought and Autoregressive Modeling | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=X-Driver%3A%20Explainable%20Autonomous%20Driving%20with%20Chain-of-Thought%20and%20Autoregressive%20Modeling) | — |
| 2024 | **RAG-Driver** | RAG-Driver: Retrieval-Augmented In-Context Learning for Explainable Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=RAG-Driver%3A%20Retrieval-Augmented%20In-Context%20Learning%20for%20Explainable%20Autonomous%20Driving) | — |
| 2024 | **Senna** | Senna: Bridging Large Vision-Language Models and End-to-End Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=Senna%3A%20Bridging%20Large%20Vision-Language%20Models%20and%20End-to-End%20Autonomous%20Driving) | — |
| 2024 | **VLAD** | VLAD: Vision-Language Assisted Driving for Interpretable Hierarchical Planning | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=VLAD%3A%20Vision-Language%20Assisted%20Driving%20for%20Interpretable%20Hierarchical%20Planning) | — |
| 2024 | **LLaDA** | LLaDA: Large Language Assisted Driving Adaptation | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=LLaDA%3A%20Large%20Language%20Assisted%20Driving%20Adaptation) | — |
| 2025 | **DriVLMe** | DriVLMe: Embodied Experience for Vision-Language Driving Models | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=DriVLMe%3A%20Embodied%20Experience%20for%20Vision-Language%20Driving%20Models) | — |
| 2025 | **TS-VLM** | TS-VLM: Query-Aware Multi-View Temporal Reasoning for Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=TS-VLM%3A%20Query-Aware%20Multi-View%20Temporal%20Reasoning%20for%20Autonomous%20Driving) | — |
| 2025 | **CoVLA** | CoVLA: A Language-Action Dataset and Model for Cooperative Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=CoVLA%3A%20A%20Language-Action%20Dataset%20and%20Model%20for%20Cooperative%20Autonomous%20Driving) | — |

</details>

<details>
<summary><b>Auxiliary VLA / Supervision-Oriented Assistance</b></summary>

| Year | Model | Title | Paper | Code |
|:---:|---|---|:---:|:---:|
| 2023 | **DriveMLM** | DriveMLM: Aligning Multi-Modal Large Language Models with Behavioral Planning States for Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=DriveMLM%3A%20Aligning%20Multi-Modal%20Large%20Language%20Models%20with%20Behavioral%20Planning%20States%20for%20Autonomous%20Driving) | — |
| 2024 | **VLP** | Vision-Language Pre-Training for Autonomous Driving Planning | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=Vision-Language%20Pre-Training%20for%20Autonomous%20Driving%20Planning) | — |
| 2024 | **VLM-E2E** | VLM-E2E: Enhancing End-to-End Autonomous Driving with Vision-Language Model Guidance | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=VLM-E2E%3A%20Enhancing%20End-to-End%20Autonomous%20Driving%20with%20Vision-Language%20Model%20Guidance) | — |
| 2024 | **VLMPlanner** | VLMPlanner: Driving-Oriented VQA Pretraining and 3D Reasoning for Planning | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=VLMPlanner%3A%20Driving-Oriented%20VQA%20Pretraining%20and%203D%20Reasoning%20for%20Planning) | — |
| 2024 | **DriveVLM** | DriveVLM: The Convergence of Autonomous Driving and Large Vision-Language Models | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2402.12289) | [![GitHub][github-badge]](https://github.com/OpenDriveLab/DriveVLM) |
| 2024 | **VLM-AD** | VLM-AD: End-to-End Autonomous Driving through Vision-Language Model Supervision | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=VLM-AD%3A%20End-to-End%20Autonomous%20Driving%20through%20Vision-Language%20Model%20Supervision) | — |
| 2024 | **DiMA** | DiMA: Distilling Multimodal Large Language Models for Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=DiMA%3A%20Distilling%20Multimodal%20Large%20Language%20Models%20for%20Autonomous%20Driving) | — |
| 2024 | **VERDI** | VERDI: Aligning Driving Representations with Textual Reasoning Features | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=VERDI%3A%20Aligning%20Driving%20Representations%20with%20Textual%20Reasoning%20Features) | — |
| 2024 | **FASIONAD** | FASIONAD: Fast-Slow Vision-Language Supervision for End-to-End Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=FASIONAD%3A%20Fast-Slow%20Vision-Language%20Supervision%20for%20End-to-End%20Autonomous%20Driving) | — |
| 2025 | **EvoDriveVLA** | EvoDriveVLA: Collaborative Distillation and Oracle-Guided Trajectory Supervision for VLA Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=EvoDriveVLA%3A%20Collaborative%20Distillation%20and%20Oracle-Guided%20Trajectory%20Supervision%20for%20VLA%20Driving) | — |
| 2025 | **LeapAD** | LeapAD: Transferring LLM-Based Driving Experience to Lightweight Autonomous Driving Models | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=LeapAD%3A%20Transferring%20LLM-Based%20Driving%20Experience%20to%20Lightweight%20Autonomous%20Driving%20Models) | — |
| 2025 | **CoC-VLA** | CoC-VLA: Chain-of-Causality Supervision for Long-Tail Domain Transfer | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=CoC-VLA%3A%20Chain-of-Causality%20Supervision%20for%20Long-Tail%20Domain%20Transfer) | — |
| 2025 | **DME-Driver** | DME-Driver: Transforming VLM Decisions into Planning-Oriented Control Signals | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=DME-Driver%3A%20Transforming%20VLM%20Decisions%20into%20Planning-Oriented%20Control%20Signals) | — |
| 2025 | **XYZ-Drive** | XYZ-Drive: Vision-Language Cross-Attention for Action Prediction and Textual Supervision | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=XYZ-Drive%3A%20Vision-Language%20Cross-Attention%20for%20Action%20Prediction%20and%20Textual%20Supervision) | — |
| 2025 | **DrivePI** | DrivePI: Multimodal Perception, Language Instruction, and Action Diffusion for Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=DrivePI%3A%20Multimodal%20Perception%2C%20Language%20Instruction%2C%20and%20Action%20Diffusion%20for%20Autonomous%20Driving) | — |

</details>

<details>
<summary><b>VLA for Action Generation / Indirect Guidance via Intermediate Representations</b></summary>

| Year | Model | Title | Paper | Code |
|:---:|---|---|:---:|:---:|
| 2023 | **DiLu** | DiLu: A Knowledge-Driven Approach to Autonomous Driving with Large Language Models | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2309.16292) | [![GitHub][github-badge]](https://github.com/PJLab-ADG/DiLu) |
| 2023 | **LanguageMPC** | LanguageMPC: Large Language Models as Decision Makers for Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=LanguageMPC%3A%20Large%20Language%20Models%20as%20Decision%20Makers%20for%20Autonomous%20Driving) | — |
| 2023 | **Drive as You Speak** | Drive as You Speak: Enabling Human-Like Interaction with Autonomous Vehicles via LLMs | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=Drive%20as%20You%20Speak%3A%20Enabling%20Human-Like%20Interaction%20with%20Autonomous%20Vehicles%20via%20LLMs) | — |
| 2024 | **InsightDrive** | InsightDrive: Efficient Scene Understanding and Decision Guidance for Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=InsightDrive%3A%20Efficient%20Scene%20Understanding%20and%20Decision%20Guidance%20for%20Autonomous%20Driving) | — |
| 2024 | **DME-Driver** | DME-Driver: Logical Decision Making and Planning-Oriented Control for Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=DME-Driver%3A%20Logical%20Decision%20Making%20and%20Planning-Oriented%20Control%20for%20Autonomous%20Driving) | — |
| 2024 | **SOLVE** | SOLVE: Synergizing Language-Vision Reasoning and End-to-End Networks for Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=SOLVE%3A%20Synergizing%20Language-Vision%20Reasoning%20and%20End-to-End%20Networks%20for%20Autonomous%20Driving) | — |
| 2024 | **WiseAD** | WiseAD: Knowledge-Augmented VLM Reasoning for End-to-End Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=WiseAD%3A%20Knowledge-Augmented%20VLM%20Reasoning%20for%20End-to-End%20Autonomous%20Driving) | — |
| 2024 | **DriveRX** | DriveRX: Cross-Task Decision Guidance for Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=DriveRX%3A%20Cross-Task%20Decision%20Guidance%20for%20Autonomous%20Driving) | — |
| 2024 | **RAD** | RAD: Retrieval-Augmented Driving with Meta-Action Guidance | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=RAD%3A%20Retrieval-Augmented%20Driving%20with%20Meta-Action%20Guidance) | — |
| 2024 | **SafeAuto** | SafeAuto: Safety-Aware VLM-Guided Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=SafeAuto%3A%20Safety-Aware%20VLM-Guided%20Autonomous%20Driving) | — |
| 2024 | **Senna** | Senna: Bridging Large Vision-Language Models and End-to-End Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=Senna%3A%20Bridging%20Large%20Vision-Language%20Models%20and%20End-to-End%20Autonomous%20Driving) | — |
| 2025 | **RAG** | RAG-Based Driving Decision Guidance with Historical Cases | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=RAG-Based%20Driving%20Decision%20Guidance%20with%20Historical%20Cases) | — |

</details>

<details>
<summary><b>VLA for Action Generation / Direct Action Generation</b></summary>

| Year | Model | Title | Paper | Code |
|:---:|---|---|:---:|:---:|
| 2023 | **LMDrive** | LMDrive: Closed-Loop End-to-End Driving with Large Language Models | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=LMDrive%3A%20Closed-Loop%20End-to-End%20Driving%20with%20Large%20Language%20Models) | [![GitHub][github-badge]](https://github.com/opendilab/LMDrive) |
| 2024 | **DriveVLM** | DriveVLM: The Convergence of Autonomous Driving and Large Vision-Language Models | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2402.12289) | [![GitHub][github-badge]](https://github.com/OpenDriveLab/DriveVLM) |
| 2024 | **DriveVLM-Dual** | DriveVLM-Dual: Dual-Branch Vision-Language-Action Driving Policy | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=DriveVLM-Dual%3A%20Dual-Branch%20Vision-Language-Action%20Driving%20Policy) | — |
| 2024 | **OpenDriveVLA** | OpenDriveVLA: Towards End-to-End Autonomous Driving with Large Vision Language Action Model | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=OpenDriveVLA%3A%20Towards%20End-to-End%20Autonomous%20Driving%20with%20Large%20Vision%20Language%20Action%20Model) | — |
| 2024 | **SparseVLA** | SparseVLA: Sparse Vision-Language-Action Model for Efficient Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=SparseVLA%3A%20Sparse%20Vision-Language-Action%20Model%20for%20Efficient%20Autonomous%20Driving) | — |
| 2024 | **AutoDrive** | AutoDrive: Vision-Language-Action End-to-End Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=AutoDrive%3A%20Vision-Language-Action%20End-to-End%20Autonomous%20Driving) | — |
| 2025 | **SimLingo** | SimLingo: Vision-Only Closed-Loop Autonomous Driving with Language-Action Alignment | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=SimLingo%3A%20Vision-Only%20Closed-Loop%20Autonomous%20Driving%20with%20Language-Action%20Alignment) | [![GitHub][github-badge]](https://github.com/wayveai/simlingo) |
| 2025 | **EMMA** | EMMA: End-to-End Multimodal Model for Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=EMMA%3A%20End-to-End%20Multimodal%20Model%20for%20Autonomous%20Driving) | — |
| 2025 | **DriveGPT4-v2** | DriveGPT4-v2: Harnessing Large Language Model Capabilities for Enhanced Closed-Loop Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=DriveGPT4-v2%3A%20Harnessing%20Large%20Language%20Model%20Capabilities%20for%20Enhanced%20Closed-Loop%20Autonomous%20Driving) | — |
| 2025 | **LLaViDA** | LLaViDA: A Large Language Vision Driving Assistant for Explicit Reasoning and Enhanced Trajectory Planning | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2512.18211) | — |
| 2025 | **StyleVLA** | StyleVLA: Driving Style-Aware Vision Language Action Model for Autonomous Driving | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2603.09482) | — |
| 2026 | **AutoMoT** | AutoMoT: A Unified Vision-Language-Action Model with Asynchronous Mixture-of-Transformers for End-to-End Autonomous Driving | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2603.14851) | — |
| 2026 | **V2X-VLM** | V2X-VLM: End-to-End V2X Cooperative Autonomous Driving through Large Vision-Language Models | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=V2X-VLM%3A%20End-to-End%20V2X%20Cooperative%20Autonomous%20Driving%20through%20Large%20Vision-Language%20Models) | — |

</details>

<details>
<summary><b>Cognition-Enhanced VLA / Reasoning-Enhanced VLA</b></summary>

| Year | Model | Title | Paper | Code |
|:---:|---|---|:---:|:---:|
| 2025 | **ORION** | ORION: A Holistic End-to-End Autonomous Driving Framework by Vision-Language Instructed Action Generation | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=ORION%3A%20A%20Holistic%20End-to-End%20Autonomous%20Driving%20Framework%20by%20Vision-Language%20Instructed%20Action%20Generation) | [![GitHub][github-badge]](https://github.com/Orion-Autonomous-Driving/ORION) |
| 2025 | **AutoVLA** | AutoVLA: A Vision-Language-Action Model for End-to-End Autonomous Driving with Adaptive Reasoning and Reinforcement Fine-Tuning | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2506.13757) | [![GitHub][github-badge]](https://github.com/LeapLabTHU/AutoVLA) |
| 2025 | **Reasoning-VLA** | Reasoning-VLA: A Fast and General Vision-Language-Action Reasoning Model for Autonomous Driving | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2511.19912) | — |
| 2025 | **FutureSightDrive** | FutureSightDrive: Thinking Visually with Spatio-Temporal CoT for Autonomous Driving | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2505.17685) | — |
| 2025 | **DiffVLA** | DiffVLA: Vision-Language Guided Diffusion Planning for Autonomous Driving | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2505.19381) | — |
| 2025 | **DiffVLA++** | DiffVLA++: Bridging Cognitive Reasoning and End-to-End Driving through Metric-Guided Alignment | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2510.17148) | — |
| 2025 | **VLA-R** | VLA-R: Vision-Language Action Retrieval toward Open-World End-to-End Autonomous Driving | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2511.12405) | — |
| 2025 | **MindDrive** | MindDrive: A Vision-Language-Action Model for Autonomous Driving via Online Reinforcement Learning | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2512.13636) | — |
| 2026 | **DynVLA** | DynVLA: Learning World Dynamics for Action Reasoning in Autonomous Driving | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2603.11041) | — |
| 2026 | **LaST-VLA** | LaST-VLA: Thinking in Latent Spatio-Temporal Space for Vision-Language-Action in Autonomous Driving | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2603.01928) | — |
| 2026 | **Uni-World VLA** | Uni-World VLA: Interleaved World Modeling and Planning for Autonomous Driving | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2603.27287) | — |
| 2026 | **UniDrive-WM** | UniDrive-WM: Unified Understanding, Planning and Generation World Model for Autonomous Driving | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2601.04453) | — |
| 2026 | **VLA-World** | Learning Vision-Language-Action World Models for Autonomous Driving | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2604.09059) | — |
| 2026 | **ExploreVLA** | ExploreVLA: Dense World Modeling and Exploration for End-to-End Autonomous Driving | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2604.02714) | — |
| 2026 | **DriveVLA-W0** | DriveVLA-W0: World Models Amplify Data Scaling Law in Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=DriveVLA-W0%3A%20World%20Models%20Amplify%20Data%20Scaling%20Law%20in%20Autonomous%20Driving) | [![GitHub][github-badge]](https://github.com/OpenDriveLab/DriveVLA-W0) |

</details>

<details>
<summary><b>Cognition-Enhanced VLA / Geometry-Enhanced VLA</b></summary>

| Year | Model | Title | Paper | Code |
|:---:|---|---|:---:|:---:|
| 2024 | **DrivingGaussian** | DrivingGaussian: Composite Gaussian Splatting for Surrounding Dynamic Autonomous Driving Scenes | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=DrivingGaussian%3A%20Composite%20Gaussian%20Splatting%20for%20Surrounding%20Dynamic%20Autonomous%20Driving%20Scenes) | — |
| 2025 | **VGGT** | VGGT: Visual Geometry Grounded Transformer | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=VGGT%3A%20Visual%20Geometry%20Grounded%20Transformer) | [![GitHub][github-badge]](https://github.com/facebookresearch/vggt) |
| 2025 | **VGD** | VGD: Visual Geometry Gaussian Splatting for Feed-Forward Surround-View Driving Reconstruction | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2510.19578) | — |
| 2025 | **DriveVGGT** | DriveVGGT: Calibration-Constrained Visual Geometry Transformers for Multi-Camera Autonomous Driving | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2511.22264) | — |
| 2026 | **3D-Mix for VLA** | 3D-Mix for VLA: A Plug-and-Play Module for Integrating VGGT-Based 3D Information into VLA Models | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2603.24393) | — |
| 2026 | **DVGT-2** | DVGT-2: Vision-Geometry-Action Model for Autonomous Driving at Scale | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2604.00813) | — |
| 2026 | **ReconDrive** | ReconDrive: Fast Feed-Forward 4D Gaussian Splatting for Autonomous Driving Scene Reconstruction | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2603.07552) | — |
| 2026 | **SpaceDrive** | SpaceDrive: Infusing Spatial Awareness into VLM-Based Autonomous Driving | [![Scholar][scholar-badge]](https://scholar.google.com/scholar?q=SpaceDrive%3A%20Infusing%20Spatial%20Awareness%20into%20VLM-Based%20Autonomous%20Driving) | — |
| 2026 | **UniDriveVLA** | UniDriveVLA: Unifying Understanding, Perception, and Action Planning for Autonomous Driving | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2604.02190) | — |
| 2026 | **VG3S** | VG3S: Visual Geometry Grounded Gaussian Splatting for Semantic Occupancy Prediction | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2603.06210) | — |
| 2026 | **VGGDrive** | VGGDrive: Empowering Vision-Language Models with Cross-View Geometric Grounding for Autonomous Driving | [![arXiv][arxiv-badge]](https://arxiv.org/abs/2602.20794) | — |

</details>

<!-- Badge definitions -->
[arxiv-badge]: https://img.shields.io/badge/arXiv-Paper-b31b1b?logo=arxiv&logoColor=white
[scholar-badge]: https://img.shields.io/badge/Scholar-Paper-2f80ed?logo=googlescholar&logoColor=white
[github-badge]: https://img.shields.io/badge/GitHub-Code-181717?logo=github&logoColor=white
[website-badge]: https://img.shields.io/badge/Website-Project-2ea44f?logo=googlechrome&logoColor=white
