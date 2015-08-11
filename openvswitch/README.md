OpenVSwitch
===

Introduction:
------------

OpenVswitch is a opensource Openflow capable virtual switch. typically used to interconnect virtual machines.

Features:
------
    1. VLAN tagging with 802.1q trunkning
    2. STP
    3. LACP
    4. Port Mirroring
    5. Flow Export (netflow,sflow,ipfix)
    6. tunneling (GRE, VXLAN, IPSEC)
    7. QoS Control

Config Examples:
------

Create a bridge:

    ovs-vsctl addbr mybridge

Add a port to the bridge

    ovs-vsctl add-port mybridge eth0

Show a bridge details:

    ovs-vsctl show

To make the brige up:

    ifconfig mybridge up



