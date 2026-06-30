# 🌐 Project 01 - VLAN and Switching

## 📖 Background

A small company consists of three departments: IT, Finance, and Marketing. To improve network security and management, each department is placed in a separate VLAN using a single Cisco switch.

---

## 🎯 Objectives

- Create VLAN 10, VLAN 20, and VLAN 30.
- Assign switch ports to the correct VLAN.
- Verify VLAN configuration.
- Test communication between devices in the same VLAN.

---

## 📂 Project Resources

- 📷 Topology Diagram → `images/`
- ⚙️ Configuration Files → `configs/`
- 💻 Cisco Packet Tracer File → `vlan-and-switching.pkt`

---

## 💡 Lessons Learned

During this project, I learned:

- How to create VLANs on a Cisco switch.
- How to assign access ports to different VLANs.
- How VLANs separate broadcast domains.
- How to verify VLAN configuration using Cisco IOS commands.

---

## 📚 Commands Used

```bash
show vlan brief
show running-config
show mac address-table
```

---

## 🚀 Future Improvements

- Add trunk links between multiple switches.
- Implement Inter-VLAN Routing.
- Configure DHCP for each VLAN.
