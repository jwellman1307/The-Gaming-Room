# The Gaming Room – Web-Based Multiplayer Game Platform

The Gaming Room project involves designing and planning a software system capable of supporting a web-based version of the mobile game **Draw It or Lose It**. The goal was to transition the existing Android-only game into a scalable, multi-platform web application that supports multiple teams, players, and game sessions simultaneously.

This project focuses on software design, system architecture, platform evaluation, and client requirements, producing a complete design document that outlines how the game should be built.

## Project Overview

The client, **The Gaming Room**, wanted:

- A multi-platform game accessible via web browsers  
- Support for multiple game instances  
- Unique team and player identities  
- Efficient server-side resource management  
- A scalable, maintainable backend architecture  

My role was to evaluate technologies, recommend platforms, and design a system that meets performance, security, and scalability needs.

## Key Design Components

### System Architecture
The proposed system follows a **client–server architecture**, ensuring:
- Centralized game logic  
- Consistent state management  
- Ability to serve many clients concurrently  

### Object Model & Requirements
Designed classes include:
- **Game** – manages game instances  
- **Team** – ensures unique team names  
- **Player** – maintains unique player identities  
- **Game Service** – handles creation, updates, and session management  

### Platform & Technology Evaluation
I compared options such as:
- Windows vs. Linux for hosting  
- Local vs. cloud deployment  
- Java vs. other server-side languages  

Final recommendations were based on:
- Cost  
- Security  
- Scalability  
- Cross-platform support  
- Maintainability  

### Multi-Client Support
The system must prevent:
- Duplicate names  
- Duplicate teams  
- Conflicting game sessions  

Server-side validation ensures data consistency across all clients.

## Technologies Evaluated / Considered

- **Java** (recommended for server-side logic)  
- **RESTful APIs** for client communication  
- **Web Browser Clients** (HTML/CSS/JS)  
- **Cloud Hosting** (AWS, Azure, Google Cloud)  
- **Linux OS** (recommended for security and efficiency)  

## What I Contributed

- Analyzed system requirements and client expectations  
- Researched platform options and justified technology choices  
- Designed class structure and system architecture  
- Proposed solutions for handling user identity, concurrency, and scalability  
- Evaluated performance, security, and maintainability impacts  

## What I Learned

- The importance of collecting and defining **clear requirements** early  
- How architectural decisions impact scalability and user experience  
- How to compare platforms using cost, security, and performance criteria  
- Why planning system structure before coding improves long-term maintainability  
- Best practices for resource management in multi-user systems  

## Future Improvements & Expansion

- Implementing the full backend in Java with Spring Boot  
- Adding real-time gameplay using WebSockets  
- Building a scalable cloud deployment with load balancing  
- Developing the browser client interface  
- Supporting cross-device synchronization  

