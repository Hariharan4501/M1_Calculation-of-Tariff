# Test Plan
<br>
## High Level Test Plan
<br>
| Units |  Calculation | Expected input | Expected output | Actual output | Type of Test | 
|--------|-------------------|-----------------|----------------|-----------|
|HP01| previous reading | current reading | Units | Enters to group | Pass Requirement | 
|HP02| Bill Amount | Group | Bill amount will be calculated | Pass Requirement|
<br>
<br>
<br>

## Low Level Test Plan
<br>
|Units | Previous reading | Current reading | Expected output | Actual output | Type of test|
|-------|---------------------|---------------|-------------|----------------------|
|LP01| Previous reading ang current reading is given | Integer 1| View the readings | pass | Requirement |
|LP02| Units will be calculated | Interger 2| View the units | Pass | Requirement |
|LP03| Selection of group to calculate the bill amount | Exit | Pass | requirement | 
|LP04| Three groups are available | Pass | Requirement|
|LP05| You can select group | char group| pass | Requirement|
|LP06| The rate of charge will be noted | Pass | Requirement |
|LP07| The energy charges will get | Pass | Requirement |
|LP08| The energy charges will be added to customer charges ,ED,Fixed charges | Pass | Requirements |
|LP09| Bill amounts will get as output | Exits from loop | Pass | Requirement |
## USAGE UNITY TEST FRAMEWORK:
The Unity Test Framework (UTF) enables Unity users to test their code in both Edit Mode and Play Mode, and also on target platforms such as Standalone, Android, iOS, etc.
UTF uses a Unity integration of NUnit library, which is an open-source unit testing library for .Net languages.
It is possible to extend the Unity Test Framework (UTF) in many ways, for custom workflows for your projects and for other packages to build on top of UTF.


## Best Practices

 - [x] Checked all the possibilities of output
 - [x] Mentioned all the inputs for better understanding
 - [x] Presented in tabular form for easy understanding
 - [x] Both High level and low level Test plans are shown
