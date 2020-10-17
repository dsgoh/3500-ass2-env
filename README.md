# 3500-ass2

**NOTE THAT THIS REPO WAS MADE SO YOU DON'T HAVE TO SETUP YOUR DEV ENV FROM SCRATCH**

## Specification

Design an architecture which includes:
- Process Management Module
- Laser Module
- GNSS Module
- Vehicle Control Module
- Camera Module
- Display Module

Deliverables:
- GPS data display
- Steering and propulsion contorl of UGV
- Graphical display of laser data, camera data, GPS data

### Process Management Module
Set up "shared memory", start up all processes, monitor operational health of all processes, and shutdown of all processes.

1. Set up shared memory, shared memory module must provide:
  1. Read/write access to laser data
  2. Read/write access to GPS data
  3. Read/write access to camera data
  4. Read/write access to vehicle contorl data
  5. Read/write access to process management data
2. Start all other processes in logical sequence suitable for teleop of UGV
3. Monitor process heartbeats
  1. Shutdown event if failure of critical process
  2. Attempt to restart failed non-critical processes
  3. Indicate main process is alive. If dead, shutdown.
4. Routine shutdown of all processes in response to keypress event

### Laser Module

### GNSS Module

### Camera Module

### Vehicle Control Module

### Display Module

## Assessment
1. Complete above
2. Process check in week 8 to demonstrate architecture
3. Complete assessment in week 10
4. Submit work in zip file on 20 November.
