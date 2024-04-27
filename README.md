# CS-230-Operating-Platforms-Draw-It-Lose-It

## Summary of The Gaming Room Client and Software Requirements
The Gaming Room is looking for help to expedite the creation of a web-based version of their gaming program. The main software requirements include:
- Business Requirements:
  *	The ability to play with several teams and players.
  *	Users can be identified by their game and team names.
- Technical Requirements:
  *	Using the singleton technique to keep only one instance of a game in memory.
  *	Using the iterator technique to effectively handle game instances and team/player collections.
## Strengths in Developing the Documentation
In developing this documentation, I excelled in the following areas:
- Logical System Architecture:
  *	I methodically created a client-server architecture for the system.
  *	The server runs the gaming program and handles the player, team, and game instances.
  *	The client side interfaces with the server to manage user interactions and show game data.
- Adherence to Technical and Business Objectives:
  *	I verified that the design met both technical and business objectives.
  *	The usage of patterns such as the singleton and iterator patterns directly handled the stated criteria.
## Helpful Aspects of Working Through the Design Document
The process of working through the design document was particularly helpful in the following ways:
- Clarity and Focus:
  *	The paper outlined a detailed plan for turning requirements into code.
  *	It helped me stay focused on critical features and avoid scope creeps.
- Structured Approach:
  *	The document's ordered parts allowed for step-by-step planning and implementation.
## Area for Revision in the Documents
If I were to change any of my work on these papers, I would prioritize security concerns. While I addressed security in the proposals, I would further improve it by:
- Multilayered Defense Strategy:
  *	Improving security at the code, client, network, and server levels.
  *	Keeping security as a high concern throughout the application lifetime.
- Web Application Firewall (WAF):
  *	Consider using a Web Application Firewall (WAF) as an extra layer of defense.
  *	WAFs, which are commonly delivered as cloud services, provide up-to-date firewall rules and monitoring.
## Importance of User Needs in Software Design
Considering user demands during software design is critical for various reasons:
- User-Centric Approach:
  *	Designing with users in mind ensures that the application meets their expectations.
  *	It leads to a more intuitive and user-friendly experience.
- Avoiding Assumptions:
  *	By understanding user requirements, we avoid making assumptions that may lead to design flaws.
  *	User feedback helps refine the application.
## Approach to Designing Software
In designing software, I would follow these strategies:
- Cross-Platform Compatibility:
  *	For web development, I examine several platforms (desktop browsers, mobile devices) and frameworks such as React or Angular.
  *	Testing across several configurations assures compatibility.
- Memory Optimization:
  *	I improve memory consumption by using strategies like efficient picture loading, compression, and garbage collection.
  *	This enables smooth functioning.
- Distributed Systems and Networks:
  *	Utilization of RESTful APIs to communicate with dispersed components.
  *	Using a Content Delivery Network (CDN) lowers latency and increases availability.
- Security Best Practices:
  *	Focus on security at the code and server levels.
  *	HTTPS encryption and other security measures protect user data.

