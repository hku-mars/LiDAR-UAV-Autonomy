# LiDAR-UAV-Autonomy

This repository curates open-source resources for LiDAR-based autonomous UAVs, originally presented in Table I of our survey paper.

```bib
@article{ren2025lidar,
  author  = {Ren, Yunfan and Cai, Yixi and Li, Haotian and Chen, Nan and Zhu, Fangcheng and Yin, Longji and Kong, Fanze and Li, Rundong and Zhang, Fu},
  journal = {arXiv preprint},
  title   = {A Survey on LiDAR-based Autonomous Aerial Vehicles},
  year    = {2025}
}
```

 It aims to support the UAV autonomy research community by providing accessible, up-to-date tools, frameworks, and resources for advancing LiDAR-based UAV technologies.

## Resources by Category

### Perception
Includes tools and frameworks for localization, mapping, calibration, and software stacks focused on perception.

| **Name**           | **Year** | **Link**                                                     |
| ------------------ | -------- | ------------------------------------------------------------ |
| FAST-LIVO2         | 2024     | [GitHub](https://github.com/hku-mars/FAST-LIVO2)             |
| Swarm-LIO2         | 2024     | [GitHub](https://github.com/hku-mars/Swarm-LIO2)             |
| ROG-Map            | 2024     | [GitHub](https://github.com/hku-mars/ROG-Map)                |
| D-Map              | 2024     | [GitHub](https://github.com/hku-mars/D-Map)                  |
| CLEARLAB           | 2024     | [GitHub](https://github.com/Zhefan-Xu/CERLAB-UAV-Autonomy)   |
| Point-LIO          | 2023     | [GitHub](https://github.com/hku-mars/Point-LIO)              |
| DVLC               | 2023     | [GitHub](https://github.com/koide3/direct_visual_lidar_calibration) |
| FAST-LIO2          | 2022     | [GitHub](https://github.com/hku-mars/FAST_LIO)               |
| LI-Init            | 2022     | [GitHub](https://github.com/hku-mars/LiDAR_IMU_Init)         |
| LVI-ExC            | 2022     | [GitHub](https://github.com/peterWon/LVI-ExC)                |
| lidar-camera-calib | 2021     | [GitHub](https://github.com/hku-mars/livox_camera_calib)     |
| LIO-SAM            | 2020     | [GitHub](https://github.com/TixiaoShan/LIO-SAM)              |
| A-LOAM             | 2020     | [GitHub](https://github.com/HKUST-Aerial-Robotics/A-LOAM)    |
| CMU                | 2020     | [GitHub](https://github.com/HongbiaoZ/autonomous_exploration_development_environment) |
| FIESTA             | 2019     | [GitHub](https://github.com/HKUST-Aerial-Robotics/FIESTA)    |
| Voxblox            | 2017     | [GitHub](https://github.com/ethz-asl/voxblox)                |
| Kalibr             | 2016     | [GitHub](https://github.com/ethz-asl/kalibr)                 |
| OctoMap            | 2013     | [GitHub](https://github.com/OctoMap/octomap)                 |

### Planning
Includes planners and combined planner-controller frameworks.

| **Name**       | **Year** | **Link**                                                     |
| -------------- | -------- | ------------------------------------------------------------ |
| SUPER            | 2024     | [GitHub](https://github.com/hku-mars/SUPER)         |
| PMM            | 2024     | [GitHub](https://github.com/ctu-mrs/pmm_uav_planner)         |
| IPC            | 2023     | [GitHub](https://github.com/hku-mars/IPC)                    |
| GCOPTER        | 2022     | [GitHub](https://github.com/ZJU-FAST-Lab/GCOPTER)            |
| mintime-replan | 2022     | [GitHub](https://github.com/uzh-rpg/sb_min_time_quadrotor_planning) |
| FASTER         | 2021     | [GitHub](https://github.com/mit-acl/faster)                  |
| time optimal   | 2021     | [GitHub](https://github.com/uzh-rpg/rpg_time_optimal)        |
| TRR            | 2020     | [GitHub](https://github.com/HKUST-Aerial-Robotics/Teach-Repeat-Replan) |
| FastPlanner    | 2020     | [GitHub](https://github.com/HKUST-Aerial-Robotics/Fast-Planner) |
| EGO-Planner    | 2020     | [GitHub](https://github.com/ZJU-FAST-Lab/ego-planner)        |

### Control
Includes controllers for UAVs.

| **Name**          | **Year** | **Link**                                                     |
| ----------------- | -------- | ------------------------------------------------------------ |
| Geometry Control  | 2021     | [GitHub](https://github.com/yorgoon/minimum-snap-geometric-control) |
| PMPC              | 2018     | [GitHub](https://github.com/uzh-rpg/rpg_mpc)                 |
| RPG Quad Control  | 2018     | [GitHub](https://github.com/uzh-rpg/rpg_quadrotor_control)   |
| QuadRotor-Control | 2018     | [GitHub](https://github.com/srikantrao/QuadRotor-Control)    |

### Hardware
Includes hardware-related projects (LiDAR, vision, and simulators).

| **Name**       | **Year** | **Link**                                                   |
| -------------- | -------- | ---------------------------------------------------------- |
| SUPER-Hardware        | 2025     | [GitHub](https://github.com/hku-mars/SUPER-Hardware) |
| OmniNxt        | 2024     | [GitHub](https://github.com/HKUST-Aerial-Robotics/OmniNxt) |
| UniQuad        | 2024     | [GitHub](https://github.com/HKUST-Aerial-Robotics/UniQuad) |
| Aerial Gym     | 2024     | [GitHub](https://github.com/ntnu-arl/aerial_gym_simulator) |
| Agilicious     | 2023     | [GitHub](https://github.com/uzh-rpg/agilicious)            |
| PULSAR         | 2023     | [GitHub](https://github.com/hku-mars/PULSAR)               |
| MARSIM         | 2023     | [GitHub](https://github.com/hku-mars/MARSIM)               |
| Fast-Drone-250 | 2022     | [GitHub](https://github.com/ZJU-FAST-Lab/Fast-Drone-250)   |
| Flightmare     | 2021     | [GitHub](https://github.com/uzh-rpg/flightmare)            |
| AirSim         | 2020     | [GitHub](https://microsoft.github.io/AirSim/)              |
| RotorS         | 2016     | [GitHub](https://github.com/ethz-asl/rotors_simulator)     |

### Autopilots
Includes autopilot frameworks.

| **Name**   | **Year** | **Link**                                           |
| ---------- | -------- | -------------------------------------------------- |
| PX4        | -        | [GitHub](https://github.com/PX4)                   |
| Betaflight | -        | [GitHub](https://github.com/betaflight/betaflight) |
| ArduPilot  | -        | [GitHub](https://github.com/ArduPilot/ardupilot)   |

## Contributing

We welcome contributions to expand and refine this collection! To add or update resources relevant to LiDAR-based UAV autonomy:
1. Fork this repository.
2. Add your resource to the appropriate category table in the README or include additional files if necessary.
3. Submit a pull request with a brief description of your changes.

Please ensure that all contributions are open-source and align with the focus of this repository.

## License

This repository is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the content, provided the original license is included.