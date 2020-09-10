# OSPF Routing

### There are 3 types of routing: 
**Static | Default | Dynami**

All three have their **_Advantages_** and **_Disadvantages_**

# What is Open Shortest Path First (OSPF)?

 **_Open Shortest Path First_** is one of the IP family routing protocols and is also an interior 
    gateway for the internet **_IGP_**.  
 
* The protocol recalculates routes when network topology changes, using the Dijkstra algorithm, and   
  minimises the routing protocol traffic that it generates.
* It provides support for multiple paths of equal cost.
* It provides a multi-level hierarchy (two-level for OSPF) called "area routing," so that information  
  about the topology within a defined area of the AS is hidden from routers outside this area. This enables  
  an additional level of routing protection and a reduction in routing  protocol traffic.
* All protocol exchanges can be authenticated so that only trusted routers can join in the routing exchanges for the AS.  

# OSPF Version 3 (OSPFv3)

OSPF version 2 (OSPFv2) is used with IPv4. OSPFv3 has been updated for compatibility with IPv6's 128-bit address space.   
However, this is not the only difference between OSPFv2 and OSPFv3. Other changes in OSPFv3, as defined in RFC 2740, include

* protocol processing per-link not per-subnet
* addition of flooding scope, which may be link-local, area or AS-wide
* removal of opaque LSAs
* support for multiple instances of OSPF per link
* various packet and LSA format changes (including removal of addressing semantics).  

**_Both OSPFv2 and OSPFv3 are fully supported by DC-OSPF._**

https://www.metaswitch.com/knowledge-center/reference/what-is-open-shortest-path-first-ospf
