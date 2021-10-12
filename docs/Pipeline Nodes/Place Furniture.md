# **Place Furniture**
This node places interior furniture to input cells.  
![[Pasted image 20211004122733.png]]  
- **In** - cells to place furniture
- **Out** - result
- **Room Interiors** - An info about rooms of interiors. To calculate it use a **Calculate Room Interiors** node.

Read this to find out how to:  
- **Add look for furniture** - [[Furniture]]
- **Create new furniture** - [[Documentation/Placeable Object]]
- **Add furniture to the interior** - [[Interiors]]



### Example
In this example we will use precalculated cells with empty rooms  

![[Pasted image 20211004123402.png]]
![[Pasted image 20211004113350.png]]

Now let's calculate Rooms Interiors to know what interior should be for  every room.  
![[Pasted image 20211004113635.png]]
![[Pasted image 20211004113646.png]]

And now we can add furniture  

![[Pasted image 20211004114033.png]]
![[Pasted image 20211004114101.png]]