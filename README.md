<p align="center"><img src="assets/ssrobotics-logo.jpg" alt="SSRobotics — original logo by SSRobotic" width="240"></p>

<h1 align="center">🦾 Models & URDF</h1>
<p align="center"><b>SSRobotics · Source Code Collection</b></p>

<p align="center">
  <a href="https://ssrobotic.github.io/humanoid-robot-hub/"><img src="https://img.shields.io/badge/Resources-6-f28c28?style=flat-square" alt="6 curated resources"></a>
  <a href="https://ssrobotic.github.io/humanoid-robot-hub/"><img src="https://img.shields.io/badge/Language-TH_%2F_EN-555555?style=flat-square" alt="Thai and English"></a>
  <a href="https://github.com/SSRobotic/humanoid-robot-hub/blob/main/CREDITS.md"><img src="https://img.shields.io/badge/Original_sources-Credited-555555?style=flat-square" alt="Original authors credited"></a>
</p>


**Part of [Humanoid Robot Hub](https://github.com/SSRobotic/humanoid-robot-hub)** · [🔎 Search all resources](https://ssrobotic.github.io/humanoid-robot-hub/)

Robot descriptions, URDF / MJCF assets and model inspection resources.

Robot Description, URDF / MJCF และเครื่องมือสำรวจโมเดลหุ่นยนต์

Curated by **SSRobotic — Robotics Engineer & Open-source Curator**. This repository is a focused resource directory and engineering guide. Linked SDKs, models and research implementations belong to their original creators.

## 🗂️ Resource directory

| Resource | What it provides | Keywords | Original source |
| --- | --- | --- | --- |
| [Unitree Robot Models](https://github.com/SSRobotic/unitree-robot-models) | A1 / Aliengo / AliengoZ1 model snapshots and legacy ROS / Gazebo packages; modern humanoid models are linked upstream. | A1, Aliengo, URDF | [unitreerobotics](https://github.com/unitreerobotics/unitree_ros) |
| [DOBOT Atom Models](https://github.com/SSRobotic/dobot-atom-models) | DOBOT Atom URDF / Xacro model and mesh collection. | Atom, URDF, Xacro | [Dobot-Arm](https://github.com/Dobot-Arm/dobot_atom_urdf) |
| [MuJoCo Menagerie](https://github.com/google-deepmind/mujoco_menagerie) | A collection of robot models for MuJoCo. Inspect individual model folders for hardware coverage and asset licenses. | MJCF, Models, MuJoCo | [google-deepmind](https://github.com/google-deepmind/mujoco_menagerie) |
| [TienKung URDF](https://github.com/Open-X-Humanoid/TienKung_URDF) | Robot description and mesh resources for the TienKung humanoid. | TienKung, URDF, Meshes | [Open-X-Humanoid](https://github.com/Open-X-Humanoid/TienKung_URDF) |
| [ArtVIP Assets](https://huggingface.co/datasets/X-Humanoid/ArtVIP) | Articulated-object digital-twin datasets and scene assets from X-Humanoid. | Digital twin, USD, Assets | [X-Humanoid](https://huggingface.co/datasets/X-Humanoid/ArtVIP) |
| [Pink Inverse Kinematics](https://github.com/pink-kinematics/pink) | Differential inverse kinematics in Python using Pinocchio and QP solvers. | IK, Pinocchio, QP | [pink-kinematics](https://github.com/pink-kinematics/pink) |

## 📦 Code & models in this repository

**37 tracked upstream files** — เปิดโฟลเดอร์ด้านล่างเพื่อดูโค้ดจริง โมเดล และตัวอย่างต้นฉบับ

| Project files | Files | Pinned source | License / notices |
| --- | ---: | --- | --- |
| [Dobot-Arm/dobot_atom_urdf](projects/dobot_atom_urdf) | 37 | [`6a4461f532e2`](https://github.com/Dobot-Arm/dobot_atom_urdf/tree/6a4461f532e284ecbe7f8bc6e9413accfc923c01) | [LICENSE](projects/dobot_atom_urdf/LICENSE) |

[Source manifest](source-manifest.json) records commits, file counts, Git LFS pointers and external submodules. [Per-file manifests](source-manifests/) record original Git blob hashes. `projects/` keeps upstream code, README files, licenses and notices; SSRobotics supplies the organization and guides.

```bash
git clone --depth 1 https://github.com/SSRobotic/humanoid-models.git
cd humanoid-models
```

Open the imported project README for its dependencies, build instructions and supported robot/simulator versions. Each snapshot is collected independently; these projects have not been validated as one combined runnable stack.

## 🚀 Start here

1. Identify your robot and inspect the model format: URDF / Xacro, MJCF or USD.
2. Check joint names, limits, inertial parameters and the mesh / asset license.
3. Open the model in the viewer specified by its source project before adding control.

Read the [engineering guide](GUIDE.md) for a practical selection checklist. [resources.json](resources.json) contains the structured entries.

## 🔗 Explore the ecosystem

<details>
<summary>🌐 Browse all 14 categories</summary>

[🦾 Models & URDF](https://github.com/SSRobotic/humanoid-models) · [🌐 Simulation](https://github.com/SSRobotic/humanoid-simulation) · [🧠 Robot Learning](https://github.com/SSRobotic/humanoid-robot-learning) · [⚙️ Whole-body Control](https://github.com/SSRobotic/humanoid-whole-body-control) · [👁️ Vision & 3D Perception](https://github.com/SSRobotic/humanoid-vision) · [🤏 Manipulation & Planning](https://github.com/SSRobotic/humanoid-manipulation) · [🎮 Teleoperation](https://github.com/SSRobotic/humanoid-teleoperation) · [💾 Datasets & Demonstrations](https://github.com/SSRobotic/humanoid-datasets) · [💬 Vision-Language-Action](https://github.com/SSRobotic/humanoid-vla) · [🔌 Hardware & SDKs](https://github.com/SSRobotic/humanoid-hardware-sdks) · [📡 ROS & Integration](https://github.com/SSRobotic/humanoid-ros2) · [📚 Research & Benchmarks](https://github.com/SSRobotic/humanoid-research) · [🟢 Isaac Sim & Isaac Lab](https://github.com/SSRobotic/humanoid-isaac-sim) · [🧮 Robotics Algorithms](https://github.com/SSRobotic/humanoid-algorithms)

</details>

[🏠 Main Hub](https://github.com/SSRobotic/humanoid-robot-hub) · [🤖 Profile](https://github.com/SSRobotic)

## 🙌 Help this collection grow

⭐ [Star the Hub](https://github.com/SSRobotic/humanoid-robot-hub) · 👤 [Follow SSRobotic](https://github.com/SSRobotic) · 💡 [Suggest a resource](https://github.com/SSRobotic/humanoid-robot-hub/issues/new/choose)

Contribute accurate descriptions and original source links through the [Hub contribution guide](https://github.com/SSRobotic/humanoid-robot-hub/blob/main/CONTRIBUTING.md). Source terms, model compatibility and dataset access conditions remain with each upstream project.
