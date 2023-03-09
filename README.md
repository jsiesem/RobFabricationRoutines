# RobFabricationRoutines
 Repo for archiving miscellaneous rapid routines for an ABB robots
 
## Brickstacking
### BrickProcedures
Procedures for eased pickup of bricks with a pneumatic gripper, saves last pickup position index and continues with subsequent ones if called.
- setPickUpGrid
  - Set grid for pickup locations
- ResetLoopCounter
  - Reset following brick index to 1
- GetBrick
  - Picks up brick and moves to recorded save location
