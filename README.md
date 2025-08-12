# Weather-Alert-System
**Overview**<br>
The Weather Alert System is an IoT-based real-time monitoring solution designed to improve residential safety by tracking environmental parameters such as temperature, humidity, and harmful gas levels. The system provides multi-stage alerts to notify residents about potential hazards and can automatically activate safety measures like ventilation.

By integrating climate monitoring with gas detection and automated responses, the project aims to reduce human life risks and enhance the overall safety of individuals in their homes.

**Features**<br>
Real-time Monitoring of:

Temperature

Humidity

Gas levels (using MQ2 sensor)

Multi-stage Alert System:

Visual alert via Red Light

Auditory alert via Buzzer/Alarm

SMS notifications via GSM Module

Automated Ventilator Fan activation

Proactive Safety Measures to prevent accidents like carbon monoxide poisoning.

**Hardware Components**<br>
Temperature & Humidity Sensor (e.g., DHT11/DHT22)

MQ2 Gas Sensor

Arduino Board (e.g., Arduino UNO)

GSM Module for SMS alerts

LED Light (Red) for visual alert

Buzzer for sound alerts

Ventilator Fan for safety action

**Working Principle**<br>
Sensors continuously collect temperature, humidity, and gas concentration data.

If thresholds are exceeded:

Stage 1: Red light turns ON.

Stage 2: Alarm activates.

Stage 3: SMS notification sent to the user.

Stage 4: Ventilator fan starts automatically.

The system resets to safe mode when parameters return to normal.

**Use Cases**<br>
Home Safety Monitoring (detecting harmful gases & indoor climate changes)

Industrial Safety Systems

Smart Building Automation

**Future Enhancements**<br>
Integration with cloud-based dashboards for data logging and remote access

Mobile app notifications instead of just SMS

AI-based prediction models for hazard prevention

**Acknowledgements**<br>
This project was inspired by real-life incidents where harmful gases led to fatalities, highlighting the need for affordable and proactive safety systems in residential spaces.
