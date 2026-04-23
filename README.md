# SDN Learning Switch Controller

## 📌 Abstract
This project implements a Software Defined Networking (SDN) Learning Switch using the Ryu controller and Mininet emulator.

The switch initially does not know MAC addresses, so it sends packets to the controller. The controller learns MAC addresses dynamically and installs flow rules for efficient packet forwarding.

---

## 🎯 Objective
- Implement MAC address learning
- Install dynamic flow rules
- Validate packet forwarding
- Inspect flow tables

---

## 🛠️ Requirements

```bash
sudo apt update
sudo apt upgrade -y
