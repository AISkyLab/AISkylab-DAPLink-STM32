Place following files here:

- Mechanical Drawing (Board dimensions, holes position, ..)
- TOP and BOTTOM Assembly Drawing (Component position with Reference Designator)
- TOP and BOTTOM VIEW (shows board outline, assembly layer, TOP + BOTTOM layers)
- Bill of Materials (grouped by component type)
- Component reference BOM (each component on one line: Designator, Description, Manufacturer 1,
  Manufacturer, Part Number 1, Package / Case, Supplier 1, Supplier Part Number 1)
- Component reference BOM (as above) grouped by component type.
- Pick and Place
- TOP and BOTTOM Layer + TOP and BOTTOM Paste Gerber Files (for stencil - if panel is done in a PCB house, ask them later for the top/bottom layers and paste for the panel)
- PDF 3D Model

!!! BE AWARE !!! If you use a VARIANT were you replace a component by other component,
THIS WILL NOT BE REFLECTED IN ASSEMBLY DRAWING and component will look like not fitted.
This may be a bug in Altium 14.3. Use a TEMP Schematic to generate the ASM DRWG. SAME
FOR PICK & PLACE!!

