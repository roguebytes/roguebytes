### Frank Loewenich
     
  Software engineer with 12 years in commercial mobile development (including an iOS
  team-lead role), now focused on **AI and aerial robotics** via a research master's (MPhil, QUT) — building edge computer vision and autonomy for UAVs.
  
  **What I'm working on**
  - **Edge / on-device computer vision** — running perception models efficiently on
    low-cost hardware (Raspberry Pi, Jetson)
  - **3D-printed fixed-wing UAVs** with PX4 / ArduPilot and ROS 2 — airframe through
    flight stack to onboard inference
  - **Precision agriculture** — turning aerial imagery into weed and crop-health maps
  
  **Recent work**
  - [**uav-survey-strategy-simulation**](https://github.com/roguebytes/uav-survey-strategy-simulation)
    — the simulation behind my MPhil paper *"Fly High or Fly Low?"* (submitted to
    *Remote Sensing*, 2026): a stochastic framework that pre-computes when a
    high-altitude UAV survey beats a low-altitude sweep, cutting mission time by up
    to **68%** in sparse fields — fully reproducible from a single seed.
  - [**deepweeds-edge-classifier**](https://github.com/roguebytes/deepweeds-edge-classifier)
    — weed classification for the Australian DeepWeeds dataset, taken all the way to
    silicon: **96% top-1 at 2,200+ FPS** (1.8 ms) on a Raspberry Pi 5 + Hailo-8 NPU,
    within 1 pp of the FP32 baseline — plus the INT8 quantization post-mortem that
    forced a MobileNetV3 → V2 backbone switch.
  - [**Krumbs: Recipe Keeper**](https://apps.apple.com/au/app/krumbs-recipe-keeper/id6761420743)
    — shipped on the App Store (2026): turns messy recipe pages and video captions into
    clean, structured recipe cards using **on-device extraction with Apple Intelligence**,
    with a cloud fallback on older hardware. No accounts, private iCloud-only sync —
    the same on-device inference discipline as the Pi/Hailo work, on Apple silicon.
  
  **Experience**
  12 years building production mobile apps, including an **iOS team-lead** role
  delivering and maintaining a large custom-branded app suite with CI/CD at scale.
  Shipped iOS/Android apps across **fintech, commercial real estate, logistics &
  agriculture, and food retail** — mapping & real-time navigation, point-of-sale,
  Apple TV, and secure transactional features. More recently, an **AI research
  assistant** role building a mobile/robot front-end with **ROS 2** and real-time
  robot↔cloud communication. Earlier academic work published in **computer vision**
  (optical-flow head-tracking, motion tracking).
  
  **Background**
  MPhil — AI & robotics research, QUT (in progress) · BIT (Honours), QUT ·
  CASA Remote Pilot Licence (to 25 kg) · MAAA Bronze Wings · Brisbane, Australia.
  
  **Tech:** Python · PyTorch · ONNX / ONNX Runtime · Computer Vision · Edge AI ·
  ROS 2 · Gazebo · PX4 / ArduPilot · Docker · FastAPI · (mobile: Swift, Objective-C,
  Kotlin/Java)
