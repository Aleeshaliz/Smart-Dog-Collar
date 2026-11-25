# Smart Dog Collar (PawPulse)

A wearable IoT health and activity monitoring collar for dogs that tracks heart rate, body temperature, and movement/posture, paired with a 1D CNN + LSTM activity classifier, Flask/Render backend, and the **PawPulse** Flutter mobile app.

## Why This Project
Dogs can develop issues like heatstroke, irregular heart rates, or sudden lethargy that are easy to miss between periodic vet visits. This project provides continuous, non-invasive monitoring and real-time mobile alerts to help owners spot health or activity changes early.

## Tech & Hardware
* **Embedded & Power:** ESP32 (Arduino IDE), MAX30102/MAX30105 heart rate sensor, MLX90614 non-contact IR temperature sensor, MPU9250 IMU, QMC5883L magnetometer, piezoelectric vibration sensor, 3.7V Li-ion battery, buck converter, and HW373 charging module.
