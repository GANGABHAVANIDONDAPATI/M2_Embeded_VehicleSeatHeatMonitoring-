# Test Plan
## High Level Test plan
| Test ID |	Description |   Exp I/P |	Exp O/P |	Actual Out |	Type of Test | 
| ----- | ------- | -------- | --------- | --------- | --------- | 
| HLT_01 |	Seat Switch is ON and Heater Switch is OFF |	Seat Switch is ON |	LED will not GLOW |	SUCCESS |	Requirement Based | 
| HLT_02 |	Seat Switch is OFF and Heater Switch is ON |	Heater Switch is ON |	LED will not GLOW |	SUCCESS |	Requirement Based |
 |HLT_03 |	Seat Switch is ON and Heater Switch is ON |	Both Switches are ON |	LED will GLOW |	SUCCESS |	Requirement Based |
## Low level test plan
| Test ID |	Description |	Exp I/P |	Exp O/P |	Actual Out |	Type of Test | 
| ----- | ------ | ------- | --------- | --------- | ---------- |
| LLR_01 |	Duty Cycle |	20% |	Temperature displayed in the LCD |	SUCCESS |	Requirement Based |
| LLR_02 |	Duty Cycle |	40% |	Temperature displayed in the LCD |	SUCCESS |	Requirement Based |
| LLR_03 |	Duty Cycle |	70% |	Temperature displayed in the LCD |	SUCCESS |	Requirement Based |
| LLR_04 |	Duty Cycle |	95% |	Temperature displayed in the LCD |	SUCCESS |	Requirement Based |
# Output
## When Requirements not met
* Case1: When both the Seat Switch and HeaterSwitch turned off

![case1](https://user-images.githubusercontent.com/101049340/164466137-14cea451-d834-4297-898d-f773a1fce0d4.jpeg)

* Case2: When Seat Switch is on and Heater Switch is OFF

![case2](https://user-images.githubusercontent.com/101049340/164466221-ea322ca1-cd7d-4fd0-93fb-9a3c801ab68d.jpeg)

* Case 3: When Seat switch is OFF and Heater Switch is ON

![case3](https://user-images.githubusercontent.com/101049340/164466284-e8632930-7c58-4cdd-b3e4-9034e3581f32.jpeg)

* Case4: When both the switches are ON

![case4](https://user-images.githubusercontent.com/101049340/164466369-21e51abf-0694-4082-8590-a9d55051efce.jpeg)

## Both Switches ON
| Duty Cycle |	Output | | ---- | ------- |
| 20% | ![20%](https://user-images.githubusercontent.com/101049340/164468567-edb378dc-5de0-44d3-821d-665d4652fc39.jpeg) |
| 40% |	![40%](https://user-images.githubusercontent.com/101049340/164468674-37b6e153-34d6-4c36-a84b-0b77d71c2974.jpeg) |
| 70% |	![70%](https://user-images.githubusercontent.com/101049340/164468764-5bbbd25c-64e4-4d6a-9691-32e29a467348.jpeg) |
| 95% |	![95%](https://user-images.githubusercontent.com/101049340/164468897-261d0986-6ac1-4a12-a106-91a7f794c88b.jpeg) |
