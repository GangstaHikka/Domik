# **Place Placeable Object**
This node places a **PlaceableObject** or **PlaceableObjectsContainer** to input cells.  
![[Pasted image 20211005165304.png]]  

- **In** - cells to place.
- **Out** - placing result.
- **Placing Mode**: 
	- **Once Per House** - try to place this **Placeable Object** only once somewhere into the house.
	- **Once Per Floor** - try to place this **Placeable Object** once per floor.
	- **Once Per Room** - try to place this **Placeable Object** in every room.
	- **In Every Cell** - try to place this **Placeable Object** in every input cell.
	
- **A Placeable field** - **PlaceableObject** of **PlaceableObjectsContainer** what you want to place.

### Examples
For this examples we'll use generated rooms without anything as it shows below.  
![[Pasted image 20211005165339.png]]
![[Pasted image 20211005145613.png]]

Now let's add a **Chilling Small Section** placeable object with different placing rules.  

#### Once Per Cell
With this parameter node will try to place a **PlaceableObject** on every cell.   

![[Pasted image 20211005151444.png]]
![[Pasted image 20211005150607.png]]

#### Once Per Room
With this parameter node will try to place a **PlaceableObject** only once per room.   
![[Pasted image 20211005151246.png]]
![[Pasted image 20211005150806.png]]

#### Once Per Floor
The result of selecting this parameter pretty hard to show, because there is only one chilling section per floor now.  
![[Pasted image 20211005151324.png]]
![[Pasted image 20211005154308.png]]
![[Pasted image 20211005154452.png]]

#### Once Per House
Now it's even harder because there is only one place where this Placeable Object can be.  
![[Pasted image 20211005151405.png]]
![[Pasted image 20211005155054.png]]

There is no necessary to use a main cells flow as an input, you can filter some bunch of cells and place some PlaceableObject there, just don't forget to override a main cells flow after that.  

Let's filter several random cells.  
![[Pasted image 20211005160228.png]]
![[Pasted image 20211005160342.png]]
Now let's place things on them.  
![[Pasted image 20211005160424.png]]
![[Pasted image 20211005160444.png]]
And now we can apply it to the main cells flow.  
![[Pasted image 20211005160551.png]]
![[Pasted image 20211005160621.png]]