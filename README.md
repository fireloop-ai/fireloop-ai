---

## About FireLoop

FireLoop builds software that tests robots.

As Physical AI moves from controlled demonstrations into warehouses and other real-world environments, testing becomes increasingly difficult. Real deployments introduce people, changing lighting, sensor noise, obstacles, surface conditions, operational constraints, and edge cases that are difficult to reproduce consistently.

FireLoop exists to make those conditions testable before deployment.

Our mission is to bring the same independent, automated, and repeatable testing discipline that transformed software engineering to Physical AI.

## FireLoop Forge

**Forge** is FireLoop's simulation-based evaluation platform for Physical AI.

Forge creates a physically calibrated digital twin of a deployment environment, connects the robot's existing autonomy stack, generates realistic test scenarios and edge cases, executes approved evaluations, and produces measurable, replayable results.

The goal is simple:

> Find where the robot fails in simulation — before it fails in the real world.

### How Forge works

**01 — Describe the environment**

Describe a warehouse, deployment site, or operational scenario using natural language or site information.

**02 — Build the digital twin**

Forge constructs the environment, configures the robot, models its physics, and calibrates cameras, LiDAR, and other sensors.

**03 — Define the tests**

Describe the expected robot behavior in plain English.

Forge converts those requirements into executable scenarios and proposes additional edge cases across conditions such as:

* Robot speed
* Lighting
* Sensor noise
* Occlusion
* Surface conditions
* Dynamic obstacles
* Human interaction
* Environmental variation

Engineers review and approve the scenarios before execution.

**04 — Run the robot**

The robot's existing autonomy software runs against the simulated environment without requiring a simulation-specific decision-making stack.

**05 — Get the evidence**

Every evaluation produces measurable results that can include:

* Pass/fail verdicts
* Safety margins
* Failure conditions
* ROS-level diagnostic evidence
* Root-cause analysis
* Regression trends
* Deterministic replay information

The result is evidence engineers can inspect, reproduce, and use to improve the next release.

---

## Who We Build For

### Robot OEMs

Evaluate releases against real deployment conditions before shipping them to customers.

Use Forge to:

* Test release candidates
* Detect regressions
* Reproduce customer-site conditions
* Investigate failures
* Validate challenging edge cases
* Generate evidence before field pilots

### Robot Deployers

Understand how a robot will behave inside your environment before committing to a full deployment.

Evaluate robots against:

* Your aisles
* Your docks
* Your operating conditions
* Your traffic patterns
* Your safety requirements
* Your edge cases

### System Integrators & Field Teams

Build repeatable evaluations around customer environments and use measurable results instead of relying only on controlled demonstrations.

---

## Current Focus

FireLoop Forge is currently focused on mobile robots that move goods, including:

* Autonomous forklifts
* Autonomous mobile robots (AMRs)
* Pallet movers
* Tuggers
* Goods-to-person robots

---

## Technology

FireLoop's simulation and evaluation stack is built around technologies including:

| Area                        | Technology                                |
| --------------------------- | ----------------------------------------- |
| Robotics Simulation         | NVIDIA Isaac Sim                          |
| Robot Learning & Evaluation | NVIDIA Isaac Lab                          |
| Simulation Platform         | NVIDIA Omniverse                          |
| Robot Integration           | ROS                                       |
| Environment Modeling        | Physically calibrated digital twins       |
| Evaluation                  | Scenario-based automated testing          |
| Analysis                    | Failure diagnostics & regression analysis |
| Compute                     | GPU-accelerated simulation                |

FireLoop is a member of the **NVIDIA Inception** program.

---

## Safety & Evaluation Standards

Our evaluation workflows reference industry standards relevant to autonomous industrial vehicles and mobile robots, including:

* **ISO 3691-4** — Driverless industrial trucks and their systems
* **ANSI B56.5** — Driverless, automatic guided industrial vehicles
* **VDA 5050** — Communication between mobile robots and fleet-control systems

Standards provide the requirements.

Forge turns those requirements into repeatable simulation-based evaluation.

---

## Engineering Principles

### Test the real autonomy stack

The software making decisions in deployment should be the software being evaluated.

Forge models the environment, vehicle, and sensors while the robot's autonomy stack remains responsible for its own decisions.

### Humans approve the test

AI can accelerate scenario creation, environment generation, and analysis.

Engineers remain responsible for reviewing the environment, approving scenarios, and defining what constitutes acceptable behavior.

### Evidence over assumptions

A successful evaluation should provide more than a green checkmark.

Results should include the measurements, conditions, configuration, and evidence required to understand why a test passed or failed.

### Reproduce every failure

A failure that cannot be reproduced is difficult to fix.

Forge preserves the conditions required to replay scenarios and compare behavior across software releases.

### Test continuously

Robot behavior can change whenever autonomy software changes.

Evaluation should therefore be part of the release lifecycle rather than a one-time activity before deployment.

---

## What You'll Find Here

The FireLoop GitHub organization will host engineering projects related to areas such as:

* Physical AI evaluation
* Robotics simulation
* NVIDIA Isaac Sim
* NVIDIA Isaac Lab
* ROS integrations
* Scenario generation
* Robot testing infrastructure
* Simulation tooling
* Reference integrations
* Developer examples

More engineering resources will be published as the FireLoop platform evolves.

---

## Building Physical AI?

If you're developing, integrating, evaluating, or deploying autonomous mobile robots, we'd like to hear about the scenarios that are hardest for your robots to handle.

**Website:** `<WEBSITE_URL>`

**Email:** [build@fireloop.ai](mailto:build@fireloop.ai)

---

<p align="center">
  <strong>FireLoop AI</strong><br/>
  The independent proving ground for Physical AI.
</p>

<p align="center">
  San Jose, California · Engineering in India
</p>
