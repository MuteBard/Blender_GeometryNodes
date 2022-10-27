# DEV-02, A First Scatter
### Link:[<https://www.canopy.games/courses/bcs-geometry-nodes-3x/lectures/42544224>]
#### Tags: [Distribute Points on Faces, Instance on Points, Random Value, Join Geometry]

## Scatter an Object

    In order to scatter an object you need two things:
         The positions that we are going to scatter these things on
         The literal thing, the object to scatter

### Points | Distribute Points on Faces 

    In order for to generate points, random points on a surface is with a node called
    Distribute Points on Faces

<img src="../images/DEV-02/DEV-02-A1.png" width="1100"/>
<img src="../images/DEV-02/DEV-02-A2.png" width="1100"/>

### Instancing | Instance on Points

    The next thing that we want to do is make objects exist on those points.

<img src="../images/DEV-02/DEV-02-A3.png" width="1100"/>
<img src="../images/DEV-02/DEV-02-A4.png" width="1100"/>
<img src="../images/DEV-02/DEV-02-A5.png" width="1100"/>
<img src="../images/DEV-02/DEV-02-A6.png" width="1100"/>

    Make the original object hidden from viewport and render

<img src="../images/DEV-02/DEV-02-A7.png" width="1100"/>

    Better yet, make a new collection of your inputs and then make hidden

<img src="../images/DEV-02/DEV-02-A8.png" width="1100"/>

## Managing Random Rotation and Scale

<img src="../images/DEV-02/DEV-02-B1.png" width="1100"/>
<img src="../images/DEV-02/DEV-02-B2.png" width="1100"/>

### Rotation | Random Value (Vector) 

    The rotation is not intense enough from whats seen here. Rotation is measured in radians, where 2 * pi or tau is considered one rotation.
    1 across the board as the max as seen here is only a fraction of that.

    Use 2 * pi
<img src="../images/DEV-02/DEV-02-B4.png" width="1100"/>

    Or Use tau
<img src="../images/DEV-02/DEV-02-B5.png" width="1100"/>

    Both result into the same thing
<img src="../images/DEV-02/DEV-02-B6.png" width="1100"/>

### Scale | Random Value (Float) 

    We want the scale to be consistent across x y and z. A vector random would make these all randomize which is not what we want.
    SO we will use a float random to keep x y and z consistent with each other.

<img src="../images/DEV-02/DEV-02-B7.png" width="1100"/>

## Combining everything

### Combining | Join Geometry

<img src="../images/DEV-02/DEV-02-C1.png" width="1100"/>
<img src="../images/DEV-02/DEV-02-C2.png" width="1100"/>
