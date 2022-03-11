# Test Plan

## High Level Test:

|Test id |Description |expected i/p |expected o/p |Actuall o/p |pass/fail |            
|---- |---- |---- |---- |----|----|
|HLT1 |window status  |switch is pressed |window status display |window status display |pass |
|HLT2 |alarm status |switch is pressed |alarm status displayed |alarm status displayed  |pass |
|HLT3 |car battery info  |Switch is pressed |car battery info displayed |car battery info displayed |pass |
|HLT4 |Door status |Switch is pressed |Door status displayed |Door status displayed |pass |


## Low Level Test:


|Test id |Description |expected i/p |expected o/p |Actuall o/p |pass/fail |
|---- |---- |---- |---- |----|----|
|LLT1 |test for window status |Switch is pressed |All the led's are turned ON at same time  |All the led's are turned ON at same time |pass |  
|LLT2 |test for alarm status  |Switch is pressed Twice |All the led's are turned OFF at same time  |All the led's are turned OFF at same time |pass |  
|LLT3 |test for car battery info |Switch is pressed Thrice |All the led's are turned ON in clockwise direction  |All the led's are turned ON in clockwise direction  |pass | 
|LLT4 |test for Door status|Switch is pressed 4 times |All the led's are turned ON in anticlockwise direction  |All the led's are turned ON in anticlockwise direction  |pass |
