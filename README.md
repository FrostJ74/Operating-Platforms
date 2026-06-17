Operating Platforms
An overview and collection of coursework for the Operating Platforms course, featuring a comprehensive system design for Creative Technology Solutions (CTS) on behalf of their client, The Gaming Room.
Course Description
Students will develop a deeper understanding of operating platforms and architectures through the analysis and evaluation of the characteristics, advantages, and weaknesses of each. Students will learn the value of utilizing software design templates as well as how to utilize them to solve problems.
Project Overview: "Draw It or Lose It" TransitionClient & Objective
Client: Creative Technology Solutions (CTS)
End Client: The Gaming Room
Project Goal: Transition the existing Android-only game, Draw It or Lose It, into a modern, web-based, cross-platform distributed application to maximize market reach.
Software Requirements
Team Structure: Must support one or more teams, with multiple players assigned to each team.
Uniqueness: Game and team names must be strictly unique to allow users to verify availability.
Core Structural Constraint: Only one instance of the game can exist in memory at any given time.
Architectural ApproachSystem Architecture: Designed a browser-agnostic, client-server architecture.
Operating Platform: Hosted on a stable, secure Linux environment.
Development Strategy: Followed a top-down approach, starting with business goals, defining technical constraints, selecting architectural patterns, and evaluating hosting platforms.
Design Patterns & Documentation
Architectural Patterns Applied
Singleton Pattern: Employed directly to guarantee the core single-memory-instance constraint of the game loop.
Object-Oriented Inheritance: Implemented to efficiently manage unique naming constraints across entities without duplicating code.
Value of the Design Process
Creating a formal design document provided a clear blueprint before coding began. Mapping out the Domain Model and UML relationships early on turned complex problem solving into straightforward execution and prevented costly refactoring later in development.
Areas for Future Revision
If revising this project, adding sequence diagrams to the System Architecture View would be the primary enhancement. While the structural model is strong, behavioral diagrams would better illustrate real-time data flow and timing constraints across the distributed network.
Professional Reflection
Interpreting User Needs: Technical excellence only matters if the final product solves the client's business problem and is usable by their target audience. This design directly addresses the core need for broader market reach through its platform-agnostic architecture.
Future Strategies: Future projects will continue to rely heavily on UML Domain Modeling to map class relationships and Evaluation Matrices to objectively choose the best target environments for clients.
