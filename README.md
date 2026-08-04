# ROVEC-2026-Social-Learning

Welcome to the companion repository for our poster presentation at the **Ecuadorian Summer School on Telerobotics and Vehicle Technology (ROVEC 2026)**.

This repository contains the extended abstract and video demonstrations of our research on social learning in robot swarms.

## Table of Contents
- [Extended Abstract](#extended-abstract)
- [Simulation Videos](#simulation-videos)

---

## Extended Abstract

Our work proposes to develop and evaluate a social learning method for robot swarms that uses peer imitation for behavior learning.


- [**Read the Full Extended Abstract (PDF)**](./Abstract/Abstract.pdf)

---

## Simulation Videos

The following demonstrations present the proposed social learning method evaluated in the ARGoS3 simulator using the QUPA robot model.

> **Note:** In all videos, the left side shows the ARGoS3 simulation, while the right side displays the real-time data collected by the apprentice robot.

### 1. Local Perception (Single Master)

https://github.com/user-attachments/assets/ccb3695a-d4bb-4e09-ad2c-b4e90a92f781

**Description:** The apprentice robot (Ra) observes Master Robot 1 (Rm₁). The plot shows, in real time, the sensory data perceived by the apprentice robot.

### 2. Local Perception (Multiple Masters)

https://github.com/user-attachments/assets/5f17e82c-3331-4197-bbf5-0fa0ce6923fb

**Description:** Top view of the simulation arena. The plot illustrates the data simultaneously perceived by the apprentice robot while observing the seven master robots.

### 3. Execution of the Learned Behaviors

The apprentice robot (Ra) observes multiple master robots (Rmᵢ) and learns multiple behaviors simultaneously.

#### First Learned Behavior

https://github.com/user-attachments/assets/0aa90d06-d0fc-4cbc-8431-a70438ac9a57

**Description:** After observing multiple demonstrations performed by the master robots, the apprentice robot executes the first learned behavior (triangular trajectory).

#### Second Learned Behavior

https://github.com/user-attachments/assets/2c5f518d-6eef-4c16-86ee-2734a7900fea

**Description:** The apprentice robot executes the second learned behavior (pentagonal trajectory).

> **Note:** Although both behaviors are learned simultaneously during the same observation process, they are presented in separate videos to improve the clarity of each reconstructed trajectory.

---

## Authors

- **Jonatan Díaz** — *Universidad de Nariño* (jhonatandiaz1w1@udenar.edu.co)
- **Wilson Achicanoy** — *Universidad de Nariño* (wilachic@udenar.edu.co)
- **David Garzón Ramos** — *University College Dublin* (david.garzonramos@ucd.ie)
