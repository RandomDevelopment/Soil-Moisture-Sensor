# Soil Moisture Sensor Firmware

This project is a DIY soil moisture monitoring solution designed for low cost and maximum compatibility with Home Assistant. It's perfect for anyone interested in gardening, agriculture, or home automation and provides real-time soil moisture data to optimize plant care.

## Features

- Real-time soil moisture measurement.
- Configurable wet and dry voltage thresholds via a web interface.
- Simple and easy installation process.

## Hardware Components

The components used for this project are:

- **WeMos D1 Mini V4.0.0 (Type-C USB)**  
  [Buy on Amazon](https://www.amazon.com/dp/B0CL9CTXZH) - Pack of 10.

- **Capacitive Soil Moisture Sensor**  
  [Buy on Amazon](https://www.amazon.com/dp/B0C1BCVFJ5) - Pack of 10.

Substitutes may work if they meet the specifications.

## Installation

1. Download the latest `Soil-Moisture-Sensor-Firmware-V#.#.bin` file from the [releases page](https://github.com/RandomDevelopment/Soil-Moisture-Sensor/releases/).
2. Flash the firmware onto your WeMos D1 Mini using the [ESPHome Flasher tool](https://web.esphome.io/).
3. Connect the D1 Mini to your sensor following this wiring guide:

   - Red (VCC) -> 5V/Vbus on D1 Mini.
   - Black (GND) -> GND on D1 Mini.
   - Yellow (SIG) -> A0 on D1 Mini.

4. Place the soil moisture sensor into the soil near your plant.

## Configuration

Alter the ESPHome yaml file to modify Wi-Fi settings, device name, or update intervals.

After connecting the device to Wi-Fi, access the web interface at `http://soil-moisture-sensor-rd.local/` to adjust the sensor's dry and wet threshold values as needed.

## Contributing

Your contributions to this project are welcome! Feel free to report issues, suggest features, or submit pull requests for improvements.

## License

This project is released into the public domain under The Unlicense. For full details, see the [LICENSE](LICENSE) file.
