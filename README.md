
**Autonomous Driving Perception Engineer** — LiDAR SLAM · 3D Detection · VLM/VLA on Edge

가천대학교 컴퓨터공학과 (복수전공 스마트카융합전공) · GPA 4.13/4.5  
㈜베이리스 자율주행개발팀 인턴 (2025.09 ~.)

---

## 🎯 Highlights

- **NVIDIA Alpamayo VLM** 스택을 TensorRT-Edge-LLM v0.6.0로 직접 포팅, multi-image batch pinned-host buffer race condition 발견 및 수정 — Jetson Thor 타겟 엣지 추론
- **Cosmos-Reason2-2B Knowledge Distillation** 파이프라인 구축 (Teacher: Alpamayo-R1-10B, 200K samples) — **CoT acc ~89%**, 1.6s horizon **ADE 0.12m / FDE 0.35m**
- **GLIM 기반 LiDAR-IMU-GNSS SLAM**을 인천대교 ~20km 구간에 적용 — **XY p90 0.318m / Yaw p90 0.282°**, VGICP 100% convergence (mean 7.94ms)
- **SFA3D + SimpleTrack**을 C++/CUDA로 재구현, AGX Orin에서 **100ms 이내, 20+ FPS** 구현
- **과학기술정보통신부 장관상** (3D 객체 검출, 2024) · **한국전력 KDN 사장상** (국제 EV 자율주행, 2025)

---

## 🚀 Featured Projects

### [tensorrt-edge-llm-for-alpamayo](https://github.com/kimsunguk0/tensorrt-edge-llm-for-alpamayo) ⭐5
NVIDIA TensorRT-Edge-LLM v0.6.0에 Alpamayo 1.5 VLM 스택을 포팅한 fork. C++ 런타임 직접 수정 + ONNX export 진입점 추가.  
`C++` `TensorRT` `VLM` `Jetson Thor`

### [GLIM_SLAM](https://github.com/kimsunguk0/GLIM_SLAM)
인천대교(~20km) 구조 반복 구간 LiDAR-IMU-GNSS SLAM. glim_ext GNSS factor를 odometry graph에 삽입하여 단순 파라미터 튜닝을 넘는 해결.  
`ROS2` `GLIM` `VGICP` `gtsam` `Hesai LiDAR`

### [MultiObjectLidarTracking](https://github.com/kimsunguk0/MultiObjectLidarTracking)
SFA3D + SimpleTrack을 임베디드 보드(AGX Orin, Hailo)에서 동작하도록 C++17 재구현. HailoRT wrapper + ONNX Runtime 경로 구성.  
`C++` `CUDA` `TensorRT` `Hailo` `3D MOT`

### [cosmos_distillation](https://github.com/kimsunguk0/cosmos_distillation)
Alpamayo-R1-10B → Cosmos-Reason2-2B Knowledge Distillation 파이프라인. CoT hard CE + top-k KD + Trajectory CE 통합 objective.  
`PyTorch` `Distillation` `VLM` `Trajectory Planning`

---

## 🛠 Tech Stack

**Perception / ML** PyTorch · MMDetection3D · OpenPCDet · ONNX · TensorRT · HailoRT  
**3D & SLAM** GLIM · fast_gicp · ndt_cuda · Open3D · PCL · gtsam · ROS / ROS2  
**Languages** C++ (17/20) · Python · CUDA  
**Deployment** Jetson AGX Orin · Jetson Thor · Hailo-8 · Docker  
**Datasets / Sensors** Hesai AT128 LiDAR · MTi IMU · RTK GNSS · KITTI · nuScenes (familiar)  
**Tools** Linux · Git · WandB · CMake

---

## 🏆 Awards

- **장관상** — 과학기술정보통신부, 제1회 자율주행 인공지능 챌린지 (3D 객체 검출, 2024)
- **사장상** — 한국전력 KDN, 제4회 국제 대학생 EV 자율주행 경진대회 (2025)
- **장려상** — 한국교통안전공단/국토교통부, 대학생 창작 모빌리티 경진대회 (2024, 2025)

## 💼 Experience

- **㈜베이리스** 자율주행개발팀 인턴 (2025.09)
- **가천대학교 GADIS 자율주행팀** Perception Lead (2024.01 – 2025.11) · K-City 실증
- **㈜모라이 (MORAI)** Engineering Service팀 인턴 (2025.01 – 2025.02)
- **가천대학교 TakeOut 동아리** 회장 (2025 하반기) · 부회장 (2025 상반기)

---

## 📫 Contact

📧 sunuk903@gmail.com  
🔗 LinkedIn:  
📝 Portfolio: 
