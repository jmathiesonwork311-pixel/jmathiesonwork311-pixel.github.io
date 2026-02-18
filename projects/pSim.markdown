---
layout: default
---

# [Particle-Simulator!](https://github.com/jmathiesonwork311-pixel/Particle-Simulator) ! 

This project is one of the first that I did in my own time away from hackathons and university. It's purpose? To push forward my understanding of programming and design. 

To do this I designed a program aimed at simulating particles in a non-grid based system, so a far more continuous than discrete one, and implemented data-structures call quad-trees! 

Quadtrees allowed me to simulate collisions in nlog(n) time, far faster than the typical n squared required for this type of simulation. 

Additionally, I even used multi-threading to speed up the program, using the 4 threads available to my computer to collision testing even further, allowing me to simulate 8000+ objects with very little frame drop. 





