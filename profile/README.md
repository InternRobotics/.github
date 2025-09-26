<div align="center">
  <div>
    <a href="https://www.xiaohongshu.com/user/profile/67e24dd1000000000e011c5f"><img src="https://img.shields.io/badge/Redbook-red?style=flat&logo=xiaohongshu&logoColor=red"/></a>
    <a href="https://space.bilibili.com/3546722198358311"><img src="https://img.shields.io/badge/-bilibili-ff69b4?style=flat&labelColor=ff69b4&logo=bilibili&logoColor=white"/></a>
    <a href="https://cdn.vansin.top/InternRobotics.jpg"><img src="https://img.shields.io/badge/WeChat-brightgreen?style=flat&logo=WeChat&logoColor=green"/></a>
    <a href="https://www.zhihu.com/people/InternRobotics"><img src="https://img.shields.io/badge/Zhihu-lightblue?style=flat&logo=zhihu&logoColor=blue"/></a>
    <a href="https://twitter.com/InternRobotics"><img src="https://img.shields.io/badge/Twitter-1DA1F2?style=flat&logo=twitter&logoColor=white"/></a>
    <a href="https://discord.gg/5jeaQHUj4B"><img src="https://img.shields.io/badge/Discord-5865F2?style=flat&logo=discord&logoColor=white"/>
    </div></a>
</div>

## Toolchain - Training, Inference and Evaluation 
- [InternUtopia](https://github.com/InternRobotics/InternUtopia): A simulation platform for versatile Embodied AI research and developments.
- [InternManip](https://github.com/InternRobotics/InternManip): An all-in-one robot manipulation learning suites (5 pretrained models, 3 benchmarks, and more coming soon).
- [InternNav](https://github.com/InternRobotics/InternNav): A open platform for building generalized navigation foundation models (with 6 mainstream benchmarks and 10+ baselines).
- [InternHumanoid](https://github.com/InternRobotics/InternHumanoid): A versatile, all-in-one toolbox for whole-body humanoid robot contorl.
- [InternSR](https://github.com/InternRobotics/InternSR): A open-source toolbox for vision-based embodied spatial intelligence.

  
 
## Models, Datasets and Research

- **Humanoids/Legged Robots**
  - Datasets:
    - [InternData-H1](https://huggingface.co/datasets/InternRobotics/InternData-H1): The largest open-sourced 3D human motion dataset with text annotation, including 2.5k hours 1.9M episodes.
  - Models and Research:
    - [UniHSI](https://github.com/InternRobotics/UniHSI): Unified Human-Scene Interaction via Prompted Chain-of-Contacts
    - [HIMLoco](https://github.com/InternRobotics/HIMLoco): Hybrid Internal Model: Learning Agile Legged Locomotion with Simulated Robot Response
    - 🏆[HoST](https://github.com/InternRobotics/HoST) **[Best Systems Paper Finalist at RSS 2025]**: Learning Humanoid Standing-up Control across Diverse Postures
    - [HOMIE](https://github.com/InternRobotics/Homie): Humanoid Loco-Manipulation with Isomorphic Exoskeleton Cockpit

- **Manipulation**
  - Datasets:
    - [InternData-A1](https://huggingface.co/datasets/InternRobotics/InternData-A1): A hybrid synthetic-real manipulation dataset integrating 5 heterogeneous robots, 15 skills, and 200+ scenes, emphasizing multi-robot collaboration under dynamic scenarios.
    - [InternData-M1](https://huggingface.co/datasets/InternRobotics/InternData-M1): A large-scale synthetic dataset for generalizable pick-and-place over 80K objects, with open-ended instructions covering object recognition, spatial and commonsense reasoning, and long-horizon tasks.
  - Models and Research:
    - [InternVLA-A1](https://github.com/InternRobotics/InternVLA-A1): Unifying Understanding, Generation, and Action for Robotic Manipulation
    - [InternVLA-M1](https://github.com/InternRobotics/InternVLA-M1): An Spatially Grounded Foundation Model for Generalist Robot
    - [F1-VLA](https://github.com/InternRobotics/F1-VLA): Visual foresight generation for planning-based control
    - [VLAC](https://github.com/InternRobotics/VLAC): A generalist vision-language-action-critic model for robotic real-world reinforcement learning 
    - [Seer](https://github.com/InternRobotics/Seer): Predictive Inverse Dynamics Models are Scalable Learners for Robotic Manipulation
    - [RoboSplat](https://github.com/InternRobotics/RoboSplat): Novel Demonstration Generation with Gaussian Splatting Enables Robust One-Shot Manipulation
    - [GenManip](https://github.com/InternRobotics/GenManip): LLM-driven Simulation for Generalizable Instruction-Following Manipulation

- **Navigation**
  - Datasets:
    - [InternData-N1](https://huggingface.co/datasets/InternRobotics/InternData-N1): A high-quality navigation dataset with the most diverse scenes and extensive randomization across embodiments/viewpoints, including 3k+ scenes and 830k VLN data.
  - Models and Research:
    - [InternVLA-N1](https://internrobotics.github.io/internvla-n1.github.io/): An Open Dual-System Vision-Language Navigation Foundation Model with Learned Latent Plans
    - [NavDP](https://github.com/InternRobotics/NavDP): Learning Sim-to-Real Navigation Diffusion Policy with Privileged Information Guidance
    - [StreamVLN](https://github.com/InternRobotics/StreamVLN): Streaming Vision-and-Language Navigation via SlowFast Context Modeling
    - [VLN-PE](https://crystalsixone.github.io/vln_pe.github.io/): A Holistic Study of Physical and Visual Disparities in Vision-and-Language Navigation

- **AIGC for Embodied AI**
  - Datasets:
    - [OmniWorld](https://huggingface.co/datasets/InternRobotics/OmniWorld): A large-scale, multi-domain, multi-modal dataset, enables significant performance improvements in 4D reconstruction and video generation.
  - Models and Research:
    - [MeshCoder](https://daibingquan.github.io/MeshCoder/): Generate Structured 3D Object Blender Code from Point Clouds
    - [Infinite-Mobility](https://github.com/InternRobotics/Infinite-Mobility): Scalable High-Fidelity Synthesis of Articulated Objects via Procedural Generation
    - [Aether](https://github.com/InternRobotics/Aether): Geometric-Aware Unified World Modeling

- **3D Vision and Embodied Perception**
  - [EmbodiedScan](https://github.com/InternRobotics/EmbodiedScan): A Holistic Multi-Modal 3D Perception Suite Towards Embodied AI
  - 🏆[PointLLM](https://github.com/InternRobotics/PointLLM) **[Best Paper Candidate at ECCV 2024]**: Empowering Large Language Models to Understand Point Clouds
  - [MMSI-Bench](https://runsenxu.com/projects/MMSI_Bench/): A Benchmark for Multi-Image Spatial Intelligence
  - [OST-Bench](https://github.com/InternRobotics/OST-Bench): Evaluating the Capabilities of MLLMs in Online Spatio-temporal Scene Understanding
- **3D Assets for Embodied AI**
  - [InternScenes](https://github.com/InternRobotics/InternScenes): A large-scale interactive indoor scene dataset with realistic layouts, 40,000 diverse scenes and 1.96M 3D objects.

