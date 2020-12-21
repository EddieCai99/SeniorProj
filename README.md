# Senior Capstone Project - BioCrowds
In this project, I explore BioCrowds, which is a space-colonization determined method of crowd simulation. It is based on the formation of veination patterns on leaves. Given a goal destiantion, agents can move without colliding using the notion of personal space. Markers are scattered through the space, and in each timestep, each marker is owned by the closest agent (limited by a distance). Then, the velocity of the agrent is computed with a sum of displacement vectors using weighted average, because markers that lead more directly to the goal are weighted heavier.

## Features
### Interchangeable Parameters
You can interchange the number of Agents and Markers used for BioCrowds. In the snippet below, it is at 10 Agents and 2000 Markers. 

![](./demos/demo1.gif)

### Obstacle
You can add an obstacle in the center of the grid.

![](./demos/demo3.gif)

### Controllable Agent
Going to "Third Person" mode, you can control the Agent with WASD controls and mingle with the crowd.

![](./demos/demo2.gif)
