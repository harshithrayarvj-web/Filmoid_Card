# Filmoid_Card
A small card like device meant to resemble instant film and contains an LED matrix.

This device is meant to show sensor data, making it easier to know about certain data when needed, such as temperature or acceleration, while also using the LED matrix for fun with animations and maybe as a weak flashlight.
It is planned to have it be a device that can be compact while also reading sensor data from the humidity/temperature sensor and the IMU. Use cases for this could be things such as tracking plants, or measuring inertial measurements while displaying them on the led matrix. The size and compactness of this device should make it easy to produce, especially if they need to be cheap, such as for measuring plants, and also need something like a xiao for processing that data (as an input device or it's own device that can do actions using data from the sensors).

Although this is compact, with a next revision I could rework the pcb to contain the mcu right on the board to make it more compact and reduce costs, while also improving it's capability, like adding the IMU right on the pcb and adding more sensors. This way I can reduce costs and make it more compact, and potentially make it very compact that it can be a small and cheap addition for small projects like potted plant gardens or as a sensor module for a larger project. Hopefully a wireless version could be possible. I can't promise a revision, but if it is going to be real, then I would rename this and give it to a different project that would benefit more.


<img width="600" height="595" alt="Screenshot 2026-10-11 230813" src="https://github.com/user-attachments/assets/afded4e8-b9c0-4f24-adf5-eee6f4702ab7" />
<img width="490" height="601" alt="Screenshot 2026-10-11 230803" src="https://github.com/user-attachments/assets/e586d0c0-9542-4fa7-93d6-3108633a8ba7" />
<img width="1154" height="864" alt="Screenshot 2026-10-11 230726" src="https://github.com/user-attachments/assets/bb515ac6-288d-4e84-93db-4dd5c82ac4fc" />
<img width="724" height="843" alt="Screenshot 2026-10-11 203206" src="https://github.com/user-attachments/assets/bd39ccc4-b231-4ea2-a9c1-b6894956d533" />

|          Name         | Amount | Unit | Total |    Vendor   | Funding   |
|:---------------------:|:------:|:----:|:-----:|:-----------:|-----------|
| 0603 Yellow LED SMD   | 30     | 0.1  | 3     | Digikey     | 30        |
| MPU6050               | 1      | 8.59 | 8.59  | Amazon      | Left Over |
| 10k SMD 0603 resistor | 1      | 0.1  | 0.1   | Digikey     | 11.26     |
| XIAO RP2040 MCU       | 1      | 4.9  | 4.9   | Digikey     |           |
| DHT11                 | 1      | 1.89 | 1.89  | Ali Express |           |
| Switch                | 2      | 0.13 | 0.26  | Digikey     |           |
| PCB(selffunded)       | 1      | 4    | 30.64 | JLCPCB      |           |
|                       |        |      | 49.38 |             |           |
