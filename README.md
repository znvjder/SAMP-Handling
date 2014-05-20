SAMP-Handling
-----------

Lista oryginalnego handlingu pojazdów z GTA San Andreas pod multiplayer SA-MP.


Funkcje/Functions
-----------

```sh
- Returns float value
native Float:GetVehicleMass(vehicle);
native Float:GetVehicleDragCoeff(vehicle);
native Float:GetVehicleFrontRearBias(vehicle);
native GetVehicleCenterMass(vehicle, &Float:cx, &Float:cy, &Float:cz);
native Float:GetVehicleSusAntiDriveMul(vehicle);
native Float:GetVehicleSusHighSpeedDpg(vehicle);
native Float:GetVehicleSusLowerLimit(vehicle);
native Float:GetVehicleSusUpperLimit(vehicle)
native Float:GetVehicleSusForceLvl(vehicle);
native Float:GetVehicleSteeringLock(vehicle);
native Float:GetVehicleTurnMass(vehicle);
native Float:GetVehicleTractionMultiplier(vehicle);
native Float:GetVehicleEngineAccel(vehicle);
native Float:GetVehicleEngineInertia(vehicle);
native Float:GetVehicleTractionBias(vehicle);
native Float:GetVehicleTractionLoss(vehicle);
native Float:GetVehicleTractionLoss(vehicle);
native Float:GetVehicleDistSeatOffset(vehicle);
native Float:GetVehicleSusDamping(vehicle);
native Float:GetVehicleCollisionDmg(vehicle);
native Float:GetVehicleMaxVelocity(vehicle);
- Returns integer
native GetVehicleNumberOfGear(vehicle);
native GetVehiclePercentSubMerged(vehicle);
- Returns string
native GetVehicleEngineType(vehicle); 
native GetVehicleDriveType(vehicle);
```

Licencja/License
-----------

GPLv2
