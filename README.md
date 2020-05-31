## New technologies used in this project
#### curently only Firefox browser supports all of them
___

### clamp()

##### The clamp() CSS function clamps a value between an upper and lower bound. clamp() enables selecting a middle value within a range of values between a defined minimum and maximum. It takes three parameters: a minimum value, a preferred value, and a maximum allowed value.
##### The clamp() function takes three comma separated expressions as its parameter, in the order of minimum value, preferred value, maximum value.
##### clamp(MIN, VAL, MAX) is resolved as max(MIN, min(VAL, MAX))
##### font-size: clamp(1rem, 10vw, 2rem); 
##### Note that using clamp() for font sizes, allows you to set a font-size that grows with the size of the viewport, but doesn't go below a minimum font-size or above a maximum font-size.
___

### subgrid

##### If you set the value subgrid on grid-template-columns, grid-template-rows or both, instead of creating a new track listing the nested grid uses the tracks defined on the parent.
##### For example, if you use grid-template-columns: subgrid and the nested grid spans three column tracks of the parent, the nested grid will have three column tracks of the same size as the parent grid. Gaps are inherited but can also be overridden with a different gap value. Line names can be passed from the parent into the subgrid, and the subgrid can also declare its own line names.
##### Note that line numbering restarts inside the subgrid — column line 1, when inside the subgrid, is the first line of the subgrid. The subgridded element doesn't inherit the line numbers of the parent grid. This means that you can safely lay out a component that may be placed in different positions on the main grid, knowing that the line numbers on the component will always be the same.
___

#### Other grid related technologies used in this project

##### grid-auto-flow: dense;
##### grid-auto-rows: min-content;