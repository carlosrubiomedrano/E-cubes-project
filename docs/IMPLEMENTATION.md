E-Cubes Implementation Details
This document outlines the core implementation, architecture, and educational model of the E-Cubes framework.

Introduction
E-Cubes is a customizable, extensible, and convenient educational framework designed to address the need for easy-to-use and easy-to-support educational materials. The framework delivers open-access, plug-and-play, hands-on learning modules that can be used for class assignments, lab exercises, and competition challenges. E-Cubes is available as a series of self-contained modules under a CC BY (Creative Commons) open-source license.




Core Architecture
E-Cubes modules are built on a four-layer architecture, ensuring that all necessary components are self-contained and ready to use, which helps prevent configuration issues.



Container Layer: This foundational layer uses OS-level virtualization to provide a convenient way to install E-Cubes on various hardware and software platforms.


Technology Example: Kubernetes.


Tools Layer: This layer contains the necessary back-end software required to support the educational tasks. It includes operating systems, Software Development Kits (SDKs), runtime libraries, and other security or AI suites.



Technology Examples: Ubuntu, Wireshark.


Payload Layer: This layer holds the core educational materials for the learning experience.


Content Examples: Course assignments, lab sessions like a "Network Sniffing and Spoofing Exercise," and competition challenges.



Support Layer: This top layer provides additional materials to help students complete the educational payload.


Content Examples: Tutorials, documentation websites, and videos (e.g., hosted on YouTube).


Educational Model
The framework's design is based on the 

Attention, Relevance, Confidence, and Satisfaction (ARCS) model to enhance learner motivation and success.



Attention: E-Cubes captures learner interest by focusing on relevant topics and using feedback to customize materials to keep them engaged.


Relevance: The content is designed to be useful in the real world, often mapping theoretical topics to recent events like security incidents to demonstrate practical importance.


Confidence: The modules are developed as a step-by-step process, allowing learners to build confidence and feel satisfied with their progress, which increases their chances of success.


Satisfaction: Future versions will include tools to measure learner satisfaction, aiming to positively impact motivation and success.
