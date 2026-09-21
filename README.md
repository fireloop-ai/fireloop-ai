<div align="center">

# 🔥 FireLoop

### The independent proving ground for Physical AI

**We build software that tests robots.**

![NVIDIA Inception](https://img.shields.io/badge/NVIDIA-Inception%20Member-76B900?logo=nvidia&logoColor=white)
![Isaac Sim](https://img.shields.io/badge/NVIDIA-Isaac%20Sim-76B900?logo=nvidia&logoColor=white)
![ROS](https://img.shields.io/badge/ROS-Integrated-22314E?logo=ros&logoColor=white)
![Focus](https://img.shields.io/badge/Focus-Mobile%20Robots-orange)

[Website](https://fireloop.netlify.app/) · [Contact us](mailto:build@fireloop.ai)

</div>

---

## About FireLoop

As Physical AI moves from controlled demonstrations into warehouses and other real-world environments, testing becomes increasingly difficult. Real deployments introduce people, changing lighting, sensor noise, obstacles, surface conditions, operational constraints, and edge cases that are hard to reproduce consistently.

**FireLoop exists to make those conditions testable before deployment.**

Our mission is to bring the independent, automated, and repeatable testing discipline that transformed software engineering to Physical AI.

## FireLoop Forge

**Forge** is our simulation-based evaluation platform for Physical AI. It creates a physically calibrated digital twin of a deployment environment, connects the robot's existing autonomy stack, generates realistic scenarios and edge cases, runs approved evaluations, and produces measurable, replayable results.

> **Find where the robot fails in simulation, before it fails in the real world.**

### How Forge works

| Step | What happens |
| :---: | --- |
| **01** | **Describe the environment.** Describe a warehouse, deployment site, or operational scenario using natural language or site information. |
| **02** | **Build the digital twin.** Forge constructs the environment, configures the robot, models its physics, and calibrates cameras, LiDAR, and other sensors. |
| **03** | **Define the tests.** Describe expected robot behavior in plain English. Forge converts requirements into executable scenarios and proposes additional edge cases. Engineers review and approve them before execution. |
| **04** | **Run the robot.** The robot's existing autonomy software runs against the simulated environment, with no simulation-specific decision-making stack required. |
| **05** | **Get the evidence.** Every evaluation produces measurable results that engineers can inspect, reproduce, and use to improve the next release. |

<details>
<summary><b>Edge-case dimensions Forge can vary</b></summary>

<br>

- Robot speed
- Lighting
- Sensor noise
- Occlusion
- Surface conditions
- Dynamic obstacles
- Human interaction
- Environmental variation

</details>

<details>
<summary><b>What every evaluation can produce</b></summary>

<br>

- Pass/fail verdicts
- Safety margins
- Failure conditions
- ROS-level diagnostic evidence
- Root-cause analysis
- Regression trends
- Deterministic replay information

</details>

---

## Who We Build For

| Audience | How Forge helps |
| --- | --- |
| **Robot OEMs** | Test release candidates, detect regressions, reproduce customer-site conditions, investigate failures, validate edge cases, and generate evidence before field pilots. |
| **Robot Deployers** | Understand how a robot will behave in your aisles, docks, traffic patterns, operating conditions, and safety requirements before committing to full deployment. |
| **System Integrators & Field Teams** | Build repeatable evaluations around customer environments and rely on measurable results instead of controlled demonstrations alone. |

## Current Focus

Forge is currently focused on **mobile robots that move goods**:

- Autonomous forklifts
- Autonomous mobile robots (AMRs)
- Pallet movers
- Tuggers
- Goods-to-person robots

---

## Technology

| Area | Technology |
| --- | --- |
| Robotics simulation | NVIDIA Isaac Sim |
| Robot learning & evaluation | NVIDIA Isaac Lab |
| Simulation platform | NVIDIA Omniverse |
| Robot integration | ROS |
| Environment modeling | Physically calibrated digital twins |
| Evaluation | Scenario-based automated testing |
| Analysis | Failure diagnostics & regression analysis |
| Compute | GPU-accelerated simulation |

FireLoop is a member of the **NVIDIA Inception** program.

## Safety & Evaluation Standards

Our evaluation workflows reference industry standards for autonomous industrial vehicles and mobile robots:

| Standard | Scope |
| --- | --- |
| **ISO 3691-4** | Driverless industrial trucks and their systems |
| **ANSI B56.5** | Driverless, automatic guided industrial vehicles |
| **VDA 5050** | Communication between mobile robots and fleet-control systems |

*Standards provide the requirements. Forge turns them into repeatable, simulation-based evaluation.*

---

## Engineering Principles

1. **Test the real autonomy stack.** The software making decisions in deployment should be the software being evaluated. Forge models the environment, vehicle, and sensors while the autonomy stack makes its own decisions.
2. **Humans approve the test.** AI accelerates scenario creation, environment generation, and analysis. Engineers review the environment, approve scenarios, and define acceptable behavior.
3. **Evidence over assumptions.** Results include the measurements, conditions, configuration, and evidence needed to understand why a test passed or failed, not just a green checkmark.
4. **Reproduce every failure.** A failure that can't be reproduced is hard to fix. Forge preserves the conditions needed to replay scenarios and compare behavior across releases.
5. **Test continuously.** Robot behavior can change whenever autonomy software changes, so evaluation belongs in the release lifecycle, not just before deployment.

---

## What You'll Find Here

This organization will host engineering projects across:

`Physical AI evaluation` · `Robotics simulation` · `NVIDIA Isaac Sim` · `NVIDIA Isaac Lab` · `ROS integrations` · `Scenario generation` · `Robot testing infrastructure` · `Simulation tooling` · `Reference integrations` · `Developer examples`

More engineering resources will be published as the FireLoop platform evolves.

---

## Building Physical AI?

If you're developing, integrating, evaluating, or deploying autonomous mobile robots, we'd like to hear about the scenarios that are hardest for your robots to handle.

🌐 **Website:** [fireloop.netlify.app](https://fireloop.netlify.app/)
📧 **Email:** [build@fireloop.ai](mailto:build@fireloop.ai)

<br>

<p align="center">
  <strong>FireLoop AI</strong><br/>
  The independent proving ground for Physical AI.
</p>

<p align="center">
  San Jose, California · Engineering in India
</p>
