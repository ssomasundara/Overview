# Overview
This github is for making technology specific extensions to the ONF Core Information Model (ONF TR-512) available.

The following types of extensions are distinguished:
- Interfaces : Similar to management of network layers at the ports of devices (attached to LayerProtocol class)
- Profiles : Similar to management of functionalities valid for entire devices (attached to Profile class)

### Interfaces
- [airInterface](../../../airInterface) : Physical layer of the microwave radio interface
- [ethernetContainer](../../../ethernetContainer) : Transport resource for Ethernet
- [hybridMwStructure](../../../hybridMwStructure) : Structuring of a microwave radio interface into multiple TDM and a single Ethernet segment
- [ipInterface](../../../ipInterface) : IPv4 interface according to IETF RFC 791
- [macInterface](../../../macInterface) : Ethernet MAC interface according to IEEE 802.1
- [pureEthernetStructure](../../../pureEthernetStructure) : Structuring of a microwave radio interface into a single Ethernet segment
- [tdmContainer](../../../tdmContainer) : Transport resource for TDM
- [vlanInterface](../../../vlanInterface) : VLAN interfaces according to IEEE 802.1Q and 802.1ad
- [wireInterface](../../../wireInterface) : Physical layer of an Ethernet PHY interface according to IEEE 802.3

### Profiles
- [l3vpnProfile](../../../l3vpnProfile) : Layer 3 Virtual Private Networks
- [qosProfile](../../../qosProfile) : Quality of Service based on 802.1p, MPLS Exp and IP DSCP
- [wredProfile](../../../wredProfile) : WRED (Weighted Random Early Detection)

### Equipment
- [wireEquipment](../../../wireEquipment) : Equipment for an Ethernet PHY interface according to IEEE 802.3
