# Waypoint-Based-2D-A-pathfinding
Hi! This is my implementation of **A-star pathfinding** solution for use in 2D or 3D games*. Use it freely in your projects

# Getting Started

 1. Create empty GameObject and attach Waypoint.cs
 2. Distribute your waypoints as you wish
 3. Add Pathfinding.cs to NPC, add target
 4. Play and press **Pathfind** in the inspector

# Files and explanation
Included here is:

 - Pathfinding.cs
 - Waypoint.cs
 - Edge.cs
 - PathfindingEditor.cs (extension for unity editor)
 - NPCMovement.cs

## Pathfinding.cs
This is the pathfinder, it uses A* algorithm to find shortest path to destination using waypoints and edges, edges being connections between waypoints.
Its still kinda messy and ill continue to be working on it making it more optimized and readable as well as including comments :)

## Waypoint.cs

All your files and folders are presented as a tree in the file explorer. You can switch from one to another by clicking a file in the tree.

## Edge.cs

Definiton of edge for use in Pathfinding.cs

## PathfindingEditor.cs

Basic editor script that adds 2 buttons to inspector

## NPCMovement.cs
Companion script for Pathfinder.cs

# NOTES

 - Still DEEP in development.
 - Its made specificaly for 2D sidescrolling, but any 2D projection will work.
 - If you want to use it in 3D you will need to change Physics2D to Physics in Pathfinding.cs

# Roadmap

 1. Fix Bugs
 2. Add support for 3D
 3. Convert to DOTS
 4. Make it faster
 5. Add QOL improvements
