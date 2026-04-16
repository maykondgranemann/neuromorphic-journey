# Neuromorphic Journey: From Silicon to Flight 🧠🚀

This repository documents my technical and academic transition from traditional Systems Engineering to **Neuromorphic Computing**. The core objective is to explore how **Spiking Neural Networks (SNN)** can provide efficient, low-latency control for real-time robotic systems.

My ultimate goal is to validate these bio-inspired models within the **SpiNNaker** ecosystem at the University of Manchester.

---

## 🗺️ Research & Engineering Roadmap

The project is structured into evolutionary milestones, moving from fundamental neural theory to physical implementation on high-performance drone hardware.

### [01. The Atom: LIF Neuron on sPyNNaker](./01-lif-neuron)
Modeling and simulating the *Leaky Integrate-and-Fire* (LIF) neuron using Manchester’s official software stack. Focus on membrane potential decay and spike generation.
- **Tech Stack:** Python, sPyNNaker8, Matplotlib.

### [02. Efficiency on Metal: Porting to STM32](./02-stm32-port)
Translating neural logic into bare-metal C. Focus on mathematical optimization using **Fixed-point arithmetic** for the ARM Cortex-M7 to mirror SpiNNaker’s efficiency.
- **Tech Stack:** C, STM32F767ZI, ARM CMSIS.

### [03. Perception: Sensor Encoding](./03-perception-coding)
Converting IMU data (MPU-6050) into spike trains (*Rate Coding*). Teaching the system to "perceive" gravity and orientation through spikes.
- **Tech Stack:** I2C, SNN Encoding, Real-time Processing.

### [04. Actuation: Motor Control via Spikes](./04-motor-actuation)
Decoding neural spikes back into PWM signals. Closing the loop between bio-inspired stimuli and mechanical torque response.
- **Tech Stack:** PWM, ESC, Brushless Motor Control.

### [05. The Final Rig: 1-DOF & 3-DOF Neuromorphic Drone](./05-drone-rig)
Final implementation on a 10" professional carbon fiber frame. Dynamic stabilization using SNN control laws and potential STDP (Spike-Timing-Dependent Plasticity) for adaptation.
- **Tech Stack:** Carbon Fiber Hardware, SNN Control Laws, PID vs. SNN Comparative Analysis.

---

## 🛠️ Technology Stack
- **Simulations:** Python (sPyNNaker/PyNN).
- **Embedded:** C/C++ (Bare-metal), ARM Cortex-M7.
- **Hardware:** STM32F767ZI (Nucleo-144), MPU-6050, 1000KV Brushless Motors.
- **OS:** Linux (Ubuntu 24.04 LTS).

---

## 👨‍🔬 About the Author
Senior Systems Engineer with 20+ years of experience in mission-critical software. Currently researching neuromorphic architectures as a bridge to a Research Master’s at the University of Manchester.

---
*"The brain doesn't compute with numbers; it computes with spikes."*
