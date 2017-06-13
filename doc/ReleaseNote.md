# iHealth SDK Release Note

### 1. V1.0.14
```
Description: SDK
Release Date: 2015-12-18
```

### 2. V1.0.15
```
Description: fix po3 bug
Release Date: 2016-3-7
```

### 3. V1.0.16
```
Description: More function for AM
Release Date: 2016-5-3
   a. Add dataID for measure result(BP BG HS AM PO),
   	  etc: {"weight":60,"dataID":"xxxxxxx"}  
   b. Add 'activityLevel' property for AM user, 'bmr' property is invalidate now.   
      activityLevel=1, Sedentary,spend most of day sitting.      
      activityLevel=2, Active,spend a good part of day doing some physical activity.  
      activityLevel=3, Very Active,spend most of day doing heavy physical activity.  
   c. Modify calories for AM, etc {Calories = 49,Step = 1213,TotalCalories = 656}  
      Calories is for sport only.  
      TotalCalories sum Calories and bmr.  
```
### 4. V1.0.17
```
Description: fix po3 measure again bug
Release Date: 2016-5-4
```


### 5. V2.0
```
Description: Add Scan and Connect function for iHealth device with low energy.
Release Date: 2016-5-5
```

```
Old version：SDK will scan and connect all iHealth Device automatically.
New version: SDK supply the Api for scan, and Api for connect Separately.

More info, please read class :
ScanDeviceController.h
ConnectDeviceController.h

More details, please read iHealth Demo App

```

### 6. V2.0.1
```
Description: Add Flow Chart, BG errorID.
Release Date: 2016-5-12
```

### 7. V2.1
```
Description:

1. Modify the authentication way, If you want to use the iHealth Device, you must first call authentication method, can call after certification by iHealth relevant methods of the device.
2. Method call any product authentication cancelled.
3. Add support Device:iHealth BP5S 、Continua BP
4. Support GDH code
5. upgrade SDKUpdateDevice Method  support file download progess
6. To optimize the demo program
7. To reconstruct the BP method is called
8. To optimize the interface calls, support the instruction cache

Release Date: 2017-5-5
```
