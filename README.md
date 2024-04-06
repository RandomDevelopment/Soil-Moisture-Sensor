# Soil Moisture Sensor Firmware

This Project is designed for a DIY soil moisture monitoring solution for a low cost and maximum compatibility with Home Assistant, perfect for anyone interested in gardening, agriculture, or home automation. It provides real-time soil moisture data, helping to ensure your plants are well-watered without the guesswork.

## Features

- Real-time soil moisture measurement
- Configurable wet and dry voltage thresholds via a web interface
- Easy installation

## Hardware Components

The following components we used for this project:

- **WeMos D1 Mini V4.0.0 (Type-C USB)**  
    [Buy on Amazon](https://www.amazon.com/dp/B0CL9CTXZH) - Pack of 10

- **Capacitive Soil Moisture Sensor**  
    [Buy on Amazon](https://www.amazon.com/dp/B0C1BCVFJ5) - Pack of 10

You may be able to get away with Substitutes. 

## Installation

1. Download the latsed `Soil-Moisture-Sensor-Firmware-V#.#.bin` file from the [releases page](https://github.com/RandomDevelopment/Soil-Moisture-Sensor/releases/).
2. Flash the firmware onto your WeMos D1 Mini using the [ESPHome Flasher tool](https://web.esphome.io/).
3. After flashing, connect the D1 Mini to your sensor as indicated in the wiring diagram below:

  -  Red (VCC) -> 5V/Vbus on D1 Mini 
  -  Black (GND) -> GND on D1 Mini 
  -  Yellow (SIG) -> A0 on D1 Mini

4. Insert the soil moisture sensor into the soil

## Configuration

Modify the yaml file in esp home to change the Wi-Fi settings, name, or update interval.

Once the device is powered and connected to your Wi-Fi, navigate to the web interface at `http://soil-moisture-sensor-rd.local/` to adjust the dry and wet values as necessary.

## Contributing

We appreciate your interest in contributing to this project! Please feel free to report issues, suggest features, or submit pull requests.

## License

This project is under The Unlicense - which releases the software into the public domain. Full details can be found in [LICENSE](LICENSE).

