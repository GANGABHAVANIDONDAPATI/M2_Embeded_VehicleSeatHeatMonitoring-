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

![case1](https://user-images.githubusercontent.com/101049340/164469488-008ef586-c936-422d-8481-4ab3121f2e25.jpeg)

* Case2: When Seat Switch is on and Heater Switch is OFF

![case2](https://user-images.githubusercontent.com/101049340/164469607-c681fc1a-ae6e-450b-8578-463d52bfd871.jpeg)

* Case 3: When Seat switch is OFF and Heater Switch is ON

![case3](https://user-images.githubusercontent.com/101049340/164469698-19f25d4a-77fe-4231-b49c-1862eea1ecd1.jpeg)

* Case4: When both the switches are ON

![case4](https://user-images.githubusercontent.com/101049340/164469787-ae256b94-375c-4ba8-8d60-eaa44cfcb767.jpeg)

## Both Switches ON
| Duty Cycle |	Output | 
| ---- | ------- |
| 20% |	![20%](https://user-images.githubusercontent.com/101049340/164469899-31510efe-1f40-4489-892a-9c42be14c623.jpeg) |
| 40% |	![40%](https://user-images.githubusercontent.com/101049340/164470001-0524b15e-19f3-4d38-9d15-18d75a6d57bf.jpeg) |
| 70% |	![70%](https://user-images.githubusercontent.com/101049340/164470097-fafedf1c-a823-4a96-8734-64a1ea7c8a6e.jpeg) |
| 95% |	![95%](https://user-images.githubusercontent.com/101049340/164470178-55621b51-a00b-4644-b4d1-81e49d7a5c57.jpeg) |
