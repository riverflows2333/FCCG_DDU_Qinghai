# Supplementary Material for IET GTD Submission

This repository contains the supplementary data and system topology for the research paper:

**Title:** Two-stage Robust Security-Constrained Unit Commitment for Wind Power Reserve Provision Optimization Under Decision-dependent Uncertainty  
**Journal:** IET Generation, Transmission & Distribution  
**Authors:** Yuzheng Liu, Tao Ding, Yujie Ding, Biyuan Zhang, Shengjie Wang, Xuebin Wang

## Repository Structure

The repository is organized as follows:

```text
.
├── README.md               # This file
├── topology.svg            # Simplified topology diagram of the Qinghai test system
└── data/                   # Dataset used in the case study
    ├── Thermal_Gen_Params.xlsx   # Parameters of 41 thermal generators 
    ├── Trans_Line_Params.xlsx    # Parameters of 331 transmission lines 
    ├── Load_Profile_Winter.xlsx  # System load profile for a typical winter day
    └── Wind_Gen_Profile.xlsx     # Output profiles of 14 renewable generators
```

## Data Description

The dataset provided in the data/ folder corresponds to the Qinghai Power Grid test case discussed in the manuscript.

System Scale: 298 buses, 331 transmission lines, 41 thermal generators, and 14 renewable energy stations.
Scenario: The load and wind power profiles represent a typical winter day, characterized by high heating demand and significant wind power variability.
Topology: Please refer to topology.svg for a visual representation of the backbone network.