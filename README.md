# CTI_Assignment_Ruchitaben_Patel

## Task 3: Diamond Model Vertex Extraction

The following analysis is based on the CISA Advisory **AA22-110A: 2022 Russian Cyber Activity Targeting U.S. Critical Infrastructure**.

| **Vertex**     | **Extracted Information**                                           | **Supporting Evidence from Report**                                                                                              |
|----------------|---------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------|
| **Adversary**  | Russian state-sponsored cyber actors (APT29, Sandworm)             | The CISA report identifies APT29 and Sandworm as Russian cyber actors affiliated with the Russian intelligence services (SVR, GRU). |
| **Infrastructure** | Russian-controlled infrastructure (VPN services, RATs, IT/OT systems) | The report highlights the use of VPNs, RATs, and vulnerabilities in critical infrastructure (IT/OT systems) exploited by Russian actors. |
| **Capability** | Exploiting vulnerabilities, credential dumping, ransomware, data exfiltration | The report identifies techniques like exploiting vulnerabilities, credential dumping, ransomware deployment, and data exfiltration. |
| **Victim**     | U.S. critical infrastructure organizations (energy, communications, manufacturing) | CISA focuses on attacks against U.S. critical infrastructure sectors including energy, communications, and manufacturing. |

---

## Task 5: Threat Actor Profile Summary

The targeted threat actor, which was assessed in this report, is an affiliated cyber group sponsored by a Russian state, namely **APT29 (Cozy Bear)** and **Sandworm**. These teams are part of the **SVR (Russian Foreign Intelligence Service)** and the **GRU (Russian Military Intelligence)**, and have been engaged in cyber attacks against critical American infrastructure.

They mainly use these vulnerabilities as their attack vector, including the **vulnerability**. The attackers gain access to victim networks without authorization by using **Remote Access Trojans (RATs)** and **VPN services**. Upon entry, they engage in **credential dumping** and install **ransomware** to disrupt and steal sensitive data.

### Diamond Model Analysis:
The opponent here is a **Russian state-sponsored cyber-unit**, which is known for complex attacks against critical infrastructure. They have a compromised infrastructure of **VPNs**, **RATs**, and **IT/OT systems vulnerabilities**. Their general skills include exploiting popular vulnerabilities, mounting credential-based attacks, installing ransomware, and stealing data. The main targets of these attacks are **U.S. critical infrastructure** industries such as energy, communications, and manufacturing.

**Mitigation Strategies** provided by CISA include:
- **Timely vulnerability patches**
- **OT and IT network segmentation**
- **Multi-factor authentication** when accessing the network remotely
- **Continuous monitoring** of unusual operations

Such suggestions will significantly reduce the effectiveness of future attacks and enhance overall system resilience.

---

## Task 6: Reflection

### **1. How does the Diamond Model help in understanding threat actors?**
The Diamond Model assists in this by subdividing an attack into four fundamental elements the Adversary, Infrastructure, Capability, and Victim. The model provides a systematic and detailed comprehension of the attack procedure that does reveal the association among the different components involved. The analysis of each vertex and the connections they represent provides the defenders with a great understanding of the motivations, techniques, tools, and target profiles of the attacker, which results in a better understanding of the threat landscape.

### **2. What challenges did you face in identifying each vertex?**
The largest concern was to establish the specific boundaries of infrastructure and capability. Such a number of tools or techniques, as Remote Access Trojans (RAT), VPNs, etc., might be categorized as both infrastructure and capability depending on usage. Also, the fact that some of the reports were indirect text is what complicated the attribution to a particular group of APT29 or Sandworm and there are several cyber groups involved. The comparison of the report contents facilitated the explanation of these parts.

### **3. How could this model support proactive defense strategies?**
The model allows defenders to understand the attack directions in the future by finding patterns in the tactics, techniques, and procedures (TTPs) of attackers. Mapping adversary actions, infrastructure and capabilities will enable organizations to anticipate better the places of attack and focus on defence needs. Active defense measures might involve enhanced network partitioning, closing up the identified vulnerabilities, and imposing monitoring instruments that are customized to recognize the tools and techniques that were recognized in the model.

---

## Reference

https://www.cisa.gov/news-events/cybersecurity-advisories/aa22-110a
