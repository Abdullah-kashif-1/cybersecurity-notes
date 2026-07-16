# 💻 MAC Address Commands (Windows & Linux)

## 🔹 Introduction
MAC Address commands are used to **check and manage network interfaces** in a system.  
These commands help in:
- Identifying devices  
- Troubleshooting network issues  
- Understanding system connectivity  

---

## 🪟 Windows Commands

### 🔸 1. getmac
Shows the MAC address of your device.


getmac


👉 Simple and quick output  
👉 Best for beginners  

---

### 🔸 2. ipconfig /all
Displays detailed network information.


ipconfig /all


👉 Shows:
- MAC Address (Physical Address)  
- IP Address  
- DNS Server  
- Adapter details  

---

### 🔸 3. get-netadapter (PowerShell)
Used in PowerShell for advanced network details.


get-netadapter


👉 Clean and structured output  
👉 Useful for professionals  

---

## 🐧 Linux Commands

### 🔸 1. ifconfig
Traditional command to view network interfaces.


ifconfig


👉 MAC address appears as **ether**  
👉 May not be available in latest systems  

---

### 🔸 2. ip a
Modern and most commonly used command.


ip a


👉 Recommended for Linux users  
👉 Shows all network interfaces  

---

### 🔸 3. ip link show
Displays detailed information about interfaces.


ip link show


👉 Shows MAC address clearly  
👉 Useful for troubleshooting  

---

## 🔹 Summary Table

| Command           | OS       | Purpose                     |
|------------------|----------|-----------------------------|
| getmac           | Windows  | Quick MAC address check     |
| ipconfig /all    | Windows  | Detailed network info       |
| get-netadapter   | Windows  | Advanced info (PowerShell)  |
| ifconfig         | Linux    | Traditional command         |
| ip a             | Linux    | Modern command              |
| ip link show     | Linux    | Interface details           |

---

## 🔹 Key Takeaways
- MAC Address is essential for **device identification**  
- Commands help in **real-world networking tasks**  
- `ip a` and `ipconfig /all` are most important  

---

## 🔹 Tags
#CyberSecurity #Networking #Linux #Windows #LearningJourne
