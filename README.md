# swarm-rl-media

Videos of the ongoing project with Professor **Eliseo Ferrante**, by students **Mohamad Khair Altrabulsi** and **Musa Khan**.

The code will be uploaded after the project is finished in approximately **2–3 months**.  
It currently exists as a private repository.

---

# Project Description

This project has several components, some completed and others still in progress.

## 1. Re-implementing the Proximal-Alignment Control Algorithm (Finished)

We re-implemented the proximal-alignment control algorithm in Python/PyTorch.  
These implementations will be used to compare our final reinforcement learning (RL) method against standard control-based approaches.

The implementation is based on the paper:

*Self-organized flocking with a mobile robot swarm: a novel motion control method*  
by **Eliseo Ferrante**, **Ali Emre Turgut**, **Cristián Huepe**, **Alessandro Stranieri**, **Carlo Pinciroli**, and **Marco Dorigo**.

## 2. Reinforcement Learning for Alignment Using Range and Bearing (Finished but needs testing)

We implemented an RL algorithm that learns alignment behavior using only **range and bearing** information from neighboring agents.

Future directions include:
- Analyzing the trained network to understand *how* it performs alignment compared to the classical control method  
- Restricting input space and training and testing new networks. 

## Videos

- The **first video** shows the proximal-alignment control algorithm: the swarm starts at random positions and converges.  
- The **second video** shows the trained RL policy: agents start at random positions and also converge.

More videos and results will be added as the project progresses.
