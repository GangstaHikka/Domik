# Filter With Part Node
This node allows you to filter cells which contains some part.

![[Pasted image 20210922154644.png]]
- **In** - cells to filter
- **Success** - cells with a target Part
- **Failed** - cells without a target Part
- **Part Field** - part what will be used as a filter

### Examples
Input is a house that has been completed.

![[default cells.png]]
![[Pasted image 20210918153153.png]]

Now we can filter all cells with an **Audio System** without a rotation offset.

![[Pasted image 20210922160157.png]]
![[Pasted image 20210922160425.png]]

To filter all rotations use a **Filter With Part 4** node with a Filter with **Any** mode as it shows below

![[Pasted image 20210922161923.png]]
![[Pasted image 20210922161807.png]]