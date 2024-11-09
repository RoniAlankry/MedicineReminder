## MedicineReminder
This is an IoT-based smart medicine reminder system built with C++ and the ESP32 microcontroller. Designed to help patients adhere to their medication schedules, this device provides visual and auditory alerts, as well as real-time remote monitoring.

##Features
Visual and Auditory Alerts: Integrates NeoPixel LEDs and a speaker to remind users to take medication.
Touch Sensor for Interaction: Allows users to interact with the device by acknowledging alerts.
Remote Monitoring: Connects to Blynk for real-time monitoring and notifications.
Customizable Schedules: Set reminders for morning and night doses, synced with NTP for accurate timing.
##Tech Stack
#Language: C++
Hardware:
ESP32 microcontroller
NeoPixel LEDs for visual alerts
Speaker for auditory alerts
Touch sensor for user interaction
#Software:
Blynk for remote control and monitoring
NTP for time synchronization
##Getting Started
#Prerequisites
ESP32 microcontroller
Blynk account and project setup (with Auth Token)
Arduino IDE for programming
#Installation
Clone the repository:
bash
Copy code
git clone https://github.com/RoniAlankry/SmartMedicineReminder.git
cd SmartMedicineReminder
Open the project in the Arduino IDE.
Install required libraries (NeoPixel, Blynk, etc.).
Configure WiFi credentials and Blynk Auth Token in the code.
Upload the code to your ESP32.
#Usage
Set your medication reminders through the Blynk app.
When it’s time for a dose, the LEDs and speaker will alert the user.
Acknowledge alerts using the touch sensor.
Monitor and adjust reminders remotely via the Blynk app.
##Contributing
Contributions are welcome! Please submit a pull request or open an issue for feature requests and bug fixes.
