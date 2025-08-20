# Microcontroller & IoT Based Chicken Brooder

**Microcontroller & IoT Based Chicken Brooder**  
A low-cost prototype to monitor and automatically control the brooder environment for young chicks.

---

## Features
- Temperature & humidity monitoring (DHT sensor)
- Automatic control of fan, heater/LED, and pump via relays
- Servo-driven feeder routine
- Remote monitoring & control via Arduino IoT Cloud (optional)

---

## Bill of Materials (high-level)
- NodeMCU / ESP8266 board
- DHT11 or DHT22 sensor
- Relay module (2–3 channel)
- DC fan
- DC water pump
- Servo motor
- 5V power supply (sized for actuators)
- Wires, connectors, enclosure

---

## Wiring / Pin Summary (example)
- `DHT` data → D5
- `relay_fan` → D4
- `LED_relay_PIN` (heater/lighting) → D2
- `relay_pump` → D3
- `servo_PIN` → D6
- Use a common ground between controller and actuators

