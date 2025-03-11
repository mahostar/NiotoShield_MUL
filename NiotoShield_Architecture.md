rapport architecture :

- font (page de gard)
- white page
- Acknowledgments
- Dedications
- List of Acronyms (ex: VS = Visual Studio)

- al fahras (Contents) {

1 - chapter 1: Project Study
1.1 - introduction (what *proplem* we are solving):

In this chapter, we present NiotoShield, an AI-powered anti-theft system that safeguards vehicles and enriches the driver experience through an IoT-based framework. The discussion clarifies the system’s purpose, its practical applications, and its ability to prevent unauthorized access by detecting threats and delivering real-time responses. We outline the essential hardware and software components, describe the system’s architecture, and explore how AI models enhance both security and user assistance. Additionally, this chapter examines the architecture and underlying concepts in detail, adopting a technical yet accessible approach to provide a thorough understanding of NiotoShield’s design and functionality.

1.2 - Project Preparation : Addressing Industry Challenges through In-Depth Market Analysis and Effective Product Solutions

1.2.1 - General Project Context
NiotoShield was developed during our internship as part of earning our Bachelor’s degree in Embedded Systems and the Internet of Things at the Higher Institute of Computer Science of Mahdia (ISIMA). The project emerged from a focus on integrating smart vehicle security with IoT technology, culminating in a system that combines a mobile application with advanced embedded solutions to address real-world safety challenges.

1.2.2 - Analysis of Anti-Theft Solutions in the Market
Increasing vehicle thefts and specific crimes, such as catalytic converter theft, have heightened the demand for affordable yet reliable security options globally. This study explores cost-effective anti-theft car kits available in 2024, delving into their mechanical and electrical components, installation requirements, effectiveness in deterring theft, and compatibility with today’s vehicles. Through hands-on product testing and insights from academic research, we’ve identified key trends: multi-layered physical protections, the rising affordability of GPS tracking, and the value of user-friendly designs that resonate with budget-conscious drivers.

1.2.3 - Evaluating Anti-Theft Innovations
The theft of catalytic converters has increased significantly because of the precious metals they contain, making them a prime target for thieves who often focus on vehicles with higher ground clearance, such as trucks and SUVs, for quicker and easier access. To combat this, anti-theft solutions have evolved to combine sturdy physical protections with noticeable visual warnings to discourage criminals. In the following section, we provide a cost-benefit analysis of the most effective security options to demonstrate their real-world usefulness.

1.2.4 - Cost-Benefit Analysis of Security Layers
Device Type	Price Range	Installation Time	Deterrence Rating	Theft Recovery Support

Catalytic Converter Straps	$40–$220	5–20 minutes	4/5	Limited
Steering Wheel Locks	$45–$74	2–5 minutes	3/5	None
GPS Trackers	$29–$300	10–60 minutes	3.5/5	5.0/5
OBD2 Locks	$120	10 minutes	3/5	None

1.2.5 - User Behavior and Security Efficacy
A 2024 Road & Track report revealed that 40% of vehicle thefts stem from unlocked doors or visible valuables, underscoring that technology alone cannot offset lax habits. Subaru’s advice to park in well-lit areas and conceal belongings reinforces the need for a holistic approach combining user diligence with advanced tools.

1.2.6 - NiotoShield: Synthesizing Optimal Security

To address these challenges, this study distills the strongest features from existing anti-theft solutions into NiotoShield, a unified IoT-based product designed for effectiveness, affordability, and user appeal. NiotoShield seamlessly integrates:

    - Biometric face recognition with anti-spoofing models to ensure secure, foolproof access control
    - Physical protection sensors that detect unauthorized access and monitor car vibrations when the vehicle is off
    - A physically secured cut-off circuit system, linked to the main computer via encrypted wired communication
    - Latched relays that disable the engine by cutting power to the engine pump for robust theft prevention
    - Real-time GPS tracking to enable precise vehicle location and recovery
    - An AI assistant that delivers web-sourced insights and engaging conversation to enrich the driving experience
	- A mobile app with a user-friendly interface for effortless control and monitoring

This fusion of cutting-edge technologies creates a secure, accessible, and enjoyable solution tailored to the needs of modern drivers.

1.3 - NiotoShield Security Architecture and Scenario Handling

1.3.1 - Potential Worst-Case Scenarios and Possible Attack Methods Against the System

a) Possible Attack Methods

This section outlines potential vulnerabilities and the corresponding countermeasures designed to protect NiotoShield:

Attack 1: Man-in-the-Middle
Attackers might intercept communication between the app, database, and NiotoShield kit.
Solution: Implement an encryption layer across the entire ecosystem, ensuring all transmitted data to and from the database remains secure.

Attack 2: 4G Signal Jamming
An attacker could jam the 4G signal and attempt a brute-force attack on the NiotoShield system.
Solution: Equip the system with jammer detection to trigger an alarm when interference is detected.

Attack 3: Fake Face Manipulation
Attackers may use a photo to deceive the AI face recognition model.
Solution: Integrate an anti-spoofing model into the pipeline before the face recognition step to verify authenticity.

Attack 4: Physical Break-In
An intruder could physically access the car, targeting the cut-off module to bypass it.
Solution: Detect unauthorized bypass attempts, trigger an alarm with an alert notification, and include decoy wires to confuse and delay the attacker.

Attack 5: Theft with Keys Present
The car could be stolen if the keys are left inside.
Solution: Use the GPS module to track the vehicle and plan a future feature for remote deactivation.

b) Worst-Case Scenarios
These scenarios explore extreme situations and NiotoShield’s contingency measures:

Worst-Case 1: User Trapped in a Forest with No 4G or Weak Signal
Solution: Enable offline face or voice recognition to maintain access without network dependency.

Worst-Case 2: User Trapped in a Forest with a Broken Camera Module
Solution: Rely on voice recognition as a backup authentication method.

Worst-Case 3: Car with a Dead Battery
Solution: Incorporate a backup battery and solar panel to ensure continuous power supply.

Worst-Case 4: NiotoShield Kit Malfunction
Solution: Deploy a machine learning algorithm on the cloud to monitor the car’s last known location. If the vehicle remains offline in an isolated area (e.g., a forest) for an extended period, the app notifies the admin dashboard. The admin can then call the user to confirm their safety, escalating to authorities with the last GPS coordinates if there’s no response.











- overall project architecture:
	* full architecture
	* subdevide basic functionality
	* diagrams
- app side:
	* 
	
	
	
	
	
}




