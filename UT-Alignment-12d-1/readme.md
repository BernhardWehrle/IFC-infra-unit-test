
### Intent

IFC 4x3 RC2
This scenario has a simple alignment with left arc in horizontal and no vertical.

That is it has Civil Horizontal Geometry (HG):

- straight
- an arc with IFC positive radius of curvature
- a straight

In the IFC file there is only the IFC semantic definition of the alignment and no IFC geometry.
The IFC file was generated by 12d Model. 

### Prerequisites

- ProjectSetup-1

### Content

This scenario covers the additional concepts and/or IFC entities:

- `IfcAlignment`                  - fudged `Axis` as there is no Ifc geometry
- `IfcAlignmentHorizontal`
- `IfcAlignmentHorizontalSegment` with `PredefinedType=LINE`
- `IfcAlignmentHorizontalSegment` with `PredefinedType=CIRCULARARC` for a left arc

### Supporting files

Following files correspond to this scenario:

| Filename                        | Description                                                                           |
|---------------------------------|---------------------------------------------------------------------------------------|
| `UT-Alignment-12d-1.ifc`        | the exported content as an IFC file                                                   |
| `UT-Alignment-12d-1.png`        | plan view of the alignment, and the horizontal segment parameters (with Civil radius) |


