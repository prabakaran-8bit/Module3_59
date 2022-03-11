# Test Plan

## High Level Test:

|Test id |Description |expected i/p |expected o/p |Actuall o/p |pass/fail |            
|---- |---- |---- |---- |----|----|
|HLT1 |Car lock |Lock button is pressed |locked |locked |pass |
|HLT2 |Car unlock |unlock button is pressed |unlock |unlock |pass |
|HLT3 |Alarm(Activation/Deactivation) |Activation/Deactivation button is pressed |Alarm(Activated/Deactivated) |Alarm(Activated/Deactivated) |pass |
|HLT4 |Approach Lights |the button is pressed |Approach lights ON |Approach lights ON |pass |
|HLT5 |Encryption|- |Pattern |Pattern |pass |


## Low Level Test:


|Test id |Description |expected i/p |expected o/p |Actuall o/p |pass/fail |
|---- |---- |---- |---- |----|----|
|LLT1.1 |test for car lock |Switch is pressed |All the led's are turned ON at same time  |All the led's are turned ON at same time |pass |  

|Test id |Description |expected i/p |expected o/p |Actuall o/p |pass/fail |
|---- |---- |---- |---- |----|----|
|LLT2.1 |test for car Unlock |Switch is pressed Twice |All the led's are turned OFF at same time  |All the led's are turned OFF at same time |pass |  

|Test id |Description |expected i/p |expected o/p |Actuall o/p |pass/fail |
|---- |---- |---- |---- |----|----|
|LLT3.1 |test for Alram (Activation/Deactivation) |Switch is pressed Thrice |All the led's are turned ON in clockwise direction  |All the led's are turned ON in clockwise direction  |pass |  

|Test id |Description |expected i/p |expected o/p |Actuall o/p |pass/fail |
|---- |---- |---- |---- |----|----|
|LLT4.1 |test for Approach Light|Switch is pressed 4 times |All the led's are turned ON in anticlockwise direction  |All the led's are turned ON in anticlockwise direction  |pass |  

|Test id |Description |expected i/p |expected o/p |Actuall o/p |pass/fail |
|---- |---- |---- |---- |----|----|
|LLT4.1 |test for Encryption|- |pattern  |pattern  |pass |  



