# ESP32 MQTT Project with Node-RED and Mosquitto

This project demonstrates the use of the **MQTT protocol** to communicate between an **ESP32 microcontroller** and **Node-RED**, using a **Mosquitto broker** running inside an Ubuntu VM (Oracle VirtualBox).

## What I Learned
I built this project while learning MQTT. It helped me understand how clients publish and subscribe to topics, and how Node-RED interfaces with hardware over WiFi.

## Components
- ESP32
- Mosquitto MQTT Broker (Ubuntu VM)
- Node-RED (Publisher)
- Topic: `esp32/led`

## Screenshots
- [ ] Node-RED flow (inject → mqtt out)
- [ ] Mosquitto terminal
- [ ] ESP32 serial monitor output
- [ ] VM IP configuration (`ip a`)

## How it works
Node-RED publishes `"on"` or `"off"` messages to the `esp32/led` topic.  
ESP32 subscribes to the same topic, receives the message, and processes it in real-time.

---

📡 *A simple but effective intro to IoT messaging with MQTT!*
 
