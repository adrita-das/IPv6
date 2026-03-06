## 🌐 IPv6 Network Configuration Lab






A hands-on networking lab demonstrating IPv6 addressing and connectivity using Cisco Packet Tracer.
This project focuses on configuring IPv6 on routers and end devices and verifying communication between hosts.

## 📖 Project Description

IPv6 is the next generation Internet Protocol designed to replace IPv4 due to address exhaustion.
This project demonstrates how IPv6 networks are configured and tested in a small simulated environment.

- The lab includes:

- Router IPv6 configuration

- IPv6 address assignment

- End device configuration

- Connectivity testing using ping


## ⚙️ Router Configuration

```
enable
configure terminal
ipv6 unicast-routing

interface g0/0
ipv6 address 2001:DB8:1::1/64
no shutdown
```

## 💻 PC Configuration

#### PC0

```
IPv6 Address : 2001:DB8:0:1::2/64
```
#### PC1
```
IPv6 Address : 2001:DB8:0:2::2/64

```

#### PC3

```
IPv6 Address : 2001:DB8:0:3::2/64
```

## 🔍 Connectivity Test

Test communication using ping.

```
2001:DB8:0:1::2/64 #PC0
2001:DB8:0:2::2/64 #PC1
2001:DB8:0:3::2/64 #PC2
```
Successful replies confirm the IPv6 network is functioning correctly.

## 📚 Learning Resources

- https://www.youtube.com/@JeremysITLab
