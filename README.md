#  Starbie
Welcome to   **Starbie**
i built Starbie from scratch to be a living, breathing companion on my desk—capable of tracking movement, sensing environmental conditions, and reacting through a cute pixel pet displayed on an OLED screen.

---

##  What I Used (Components)
To bring Starbie to life, I selected and integrated the following hardware components:
* **Microcontroller:** Seeed Studio XIAO ESP32-C3 (Compact, powerful, and wireless-ready)
* **Display:** 0.96" I2C OLED Display (To render the pet animations and UI)
* **Motion Tracker:** MPU6050 6-Axis Accelerometer & Gyroscope (To detect tilts, shakes, and movements)
* **Environment Sensor:** DHT11 Temperature & Humidity Sensor (To sense room conditions)
* **User Input:** Tactile Push Buttons (For navigating the radial menu and interacting with Starbie)

---

## Design & Development Journey

### 1. Schematic Design
I started by mapping out the full circuit architecture in **EasyEDA**, carefully wiring the XIAO ESP32-C3 with the I2C bus (OLED & MPU6050), digital pins (DHT11 & buttons), and ensuring robust power rails and ground connections.

### 2. PCB Layout & Routing
* Defined a clean board outline tailored for compactness.
* Placed components to avoid signal interference and footprint overlaps.
* Successfully ran the **Auto Router** to achieve 100% routed traces with zero design errors.
* Inspected the final design using the 3D PCB viewer to ensure a manufacturing-ready layout.

---

