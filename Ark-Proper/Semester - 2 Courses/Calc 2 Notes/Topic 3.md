- - -
#### Topic 3: Volume by Cross-Sectional Area // Disk and Washer Methods

###### Introduction 
*The volume of a general right cylinder is the Area of its base multiplied by its height. 
We can use this fact as the building block in finding volumes of a variety of shapes.
Given an arbitrary solid, we can approximate its volume by cutting it into $n$ thin slices. As the slices become thinner, each slice can be approximated better by a general right cylinder. Thus, the volume of each slice is approximately its cross-sectional area times thickness.*

*By orienting a solid along the $x$-axis, we can let $A(x$<sub>i</sub>$)$ represent the cross-sectional area of the $i$th slice, and let $\Delta x$<sub>i</sub> represent the thickness of this slice (the thickness is a small change in $x$). The total volume of the solid is thereby approximately:*

$Volume \approx \sum_{i=1}^{n} [Area \times Thickness]$ 
$= \sum_{i=1}^{n} A(x$<sub>i</sub>$) \Delta x$<sub>i</sub>

We can recognize that this is a *Riemann Sum*. 
By taking a limit (as the number of cylinders (i) approaches infinity and thickness of the slice goes to 0) we can find the exact volume of the shape. 

$V = \lim_{n\to\infty} \sum_{i=1}^{n} A(x$<sub>i</sub>$) \Delta x = \int_{a}^{b} A(x)dx$ 
- - - 

##### <u>Disk Method:</u>
###### Definitions: 
- **Volume By Cross-Sectional Area:** $V = \int_{a}^{b} A(x)dx$
- *If the cross section is a cylinder/disk, we find the radius of the disk (in terms of $x$ or $y$) and use   $A = \pi(radius)$<sup>2</sup>* 

    *This brings us to* **The Disk Method:**
    *Let a solid be formed by revolving the curve $y = f(x)$ from $x = a$ to $x = b$ around a horizontal axis, and let $R(x)$ be the radius of the cross-sectional disk at $x$. Then the volume of the solid is:*
    $V = \pi\int_{a}^{b} R(x)$<sup>2</sup>$dx$ 

- - - 

###### Examples

**Example 1:** *Find the volume of the solid obtained by rotating the region under the curve $y = \sqrt{x-1}$ from $2$ to $5$ about the x-axis.* 

![[Pasted image 20240123022124.png]]
- - - 
**Example 2:** *Find the volume of the solid obtained by rotating about the y-axis the region bounded by the curves $x = y - y$<sup>2</sup> and $x = 0$.* 

![[Pasted image 20240123022621.png]]

*Note: The solids in Examples 1 & 2 are called <u>Solids of Revolution</u> because they are obtained by revolving a region about a line.*
- - -
##### <u>Washer Method</u>

###### Definitions: 
- *If the cross-section is a washer, we find the inner radius $r$<sub>in</sub> and outer radius $r$<sub>out</sub> from a sketch and compute the area of the washer by subtracting the area of the inner disk from the area of the outer disk.* 
	
	$A = \pi($outer radius$)$<sup>2</sup> $-$ $\pi ($inner radius$)$<sup>2</sup> 
	
	*This brings us to* **The Washer Method:** 
	*Let a region bounded by $y=f(x)$, $y=g(x)$, $x=a$, and $x=b$ be rotated about a horizontal axis that does not intersect the region, forming a solid. Each cross section at $x$ will be a washer with outside radius $R(x)$ and inside radius $r(x)$. The volume of the solid is:*
	s
	$V = \pi\int_{a}^{b} (R(x)$<sup>2</sup> $-$ $r(x)$<sup>2</sup>$)dx$   
	
- - - 

###### Examples: 

**Example 3:** *The region $R$ enclosed by the curves $y = 6 - x$<sup>2</sup> and $y = 2$ is rotated about the $x-axis$. Find the volume of the resulting solid.*

![[Pasted image 20240123024614.png]]

**Example 4:** *The region $R$ enclosed by the curves $y = x$<sup>2/3</sup>, $x = 1$, and $y = 0$ is rotated about the $y-axis$. Find the volume of the resulting solid.*

![[Pasted image 20240123024818.png]]

- - - 
###### Backlink: [[Calculus 2]]
