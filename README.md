Drivetek_MPPT
=============

Drivetek_MPPT This code came from Cal Sol (Berkeley CA) solar car team. We at UK have the same devices, but I am unable to find our copy. We plan to change the operating values in this code.  It is critical to note that Cal Sol has licensed this as GPL2. Any update that is made to this code must be shared. 

Eclipse Solar Car
=================
The Eclipse Solar Car team forked the KentuckySolarCar Drivetek_MPPT github repository. We made modifications to be able to regenerate our hex files with edited values.

MPLAB X IDE
===========
- Download MPLAB X IDE 5.35 (last one to support MPASM toolchain)
  - In the installation, install package for 8bits MCUs. DriveTek's MCU is: PIC16F877
- Open MPLAB X IDE
- Select Import -> MPLAB IDE v8 Project
- Click Browse and select the `MPPT.mcp` file
- At the compiler selection, select mpasm -> mpasm
- Once the project has been imported, you should be able to build it

Drive-tek mppt Version 4
========================
![Drive-tek mppt Version 4](img/device.JPG)
