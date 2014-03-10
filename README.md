CE3
===

Moore Elevator Controller:
https://github.com/KevinJagoda/CE3/blob/master/MooreElevatorController_Shell.vhd

Moore Testbench:
https://github.com/KevinJagoda/CE3/blob/master/Moore_testbench_Jagoda.vhd

Moore results:
https://github.com/KevinJagoda/CE3/blob/master/1.JPG

-----------------------------------------------------------------------------------------

Mealy Elevator Controller:
https://github.com/KevinJagoda/CE3/blob/master/MealyElevatorController_Shell.vhd

Mealy Testbench:
https://github.com/KevinJagoda/CE3/blob/master/Mealy_testbench_Jagoda.vhd

Mealy results:
https://github.com/KevinJagoda/CE3/blob/master/2.JPG

-----------------------------------------------------------------------------------------

After looking at the Moore and Mealy results, you know it is correct. This is due to the following:
- Elevator stays on the same floor when stop is '1'
- Elevator transfers to another floor when stop is '0'
- Elevator moves during the time period set by the testbenches
