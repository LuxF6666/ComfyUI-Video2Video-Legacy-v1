🚀 ComfyUI Video2Video Legacy v1
📌 项目简介 (Project Overview)
本项目记录了基于 AnimateDiff + SD 1.5 架构的早期视频重绘实验。虽然受限于旧版模型的稳定性，在时间一致性上存在挑战，但完整展示了 OpenPose 与 IP-Adapter 的协同控制逻辑。

🛠️ 技术栈 (Tech Stack)
Base Model: majicmixRealistic_v6

ControlNet: OpenPose (SD1.5)

Motion Module: AnimateDiff v2

Features: IP-Adapter Advanced, FaceDetailer

⚠️ 已知局限 (Known Issues)
脸部存在由于逐帧修复导致的时间轴抖动。

分辨率受限于 SD 1.5 架构，缺乏后期超分流程。

注：此版本仅作为技术进化史记录，更高画质的 v2.0 版本（基于 RTX 5070 Ti 满血版）正在开发中。
