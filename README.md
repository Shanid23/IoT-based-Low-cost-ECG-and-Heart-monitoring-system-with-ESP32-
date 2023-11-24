# IoT-based-Low-cost-ECG-and-Heart-monitoring-system-with-ESP32-

**AIM:** To provide accessible and continuous remote monitoring of a person’s cardiac health.

**OBJECTIVE:**

*Early Detection of Cardiac Issues

*Remote Patient Monitoring

*Low-Resource Settings

*Reducing Healthcare Costs

*Education and Research

**FEATURES:**

**Develop a Wearable Heart Monitoring Device:*

Design a compact and wearable device capable of continuous ECG monitoring using the ESP32 and AD8232.

**Real-Time ECG Signal Processing:*

Implement real-time signal processing algorithms to filter noise and extract meaningful ECG data for accurate heart rate calculation.

**Wireless Data Transmission:*

Enable wireless data transmission from the monitoring device to a connected device (e.g., smartphone, computer) for real-time display and analysis.

**Heart Rate Calculation Algorithm:*

Develop and optimize algorithms to calculate the user's heart rate based on the processed ECG signals.

**User Alerts for Abnormalities:*

Implement an alert system to notify users in real-time of irregular heartbeats or abnormal ECG patterns, promoting early detection of potential health issues.

**Data Logging and Storage:*

Create a data logging feature to store ECG data over time, facilitating historical analysis and tracking of changes.

**Cloud Integration:*

Integrate cloud storage for ECG data, allowing users to access their information from multiple devices and enabling remote monitoring by healthcare professionals.

**User Authentication and Privacy:*

Implement user authentication mechanisms to ensure secure access to ECG data and prioritize user privacy in compliance with relevant regulations.

**Intuitive User Interface:*

Design an intuitive and user-friendly interface for displaying real-time ECG data, heart rate, and historical trends.

**Customizable Settings:*

Provide users with customizable settings, such as monitoring duration, alert thresholds, and display preferences, to enhance the user experience.

**Integration with Health Platforms:*

Explore integration with existing health platforms or applications, allowing users to sync ECG data with other health-related metrics for a comprehensive health profile.

**Offline Mode and Local Data Storage:*

Include an offline mode that stores a certain amount of data locally, enabling users to access their ECG history even without an internet connection.

**Open-Source Collaboration:*

Foster open-source collaboration by making the project's codebase accessible to the developer community, encouraging contributions and improvements.

**Educational Resources:*

Provide educational resources within the application to help users understand their ECG data, promoting heart health awareness and informed decision-making

**COMPONENTS REQUIRED:**

*ESP32 Board

*AD8232 ECG sensor

*ECG Electrode connector with plastic patches

*Connecting wires

**MINDMAP:**

![WhatsApp Image 2023-11-16 at 1 34 17 PM](https://github.com/Shanid23/IoT-based-Low-cost-ECG-and-Heart-monitoring-system-with-ESP32-/assets/113709805/d7084699-8f5c-4fd3-a43f-014b87b5a235)


**FLOWCHART:**

![WhatsApp Image 2023-11-16 at 1 02 36 PM](https://github.com/Shanid23/IoT-based-Low-cost-ECG-and-Heart-monitoring-system-with-ESP32-/assets/113709805/7b8915a2-b732-4578-bb0c-5dda053a3c8d)

**ALGORITHM**

STEP1: Include Libraries
•	Include necessary libraries such as ‘WiFi.h’, ‘WiFiUdp.h’, ‘PubSubClient.h’ and ‘NTPClient.h’.

STEP 2: Define constants
•	Define constants for WIFI credentials, variable labels, device label and sensor pin.

STEP 3: Global variables
•	Declare global variable for MQTT broker, payload, topic and various time-related variables.

STEP 4: Main functions
•	Implement the ‘setup()’ function
•	Connect to WiFi 
•	Set sensor pin as INPUT
•	Implement the ‘loop()’ function
•	Check if MQTT client is connected; if not, attempt to reconnect
•	Increment a counter variable ‘j’
•	Construct MQTT topic using device label
•	Publish the payload

STEP 5: Data formatting
•	Format sensor reading and time stamp as strings
•	Utilize ‘printf’ to construct the MQTT payload 

STEP 6: Publish Data
•	Publish the constructed payload
STEP 7: Delay
•	Introduce the delay of 150 millisecond between sensor reading
STEP 8: Serial Output
•	Output relevant information to the serial monitor for debugging and monitoring.

**BLOCK DIAGRAM**

![Screenshot_20231123_080118_WhatsApp](https://github.com/Shanid23/IoT-based-Low-cost-ECG-and-Heart-monitoring-system-with-ESP32-/assets/113709805/bd01878a-7a03-48a9-a3e1-e797d91f87d1)

**CIRCUIT DIAGRAM**

![Screenshot_20231123_080230_WhatsApp](https://github.com/Shanid23/IoT-based-Low-cost-ECG-and-Heart-monitoring-system-with-ESP32-/assets/113709805/6e4e38da-2ee5-425e-b73d-68f5c1c44365)

**CONCLUSION**
In conclusion, the development of an IoT-based low-cost ECG monitoring system using the AD8232 ECG sensor and ESP32 presents a promising solution for remote healthcare monitoring. This innovative system leverages the power of Internet of Things (IoT) technology to provide real-time ECG data acquisition and transmission, enabling continuous monitoring of patients' cardiac health in a cost-effective manner.
The system's low-cost design addresses accessibility concerns, making it more viable for a broader range of users, including those in resource-constrained environments. By utilizing open-source hardware and software components, the project encourages collaboration and customization, potentially fostering further innovations in the field.


