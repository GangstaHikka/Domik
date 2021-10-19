---
hide:
  - toc
---
# **How to change room walls**

To change the look of the room, you have to change its [[Skins]].
In this tutorial you'll see how to do it by the example of changing of room walls.  

Skins of the room are stored in the [[Interior]]. Interior of the room is set in the process of the [[Calculate Room Interiors]] node, basically this node just sets some interior from the [[Floor]] interiors list.   

So how do you figure out which interior is applied to a room?  
You can do it visually or you can look at the name of the room, this name is the same as the name of the applied interior.  

=== "Rooms"
	![[Pasted image 20211019132827.png]]

=== "Interiors"
	![[Pasted image 20211019132900.png]]

In this tutorial I'll work with Living Room.


![[Pasted image 20210407140041.png]]

As you can see something in Skins panel is already here.
It's a Palette Random Container!
This is a container of pallets which will return one of it's random palette during house building. 
But that's a Palette? 
Palette is a container of skins, which allows you to collect skins on some topic. 
We don't need them right now so just ignore them. 
To change look of room walls we need to add some skin in top of interior skins list. This skin should have PartBuilders for internal walls. Fortunately we already have some of them in the Domik -> House Example -> Skins -> Walls
Here is three folders:
![[Pasted image 20210407141239.png]]
Let's open **Regular** folder. 

![[Pasted image 20210407152654.png]]

Skins are basically just prefabs with **Skin** component on the root object and some children objects with **PartBuilder** components.
So you can use all features of regular prefabs with them, including **nesting of prefabs**.
**Walls Origin** here is an **original prefab** a all other **Walls** prefabs are **nested**, so if you make some changes of **Origin skin** prefab it'll make effects on **nested**. 
We just need to change walls material so let's just duplicate some nested skin and open it to edit.


![[duplicate room skin.gif]]

This skin contains five PartBuilders.

![[Pasted image 20210407153553.png]]

So now let's create some material and add to the wall.
![[create and add wall mat.gif]]
Repeat it for other PartBuilders.
![[change other part builders.gif]]
Quit from prefab edit mode, add the result skin to the Living Room Interior and checkout the result by regenerating of house.

![[checkout result.gif]]

Congrats! Now you know how to change walls of the house. 
Similarly, you can change the rest of the room, including the ceiling, floor and furniture.