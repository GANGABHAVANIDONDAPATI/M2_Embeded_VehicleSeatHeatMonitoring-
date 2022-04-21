# Test Plan
## High Level Test plan
| Test ID |	Description | Exp I/P |	Exp O/P |	Actual Out |	Type of Test |
| ----- | ------- | -------- | --------- | --------- | --------- | 
| HLT_01 |	Seat Switch is ON and Heater Switch is OFF |	Seat Switch is ON |	LED will not GLOW |	SUCCESS |	Requirement Based | 
| HLT_02 |	Seat Switch is OFF and Heater Switch is ON |	Heater Switch is ON |	LED will not GLOW |	SUCCESS |	Requirement Based |
 |HLT_03 |	Seat Switch is ON and Heater Switch is ON |	Both Switches are ON |	LED will GLOW |	SUCCESS |	Requirement Based |
##Low Level Test Plan
| Test ID |	Description |	Exp I/P |	Exp O/P |	Actual Out |	Type of Test | 
| ----- | ------ | ------- | --------- | --------- | ---------- |
| LLR_01 |	Duty Cycle |	20% |	Temperature displayed in the LCD |	SUCCESS |	Requirement Based |
| LLR_02 |	Duty Cycle |	40% |	Temperature displayed in the LCD |	SUCCESS |	Requirement Based |
| LLR_03 |	Duty Cycle |	70% |	Temperature displayed in the LCD |	SUCCESS |	Requirement Based |
| LLR_04 |	Duty Cycle |	95% |	Temperature displayed in the LCD |	SUCCESS |	Requirement Based |
# Output
## When Requirements not met
* Case1: When both the Seat Switch and HeaterSwitch turned off

![case1](https://user-images.githubusercontent.com/101049340/164465678-143e4417-5827-46a9-97f9-6198cb1123eb.jpeg)

* Case2: When Seat Switch is on and Heater Switch is OFF

case2

* Case 3: When Seat switch is OFF and Heater Switch is ON

case3

* Case4: When both the switches are ON

case4

## Both Switches ON
| Duty Cycle |	Output | | ---- | ------- |
| 20% |	20 |
| 40% |	40 |
| 70% |	70 |
| 95% |	90 |
