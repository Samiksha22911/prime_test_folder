## Easy Test - Prime Number Distribution Analysis
[https://Samiksha22911.github.io/prime_test_folder](https://Samiksha22911.github.io/prime_test_folder)
# Errors:
1. Warning: Ignoring unknown aesthetics: clickSelects
   
   Cause: This happens because the standard ggplot2 library does not recognize clickSelects. If both ggplot2 and animint2 are loaded at the same time, R might use the wrong version of the ggplot() function.
   
   Fix: You must explicitly tell R to use the animint2 version by writing animint2::ggplot() instead of just ggplot().
   
   <img width="479" height="151" alt="image" src="https://github.com/user-attachments/assets/79ec5a72-7fbc-464e-b25d-052de978dd41" />



2.Error: Use of clickSelects and showSelected as aesthetics has been deprecated.

  Cause: In older versions of the animint2 package, clickSelects was placed inside the aes() function. However, the package has been updated. Now, it is no longer considered an "aesthetic" (like color or size); it is a parameter of the geom.
  
  Fix: You must move clickSelects outside of the aes() brackets.
  
  <img width="509" height="296" alt="image" src="https://github.com/user-attachments/assets/e5badeb4-d61a-4202-b1a9-4794960d5b60" />


