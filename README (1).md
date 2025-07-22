# 🏠 Home Network Documentation - NSA-590 Lab 5

## ✅ Part 1: Network Device Inventory

| Device # | Device Type   | Make & Model             | Serial Number   | Physical Location     | Purchase Date  | Warranty Info        |
|----------|----------------|--------------------------|------------------|------------------------|-----------------|-----------------------|
| 1        | Router         | Bell Giga Hub            | BELLGH123456     | Living Room near TV   | July 6, 2025    | Bell-provided         |
| 2        | Smartphone     | Samsung S23 FE           | SAMS23FE987654   | Bedroom 1             | September 2024 | 1-Year Warranty       |
| 3        | Smartphone     | Samsung S23              | SAMS23987654     | Bedroom 2             | August 2022    | Expired               |
| 4        | Smart TV       | Samsung Smart TV (2022)  | SAMTV202201      | Living Room            | January 2022   | Expired               |
| 5        | Laptop         | HP Victus 15             | HPVIC072024      | Bedroom 1              | July 2024      | 2-Year Warranty       |
| 6        | Printer        | Canon PIXMA TS3520         | CANONTS3520XX    | Dining Area            | May 2023       | 1-Year (estimated)    |
| 7        | Smartphone     | iPhone 15 Pro            | IPH15PRODEC24    | Bedroom 2              | December 2024 | AppleCare (assumed)   |

---

## 🏠 Part 2: Physical Network Layout

**Device Locations:**

- **Living Room:** Bell Giga Hub Router, Samsung Smart TV (Ethernet)
- **Bedroom 1:** Samsung S23 FE, HP Victus Laptop (Wi-Fi)
- **Bedroom 2:** Samsung S23, iPhone 15 Pro (Wi-Fi)
- **Dining Area:** Canon PIXMA TS3520 Printer (Wi-Fi)

**Cabling:**

- Ethernet: Wall → Router (Bell Giga Hub)
- Ethernet: Router → Samsung Smart TV

All other devices connect wirelessly.

---

## 🌐 Part 3: Logical Network Topology

**IP Addressing Scheme:**

| Device               | IP Address       | Assignment | Notes             |
|----------------------|------------------|------------|--------------------|
| Router               | 192.168.10.1     | Static     | Gateway            |
| Samsung Smart TV     | 192.168.10.2     | Static     | Ethernet           |
| HP Victus Laptop     | 192.168.10.10    | DHCP       | Wi-Fi              |
| Samsung S23 FE       | 192.168.10.11    | DHCP       | Bedroom 1          |
| Samsung S23          | 192.168.10.12    | DHCP       | Bedroom 2          |
| iPhone 15 Pro        | 192.168.10.13    | DHCP       | Bedroom 2          |
| Canon PIXMA TS3520     | 192.168.10.20    | Static     | Dining Area        |

**IP Management:** IPs managed through Bell Giga Hub admin panel. Static leases are assigned to key devices.

---

## ⚙️ Part 4: Firmware / Software Versions

| Device         | Firmware / OS Version      | Last Updated |
|----------------|-----------------------------|---------------|
| Router         | Bell Giga Hub OS v1.3       | July 2025     |
| HP Victus      | Windows 11 (23H2)           | July 2025     |
| Samsung S23 FE | One UI 6.1 / Android 14     | July 2025     |
| Samsung TV     | Tizen OS v7                 | June 2025     |

---

## 🔐 Part 5: Security and Access Info

| Security Feature        | Status / Tool Used             |
|--------------------------|----------------------------------|
| Wi-Fi Encryption         | WPA / WPA2 Mixed Mode            |
| Firewall                 | Default router firewall enabled  |
| Antivirus (Laptop)       | Windows Defender                 |
| VPN                     | Not in use                       |
| Password Storage         | Google Password Manager          |

---

## 📘 Notes

- Documentation created for NSA-590 Technical Writing and Documentation Lab 5.
- All private network IPs and serials have been modified for privacy.