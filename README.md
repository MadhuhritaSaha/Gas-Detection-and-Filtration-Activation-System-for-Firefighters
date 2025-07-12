# 🧯 Wearable Toxic Gas Detection and Filtration Activation System for Firefighters

## Abstract
Firefighters face hazardous environments with toxic gases. Traditional filtration masks provide constant filtration, which drains energy and wears out filters prematurely. This project introduces a smart, adaptive system: toxic gas sensors trigger automatic filtration only when needed, conserving power and filter life.

## Features
- Real-time detection of gases (CO, NH₃, SO₂)
- Automatic filtration activation via relay and fan/solenoid
- Buzzer alert for user notification
- Arduino/ESP32-based control
- Compact, wearable design

## System Overview
1. **Gas Detection Module**: MQ-series sensors monitor air quality.
2. **Alert Mechanism**: Buzzer sounds when toxic levels detected.
3. **Filtration Activation**: Relay triggers fan/solenoid for clean airflow.
4. **Control System**: Microcontroller processes data and controls system.

## Components
| Component            | Function                     |
| -------------------- | ---------------------------- |
| MQ-2, MQ-7, MQ-135   | Gas detection (CO, NH₃, SO₂) |
| Buzzer Module        | Alerts user                  |
| Relay Module         | Activates filtration         |
| Arduino/ESP32        | Main controller              |
| DC Fan/Solenoid      | Air filtration               |
| Battery Pack         | Power supply                 |
| Enclosure/Wiring     | Protective/heatproof         |

## Future Scope
- Wireless data transmission
- GPS integration
- Additional sensors (temperature, humidity, pressure)

## References
See [REFERENCES.md](REFERENCES.md) for detailed citations.

---

## Contributing

Please read [CONTRIBUTING.md](.github/CONTRIBUTING.md) before submitting issues or pull requests.

---

## License

[MIT License](LICENSE)
