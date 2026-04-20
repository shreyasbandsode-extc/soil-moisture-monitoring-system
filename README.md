# Soil Moisture Monitoring System with Solar Power Integration

An Arduino-based smart irrigation prototype that monitors soil moisture and controls a water pump automatically. The system is designed to run on solar-charged battery power for off-grid use.

## Features
- Soil moisture monitoring using an analog sensor
- Automatic pump control based on moisture level
- Solar-powered battery charging support
- Low-cost and compact prototype

## Components Used
- Arduino Nano
- Soil moisture sensor
- Relay module
- Mini water pump
- TP4056 charging module
- 18650 Li-ion battery
- Solar panel
- Breadboard and jumper wires

## How It Works
The soil moisture sensor reads the moisture level of the soil and sends the value to the Arduino. Based on a threshold value, the Arduino switches the relay to turn the pump ON or OFF. The TP4056 module charges the 18650 battery using solar energy, and the battery powers the system when sunlight is unavailable.


## ⚠️ Project Status

**Partially Complete**

The core soil moisture sensing and reading circuit is built and tested.
The following modules are currently pending:

| Module | Status |
|---|---|
| Soil Moisture Sensing (FC-28) | ✅ Done |
| Arduino Code | ✅ Done |
| Water Pump Relay Module | 🚧 Pending |
| Solar Power Integration | 🚧 Pending |

---

## 🔭 Roadmap

- [ ] Wire and test the relay module for pump control
- [ ] Integrate solar panel with battery backup circuit
- [ ] Test full system as a standalone off-grid unit
