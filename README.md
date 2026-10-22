# CS 230 – Software Design Portfolio

**Matthew Kohudic**
Southern New Hampshire University

## Project Overview
This project involved developing a software design document for The Gaming Room, a client looking to expand its existing Android game, Draw It or Lose It, into a web-based application. The goal was to allow users to access the game across different operating systems, including Windows, macOS, Linux, Android, and iOS.

The application needed to support multiple games, teams, and players simultaneously while maintaining unique identifiers and preventing duplicate game and team names. The design also needed to address scalability, security, and efficient resource management.

## Documentation Strengths
One of my strengths in this project was evaluating different operating platforms and determining which would best support the client's needs. Rather than selecting an operating system based on familiarity, I considered performance, cost, scalability, and compatibility. I ultimately recommended Linux in a cloud environment because of its flexibility, support for Java applications, and relatively low licensing costs.

I also did a good job explaining how the application's components would work together, particularly the use of the Singleton design pattern and centralized game management.

## How the Design Document Supported Development
Working through the design document helped me better understand the importance of planning before writing code. Breaking down the requirements into smaller components made it easier to identify how classes should interact and what responsibilities each class should have.

For example, identifying the need for a single GameService instance helped me understand why the Singleton pattern was appropriate. The UML diagrams were also helpful because they provided a visual representation of the application's structure before implementation. Having that reference made the development process more organized.

## Areas for Improvement
If I could revise one part of the project, I would expand the discussion of scalability and distributed systems. While I addressed the advantages of cloud hosting and centralized data management, I could have gone further in explaining how the application would handle a significant increase in simultaneous users.

I would also explore how multiple application servers could communicate with a shared database and maintain consistent game information. One important consideration is that the Singleton pattern only guarantees one instance within a particular application process, not across multiple servers. Understanding that distinction would help improve the design for larger deployments.

## Interpreting and Addressing User Needs
I approached the client's requirements by focusing on what the application needed to accomplish rather than immediately deciding how to build it. The Gaming Room wanted to make its game available to more users without having to develop and maintain separate applications for every operating system.

To address this, I recommended a browser-based application supported by a Linux server in a cloud environment. I also incorporated centralized game management, unique identifiers, and database storage into the design to help maintain consistent information across users and devices.

Considering user needs is important because even a technically sound application can fail if it does not solve the client's actual problem. Understanding those requirements early helps prevent unnecessary development, reduces costs, and makes the finished product more useful.

## Software Design Approach and Future Strategies
My approach to software design involved identifying the client's requirements, evaluating possible solutions, and determining how the application's components should interact. I used object-oriented programming principles, UML diagrams, and design patterns to organize the application's structure.

I also compared operating platforms and considered how storage, memory management, networking, and security would affect the application's performance.

In future projects, I would continue using this structured approach while placing additional emphasis on:

Scalability and support for increasing numbers of users.

Testing throughout the design and development process.

Long-term maintenance.

Small prototypes to evaluate architectural approaches before committing to a final design.

## Key Takeaways
This course helped me better understand that software development involves much more than writing functional code. Effective software design requires planning, communication, and an understanding of how applications interact with the operating systems and infrastructure supporting them.
