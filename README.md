# OSI (Open System Interconnect)

## 1. Explanation of OSI Layer

Open System Interconnect (OSI) was developed by the International Organization for Standardization (ISO) and introduced in 1984. It consists of seven layers:

- **Application Layer**
- **Presentation Layer**
- **Session Layer**
- **Transport Layer**
- **Network Layer**
- **Data Link Layer**
- **Physical Layer**

---

## 2. Which Layer is Responsible for Reliable Connection?

The **Transport Layer** guarantees a reliable end-to-end connection.

---

## 3. Protocols in Each Layer of the OSI Model

### **Application Layer**

Responsible for providing an interface for the user to interact with application or network services.

- **Examples**: HTTP (Web Browser), Telnet

### **Presentation Layer**

Defines a standard format for the data.

- **Major Functions**:
  - **Encoding-Decoding**: Examples include AVI (video), WAV (voice), JPEG (graphics), ASCII (text)
  - **Encryption-Decryption**

### **Session Layer**

Establishes, maintains, and terminates sessions.

- **Key Component**: Session ID is used to identify sessions or interactions.
- **Examples**: Remote Procedure Call (RPC), AppleTalk Session Protocol

### **Transport Layer**

Provides a data delivery mechanism between applications in the network.

- **Major Functions**:
  - Identifying Service
  - Multiplexing & De-multiplexing
  - Segmentation
  - Error Correction
  - Flow Control
- **Protocols**:
  - **TCP (Transmission Control Protocol)**
    - Connection-oriented
    - Supports acknowledgments
    - Reliable communication
    - Protocol number: 6
    - Examples: HTTP, FTP, SMTP
  - **UDP (User Datagram Protocol)**
    - Connectionless
    - No support for acknowledgments
    - Unreliable communication
    - Protocol number: 17
    - Examples: DNS, DHCP, TFTP

### **Network Layer**

Provides logical addressing and path determination (routing).

- **Protocols**:
  - **Routed Protocols**: Used to carry user data.
  - **Routing Protocols**: Used to perform path determination and routing.

### **Data Link Layer**

Facilitates communication with the Network Layer.

- **Key Component**: Media Access Control (MAC)
  - Provides reliable transit of data across a physical link.

### **Physical Layer**

Defines the electrical, mechanical, and functional specifications for communication between network devices.
