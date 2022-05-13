# LOWLEVEL TEST CASES

<html>
<body>
<!--StartFragment-->

Test ID  | Description | Input | Expected Output | Actual Output | success/fail
-- | -- | -- | -- | -- | --
01 | Ignition ON  | Press switch 2 sec | RED LED ON | RED LED ON | success
02 | Check LED | Press Button | All LEDs ON | All LEDs ON at 1Hz | success
03 | Check LED|  Press Button | All LEDs ON | All LEDs ON at 4Hz | success
04 | Check LED |  Press Button | All LEDs ON | All LEDs ON at 8Hz | success
04 | Ignition OFF | Press switch 2 sec | RED LED OFF | RED LED OFF | success

<!--EndFragment-->
</body>
</html>


# HIGHLEVEL TEST CASES 

<html>
<body>
<!--StartFragment-->

Test ID | Description | Input | Expected output | Actual Output
-- | -- | -- | -- | --
01 | Ignition On | Press Button 2 sec | Ignition key status | Exhibited
02 | Wiper On | Press Once | 1Hz | Exhibited
03 | Wiper On | Press TWICE | 4Hz | Exhibited
04 | Wiper On | Press THRICE | 8Hz | Exhibited
05 | Ignition Off | Press Button 2 sec | Ignition key status | Exhibited

<!--EndFragment-->
</body>
</html>
