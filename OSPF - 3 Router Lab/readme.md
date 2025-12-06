OSPF 3-Router Lab
📌 Overview

This lab demonstrates OSPF adjacency formation, neighbor discovery, and route exchange using a 3-router topology.

Routers:

R1

R2

R3

Each router participates in OSPF Area 0 (or whichever areas you used).

📡 Topology

(Insert your topology screenshot as topology.png)

🔧 Objectives

Configure IP addresses on all routers

Enable OSPF process

Advertise loopbacks and connected networks

Verify neighbor adjacencies

Validate OSPF routes in the routing table

🧪 Commands Used

Key verification commands:

show ip ospf neighbor
show ip route ospf
show ip protocols
show ip ospf interface

📈 Results

All three routers formed full OSPF adjacencies

All loopback prefixes are reachable

Convergence confirmed via routing table and ping tests

📁 Configuration Files

R1.txt

R2.txt

R3.txt

📝 Notes / What I Learned

(Write 2–3 bullets about what you learned, for example:)

How OSPF forms adjacencies using hello packets

How DR/BDR elections occur on multi-access networks

How network statements and wildcard masks work

How LSAs propagate routes across the topology
