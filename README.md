Project Overview

In this project I wanted to imitate an ISP traffic flow and design traffic flow between 2 ISPs
The usage of MikroTik virtual routers is fairly limited because so is my RAM and CPU, however, it's completely enoguh to study L3 and L4 protocols and modern solutions.

The devices at the end might look like comuters and in the simulator they are, however, they represent seperate customer LANs that are connected to the ISP edge router. 

Technologies Used

    Hardware: each ISP has 5 routers, 2 Prover edge and 4 redundancy routers
    ISP uses OSPF and MLPS to ensure traffic gets from both edge routers with fastest paths and the middle routers can benefit from MLPS. 

Future improvements

    All thats left is configuring OSPF, BGP, CGNAT for ISP-A and configuring ISP-B
