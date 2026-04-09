Today we did the project about IoT Smart Room Visitor Attendance System Using ESP32 and RFID.
This project is an IoT-based smart attendance system that uses RFID cards and an ESP32 microcontroller to automatically record and track visitors entering a room or building.

Instead of writing in a book, visitors use an RFID card, and their information is stored digitally in a database.

 Hardware Components:

- ESP32 (main controller)
- RFID RC522 module
- RFID cards/tags
- Jumper wires

Software Components:

- Arduino IDE (for ESP32 programming)
- PHP (backend logic)
- MySQL (database)
- HTML (web interface)
- XAMPP (local server)

How the System Works:

Step-by-step flow:

1. A visitor arrives and provides:
- Name
- Phone number
- Purpose
2. The visitor scans an RFID card using the
MFRC522 RFID Module
3. The ESP32:
- Reads the card UID
- Connects to WiFi
- Sends the UID to the server
4. The server (running on XAMPP) stores the data in a MySQL database
5. When the same card is scanned again:
- The system retrieves previous visits
- Displays visitor history.

![](<../images/week 2 images/WhatsApp Image 2026-04-09 at 17.39.32.jpeg>)
