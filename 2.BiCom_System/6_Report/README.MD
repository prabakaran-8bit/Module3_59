# Requirements

# Abstract
- A Keyless Entry System allows the car to lock or unlock without the Mechenical key  
- The key fob doesn't need to be presented to  handle car body . it just needs to be within range for the sensors to pick up the signal
- Here in our Project this system is implemented using Led's 

# Introduction:

- A BiCom system is the extention of the unidirectional RKE to bidirectional RKE system. 
- This system can check the window status, Alarm status, Battery info, Door status. 
- The status of all the above system can be verified through the led's





# Swot Analysis
## Strengths
- We can use with less power
- Not connected to the internet


## Weakness
- •	We can only lock and unlock the system within the required range 
- complex System 


## opportunities
- Advancement in Technology.
- Low cost and economical


## Threats
- Components damage 
- Power failure cant have charge backup until resolved

# 4W's And 1H

## Who??? 
- People having automobile and need to secure it  
## What??? 
- Bi com system - Allows the people to lock and unlock the car
## When??? 
- Whenever we need to lock and unlock the system
## Where??? 
- Can be used anywhere at short distance
## How??? 
- Press on the blue switch and using LED’S ON and OFF as per the requirements. 

# Requirements

## High level requirements:

|RID	|DESCRIPTION |
|---- |----|
|HLR1	|It shall check window status  |
|HLR2	|It shall check alarm status |
|HLR3	|It shall get the battery information |
|HLR4	|It shall check the door status |


## Low Level Requirement:

|RID	|DESCRIPTION |
|---- |----|
|LLR1 |The system should check window status when blue switch is pressed once|
|LLR2 |The system should check alarm status when the blue switch is pressed twice|
|LLR3 |The system should It shall get the battery information when the blue switch is pressed three times|
|LLR4 |The system should check the door status when the blue switch is pressed four times|
# BLOCK DIAGRAM
## Proposed block diagram
![Block diagram 2](https://user-images.githubusercontent.com/98816316/157873024-34c06d7b-96eb-4336-8633-12a8e6a9834c.png)
# ARCHITECTURAL
## Behavioural Diagram
![Behavioural](https://github.com/AdityaParadeshi/Module3_59/blob/8fdd8a88a043f5fbc5175f4a5e96af613f65c46c/2.BiCom_System/2_Architecture/Behavioural.png)
# Use Case STRUCTURAL DIAGRAM
## High level Structural Diagram
![High level diagram](https://github.com/AdityaParadeshi/Module3_59/blob/1cbc8dd2a2bef7d7ea6d8f7a7838fadab2320e6b/2.BiCom_System/2_Architecture/new.drawio.png)

## Low level Structural Diagram
![Low level](https://user-images.githubusercontent.com/98816316/157836122-9eebe235-4928-4c85-adaf-1a2f6e8eaaf1.png)
#
## Best Method Followed
* Initial and developed block diagrams mentioned for better understandings
* Mentioning of both High level and Low level Behavioral and structural Diagrams for better understanding
* Flow chart representation making us to understand easier
* Detailed explanation in Low level Behavioural and Structural Diagrams
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
## Output


https://user-images.githubusercontent.com/73412166/157993500-c9b80f6b-954d-445d-8d82-ba510bf57db2.mp4

