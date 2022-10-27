# DEV-09, Scattering a Collection 
### Link:[<https://www.canopy.games/courses/bcs-geometry-nodes-3x/lectures/42544238>]
#### Tags: []

## Scattering Points

### Distribute Points on Faces

<img src="../images/DEV-09/DEV-09-A1.png" width="1100"/>
<img src="../images/DEV-09/DEV-09-A2.png" width="1100"/>

### Collection info
    We get this node by dragging in our collection into the geometry node viewport

### Instance on Points
<img src="../images/DEV-09/DEV-09-A3.png" width="1100"/>
<img src="../images/DEV-09/DEV-09-A4.png" width="1100"/>

## Why are the instanced collection items off the origin?
    When we instanced our collection, we also took into consideration their location and that is something we need to disable.
    To do so we separate the children and reset the children to reset their position.

<img src="../images/DEV-09/DEV-09-A5.png" width="1100"/>

## Why are my collection items fused together?
<img src="../images/DEV-09/DEV-09-A6.png" width="1100"/>

    on the Instance on Points node, we need to select pick instances. This will make each point pick a different instance

<img src="../images/DEV-09/DEV-09-A7.png" width="1100"/>

## Why are my collection items rotation off?
<img src="../images/DEV-09/DEV-09-A8.png" width="1100"/>
<img src="../images/DEV-09/DEV-09-A9.png" width="1100"/>
<img src="../images/DEV-09/DEV-09-A10.png" width="1100"/>

## Why are my collection items scale off?
<img src="../images/DEV-09/DEV-09-A11.png" width="1100"/>
