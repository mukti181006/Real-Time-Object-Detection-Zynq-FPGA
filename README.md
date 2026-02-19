# Real-Time Object Detection on Xilinx Zynq FPGA

This repository contains the implementation of a **real-time object detection system**
using a **hardware-accelerated CNN** on a Xilinx Zynq FPGA platform with an ARM processor.

The project focuses on deploying a lightweight object detection model suitable for
low-latency, resource-constrained embedded systems.

---

## Project Overview
- CNN-based real-time object detection
- Target platform: Xilinx Zynq FPGA with ARM processor
- Emphasis on hardware acceleration for inference

---

## CNN Model
The object detection model is based on **YOLOv8-Nano**, a lightweight, anchor-free
CNN architecture optimized for real-time performance.

**Detailed CNN architecture and design explanation:**  
`cnn_model/README.md`

---

## Hardware and Software Status
- **CNN model design:** Completed
- **FPGA hardware acceleration:**  In progress
- **ARM-side software integration:**  In progress

Hardware and software components will be added to the repository
as development progresses.

---

## Repository Structure
cnn_model/   - CNN architecture and model documentation 
hardware/    - FPGA hardware design (in progress) 
software/    - ARM-side software and drivers (in progress) 
docs/        - Project documentation and reports
