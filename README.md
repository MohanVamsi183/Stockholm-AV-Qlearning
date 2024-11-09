# Stockholm-AV-Qlearning

A Q-learning simulation that models Stockholm syndrome-inspired behavior in autonomous vehicles, teaching them to mimic and adopt human driving tendencies.

# Stockholm Syndrome Replication in Autonomous Driving using Q-Learning

This project simulates a Stockholm syndrome-like effect in autonomous driving, where an autonomous vehicle learns to mimic human driving behavior, potentially adopting suboptimal driving patterns. The study uses Q-learning to train both a human driver and an autonomous vehicle agent to reach a goal in a simple road environment. The autonomous vehicle agent learns from the human driver’s actions, gradually mirroring their driving behavior.

## Introduction

With the advent of autonomous vehicles (AVs), there is significant interest in understanding how AVs can learn human-like behaviors, even if they lead to suboptimal decisions. This project investigates this phenomenon by simulating a Stockholm syndrome-like effect, where an AV is trained to mimic a human driver’s actions using Q-learning. The AV gradually adopts the human driver’s patterns, potentially learning both beneficial and risky behaviors.

## Problem Statement

This project explores:

1. How an autonomous vehicle can learn to replicate human driving patterns through Q-learning.
2. The implications of AVs mirroring human behavior in situations such as self-parking.
3. The ethical considerations of conditioning AVs to adopt potentially risky human behaviors.

## Project Structure

The project contains the following key components:

- `RoadEnvironment`: Defines the road environment where agents navigate towards a goal.
- `Agent`: Represents both the human driver and autonomous vehicle, with Q-learning-based decision-making.
- `AutonomousVehicleSimulation`: Handles training and simulation of both agents and includes methods for generating visual outputs, such as a learning progress plot and a GIF of the simulation.

## Installation

To set up this project, clone the repository and install the required dependencies listed in `requirements.txt`:

```bash
git clone https://github.com/MohanVamsi183/Stockholm-AV-Qlearning.git
cd Stockholm-AV-Qlearning
pip install -r requirements.txt
```

### Run the simulation:

```bash
python StockQsim.py
```

## Application

### Self-Parking Scenarios

This project can be extended to analyze human-like behavior in autonomous vehicles during self-parking operations. By training an autonomous vehicle to mimic a human driver's approach to parking, the AV could adopt both effective and ineffective parking strategies. This can help assess the consequences of human-like behavior in high-precision environments, where suboptimal actions may have safety or efficiency implications.

For example, an autonomous vehicle may learn to follow the human driver's method of slowly navigating into a parking spot, even if the human driver is engaging in inefficient maneuvers, such as taking too many turns or misjudging distance. This behavior could be evaluated to understand how AVs can adjust to more efficient or safer parking strategies through further learning.

### Ethical Considerations in AV Behavior

The project also serves as a base for exploring ethical concerns around conditioning autonomous systems to mimic human behavior, including potentially hazardous patterns. In real-world scenarios, autonomous vehicles must be designed to not only replicate human actions but also to outperform human decision-making when necessary. This raises questions about the limits of machine learning when it comes to adopting potentially dangerous human tendencies, making this project an important starting point for future discussions about the ethical design and training of autonomous systems.
