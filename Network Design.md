+----------------------------------+------------------------+----------+
| ![](vertopal_                    |                        |          |
| 9b63dc858dc94a67b4ca6e4ba984a5b5 |                        |          |
| /media/image1.png){width="2.4in" |                        |          |
| height="0.5881944444444445in"}   |                        |          |
|                                  |                        |          |
| SCHOOL OF INFORMATION AND        |                        |          |
| TECHNOLOGY                       |                        |          |
+----------------------------------+------------------------+----------+
| NAME: Hyra Cayambas, Dale        | DATE PERFORMED: 11/27  | /50      |
| Matthew Boquiren                 |                        |          |
+----------------------------------+------------------------+----------+
| Section: IDC1                    | DATE SUBMITTED: 12/04  |          |
+----------------------------------+------------------------+----------+

# SYSADM1 -- Capacity Management & Planning

**Part 2. Network Scalability Analysis**

Recall the e-commerce website scenario we discussed earlier. Given the
expected surge in traffic, analyze the provided network topology
diagram. Identify potential bottlenecks and areas where scalability
might be a concern. Propose specific strategies to improve the
network\'s scalability and performance to ensure a seamless user
experience during the peak traffic period. Consider factors such as
increased user demand, new applications, and security threats.

![](vertopal_9b63dc858dc94a67b4ca6e4ba984a5b5/media/image2.bin){width="5.049483814523184in"
height="3.8229166666666665in"}

**Proposed Diagram:\
**

![](vertopal_9b63dc858dc94a67b4ca6e4ba984a5b5/media/image3.png){width="8.020833333333334in"
height="5.123127734033246in"}

**Network Analysis**

**Potential Bottlenecks:**

1.  **Bandwidth Limitations:** Insufficient bandwidth could result in
    > delays during peak traffic, especially for multimedia-rich
    > content.

2.  **Overloaded Servers:** A single server or limited cluster of
    > servers handling requests might become a bottleneck.

3.  **Data Flow Through Firewalls:** If firewall rules are not optimized
    > for high traffic, they could slow down data processing.

4.  **Single Points of Failure:** Centralized systems, such as databases
    > or key infrastructure nodes, may pose risks.

5.  **Latency in CDN Usage:** Poorly configured Content Delivery
    > Networks (CDNs) might result in higher latency for users in
    > certain geographic locations.

**Security Risks:**

1.  **DDoS Attacks:** High traffic may mask distributed
    denial-of-service attacks, straining resources.

2.  **Outdated Security Protocols:** Insufficient encryption or outda
    ted security mechanisms could expose the network to breaches.

3.  **Unauthorized Access:** Weak access controls might lead to
    unauthorized usage during peak periods.

**Scalability Planning**

1.  **Network Optimization**:

    -   **Layer 3 Link Aggregation**: Enhancing bandwidth capacity by
        bundling multiple links ensures faster data flow and fault
        tolerance between core switches and access layers.

    -   **Firewall Load Balancing**: Distribute incoming traffic across
        multiple firewalls to prevent bottlenecks during traffic surges.

2.  **Hardware Scalability**:

    -   **Modular Switches**: Use modular core switches to allow future
        expansion without replacing existing equipment.

    -   **Redundant Links**: Add more redundant paths between routers,
        firewalls, and switches to improve fault tolerance and
        scalability.

3.  **Traffic Management**:

    -   **Quality of Service (QoS)**: Prioritize critical applications,
        ensuring that high-priority traffic receives bandwidth during
        peak loads.

    -   **Dynamic Routing Protocols**: Implement protocols like OSPF or
        BGP to optimize routing and prevent delays.

4.  **Security Enhancements**:

    -   **Deep Packet Inspection (DPI)**: Deploy advanced firewalls
        capable of DPI for better threat detection and management.

    -   **Distributed Denial of Service (DDoS) Protection**: Integrate
        DDoS mitigation systems to handle unexpected malicious traffic.

