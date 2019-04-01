
# Axway Titanium module for working with Powermanager


## Usage example


```js
import  PM  from  'de.appwerft.powermanager';
PM.isIgnoringBatteryOptimizations();
PM.isDeviceIdleMode();
PM.isInteractive();
PM.isPowerSaveMode();
PM.isScreenOn();
isWakeLockLevelSupported(level); // one of the constants below
```
## Requesting permission

```js
PM.requestIgnoringBatteryOptimizationsPermission();
```


## Constants

* PARTIAL\_WAKE\_LOCK
* FULL\_WAKE\_LOCK
* SCREEN\_DIM\_WAKE\_LOCK
* SCREEN\_BRIGHT\_WAKE\_LOCK

## Project Usage

Register your module with your application by editing `tiapp.xml` and adding your module.
Example:

<modules>
  <module version="1.0.0">de.appwerft.powermanager</module>
</modules>

When you run your project, the compiler will combine your module along with its dependencies
and assets into the application.
