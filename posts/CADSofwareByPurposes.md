# CAD Softwares By Purpose
Your CAD needs are already met. You just need to discover what you need.

**Author:** David Malawey
**First Draft:** 12/14/2024  

---

## Filetypes: What's in a Native CAD Model?

| Feature                       | NATIVE | .STEP | .STL | Note |
|-------------------------------|--------|-------|------|------|
| **File Size**                 | Medium | Small | Large | 1    |
| **Geometries**                | Unique bodies | Merged | Merged | 2    |
| **Assemblies of parts**       | Unique parts  | Retain geometry | Approximated geometry | 3    |
| **Material specifications**   | YES    | YES   | NO   | 4    |
| **Axes, planes, & coordinate systems** | YES | YES | NO | 4    |
| **Printers need**             | NO     | NO    | YES  | 5    |
| **System-designers need**     | NO     | YES   | NO   | 6    |
| **Feature-designers need**    | NO     | YES   | NO   | 7    |
| **Generates NATIVE?**         | YES    | NO    | NO   | 8    |
| **Generates STEP?**           | YES    | YES   | NO   | 9    |
| **Generates STL?**            | YES    | YES   | YES  | 10   |

---

## Notes:

1. **File size for a full-resolution design.**  
2. STEP and STL are files designed to transmit a geometry. For a native software, one file is for one design output. Designing & modeling differences must be understood.  
3. Native files have feature trees. Features may include geometry or many other things, even the history (chronological sequencing of features), which impacts a great deal.  
4. A designer is adjusting designs in their preferred native design software.  
5. A user of a 3D printer needs an "exported" or "compiled" and fixed geometry to perform slicing.  
6. A designer of a conveyor system wants the simplest, lightest model of a conveyor motor – they are not adjusting the motor geometry.  
7. If the design is a large part and the feature attaches to the large part (e.g., a grommet for a hole in a panel), they need the simplest representation.  
8. Only native parts can be copied to new native parts without any losses. CAD add-ons such as "feature import wizard" can accelerate making a native file from a STEP geometry.  
9. Only native designs can export STEP geometries. Other file types may be used if the developer first converts to a native file.  
10. STL is like a BMP – a fixed rendering of geometric data. It is always lossless, i.e., when a circle is exported to STL, it will become a polygon. Polygons have finite resolution.  