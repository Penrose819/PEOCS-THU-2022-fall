# Intro to Complex Systems

## Course Content

![](img/img-note1-calendar.png)

## Intro to DECS

1. What is Complex System:

   - simulation-based
   - takes long time to simulate

2. Time cost of simulation

   - a computer network, an electronic grid ...
   - several days --> optimize

3. What can we do?

   - **Model** the DEDS
   - **Simulate** the DEDS
   - **Evaluate** the DEDS
   - **Optimize** the DEDS

4. What is DEDS:

   - Discrete event dynamic system

   - state $s_{i}$ is concrete

   - state transition mechanism is **event-driven**

     e.g. Airport, The Internet

5. Nature of DEDS: 

   - A set of tasks
   - A set of resources
   - Routing (among resources)
   - Scheduing (among tasks)

   > Just like an optimization problem......

6. Comparison with a CVDS Trajectory:

   - $y$ axis --> event --> no value

     > Q: If we integrate the DEDS trajectory several times, we shall also get a smooth trajectory. What is wrong with this? 
     >
     > A: Because there are no metric assigned on the state space of a DEDS. **Integration of the DEDS trajectory makes no sense**, because the units of verticals axes has no meaning only graphical.

   - ![](img/img-note1-DEDS.png)

7. Modeling Ingredients:

   - Discrete State:

     combinatorial explosion 

   - Stochastic Effects

   - Hierarchical:

     depending on what level is needed to optimize the performance of interest

   - Computational

     computationally feasible algorithms 

8. Mathematical Specification:

   - 