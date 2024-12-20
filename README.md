# Network-Programming-with-Python

### 1. **Does every computer have an IP address?**  
Yes, every computer connected to a network (such as the internet or a local area network) must have an IP (Internet Protocol) address. This address is essential for identifying the device and enabling communication with other devices on the network.

### 2. **Is it unique?**  
- **Public IP Address**: Unique globally. Assigned by your Internet Service Provider (ISP), this address allows devices to communicate over the internet. Only one device or router in a network gets a public IP.
- **Private IP Address**: Unique within a local network. For devices connected to the same network (e.g., your home Wi-Fi), the router assigns unique private IPs to each device.

### 3. **What are ports?**  
Ports are virtual points where network connections start and end. They help in routing data to specific processes or applications on a computer. Each port is identified by a number (e.g., 80 for HTTP, 443 for HTTPS). For example:
- **Port 80**: Used by web servers for HTTP.
- **Port 22**: Used for SSH.

Think of IP addresses as "house addresses" and ports as "specific rooms in the house."

---

### 4. **How to check your MacBook's IP address?**  

#### **For a Private IP Address (Local Network):**  
1. **Open System Settings:**
   - Go to **Apple menu** > **System Settings** (or **System Preferences** on older macOS).
   - Click **Network**.
2. **Check your active connection:**
   - For Wi-Fi: Select your Wi-Fi network, and you'll see your IP address under "Status" or "Details."
   - For Ethernet: Click on the connected network, and the IP address will appear.

#### **For a Public IP Address (Internet):**  
1. **Using a web browser:**
   - Visit a website like [https://whatismyipaddress.com](https://whatismyipaddress.com).
2. **Using Terminal:**
   - Open **Terminal** and type:
     ```bash
     curl ifconfig.me
     ```
   - Press **Enter**, and it will display your public IP address.

Let me know if you'd like further assistance!
