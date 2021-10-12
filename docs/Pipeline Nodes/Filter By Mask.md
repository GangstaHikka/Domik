# **Filter By Mask**
Use this node to filter cells by some mask.  
![[Pasted image 20210918155141.png]]
- **In** - cells to filter
- **Out** - filtered cells
- **0** - result cells filtered by mask
- **90** - Result cells filtered by mask rotated by 90 degrees
- **180** - Result cells filtered by mask rotated by 180 degrees 
- **270** - Result cells filtered by mask rotated by 270 degrees 
- **Mask field** - A mask to use as a filter.


### Example
Input is a house that has been completed.  

![[default cells.png]]
![[Pasted image 20210918153153.png]]

Now lets use a **Forward House Borders** mask as a filter.  

Nodes  
![[Pasted image 20210918155743.png]]
Mask  
![[Pasted image 20210918160353.png]]
Result  
![[Pasted image 20210918155914.png]]

Mask rotated by 90 degrees  
![[Pasted image 20210918155823.png]]
![[Pasted image 20210918160028.png]]

Mask rotated by 180 degrees  
![[Pasted image 20210918155930.png]]
![[Pasted image 20210918155721.png]]

Mask rotated by 270 degrees  
![[Pasted image 20210918160011.png]]
![[Pasted image 20210918155844.png]]


Merged rotations  
![[Pasted image 20210918160126.png]]
![[Pasted image 20210918160143.png]]

Merged and inverted  
![[Pasted image 20210918160239.png]]
![[Pasted image 20210918160252.png]]