5.  **Server Expansion**:

    -   Cluster servers in the access layers for load balancing and
        failover capabilities.

    -   Introduce virtualized environments (e.g., VMware, Hyper-V) for
        scalable computing.

**Evaluation of Solutions**

1.  **Proposed Scalability Solutions**:

    -   **Link Aggregation**: Bundling links between core switches
        improves data throughput and provides redundancy, ensuring
        seamless scalability during high demand.

    -   **Modular Hardware**: Core and access switches with modular
        designs enable cost-effective expansion, ensuring the network
        can grow with user demands.

    -   **Firewall Enhancements**: Distributing traffic across multiple
        firewalls reduces bottlenecks and improves resilience.

2.  **Benefits**:

    -   **Performance Boost**: Layer 3 Link Aggregation and QoS ensure
        smooth traffic flow, even during peak periods.

    -   **Redundancy**: Redundant paths and modular hardware reduce the
        risk of system failures.

    -   **Future-Proofing**: Scalability strategies allow for
        incremental upgrades without overhauling the entire network.

3.  **Potential Drawbacks**:

    -   **Initial Costs**: Upgrading to modular hardware and adding
        firewalls might increase upfront expenses.

    -   **Configuration Complexity**: Dynamic routing protocols and
        advanced QoS policies require expert configuration and
        monitoring.

4.  **Justification**:

    -   The proposed network design is a robust, scalable, and
        future-proof solution that balances performance, security, and
        cost. Layer 3 Link Aggregation and modular switches enable
        seamless scalability and bandwidth growth. Redundant links and
        firewalls improve reliability by eliminating single points of
        failure, ensuring uninterrupted service during failures or
        attacks. Advanced security measures, such as Deep Packet
        Inspection (DPI) and DDoS mitigation, protect the network from
        evolving threats. While the upfront costs are significant, the
        design minimizes long-term expenses through modular upgrades and
        reduced downtime. Its industry-standard components ensure
        compatibility and ease of implementation, while the architecture
        supports future expansion without major overhauls, making it a
        justified and comprehensive solution

  ------------------------------------------------------------------------------
  Criteria          Excellent \| 10pts Good \| 7pts        Needs Improvement \|
                                                           4pts
  ----------------- ------------------ ------------------- ---------------------
  **Network         Accurately         Identifies key      Identifies some basic
  Analysis**        identifies         network components  network components
                    potential          and some potential  but lacks a
                    bottlenecks,       bottlenecks.        comprehensive
                    security risks,                        analysis.
                    and capacity                           
                    limitations.                           

  **Scalability     Proposes multiple  Proposes some       Proposes limited
  Planning**        relevant solutions relevant            scalability
                    and provides       scalability         strategies.
                    detailed           strategies but      
                    explanations,      lacks detail.       
                    including                              
                    potential                              
                    drawbacks and                          
                    benefits.                              

  **Evaluation of   Proposes           Provides a basic    Does not evaluate the
  Solutions**       comprehensive      evaluation of the   proposed solutions or
                    scalability        proposed solutions, provides a
                    strategies,        but lacks depth.    superficial
                    including specific                     evaluation.
                    recommendations                        
                    for hardware                           
                    upgrades, software                     
                    configurations,                        
                    and network                            
                    optimizations.                         

  **Proposed        Provides a         Provides a basic    Does not provide a
  Design**          detailed and       design but lacks    clear and detailed
                    well-justified     specific details    design.
                    design, including  and justifications. 
                    network diagrams,                      
                    configuration                          
                    details, and                           
                    implementation                         
                    plans.                                 

  **Evaluation and  Provides a         Provides a basic    Does not evaluate the
  Justification**   thorough           evaluation of the   proposed solutions or
                    evaluation of the  proposed solutions, provides a
                    proposed           but lacks depth.    superficial
                    solutions,                             evaluation
                    considering                            
                    factors like cost,                     
                    complexity, and                        
                    potential impact.                      

  Score:                                                   /50
  ------------------------------------------------------------------------------
