<p align="center"> <img src="https://raw.githubusercontent.com/qeeqbox/threat-intelligence/main/threat-intelligence.png"></p>

### Threat Intelligence

Threat intelligence or Cyber Threat Intelligence is the process of identifying and analyzing gathered information about past, current, and future cyber threats (Collecting information about a potential threat, then analyzing that information to learn more about the negative events)

* * *

### Threat Intelligence Types

*   Tactical Threat Intelligence
    *   Addresses the what (Focuses on threat actor tactics, techniques, and procedures TTPs)
        *   Scenario
            *   You receive malware alerts from TIP, and the sigs get digested automatically by the endpoint security server, the server pushes the new sigs to endpoint clients
        *   Examples  
            *   Malware hash
            *   URLs
            *   IPs
        *   Collected from
            *   Dark web
            *   Public reports
        *   Used for  
            *   SIEM
            *   Firewall
            *   Endpoints
            *   IDS/IPS
            *   SOC
*   Operational Threat Intelligence
    *   Addresses the how and where (Focuses on how and where a threat happen/happened)
        *   Scenario
            *   You receive an alert about a newly discovered MFA bypass vulnerability in a specific software. The software is currently being used by the company you work for, you patched the vulnerability and keep an eye on it by creating detection rules
        *   Collected from
            *   Dark web forums
            *   Private forums
            *   Social networks
        *   Used by  
            *   Defenders
            *   Malware Analysts
            *   IR
            *   SOC
            *   CISO
            *   CIO
        *   Used for
            *   Prevent or respond to attacks
            *   Identify possible attacks
            *   Prioritize updates
            *   Gain deep understanding of attacks
*   Strategic Threat Intelligence
    *   Addresses the who and why (Focuses on identifying the threat actor behind the threat and why the origination is being targeted)
        *   Scenario
            *   You receive an alert about a ransom gang targeting higher education institutions; you work for a higher education institution and could be a target of that Ransom gang; the higher education institution decided to implement stronger access controls. Later, you found out that the Ransom gang failed to breach the higher education institution due to the new implementation
        *   Examples
            *   CISA Alert about a threat actor
        *   Used by
            *   The board
            *   Executives
            *   C-Level
        *   Used for  
            *   Make informed investment decisions
            *   Manage risk strategies and investments based on the cyber threat landscape

* * *

### Threat Intelligence Steps

#### Planning & Direction

Define the scope and goals of the threat intelligence program (what problems need to be solved and what data has to be obtained to deliver the proper solutions)

#### Collection

Collect data from multiple sources

*   Open Source Intelligence (OSINT)
    *   Intelligence collected from free tools or resources
*   Social Media Intelligence (SOCMINT)
    *   Intelligence collected from social media platforms
*   Human Intelligence (HUMINT)
    *   Intelligence collected and provided by human sources
*   Geospatial Intelligence (GEOINT)
    *   Intelligence collected from images analysis and data associated with a particular location
*   Measurement and signature intelligence (MASINT)
    *   Intelligence collected from quantitative and qualitative data about specific target (Requires complex tools and equipment to obtain information)
*   Signals Intelligence (SIGINT)
    *   Intelligence collected from electronic signals and systems
*   Technical Intelligence (TECHINT)
*   Imagery Intelligence (IMINT)
    *   Intelligence collected through the interpretation or analysis of imagery, infrared, lasers, multi-spectral sensors, or radar
*   Financial Intelligence (FININT)
    *   Intelligence collected about suspicious or unusual financial activities

#### Processing

Convert the gathered raw data into a readable\\usable format (Remove false positives and structure the data)

#### Analysis & Production

Evaluate the structured data and create actionable information based on the requirements specified in the Planning step

#### Dissemination & Feedback

Share the finished intelligence output with the appropriate stakeholders

* * *

### Threat Intelligence Feeds 

External streams of data related to potential or current threats, those feeds can be ingested into security tools and platforms to find or block a threat.

## ID
fe47147d-35bb-4d54-b2e2-0299050a6ceb

## References
- https://en.wikipedia.org/wiki/Threat_intelligence
- https://en.wikipedia.org/wiki/List_of_intelligence_gathering_disciplines
- https://csrc.nist.gov/glossary/term/threat_intelligence
