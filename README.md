# Configuring VLANs and Securing Switch Networks 🌐🔒

## Welcome to My VLAN Adventure! 🚀

In this project, I took a deep dive into the world of **VLANs (Virtual Local Area Networks)** and secure switch configurations. Using **Cisco Packet Tracer**, I designed and implemented a secure cloud network by configuring VLANs, trunks, port security, and advanced features like DHCP snooping and BPDU guard. If you’re curious about how to segment networks for better performance and security, this guide will walk you through the process step-by-step.

---

## What Was I Doing? 🤔

This assignment was all about creating a secure and efficient network topology using VLANs and advanced switch configurations. Here’s what I accomplished:
- **Cabled and Initialized Devices**: Set up routers, switches, and PCs as per the topology diagram.
- **Configured VLANs**: Created VLANs for different purposes (e.g., Management, Native) and assigned devices to them.
- **Secured Ports**: Enabled port security, disabled unused ports, and configured DHCP snooping to prevent malicious activity.
- **Implemented Advanced Features**:
  - Enabled **PortFast** and **BPDU Guard** to optimize and protect STP (Spanning Tree Protocol).
  - Verified end-to-end connectivity between devices.

Through hands-on exercises, I learned how to configure trunking, manage access ports, and troubleshoot common issues like DHCP failures due to sticky learning.

---

## Tools Used 🔧

1. **Cisco Packet Tracer**: Simulated a real-world network environment to design, configure, and test VLAN setups.
2. **VLAN Commands**: Leveraged Cisco IOS commands to create, name, and assign VLANs to interfaces.
3. **Switch Security Features**:
   - Enabled **port security** to restrict unauthorized devices.
   - Configured **DHCP snooping** to block rogue DHCP servers.
   - Implemented **PortFast** and **BPDU Guard** for faster convergence and protection against misconfigurations.
4. **Verification Tools**:
   - Used commands like `show vlan`, `show ip dhcp snooping`, and `show port-security` to validate configurations.

---

## Skills Gained 💡

- **VLAN Configuration**:
  - Learned how to segment networks logically using VLANs.
  - Assigned devices to specific VLANs for better traffic management.
- **Trunking and Native VLANs**:
  - Configured trunk ports and set the Native VLAN to ensure seamless communication.
- **Switch Security**:
  - Disabled unused ports and moved them to an isolated VLAN (e.g., VLAN 999).
  - Enabled sticky MAC address learning to dynamically secure ports.
- **DHCP Snooping**:
  - Prevented rogue DHCP servers from assigning unauthorized IP addresses.
  - Configured trusted and untrusted ports with rate limits.
- **STP Optimization**:
  - Enabled PortFast on access ports to reduce delays during device connections.
  - Protected the network from misconfigurations using BPDU Guard.
- **Troubleshooting**:
  - Diagnosed why certain ports failed to get DHCP addresses due to sticky learning configurations.
  - Explored aging types (absolute vs. inactivity) for port security.

---

## Fun Highlights 🎉

- **"VLAN Magic"**: Created VLAN 10 (Management) and VLAN 333 (Native), then watched how devices communicated across them.
- **"Port Security Wizardry"**: Enabled port security on F0/6 and F0/18, ensuring only authorized devices could connect.
- **"DHCP Snooping Detective"**: Blocked rogue DHCP servers and verified bindings using `show ip dhcp snooping binding`.
- **"BPDU Guard Hero"**: Protected the network from potential loops by enabling BPDU Guard on VLAN 10 access ports.
- **"Sticky Learning Mystery"**: Discovered why PC-B on port F0/18 couldn’t get an IP address when sticky learning was enabled.

---

## Why Should You Care? 🌟

Understanding VLANs and switch security is crucial for modern networking. These skills help you:
- **Segment Networks**: Improve performance and reduce congestion by isolating traffic.
- **Enhance Security**: Protect your network from unauthorized access and malicious attacks.
- **Optimize Performance**: Use features like PortFast and BPDU Guard to ensure smooth operation.
- **Troubleshoot Issues**: Gain confidence in diagnosing and resolving network problems.

Whether you’re managing enterprise networks, securing IoT devices, or optimizing cloud infrastructure, these concepts are foundational.

---

## Final Thoughts 📝

This project was both challenging and rewarding, blending theory with practical application. It gave me hands-on experience in designing secure networks and troubleshooting common issues. By the end, I had a fully functional VLAN setup, a deeper understanding of switch security, and a newfound appreciation for the complexity of modern networks.

So, if you’re ready to explore VLANs and secure switch configurations, fire up Cisco Packet Tracer, follow along with this guide, and start building your own secure network. Who knows? You might just discover a hidden passion for networking!

Happy Networking! 🌐🔒
