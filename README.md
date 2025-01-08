![logo](https://github.com/allwinrajan/OSI-REFERENCE-MODEL/blob/db0659f62915e042a583421425f031be879dbd89/Layering%20Diagram.png)
### **OSI Reference Model 🌐**

---

**Layer 1: Physical Layer 🧩**
- **Responsibility**: Establishes the actual physical connection among devices.
- **Data Representation**: Information is transmitted in the form of **bits**.
- **Layer 1 Devices**: Hub, Modem, Repeater, Cables, etc.
- **Key Points**: Transmits raw data over a physical medium.  

---

**Layer 2: Data Link Layer 🔗**
- **Responsibility**: Ensures node-to-node data transfer and error-free delivery over the physical layer.
- **Sub-Layers**:  
  1. **LLC (Logical Link Control)**  
  2. **MAC (Media Access Control)**
- **Key Points**: Encapsulates the sender's and receiver's MAC address in the frame header, ensuring secure data transfer.
- **Layer 2 Devices**: Switches, Bridges.
- **Key Protocols**: Ethernet, PPP (Point-to-Point Protocol).

---

**Layer 3: Network Layer 🛣️**
- **Responsibility**: Manages packet routing, ensuring data is transferred from one host to another.
- **Key Tasks**: Determines the shortest path for data transmission over available routes.
- **Layer 3 Devices**: Routers, Layer 3 Switches.
- **Key Protocols**: IP (Internet Protocol), ICMP (Internet Control Message Protocol), ARP (Address Resolution Protocol).

---

**Layer 4: Transport Layer 🚚**
- **Responsibility**: Provides end-to-end communication and reliable data transfer between devices.
- **Data Representation**: The data is called **segments**.
- **Key Functions**: Ensures error correction, segmentation, flow control, and acknowledgment of successful data transfer.
- **Key Protocols**: TCP (Transmission Control Protocol), UDP (User Datagram Protocol).

---

**Layer 5: Session Layer 📅**
- **Responsibility**: Establishes, manages, and terminates communication sessions between two devices.
- **Key Functions**: Manages dialogs, keeping communication organized and session-based.
- **Key Protocols**: NetBIOS, PPTP (Point-to-Point Tunneling Protocol).

---

**Layer 6: Presentation Layer 🎨**
- **Responsibility**: Converts data from the application layer into a readable format and handles data encryption/decryption.
- **Key Functions**: Data translation, compression, and encryption.
- **Key Protocols**: JPEG, MPEG, SSL/TLS (for encryption).

---

**Layer 7: Application Layer 🖥️**
- **Responsibility**: Provides services directly to end-users and handles network resource access.
- **Key Functions**: Offers network services like email, file transfer, and web browsing.
- **Key Protocols**: SMTP (Simple Mail Transfer Protocol), DNS (Domain Name System), FTP (File Transfer Protocol), HTTP (HyperText Transfer Protocol).

---

**by Alvin Irudaya Rajan**
