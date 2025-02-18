# ATT&CK Framework

  MITRE ATT&CK® is a globally-accessible knowledge base of adversary tactics and techniques based on real-world observations." In 2013, MITRE began to address the need to record and document common TTPs (**Tactics, Techniques, and Procedures**) that APT (**Advanced Persistent Threat**) groups used against enterprise Windows networks. This started with an internal project known as FMX (Fort Meade Experiment). Within this project, selected security professionals were tasked to emulated adversarial TTPs against a network, and data was collected from the attacks on this network. The gathered data helped construct the beginning pieces of what we know today as the ATT&CK® framework.

  Nowadays, this platform has extended from windows to macOS and linux. MITRE ATT&CK website: [MITRE ATT&CK link](https://attack.mitre.org/)

  Across the top of the matrix, there are 14 categories. Each category contains the techniques an adversary could use to perform the tactic. The categories cover the seven-stage Cyber Attack Lifecycle (credit Lockheed Martin for the Cyber Kill Chain).


# CAR - Cyber Analytics Repository

  The MITRE Cyber Analytics Repository (CAR) is a knowledge base of analytics developed by MITRE based on the MITRE ATT&CK® adversary model. CAR defines a data model that is leveraged in its pseudocode representations but also includes implementations directly targeted at specific tools (e.g., Splunk, EQL) in its analytics. With respect to coverage, CAR is focused on providing a set of validated and well-explained analytics, in particular with regards to their operating theory and rationale.

  Simply it means that this provides detection techniques against attacks from the ATT&CK frame work. 
  We're also provided with Pseudocode and a query on how to search for specific analytic within Splunk. A pseudocode is a plain, human-readable way to describe a set of instructions or algorithms that a program or system will perform.


  To summarize, CAR is a great place for finding analytics that takes us further than the Mitigation and Detection summaries in the ATT&CK® framework. This tool is not a replacement for ATT&CK® but an added resource.

# MITRE Engage

  MITRE ENGAGE is a framework that helps organizations plan and carry out active defense strategies against cyber threats. Instead of just reacting to attacks, it provides methods to deceive, detect, and disrupt attackers. [MITRE Engage link](https://engage.mitre.org/)

  Think of it like setting traps and gathering intelligence on hackers instead of just blocking them. It includes techniques like honeytokens (fake data), decoys, and monitoring attacker behavior to better understand and counter cyber threats.


# MITRE D3FEND

  [D3FEND link](https://d3fend.mitre.org/) stands for Detection, Denial, and Disruption Framework Empowering Network Defense. 

  MITRE DEFEND is a countermeasure framework that helps organizations prevent and disrupt cyber threats. It provides a structured way to apply active defense techniques, making it easier to stop attackers before they succeed.

  It builds on the MITRE ATT&CK framework but focuses on defensive actions rather than attacker behaviors. It includes strategies like deception, adversary engagement, and attack disruption to protect systems effectively.


  **Source:** [TryHackMe link](https://tryhackme.com/room/mitre)