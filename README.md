# Implement-Physical-Security-with-IoT-Devices
# 🏠 IoT Home Security Network Lab

A Cisco Packet Tracer project demonstrating the deployment, configuration, and management of Internet of Things (IoT) devices for a smart home security system. This lab focuses on securely connecting IoT devices to a wireless network, registering them with a remote IoT Registration Server, and remotely monitoring and controlling home security devices.

---

## 📌 Project Overview

This project simulates a smart home environment where multiple IoT security devices are integrated into a wireless network. The devices communicate with an IoT Registration Server, allowing centralized management and remote monitoring.

The lab demonstrates wireless security, MAC address filtering, DHCP configuration, IoT device registration, and remote device management using Cisco Packet Tracer.

---

## 🎯 Objectives

### Part 1 – Connect IoT Devices to the Network

* Connect a Home Siren to the Home Door
* Configure IoT devices to connect to the **HomeNet** wireless network
* Configure WPA2-PSK wireless security
* Obtain IP addresses using DHCP
* Configure Wireless MAC Address Filtering
* Verify secure wireless connectivity

### Part 2 – Register IoT Devices

* Create an account on the IoT Registration Server
* Register all IoT devices
* Verify successful device registration
* Enable remote monitoring and management

### Part 3 – Explore IoT Security Features

* Monitor device status remotely
* Control doors remotely
* Enable/disable webcam
* Monitor motion sensor events
* Test smart home automation

---

# 🛠 Technologies Used

* Cisco Packet Tracer
* Internet of Things (IoT)
* Wireless Networking
* DHCP
* WPA2-PSK Wireless Security
* MAC Address Filtering
* IoT Registration Server
* Remote Device Management

---

# 🏡 Network Components

## Router

* Home Wireless Router

## Client

* Home Office PC

## IoT Devices

* Home Siren
* Home Doors
* Motion Sensor
* Webcam

## Registration Server

* ISP IoT Registration Server

---

# 🌐 Network Configuration

| Setting             | Value       |
| ------------------- | ----------- |
| SSID                | HomeNet     |
| Security            | WPA2-PSK    |
| Passphrase          | ciscorocks  |
| IP Assignment       | DHCP        |
| Router IP           | 192.168.0.1 |
| Registration Server | 10.3.0.125  |

---

# 🔐 Security Features Implemented

* WPA2-PSK Wireless Encryption
* Wireless Authentication
* DHCP Address Assignment
* Wireless MAC Address Filtering
* Remote Authentication
* Secure Device Registration
* IoT Access Control

---

# 📋 Configuration Steps

## 1. Connected IoT Devices

Connected the Home Siren to the Home Door using an IoT Custom Cable.

Verified that opening the door activates the siren.

---

## 2. Configured Wireless Connectivity

Each IoT device was configured with:

* SSID: **HomeNet**
* Security: **WPA2-PSK**
* Passphrase: **ciscorocks**
* DHCP enabled

Successfully obtained IP addresses from the **192.168.0.0/24** network.

---

## 3. Configured MAC Address Filtering

Collected MAC addresses from:

* Home Siren
* Home Door
* Motion Sensor
* Webcam

Added each MAC address to the router's Wireless MAC Filter table to allow only trusted devices.

---

## 4. Registered IoT Devices

Created an account on the IoT Registration Server.

Credentials:

**Username**

```
HomeUser
```

**Password**

```
Pa$$w0rd
```

Registered every IoT device with:

* Server Address: **10.3.0.125**
* Remote Server enabled

Verified all devices appeared on the registration server dashboard.

---

# 🧪 Testing Performed

✅ Door activates the siren

✅ IoT devices connect using WPA2

✅ DHCP assigns IP addresses

✅ MAC filtering blocks unauthorized devices

✅ Devices successfully register with server

✅ Remote door control functions properly

✅ Webcam can be enabled/disabled remotely

✅ Motion sensor sends events to server

---

# 📡 IoT Device Functionality

## Home Door

* Remote Open/Close
* Triggers Siren
* Status Monitoring

## Home Siren

* Activated by Door
* Remote Monitoring

## Webcam

* Remote On/Off
* Live Monitoring

## Motion Sensor

* Detects Motion
* Sends Alerts
* Monitoring Only

---

# 📁 Project Structure

```
IoT-Home-Security-Lab/
│
├── README.md
├── IoT Home Security.pkt
├── screenshots/
│   ├── topology.png
│   ├── registration-server.png
│   ├── mac-filter.png
│   ├── wireless-settings.png
│   └── testing.png
└── documentation/
```

---

# 📷 Screenshots

<img width="633" height="359" alt="image" src="https://github.com/user-attachments/assets/19f01543-2c48-4201-b453-38838f1ac286" />


Add screenshots of the following:

* Network Topology
* Wireless Router Configuration
* WPA2 Settings
* MAC Address Filtering
* Registered IoT Devices
* IoT Registration Server Dashboard
* Device Status
* Successful Testing

---

# 🎓 Skills Demonstrated

* Cisco Packet Tracer
* Smart Home Networking
* Wireless Security
* WPA2 Authentication
* DHCP Configuration
* MAC Address Filtering
* IoT Device Configuration
* IoT Registration
* Remote Device Management
* Network Troubleshooting
* Network Security
* IoT Automation

---

# 📚 Learning Outcomes

After completing this lab, I was able to:

* Configure wireless IoT devices
* Secure a wireless network using WPA2
* Implement MAC address filtering
* Configure DHCP for IoT devices
* Register IoT devices with a cloud registration server
* Monitor IoT devices remotely
* Control smart home devices remotely
* Understand practical IoT security concepts

---

# 🚀 Future Improvements

* Add Smart Lights
* Add Smart Thermostat
* Integrate Smart Locks
* Configure Email Alerts
* Add Mobile Device Access
* Implement VLAN Segmentation
* Deploy Firewall Rules
* Enable VPN Remote Access
* Integrate Intrusion Detection System (IDS)

---

# 🏆 Key Concepts

* Internet of Things (IoT)
* Wireless Networking
* Smart Home Security
* WPA2 Encryption
* DHCP
* MAC Filtering
* Cloud Registration
* Remote Monitoring
* Device Authentication
* Network Security

---

# 👨‍💻 Author

**Bayram Guney**

Cybersecurity | Network Security | Cisco Packet Tracer | SOC Analyst | IoT Security
