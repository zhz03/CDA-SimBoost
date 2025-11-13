# CDA-SimBoost

[Paper] CDA-SimBoost: A Unified Framework Bridging Real Data and Simulation for Infrastructure-Based CDA Systems

---

## Overall Framework

![](https://github.com/zhz03/picx-images-hosting/raw/master/workflow4.3golyhmwp0.webp)

## Features

- **Digital Twin Modeling:** Constructs high-fidelity digital twins from real-world data. 

- **Data Import Modes:** Supports both online and offline pipelines for real-time ingestion and advanced offline analysis.

- **Modularity:** Enables independent deployment and extension of CDA components.

- **Full-Stack CDA System:** Provides infrastructure-level CDA tools, including environment setup, sensors, and core modules (e.g., localization, perception, planning, communication).

- **Data Generation:** Integrates flexible interfaces to produce synthetic and simulation data in customizable modes.

- **Benchmarking:** Offers benchmark scenarios based on the [NHTSA report](https://www.nhtsa.gov/automated-vehicles-safety/published-reports-and-documents) and provides performance metrics at both system and agent levels.

## Comparison

The following table is the comparison with other CDA-relevant methods:

![](https://github.com/zhz03/picx-images-hosting/raw/master/Simboost_comp.3rbni8zyhb.webp)

## Digital Twin Builder

![](https://github.com/zhz03/picx-images-hosting/raw/master/digital_twin_builder_4.6t7bsv37sa.webp)

For using the resources of our digital twin (UCLA@Westwood), please check following links:

- UCLA Westwood vector map: [Box](https://ucla.box.com/s/r8vbfnzgg6w8yyntnmzxv0z91rge8oi8)

- UCLA smart intersection CARLA resources: [Box](https://ucla.box.com/s/z9x7d9u1t4bw7148fmxg68hmwbi87ueb) 

- For using road runner, please check [Mathwork website](https://www.mathworks.com/products/roadrunner.html).

- For using Unreal Enginer for CARLA, please check following documents:
  
  - [Build Unreal Engine and CARLA in Docker - CARLA Simulator](https://carla.readthedocs.io/en/0.9.14/build_docker_unreal/)
  
  - [Linux build - CARLA Simulator](https://carla.readthedocs.io/en/latest/build_linux/)

## OpenCDA-InfraX

Built upon the framework of OpenCDA [9][19], OpenCDA-InfraX is an infrastructure-centric cooperative drivign simulation platform that integrates multiple components, including a digital twin environment, a comprehensive CDA ecosystem, and use cases.

For code and more detailed introduction, please check out [GitHub - ucla-mobility/OpenCDA-InfraX](https://github.com/ucla-mobility/OpenCDA-InfraX)

## Contribution Rule

We welcome your contributions.

- Please report bugs and imporvement by submitting issues.

- Submit your contributions using pull requests.

## Citation

If you are using our framework or codes for your work, please cite the following paper:

```
CDA-SimBoost: A Unified Framework Bridging Real Data and Simulation for infrastructure-based CDA Systems
```

## Reference

[7] H. Scott, L. Niccolini, and other, “Scenario gym: A scenario-centric lightweight simulator,” in 2023 IEEE 26th International Conference on Intelligent Transportation Systems (ITSC). IEEE, 2023.

[9] R. Xu, Y. Guo, and other, “Opencda: an open cooperative driving automation framework integrated with co-simulation,” in 2021 IEEE International Intelligent Transportation Systems Conference (ITSC). IEEE, 2021

[13] L. Zhou, Y. Song, and other, “Garchingsim: An autonomous driving simulator with photorealistic scenes and minimalist workflow,” in 2023 IEEE 26th International Conference on Intelligent Transportation Systems (ITSC). IEEE, 2023.

[19] R. Xu, H. Xiang, and other, “The opencda open-source ecosystem for cooperative driving automation research,” IEEE Transactions on Intelligent Vehicles, 2023.