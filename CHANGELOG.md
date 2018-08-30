### 1.1.10: Maintenance Release

**Enhancements**

 - Revision README.md
 - Message property for ADS-OUT/ADS-NOTIFICATION 

**Fixes**

 - Node red does not start if the port number is too large
 - System-state on timer 50 ms decoupled so that it sends less frequently
 - Set system-state to INVALID, when connect-state not RUN
 - Exception by get a message property on ADS-IN 