# IoT-Based-Efficient-Temperature-Monitoring-and-Cooling-Automation-Framework


Welcome to the implementation.

---

## Screenshots

| Screenshot                                       | Description                |
|--------------------------------------------------|----------------------------|
|![IoT Level](https://github.com/raihan40/IoT-Based-Efficient-Temperature-Monitoring-and-Cooling-Automation-Framework/assets/86623443/d4edaac1-29d2-4ca5-84aa-f183d1c58d10)|IoT Level|
|![Architecture](https://github.com/raihan40/IoT-Based-Efficient-Temperature-Monitoring-and-Cooling-Automation-Framework/assets/86623443/e8c1afc3-06ef-4e54-9743-8a8e009327af)|Architecture|
|![image5](https://github.com/raihan40/IoT-Based-Efficient-Temperature-Monitoring-and-Cooling-Automation-Framework/assets/86623443/5390de56-b1cd-4e49-89af-9e2115767ba8)|Web DashBoard|
|![image3](https://github.com/raihan40/IoT-Based-Efficient-Temperature-Monitoring-and-Cooling-Automation-Framework/assets/86623443/4c27ebf3-3d7d-4e58-b23b-4bce7172757d)|Application Dashboard|
|![Notification Alert](https://github.com/raihan40/IoT-Based-Efficient-Temperature-Monitoring-and-Cooling-Automation-Framework/assets/86623443/ba97894b-aff6-4be8-b9a0-40d68c887cbc)|Notification Alert|

---

## Video




https://github.com/raihan40/IoT-Based-Efficient-Temperature-Monitoring-and-Cooling-Automation-Framework/assets/86623443/68d9d2cc-8e17-4fd6-9d3a-46ed475395c0





https://github.com/raihan40/IoT-Based-Efficient-Temperature-Monitoring-and-Cooling-Automation-Framework/assets/86623443/7454b878-865f-43cf-871f-1d11829ed933




https://github.com/raihan40/IoT-Based-Efficient-Temperature-Monitoring-and-Cooling-Automation-Framework/assets/86623443/0bbff19e-c479-4695-bdd0-498dfa3bb3f9


---

## Installation

1. Clone the repository:
git clone https://github.com/raihan40/Ben10_game.git

2. Add Temperature Sensor to the NodeMCU
3. Configure the NodeMcu (Code is given)
4. Setup the rasberry pie
5. Run the actuation code inside pie
6. Your are good to go, all codes are already given.

---


## Features
Here are some features of your IoT-based temperature control system using Raspberry Pi:

1. **Real-time Temperature Monitoring:** Constantly monitors the temperature using sensors in real-time.

2. **Threshold Alerts:** Sends immediate alerts when the temperature exceeds a predefined safe threshold.

3. **Automated Cooling System:** Initiates a cooling system, in this case, a 12V fan, as soon as the temperature surpasses the safe limit.

4. **Relay Control:** Uses a relay to manage and control higher voltage devices, ensuring safe and efficient operation.

5. **Energy Efficiency:** Optimizes energy consumption by running the cooling system only when necessary, based on temperature conditions.

6. **Remote Monitoring:** Allows users to remotely monitor the temperature and system status through a centralized server.

7. **Alert Notifications:** Sends alerts or notifications to designated recipients (e.g., administrators or users) in case of temperature anomalies.

8. **Automated Shutdown:** Automatically stops the cooling system and sends an alert when the temperature returns to a safe level.

9. **User-Friendly Interface:** Provides a user-friendly interface for configuration, monitoring, and control, accessible through a web interface or a dedicated application.

10. **Customizable Settings:** Offers customizable settings for threshold values, alert preferences, and cooling system parameters to adapt to different environments.

11. **Open Source Integration:** Utilizes open-source technologies, facilitating community contributions and customization.

---

## Requirements

- DHT11 sensor for temperature sensing
- NodeMCU for data sensing and MQTT communication
- Raspberry Pi as the MQTT broker and for actuation
- LED with resistance for visual indication
- Relay to control the cooling system 
- Snitch app SMS API for sending SMS notifications


---

## Contributing

If you'd like to contribute to the development of this game, please follow these steps:

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Push your branch to your forked repository
5. Submit a pull request
