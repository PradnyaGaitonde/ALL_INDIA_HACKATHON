# Watchful Guardian

#### Problem Statement:

The idea of employing surveillance cameras to detect harassment against women on roads and promptly provide location information to law enforcement arises from the urgent necessity to combat gender-based violence and ensure the safety of women in public spaces. Harassment and assault against women in public areas are pervasive issues in many societies, causing physical and psychological harm, limiting women's freedom of movement, and perpetuating gender inequality. While the implementation of surveillance camera systems has become increasingly common in urban environments to enhance public safety and crime prevention, their potential to specifically address gender-based violence has not been fully explored. By leveraging computer vision and machine learning technologies, it is possible to develop intelligent systems that can actively detect and respond to instances of harassment, thereby creating a safer environment for women.

#### Objective:
The main goal of this project is to use surveillance cameras to make public spaces safer for women by quickly detecting and responding to instances of harassment or violence. By using advanced technology, such as facial recognition and location tracking, we aim to help law enforcement authorities intervene faster and prevent gender-based violence.

#### Innovative Solution:

CCTV cameras detecting a crime scene and immediately transmitting a signal, along with location information, to the police. This concept builds upon the previous explanation, with added emphasis on transmitting location details to enhance the effectiveness of law enforcement response. Here is an expanded overview:
1. **CCTV Camera Placement and Crime Detection:** CCTV cameras are strategically placed to monitor public areas, streets, or buildings for potential criminal activities. The cameras utilize features such as motion detection, facial recognition, or object tracking to identify suspicious behavior or events.
2. **Real-time Monitoring and Event Triggering:** The CCTV camera feeds are continuously monitored, either by human operators or automated systems. These systems analyze the video streams in real-time to detect potential criminal activities, triggering an alert when certain criteria are met.
3. **Location Identification:** In addition to detecting the crime, the CCTV camera system utilizes location-tracking technology, such as GPS or IP-based geolocation, to determine the precise location where the incident is taking place.
4. **Signal Transmission:** When an alert is triggered, the CCTV system immediately sends a signal to a central monitoring station or directly to the nearest police station. The signal includes relevant information such as the nature of the incident, the video footage from the camera, and most importantly, the location coordinates of the crime scene.
5. **Police Response and Location-based Dispatch:** Upon receiving the alert, the police assess the situation and use the location information provided by the CCTV system to determine the exact crime scene. This location-based data allows them to quickly dispatch officers to the specific area, minimizing response time.
6. **Enhanced Situational Awareness:** The live video feed from the CCTV camera, combined with the location information, provides the responding officers with real-time situational awareness. They can assess the situation remotely, gather additional information, and make more informed decisions about their response.

#### Technological Stack:

1. **CCTV Cameras:** High-quality cameras equipped with advanced features such as motion detection, facial recognition, object tracking, and potentially geolocation capabilities. These cameras capture the video footage of the monitored area.
2. **Video Analytics:** Software or algorithms that analyze the video feed from the CCTV cameras in real-time. These analytics systems can detect suspicious activities or events based on predefined criteria, triggering an alert when a potential crime is detected.
3. **Signal Transmission:** Depending on the infrastructure and requirements, the CCTV system can use various communication methods to transmit the alert and location information to the police.
	- Wired Connectivity: Ethernet or fiber-optic cables to connect the cameras and the monitoring station or police headquarters.
	- Wireless Connectivity: Wi-Fi, cellular networks, or specialized wireless protocols to transmit the alerts and data over the air.
	- Internet Protocol (IP) Networking: Utilizing IP-based communication protocols for transmitting data over the internet or private networks.
4. **Central Monitoring Station/Command Center:** A control center where the CCTV feeds are monitored by human operators or automated systems. This station serves as the hub for receiving alerts and managing the response process.
5. **Location Services:** To determine the precise location of the crime scene, the CCTV system can utilize location services such as:
	- GPS (Global Positioning System): Cameras equipped with GPS modules can provide accurate coordinates of their position.
	- IP-based Geolocation: Using IP addresses and databases to approximate the location based on the camera's network connection.
6. **Integration with Police Systems:** The CCTV system needs to integrate with the police infrastructure to transmit the alert and location information effectively.
	- Computer-Aided Dispatch (CAD) Systems: The CCTV system can interface with CAD systems used by the police to receive and manage emergency calls and incidents.
	- Geographic Information Systems (GIS): Integrating with GIS platforms allows for mapping and visualization of crime locations and optimal route planning for police dispatch.
7. **Data Storage and Management:** The CCTV system requires storage infrastructure to store the captured video footage for review and potential evidence. This can involve on-site or cloud-based storage solutions, depending on the scale and requirements of the system.

### Setup Instructions

#### Prerequisites
1. Python 3.7 or higher
2. Git

**Clone the Repository**
``` 
git clone https://github.com/yourusername/watchful-guardian.git
cd watchful-guardian
```
**Setting up OpenCV**
1. Install OpenCV 
```
pip install opencv-python
```
```
pip install opencv-python-headless  # If you are using a headless server
```

2. Verify Installation 
```
import cv2
print(cv2.__version__)
```

**Setting up TensorFlow**
1. Install TensorFlow 
```
pip install tensorflow 
```

2. Verify Installation
```
import tensorflow as tf
print(tf.__version__)
```
**Addittional Dependencies**

Install other addittional libraries
```
pip install numpy pandas requests
```
**Configuring the Project**

1. Modify the configuration files located in the config directory to suit your setup. This includes specifying paths for video input, setting up database connections, and configuring alert transmission settings.
2. Ensure your database is set up correctly. You might need to create the necessary tables and set up a connection string in the configuration file.

### Running Application
**1.Start the Application**
```
python main.py
```
**2.Monitor logs**
Check the logs to ensure the system is running smoothly and to debug any issues.

### Usage
**Real-Time Monitoring**

The system will start analyzing the video feeds in real-time and trigger alerts based on the predefined criteria.

**Notifications & Alerts**

Alerts will be sent to the specified command center or law enforcement with the video footage and location details.

### Areas of Improvement for the "Watchful Guardian" System

1. **Privacy Protection:**
   - Implement strict data protection measures.
   - Anonymize personal information in video feeds.
   - Provide transparent information to the public about CCTV camera use.

2. **Bias Mitigation:**
   - Regularly audit and recalibrate surveillance algorithms.
   - Minimize false positives and negatives, especially in facial recognition.

3. **Response Coordination:**
   - Improve coordination with law enforcement for prompt responses.
   - Develop standardized protocols for alert transmission and dispatch.

4. **Community Engagement:**
   - Involve local communities, especially women's organizations, in system design.
   - Solicit feedback to address concerns and build trust.

5. **Accessibility Considerations:**
   - Ensure accessibility for people with disabilities.
   - Provide alternative communication methods for alerts.

6. **Ethical Oversight:**
   - Establish clear ethical guidelines and oversight mechanisms.
   - Conduct regular ethics reviews and public consultations.

7. **Data Security:**
   - Strengthen encryption protocols and access controls.
   - Implement cybersecurity best practices to safeguard sensitive data.

8. **Continuous Evaluation and Improvement:**
   - Establish a process for continuous evaluation based on feedback and data analysis.
   - Regularly assess the system's impact and identify areas for enhancement.

By addressing these areas, the "Watchful Guardian" system can become more robust and responsive in combating gender-based violence.
