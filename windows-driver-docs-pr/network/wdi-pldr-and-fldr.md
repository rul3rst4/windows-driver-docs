---
title: WDI PLDR Recovery
description: This section describes recovery of PLDR for WDI drivers
ms.date: 04/20/2017
---

# PLDR


## Recovery of PLDR


After the surprise-remove, the drivers (both UE and LE) must release all resources so that the device object can be removed and re-enumerated (by the bus). If this does not happen, the device is not re-enumerated, and therefore not recovered.

 

 





