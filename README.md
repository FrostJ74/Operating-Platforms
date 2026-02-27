# Operating-Platforms

The client for this project is Creative Technology Soulutions (CTS) working on behalf of The Gaming Room.

What type of software did they want you to design?
  The Gaming Room wanted to transition their existing Android-only game, Draw It or Lose It, into a web-based, cross-platform
distributed application.
Software Requirements:
  * The game must support one or more teams, with multiple players assigned to each team
  * Game and team names must be strictly unique to allow users to verify availability.
  * Core Constraint: Only one instance of the game can exist in memory at any given time.

Documentation Strengths
  I successfully mapped strict client constraints to software design patterns. I applied the Singleton Pattern
to guarantee the single-memory-instance requirement, and used Object-Oriented Inheritance to efficiently manage unique naming without 
duplicating code.

Value of the Design Process
  Creating a formal design document provided a clear blueprint before coding began. Mapping out the Domain Model and UML 
relationships early on turns complex problem solving into straightforwared execution and prevents costly refactoring later 
in development.

Areas of Revision
  If I could revise one section, I would add sequence diagrams to the System Architecture View. While the structural model
is strong, behavioral diagrams would better illustrate the real time data flow and timing constraints across the distruibuted network.

Interpreting User Needs
  I addressed the core need for broader market reach by designing a browser-agnostic, client-server architecture hosted on LInux.
Considering user needs is crucial; technical excellence only matters if the final product actually solves the client's business
problem and is usable by their target audience.

Design Approach & Future Strategies
  I took a top-down approach: identifying business goals, defining technical constraints, selecting architectureal patterns, and finally
evaluating hosting platforms. In future projects, I will continue relying heavily on UML Domain Modeling to map class relationships and
Evaluation Matrices to ovjectively choose the best environments for the client.
