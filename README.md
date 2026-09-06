**Case Study on Autonomous Boat**

A 6th semester case study project on an Autonomous Boat, controlled via an ESP8266 microcontroller with an accompanying Android control application.

📁 Repository Contents

🎮 Boat_Control/

Android application project (Gradle-based) used to control the boat.

File	Description
.gitignore	Git ignore rules for the Android/Gradle project

build.gradle.kts	Gradle build configuration for the app module

settings.gradle.kts	Gradle project settings

gradle.properties	Gradle build properties

gradlew	Gradle wrapper script (Linux/macOS)

gradlew.bat	Gradle wrapper script (Windows)

🔌 esp8266_autonomousBoat.ino

Arduino/ESP8266 firmware running on the boat - handles motor control, navigation logic, and communication with the control app.

📘 Case_study_book.pdf

The full case study submission document - covers the project background, design, implementation, and results.

🎥 Autonomous_Boat.mp4

A short demo video of the boat operating.

📄 gitignore.txt

Additional ignore rules reference for the overall project.

🛠️ How It Works

The ESP8266 (esp8266_autonomousBoat.ino) acts as the boat's onboard controller, receiving commands and driving the navigation. The Boat_Control Android app sends control commands to the boat over its connection (e.g. Wi-Fi), allowing autonomous operation to be monitored and controlled.

▶️ Demo

See Autonomous_Boat.mp4 for a working demonstration of the boat in action.

<img width="466" height="488" alt="image" src="https://github.com/user-attachments/assets/724d23e0-a613-443b-8565-4ff2434a6fbe" />

📚 Documentation

Full technical details, design decisions, and results are documented in Case_study_book.pdf.
