# **Getting Started**

**This is a Domik** - a tool for houses creation.  

It uses a visual scripting system to determine a logic of generation and designed to work with modular building systems. 
## **Highlights**
- Generation of room **interiors** with **furniture**.
- Powerful visual scripting system - [**the Pipeline**](Introduction%20to%20the%20Pipeline.md).
- [Supports of third party assets.](How%20to%20replace%20models%20or%20materials.md)
- **Seed** number based generation, feel free to integrate it with your own procedural worlds.
- Supports of **all types of gameobjects**, so you can place something like a spawn-point right in a house. [Just use a furniture system](Furniture%20workflow.md).
- **In-Editor** Generation.
- **Runtime** Generation.
- **Multiple floors**.
- **Stairs**.
- **Mesh combine system** is built-in.
- **2D** Assets support (example is not included yet).
- **Mobile**, **Consoles**, **WebGL** and **PC** are supported.
- **HDRP**, **URP** and **Built-in** scriptable pipeline are supported.

---

## Tutorials
- [[How to create a procedural house]]
- [[How to change a house size]]
- [[How to change house floors]]
- [[How the Domik builds a house]]
- [[How to change room walls]]
- [[How to replace models or materials]]
- [[Furniture workflow]]
- [[Facades workflow]]
- [[Deep Dive Into House Building Process]]

---

## Main Concepts
- [[House Generator]]
- [[Preview System]]
- [[Part]]
- [[Part Builder]]
- [[Skin]]
- [[Palette]]
- [[Palettes Random Container]]
- [[Place]]
- [[Mask]]
- [[Placeable Object]]
- [[Placeable Objects Container]]
- [[Floor]]
- [[Interior]]
- [[Floor Tag]]
- [[Pipeline]]

---

## Pipeline Nodes

- Action:
	- [[Extract Positions]]
	- [[Find And Replace]]
	- [[Shift]]
- Add:
	- [[Add Part]]
- Filter:
	- [[Filter By Mask]]
	- [[Filter By Positions]]
	- [[Filter By Tag]]
	- [[Filter Floor]]
	- [[Filter Internal Doors Places]]
	- [[Filter Intersections]]
	- [[Filter Neighbor Cells]]
	- [[Filter Random Cells]]
	- [[Filter Random Input]]
	- [[Filter With Part]]
	- [[Filter With Parts]]
	- [[Filter Without Part]]
- Flow:
	- [[Exclude]]
	- [[Merge]]
	- [[Override]]
	- [[Shuffle]]
- Interiors:
	- [[Calculate Room Interiors]]
	- [[Place Furniture]]
	- [[Return Interiors]]
	- [[Split Into Rooms]]
- Main:
	- [[End]]
	- [[Start]]
- Place:
	- [[Place Part By Mask For All Rotations]]
	- [[Place Placeable Object Forced]]
	- [[Place Placeable Object]]
	- [[Place Stairs]]
- Remove:
	- [[Apply Parts Removing]]
	- [[Remove Part]]
	- [[Remove Part Later]]
- Skins:
	- [[Create Skins Layer]]
	- [[Override Skins Layer]]
	- [[Return Skins Layer]]

