# Sumo Robot – National Sumo Robot Competition – HTUJO 2024

## Overview
This sumo robot is designed to compete in the **National Sumo Robot Competition – HTUJO 2024**.  
It is built for agility, speed, and autonomous decision-making to push the opponent robot out of the ring efficiently.

The robot integrates high-torque motors, precise sensors, and a robust control system to perform in the competitive sumo arena.

---

## Robot Features
- Autonomous movement and decision-making.
- High-torque DC motors for rapid pushes.
- Precision distance sensors (Lidar, IR) to detect opponent and ring boundaries.
- Safety features to avoid falling off the ring.
- Compact design within competition weight and size limits.

---

## Robot Images

<div style="display: flex; gap: 10px; justify-content: center; flex-wrap: wrap;">
  <img src="https://github.com/Saeed-Ghazal/Sumo-Robot/blob/main/IMG-20250925-WA0079.jpg?raw=true" alt="Image 1" style="width: 300px; max-width: 100%; height: auto;" />
  <img src="https://github.com/Saeed-Ghazal/Sumo-Robot/blob/main/IMG-20250925-WA0091.jpg?raw=true" alt="Image 2" style="width: 300px; max-width: 100%; height: auto;" />

</div>

<div style="display: flex; gap: 10px; justify-content: center; flex-wrap: wrap;">
   <img src="https://github.com/Saeed-Ghazal/Sumo-Robot/blob/main/Image%202025-11-22%20at%2015.10.54_2ed6a447.jpg?raw=true" alt="Image 3" style="width: 300px; max-width: 100%; height: auto;" />
  <img src="https://github.com/Saeed-Ghazal/Sumo-Robot/blob/main/Image%202025-11-22%20at%2015.11.25_562c53e6.jpg?raw=true" alt="Image 4" style="width: 300px; max-width: 100%; height: auto;" />
  <img src="https://github.com/Saeed-Ghazal/Sumo-Robot/blob/main/Image%202025-11-22%20at%2015.06.44_b4203e6c.jpg?raw=true" alt="Image 5" style="width: 300px; max-width: 100%; height: auto;" />
</div>

---

## Components

| Component | Quantity | Description |
|-----------|---------|-------------|
| VL53L0X Lidar Sensor | 6 | Measures distance to detect opponent position accurately in 3D. |
| TCRT-5000 IR Sensor | 4 | Detects white boundary line to prevent falling off the ring. |
| PCF8574 I2C Expander | 1 | Expands IO pins for multiple sensors and buttons. |
| BTS7960 Motor Driver | 2 | High-current motor driver for main drive wheels. |
| 3S LiPo Battery | 1 | Main power source providing high voltage and current. |
| LM2596 Step-Down Module | 3 | Reduces battery voltage to safe levels for controllers and sensors. |
| Arcade Buttons | 6 | User input for setup and strategy selection. |
| Round Rocker Switch | 3 | Power and system switches. |
| Buzzer Module | 8 | Audio alerts for status, countdown, or opponent detection. |
| FAN 12V | 1 | Airflow for cooling or mechanical operation (not for suction). |

---

## Rules Summary

- **Arena**: Circular sumo ring with 1.5m diameter, black floor, white border (3 cm thick).  
- **Robot Specs**:
  - Max weight: 3 kg
  - Max length/width: 20 cm
  - No remote control allowed; fully autonomous.
  - No adhesives, suction, magnets, or liquids allowed to fix robot to the arena.
- **Match**:
  - Best-of-three rounds.
  - Each round lasts up to 3 minutes.
  - A robot wins a round by pushing the opponent out of the ring completely.
  - Red card: disqualification.
  - Yellow card: warnings; 3 per round may result in round loss.
- **Scoring**:
  - 1 point for pushing opponent out.
  - 2 points for winning two rounds.
  - Infractions, delays, or detached parts result in penalties.

---

## Summary
This robot is designed for competitive sumo matches, focusing on:

- High-speed autonomous pushes
- Accurate boundary and opponent detection
- Compliance with HTUJO 2024 rules

It demonstrates a balance of mechanical design, electronics, and autonomous control suitable for national-level competition.
