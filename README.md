# obj2urdf
Simple script to wrap an .obj file in a .urdf file.

## Description
Creates a .urdf file wrapping a .obj file representing
the 3D geometry of an object.
The urdf file is created in the same folder as the obj
file.

## Usage
```bash
python obj2urdf.py <path to the file.obj>
```
By default the object is made white, its position set
to 0, its scale set to 1, and its inertia set to 0.