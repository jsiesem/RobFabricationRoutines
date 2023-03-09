# RobFabricationRoutines
 Repo for archiving miscellaneous rapid routines for ABB robots
 
## Brickstacking
### BrickProcedures
Procedures for eased pickup of bricks with a pneumatic gripper, saves last pickup position index and continues with subsequent ones if called.
- setPickUpGrid
  - Set grid for pickup locations
- ResetLoopCounter
  - Reset following brick index to 1
- GetBrick
  - Picks up brick and moves to recorded save location

## MarbleProcedures
Procedures for more intuitive use of a diamond wiresaw for stone cutting. Includes exemples intended as starting point for small rapid seminar on digital craftmanship
- onepoint
  - simple tcp translation in y-axis by given distance
- twopointlinear
  - version of previous command that allows modified starting point and safe movement over workpiece from defined end-point to movement start-point
- twopointscallop
  - motion producing a scallop-cut; function for mid position interpolation draws from: [Robert Andersson](https://github.com/ernell/ABB-RAPID-UTILITY-LIBRARY/blob/master/Contributions/RobertAndersson/lib_rob.sys)
