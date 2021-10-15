# **Filter By Tag**


![[Pasted image 20210918175526.png]]

This node filters nodes by the [[Tag]].  
Use this node to filter and process a specific floor.  

<br /><br />

- **In** - cells to filter
- **Success** - filtered cells
- **Failed** - unfiltered cells
- **Floor Tag Field** - [[Tag]] which will be used as a filter
<br />

--------

# Examples
Input is a house that has been completed.  

![[default cells.png]]  
![[Pasted image 20210918153153.png]]  

Now lets filter a floor with a **Roof** floor tag.  

=== "Success output"
	![[Pasted image 20210918180235.png]]  
	![[Pasted image 20210918180245.png]]  

=== "Failed output"
	![[Pasted image 20210918180347.png]]  
	![[Pasted image 20210918180406.png]]  
