# Testing

## Unit Tests: 
  - Job Class: <br>
    -- Create using constructor and fill in with additional functions -- Works<br>
    -- Create using contructor and filling in with constructor -- Works<br>
    -- Output override --Works <br><br>
  - Occupant Class:<br>
    -- Create using constructor and fill in with additional functions -- Works<br>
    -- Create using contructor and filling in with constructor --Works <br>
    -- Output override -- Works<br><br>
  - Vehicle Class: <br>
    -- Create using constructor and fill in with additional functions --Works <br>
    -- Create using contructor and filling in with constructor -- Works <br>
    -- Output override -- Works<br><br>
  - IO Class: <br>
    -- Output a job to a file -- Broken but fixable by end of year <br><br>
  - Front End: <br>
    1.	Test all buttons and non-editable (read-only) boxes and make sure they have tool tips that display <br>
    + Quick Access Bar<br>
      + AutoSave Button -- Displays Auto Save<br>
      + Save Button -- Displays Save to Desktop<br>
      + Save to Cloud Button -- Displays Save to Cloud<br>
      + Send to Report -- Displays Send Info to Create Report <br>
      + Undo Button -- Displays Undo <br>
      + Redo Button -- Displays Redo <br>
    + Top Ribbon File Tab<br>
      + Save Button -- Displays Saves the current job to a specified location <br>
      + Print Button -- Displays Print the report <br>
      + Save to Cloud Button -- Displays Saves current job to cloud <br>
      + Export Button -- Displays Export to database <br>
      + Create Report Button -- Displays Compiles the information into a report which can then be printed <br>
      + Import Data Button -- Displays Allows you to import data stored on the server from the mobile app <br>
      + Open Button -- Displays Open a previously saved job <br>
      + Create New Job Button -- Displays Create a New Job <br>
      + Exit Button -- Displays Exit Current Job <br>
    + Top Ribbon Edit Tab<br>
      + Undo Button -- Displays Undo <br>
      + Redo Button -- Displays Undo <br>
      + Cut Button -- Displays Cut <br>
      + Copy Button -- Displays Copy <br>
      + Paste Button -- Displays Paste <br>
      + Select Button -- Displays Select <br>
    + Top Ribbon Draw Tab<br>
      + Point Button -- Displays Draw Points (advanced options on left panel)<br>
      + Line Button -- Displays Draw Lines (advanced options on left panel)<br>
      + Polyline Button -- Displays Draw Polylines (advanced options on left panel) <br>
      + Curve Button -- Displays Draw Curves (advanced options on left panel) <br>
      + Arc Button -- Displays Draw Arcs (advanced options on left panel) <br>
      + Circle Button -- Displays Draw Circles (advanced options on left panel) <br>
      + Rectangle Button -- Displays Draw Rectangles (advanced options on left panel)<br>
      + Photo Button -- Displays Display Photos <br>
      + Fill Button -- Displays Fill (advanced options on left panel) <br>
    + Right Panel Tabs<br>
      + General Info Tab -- Displays Display General Info <br>
      + Vehicle Info Tab -- Displays Display Vehicle Infor <br>
      + Occupant Info Tab -- Dipslays Display Occupant Info <br>
      + Reference Mats Tab -- Displays Display Reference Materials <br>
    + General Info Page<br>
      + Location of Crash Box -- Displays Location of the Crash<br>
      + Date/Time Box -- Displays Date and Time of the Crash in EST <br>
      + Temp Box -- Displays Temperature Outside at the time of the crash in F <br>
      + Visibility Box -- Displays Visibility Outside at the time of the crash <br>
      + Weather Box -- Displays Weather Outside at the time of the crash <br>
      + Lighting Box -- Displays Lighting at the location of the crash <br>
      + Roadway Surface Box -- Displays Type of Roadway Surface at the location of the crash <br>
      + Speed Limit Box -- Displays Speed Limit at the location of the crash <br>
      + Drag Factor Box -- Displays Estimated Drag Factor <br>
      + Exit Button -- Displays Exit General Info <br>
    + Vehicle Info Pages <br>
      + Year Box -- Displays Year of Vehicle <br>
      + Make Box -- Displays Make of Vehicle <br>
      + Model Box -- Displays Model of Vehicle <br>
      + License Plate, State, Expiration Date Box -- Displays License Plate Number, State it was issued in, and Expiration Date<br>
      + Color Box -- Displays Color of Vehicle <br>
      + VIN Box -- Displays Vehicle VIN Number <br>
      + Specs Box -- Displays Specs on Vehicle<br>
      + Number in Crash Box -- Displays Number Vehicle assigned in reference to the crash <br>
      + Next Button -- Display Next Vehicle Info<br>
      + Previous Button -- Display Previous Vehicle Info <br>
      + Exit Button -- Displays Exit Vehicle Info <br>
    + Occupant Info Pages <br>
      + Name Box -- Displays Name <br>
      + Address Box -- Displays Address of Person<br>
      + Phone Number Box -- Displays Phone Number <br>
      + Birthdate Box -- Displays Birthdate of Person <br>
      + Vehicle Number Box -- Displays Vehicle Number this person is associated with<br>
      + Position in Car -- Displays Position in Car <br>
      + Impairment -- Displays Impairment at Time of Accident<br>
      + Point of View Box -- Displays Point of View if the person is a witness<br>
      + Next Button -- Displays Next Occupant <br>
      + Previous Button -- Displays Previous Occupant<br>
      + Exit Button -- Displays Exit Occupant Info<br>
    + Upper Left Panel <br>
      + Cut Button -- Displays Cut <br>
      + Copy Button -- Displays Copy <br>
      + Paste Button -- Displays Paste <br>
      + Snaps Group Box -- Displays Snaps <br>
      + -- N Button -- Displays Near <br>
      + -- E Button -- Displays East <br>
      + -- M Button -- Displays Middle of a Line <br>
      + -- C Button -- Displays Center of a Circle <br>
      + -- I Button -- Displays Intersection <br>
      + -- T Button -- Displays Tangent <br>
      + -- J Button -- Displays Jump <br>
      + -- G Button -- Displays Grid <br>
      + -- A Button -- Displays Angle <br>
      + Grid On/Off Toggle -- Displays Turn Grid On <br>
      + Spacing Box -- Displays Grid Spacing <br>
      + Layers Button -- Displays Layers <br>
    + Left Panel Point Page
      + Feet/Metric Drop Down -- Displays Feet or Metric Measurements <br>
      + X - Coordinate Box -- Displays X-Coordinate of Point <br>
      + Y - Coordinate Box -- Displays Y-Coordinate of Point <br>
      + Elevation Box -- Displays Elevation of Point <br>
      + Point to Symbol Drop Down -- Displays Point to Symbol <br>
      + Exit Button -- Displays Exit Left Panel <br>
    + Left Panel Line Page <br>
      + Feet/Metric Drop Down -- Displays Feet or Metric Measurements <br>
      + Length Box -- Displasy Length of Line <br>
      + Width Box -- Displays Width of Line <br>
      + Color Box -- Displays Color of Line <br>
      + Starting Elevation Box -- Displays Starting Elevation of Line <br>
      + Ending Elevation Box -- Displays Ending Elevation of Line <br>
      + Roadway Lines Drop Down -- Displays Roadway Lines <br>
      + Symbols Drop Down -- Displays Symbols <br>
      + Symbol Spacing -- Displays Spacing between Symbols <br>
      + Exit Button -- Displays Exit Left Panel <br>
    + Left Panel Polyline Page
      + Feet/Metric Drop Down -- Displays Feet or Metric Measurements <br>
      + Length Box -- Displasy Length of Polyline <br>
      + Width Box -- Displays Width of Polyline <br>
      + Color Box -- Displays Color of Polyline <br>
      + Starting Elevation Box -- Displays Starting Elevation of Polyline <br>
      + Ending Elevation Box -- Displays Ending Elevation of Polyline <br>
      + Roadway Lines Drop Down -- Displays Roadway Lines <br>
      + Symbols Drop Down -- Displays Symbols <br>
      + Symbol Spacing -- Displays Spacing between Symbols <br>
      + Polyline Button -- Displays Polyline (Type of Polyline)<br>
      + Perpendicular Polyline Button -- Displays Perpendicular Polyline (Type of Polyline)<br>
      + Exit Button -- Displays Exit Left Panel <br>
    + Left Panel Curve Page
      + Feet/Metric Drop Down -- Displays Feet or Metric Measurements <br>
      + Length Box -- Displasy Length of Curve <br>
      + Width Box -- Displays Width of Curve <br>
      + Color Box -- Displays Color of Curve <br>
      + Starting Elevation Box -- Displays Starting Elevation of Curve <br>
      + Ending Elevation Box -- Displays Ending Elevation of Curve <br>
      + Roadway Lines Drop Down -- Displays Roadway Lines <br>
      + Symbols Drop Down -- Displays Symbols <br>
      + Symbol Spacing -- Displays Spacing between Symbols <br>
      + Fitted Button -- Displays Fitted (Type of Curve)<br>
      + Spline Button -- Spline (Type of Curve)<br>
      + Exit Button -- Displays Exit Left Panel <br>
    + Left Panel Arc Page
      + Feet/Metric Drop Down -- Displays Feet or Metric Measurements <br>
      + Length Box -- Displasy Length of Arc <br>
      + Width Box -- Displays Width of Arc <br>
      + Color Box -- Displays Color of Arc <br>
      + Starting Elevation Box -- Displays Starting Elevation of Arc <br>
      + Ending Elevation Box -- Displays Ending Elevation of Arc <br>
      + Roadway Lines Drop Down -- Displays Roadway Lines <br>
      + 3-point Arc Button -- Displays 3-point Arc (Type of Arc)<br>
      + --  X Box -- Displays X-Coordinate for 3-point arc <br>
      + -- Y Box -- Displays Y-Coordinate for 3-point arc <br>
      + -- Radius Box -- Displays Radius of 3-point arc <br><br>
      + 2-points ang Button -- Displays 2-points and angle arc (Type of Arc)<br>
      + -- X Box -- Displays X-Coordinate for 2-points and angle arc<br>
      + -- Y Box -- Displays Y-Coordinate for 2-points and angle arc<br>
      + -- Radius Box -- Displays Radius of 2-points and angle arc <br><br>
      + 2-points ctr Button -- Displays 2-points and center arc (Type of Arc) <br>
      + -- X Box -- Displays X-Coordinate for 2-points and center arc<br>
      + -- Y Box -- Displays Y-Coordinate for 2-points and center arc<br>
      + -- Radius Box -- Displays Radius of 2-points and center arc<br><br>
      + Exit Button -- Displays Exit Left Panel <br>
    + Left Panel Circle Page
      + Feet/Metric Drop Down -- Displays Feet or Metric Measurements <br>
      + Length Box -- Displasy Length of Circle <br>
      + Width Box -- Displays Width of Circle <br>
      + Color Box -- Displays Color of Circle <br>
      + ctr and side Button -- Displays Center Point and Side Circle (Type of Circle)<br>
      + -- X Box -- Displays X-Coordinate for Center Point and Side Circle<br>
      + -- Y Box -- Displays Y-Coordinate for Center Point and Side Circle<br>
      + -- Radius Box -- Displays Radius of Center Point and Side Circle<br><br>
      + 2-sides Button -- Displays 2-Sides Circle (Type of Circle)<br>
      + --X Box -- Displays X-Coordinate for 2-Sides Circle<br>
      + -- Y Box -- Displays Y-Coordinate for 2-Sides Circle<br>
      + -- Radius Box -- Displays Radius of 2-Sides Circle<br><br>
      + 3-point Button--- Displays 3-Point Circle (Type of Circle)<br>
      + -- X Box -- Displays X-Coordinate for 3-Point Circle<br>
      + -- Y Box -- Displays Y-Coordinate for 3-Point Circle<br>
      + -- Radius Box -- Displays Radius of 3-Point Circle<br><br>
      + ctr and radius Button -- Displays Center Point and Radius Circle (Type of Circle)<br>
      + -- X Box -- Displays X-Coordinate for Center Point and Radius Circle<br>
      + -- Y Box -- Displays Y-Coordinate for Center Point and Radius Circle<br>
      + -- Radius Box -- Displays Radius of Center Point and Radius Circle<br><br>
      + 2-tangent Button -- Displays 2-Tangent Line Circle (Type of Circle)<br>
      + -- X Box -- Displays X-Coordinate for 2-Tangent Line Circle<br>
      + -- Y Box -- Displays Y-Coordinate for  2-Tangent Line Circle<br>
      + -- Radius Box -- Displays Radius of  2-Tangent Line Circle<br><br>
      + Ellipse rect Button -- Displays Ellipse Rectangle Circle (Type of Circle)
      + -- X Box -- Displays X-Coordinate for Ellipse Rectangle Circle<br>
      + -- Y Box -- Displays Y-Coordinate for  Ellipse Rectangle Circle<br>
      + -- Radius Box -- Displays Radius of  Ellipse Rectangle Circle<br><br>
      + Ellipse axis Button -- Displays Ellipse Axis Circle (Type of Circle)<br>
      + -- X Box -- Displays X-Coordinate for Ellipse Axis Circle<br>
      + -- Y Box -- Displays Y-Coordinate for  Ellipse Axis Circle<br>
      + -- Radius Box -- Displays Radius of  Ellipse Axis Circle<br><br>
      + Exit Button -- Displays Exit Left Panel <br>
    + Left Panel Rectangle Page
      + Feet/Metric Drop Down -- Displays Feet or Metric Measurements <br>
      + Rectangle Button -- Displays Rectangle (Type of Rectangle) <br>
      + -- Perimeter Box -- Displays Perimeter of Rectangle<br>
      + -- Area Box -- Displays Area of Rectangle<br><br>
      + Irr Poly Button -- Displays Irregular Polygon (Type of Rectangle)<br>
      + -- Perimeter Box -- Displays Perimeter of Irregular Polygon<br>
      + -- Area Box -- Displays Area of Irregular Polygon<br><br>
      + Irr Cloud Button -- Displays Irregular Cloud (Type of Rectangle) <br>
      + -- Perimeter Box -- Displays Perimeter of Irregular Cloud<br>
      + -- Area Box -- Displays Area of Irregular Cloud<br><br>
      + Width of Lines Box -- Displays Width of Lines <br>
      + Exit Button -- Displays Exit Left Panel <br>
    + Left Panel Fill Page
      + Color Button -- Displays open a full color pallet that a user can drag and drop color from the pallet into a closed box which will fill with this color<br>
      + Hatch Button -- Displays open a full texture pallet that a user can drag and drop texture from the pallet into a closed box which will fill with this texture<br><br>
2.	Test all right tabs and make sure they display the correct information <br>
  + General Info Tab -- WORKS
  + Vehicle Info Tab -- WORKS
  + Occupant Infor Tab -- WORKS
3.	Test all buttons on the draw tab and make sure they display the correct left panel <br>
4.	Test all buttons on the file tab <br>
5.	Test all buttons on the edit tab <br>
6.	Test all buttons in the quick access bar <br>
7.	Test all buttons on the left panel <br>
8.	Test all buttons displayed after selecting from a tab on the right panel <br>


## Function Tests: 

## System Tests: 
  -Run tests from both Windows and Apple Machines
  
## Customer Tests:
  -Ensure the customer likes the look of the GUI
  -Ensure customer finds the GUI to be simple enough for intended audience 
