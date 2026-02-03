# Soton Robo Hack 2025 - Autonomous Navigation Robot
**Achievement:** 3rd Place Winner (out of 15+ teams)
**Event:** 24-Hour Engineering Sprint at University of Southampton (Building 42)

## Project Overview
This project was developed during a high-intensity 24-hour hackathon. Our team engineered an autonomous robot capability of navigating a physical course and identifying target objects in real-time.

## The Engineering Challenge
The core challenge was to integrate hardware sensors (camera) with software logic (Python) to navigate a maze and identify specific boxes based on visual markers.

## My Technical Contributions
### 1. Hardware Integration (Raspberry Pi 5)
* Configured the **Raspberry Pi** environment to handle real-time image processing.
* Managed the interface between the camera module and the Python backend.

### 2. The "360 Scan" Logic
I designed and implemented the core search algorithm:
* **Problem:** The robot needed to find a specific target without external guidance.
* **Solution:** Developed a "Spin & Lock" logic.
    * The robot executes a calibrated rotation.
    * Continuous frame analysis scans for QR codes.
    * Upon detection, the movement loop terminates, and the robot logs the positive ID.

## Outcome
* **Performance:** Successfully navigated the course and identified targets efficiently.
* **Result:** Secured **3rd Place** against 15+ competing teams.
* **Key Takeaway:** Gained rapid experience in hardware-software interfacing and deploying logic under extreme time constraints.
