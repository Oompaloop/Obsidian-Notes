- - - 
#### Topic 4: The Shell Method

###### Introduction
*Often a given problem can be solved in more than one way. A particular method may be chosen out of convenience, personal preference, or perhaps necessity. Ultimately, it is good to have options.*

*The previous section introduced the Disk and Washer Methods, which computed the volume of solids of revolution by integrating the cross-sectional area of the solid. This section develops another method of computing volume, the Shell Method. Instead of slicing the solid perpendicular to the axis of rotation creating cross-sections, we now slice it parallel to the axis of rotation, creating “shells.”*

*The shell method is a technique used in calculus to find the volume of a solid of revolution formed by rotating a region bounded by a curve around an axis.*

*When using the shell method, a cylindrical shell is created within the solid. The volume of each individual shell is calculated by multiplying the circumference of the shell (which depends on the distance from the axis of rotation) by the height of the shell (which represents the difference in the function values or distances between two curves in the region).*

*By summing up the volumes of these infinitely thin cylindrical shells over the interval of interest using integration, the total volume of the solid of revolution can be determined. This method is particularly useful when the solid is formed by a curve that is perpendicular to the axis of rotation.*
- - - 

##### <u>Shell Method:</u>
![[Pasted image 20240123050539.png]]
- $Average$ $Radius$ $r = \frac{(r_1 + r_2)}{2}$
- $Circumference = 2\pi r$
- $Height = h$
- $Thickness = \Delta r = r$<sub>2</sub> $-$ $r$<sub>1</sub> 
$V = Circumference \times Height \times Thickness$ $= 2\pi r \times h \times \Delta r$ 

![[Pasted image 20240123052125.png]]

- **Shell Method:** $V = \int_{a}^{b} 2\pi x \times f(x) dx$

*Note:*
- $x$ *is representative of the Radius*
- $2\pi x$ *is representative of the Circumference*
- $f(x)$ *is representative of the Height*
- $dx$ *is representative of the Thickness*
- - - 

###### Examples

**Example 1:** *Use the Shell Method to find the volume of the solid formed by rotating the region given below around the $y-axis$.*
![[Pasted image 20240123052821.png]]

**Example 2:** *Use the Shell Method to find the volume of the solid formed by rotating the region given below around the $x-axis$.* 
![[Pasted image 20240123053155.png]]

**Example 3:** *Find the volume of the solid obtained by rotating the region between
$y = 3+2x-x^2$ and $x+y=3$ around the $y-axis$.* 
![[Pasted image 20240123053808.png]]
- - -
![[Pasted image 20240125040820.png]]
##### Caption:
*As can be seen above, the Washer Method makes use of x-functions when finding the volume of horizontally revolved objects, and y-functions for vertically revolved objects. This can be remembered as Wa-Xh and Wa-Yv. The Shell Method on the other hand is the opposite of this. For finding the volume of horizontally revolved objects, the Shell Method takes y-functions, and for vertically revolved objects, the Shell Method takes x-functions. This can be remembered as Sh-Yh and Sh-Xv*
- - - 
###### Backlink: [[Calculus 2]]
