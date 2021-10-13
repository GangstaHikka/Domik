# **Create Skins Layer**

![[Pasted image 20211008164616.png]]{ align=left }    

This node creates an override skins layer, use it if you want to add some special look for several cells.  

<br /><br />

- **In** - cells for which you want to override the look
- **Skins Layer** - a result data that you have to return to the end node to apply changes
- **Skin field** - skin that you want to apply to input cells.

<br />

--------

# Examples
In this example we'll change a color of basement floor facade walls.  
![[Pasted image 20211008164806.png]]  
![[Pasted image 20211008164914.png]]  
Now let's filter a basement floor.  
![[Pasted image 20211008165045.png]]  
![[Pasted image 20211008165028.png]]  
Now we can use filtered cells as a base for the Skins Layer.  
![[Pasted image 20211008165146.png]]  
Apply changes by the **Return Skins Layer** node.  
![[Pasted image 20211008165317.png]]  

![[Pasted image 20211008165219.png]]  
