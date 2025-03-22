# C02Monitor
C02 Monitor Lancs UK
https://benb0jangles.github.io/C02Monitor/
#
Environmental Monitor with SCD41 Sensor
Project Overview

This project is an environmental monitoring system built with an ESP32-S3 Nano microcontroller and a Sensirion SCD41 sensor. It measures CO2 levels, temperature, and humidity in indoor environments, displaying real-time data on an OLED screen and uploading measurements to ThingSpeak for remote monitoring and data analysis.

The system provides valuable insights into indoor air quality, which can affect health, comfort, and cognitive performance. Poor ventilation leads to increased CO2 levels, which can cause drowsiness, headaches, and reduced concentration.
Understanding CO2 Levels

CO2 concentration is measured in parts per million (ppm). Here's what different readings indicate:

    400-450 ppm: Typical outdoor air concentration
    < 800 ppm: Excellent indoor air quality
    800-1000 ppm: Good indoor air quality
    1000-1500 ppm: Moderate air quality; consider increasing ventilation
    1500-2000 ppm: Poor air quality; headaches, drowsiness, and loss of concentration may occur
    2000-5000 ppm: Very poor air quality; potential for serious health effects with prolonged exposure
    > 5000 ppm: Extremely high; immediate ventilation required

Hardware Components

    ESP32-S3 Nano microcontroller
    Sensirion SCD41 CO2, temperature, and humidity sensor
    128x64 OLED display
    External 3.3V power supply for the SCD41 sensor (necessary for stable operation)

Features

    Real-time monitoring of CO2, temperature, and humidity
    Visual display with air quality indicators
    WiFi connectivity for data transmission
    ThingSpeak integration for cloud storage and visualization
    Temperature correction to account for sensor self-heating
    Robust error handling and debugging

Future Enhancements

    Add alert system for high CO2 levels
    Implement data logging to microSD card
    Add battery operation for portability
    Create mobile app for notifications
    Expand with additional environmental sensors

Notes on Indoor Air Quality

Maintaining good indoor air quality is essential, especially in bedrooms, offices, and classrooms. Regular ventilation and monitoring can prevent CO2 buildup. Open windows periodically or use mechanical ventilation systems to introduce fresh air. Plants can help improve air quality but aren't sufficient to mitigate high CO2 levels in poorly ventilated spaces.
