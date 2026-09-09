# Agricultural Field Shape Classification Dataset

A dataset of agricultural field geometries organized into seven potentially overlapping shape categories.

This dataset is part of the following PhD thesis: 

**Hoeffmann, Maria. Optimal Coverage Path Planning for Agricultural Machines. University of Bremen. [final publication in process].**
Details about the classification process can be found there.



## Classes

| Class | Number of Fields |
|----------|----------|
| Convex | 45 |
| Rectangular | 26 |
| Smooth | 46 |
| Elongated | 21 |
| Obstacles | 26 |
| Irregular | 69 |
| HighlyIrregular | 53 |

## Structure

```text
Convex/
Rectangular/
Smooth/
Elongated/
Obstacles/
Irregular/
HighlyIrregular/
```

Each JSON file contains:

- Classification labels
- Shape metrics
- Polygon geometry
- Obstacle geometry (if present)

Each class folder additionally contains:

- README.md
- gallery.png
- images/*.png
