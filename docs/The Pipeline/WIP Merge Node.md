# Merge Node
This node merges input cells together.
![[Pasted image 20210923145608.png]]

- **In** - cells to merge. Multiple input is accessible (obviously)
- **Out** - merge result

!Note Don't use a **Remove Part** node before the **merge** node!
It'll cause artifacts because there is no way to merge removing actions properly.
Instead of that use the **Remove Part Later** and the **Apply Parts Removing** as it shows below.

Wrong:

![[dont_use_remove_part_before_merge.png]]
![[dont_use_remove_part_before_merge_result.png]]

Good:

![[well_using_merge_with_removing.png]]
![[Pasted image 20210920170151.png]]

### Examples

