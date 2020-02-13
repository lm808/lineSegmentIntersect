# lineSegmentIntersect
Finds the pairwise intersection points between line segments in 2D Cartesian space. 

## Usage
```matlab
OUT = lineSegmentIntersect(XY1,XY2)
```
Generates intersection analysis between the line segment sets given in XY1 and XY2. Code can handle coincident and parallel lines.

The main emphasis is on speed. The code is fully vectorized and it runs pretty fast (orders of magnitude) compared to some of the previous postings.

## Cite As
U. Murat Erdem (2020). Fast Line Segment Intersection (https://www.mathworks.com/matlabcentral/fileexchange/27205-fast-line-segment-intersection), MATLAB Central File Exchange. Retrieved February 13, 2020. 

## Version
version 1.1.0.0 (3.5 KB) by U. Murat Erde

Forked manually and unaltered from the above URL. All credits go to the original author.
