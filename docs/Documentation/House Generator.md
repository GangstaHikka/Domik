# **House Generator**


The House Generator component is the entry point to start generation of house.

![[Pasted image 20210814115724.png]]


There are two ways to create a House Generator instance: 
- Right Click on the scene hierarchy -> **Create Empty** -> select created gameObject -> **AddComponent** -> **House Generator**.
- Just drag-n-drop a house generator prefab to the scene.

---

## Generate Section
![[b32819f4dfdc71e12ee5da5a8454e483.png]]

- **Generate Random** - click it to generate a house with a random seed.

- **Seed** - a seed number which uses to generate a house. 

- **Generate** - click it to generate a house from the current seed number. Pretty useful to regenerate a house after some changes to see difference.                    
- **Pipeline** - a reference to the Pipeline Node Graph asset. If you want to change rules of generation, just change the pipeline!
- **Combining Mode** - defines how meshes of the house should be combined.
   - **Realtime**  - Fast. Vertices welding and normals recalculation are disabled, so expect some artefacts on seams between flat meshes (walls, floor, ceiling etc.). Backed lighting also will be broken. Good choice for rogue-like games or to fast check some changes, btw.                                          
   - **Baked** - very slow but artefacts free. Good choice for final creating of the house. Can be used in realtime too (in playtime, in the game build, you know that I mean). 
  
---


#### **Change Size Of The House**
To change size of the house use the **Base Size** panel in the House Generator component.
![[change house size.gif]]
This panel defines the target size of the house. 

??? note
	This values not using directly, but sends to the **Start Node** in the **Pipeline**, so the final size of the house depends on the Pipeline algorithm.  
	![[Pasted image 20210814123203.png]]  
	The **Start Node** handles values from this panel and returns empty cells grid based on these sizes.

- **Width** - target width of the house.
- **Length** - target length of the house.
- **Floors** - target floors count.  

You can select between two size modes: **const** and **rand**

- **const** - constant size.
- **rand** - random size.


??? example "Random Size Example"
	Random size example
	![[change house size rnd.gif]]

---

#### **Change floors**


Floors system bases on the premade floors scriptable objects, and the Domik includes some floors examples which you can inspect, extend and use.

Use **Floors** panel in the **House Generator** component to change house floors.
![[change floors.gif]]
Here you can add, remove or reorder some of premade floors.

See also: [[How to create new floor OLD]]

---

## House Skins

![[Pasted image 20210105135701.png]]

Here is a list of base house skins. 
You can think about these skins as about skins by default.

---

## Floors
**Floors** is a description of expected house floors.

![[Pasted image 20210105155951.png]]


#### Floor Plans
Floor Plans is a list of expected floors.
Select some floor or add new to start changes.
**Panels below represents settings of selected house.**

- **Name** - name of selected floor.
- **Interiors** - List of possible [[Interior OLD]] for selected floor. If you want to increase chance of placing some interior - reorder it to top of the list.
- **Tags** - floor tags. This floor will be marked by these tags, so you'll be able to filter this floor by some of these tags and make changes.
	
	Example of filtering by tag:
	
	![[Pasted image 20210105141516.png]]









