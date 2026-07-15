# 📌 MAC Address (Media Access Control Address)

## 🔹 What is a MAC Address?
A **MAC Address (Media Access Control Address)** is a **unique hardware identifier** assigned to a device’s network interface card (NIC).  

It is used to identify devices **inside a local network (LAN)** so they can communicate with each other.

👉 Think of it like:
- IP Address = Your home address (can change)  
- MAC Address = Your fingerprint (permanent & unique)  

---

## 🔹 How MAC Address Works
When a device sends data in a network:
1. The data is broken into small units called **frames**
2. Each frame contains:
   - Source MAC Address  
   - Destination MAC Address  
3. The network uses these MAC addresses to deliver data to the correct device  

👉 This process happens at the **Data Link Layer (Layer 2)** of the OSI Model.

---

## 🔹 Key Features of MAC Address
- ✅ **Unique for every device** (no two devices should have same MAC)  
- ✅ **Assigned by manufacturer**  
- ✅ **Permanent (hardware-based)**  
- ✅ Works on **Layer 2 (Data Link Layer)**  
- ✅ Used only in **Local Area Network (LAN)**  

---

## 🔹 Format of MAC Address

Example:

00:1A:2B:3C:4D:5E


### 🔸 Breakdown:
- Total = **12 hexadecimal digits**  
- Written in **6 pairs (bytes)**  
- Each pair = **2 hex digits (0-9, A-F)**  

👉 Example breakdown:

00 : 1A : 2B : 3C : 4D : 5E
│ │
│ └── Device Identifier
└──────── Manufacturer ID (OUI)


---

## 🔹 Types of MAC Address

### 1. Unicast
- One-to-one communication  
- Data sent to a single device  

### 2. Broadcast
- One-to-all communication  
- Sent to every device in network  
- Example:

FF:FF:FF:FF:FF:FF


### 3. Multicast
- One-to-group communication  
- Sent to a group of devices  

---

## 🔹 MAC Address vs IP Address

| Feature        | MAC Address              | IP Address              |
|---------------|--------------------------|--------------------------|
| Type          | Hardware-based           | Software-based           |
| Permanence    | Permanent                | Can change               |
| Layer         | Data Link Layer (L2)     | Network Layer (L3)       |
| Use           | Local network (LAN)      | Internet communication   |

---

## 🔹 Why MAC Address is Important?
- 🔐 Helps identify devices uniquely  
- 🌐 Enables communication inside LAN  
- 🛡️ Used in **network security (MAC filtering)**  
- 📡 Required for data delivery at Layer 2  

---

## 🔹 How to Check MAC Address

### 🖥️ Windows:

getmac

or

ipconfig /all


### 🐧 Linux:

ifconfig

or

ip a


---

## 🔹 Real-Life Example
When your phone connects to WiFi:
- Router checks your **MAC Address**  
- Then allows or blocks access  
- Sends data directly to your device using MAC  

---

## 🔹 Summary
A MAC Address is a **unique hardware identifier** that helps devices communicate inside a local network.  

👉 It works behind the scenes but is **essential for networking and cybersecurity**.

---

## 🔹 Tags
#Networking #CyberSecurity #MACAddress #LearningJourney
