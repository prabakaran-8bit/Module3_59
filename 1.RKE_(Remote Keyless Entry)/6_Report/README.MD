# Remote Keyless Entry

# Table of contents
1. Remote Keyless Entry
    * 1.1 Abrstact
    * 1.2 Introduction
    * 1.3 SWOT Analysis
    * 1.5 4W & 1H
2. Requirements
    * 2.1 High Level requirements
    * 2.2 Low Level requirements
3. Block Diagrams
   
4. Architecture
   * 4.1 Behavioural Diagram
   * 4.2 Use Case Structural Diagram (Low & High level)
   *  4.3 Flow Chart
   
5. Test plans
   *  5.1 High level test 
   * 5.2 Low level test 



# Requirements

# Abstract
- A Keyless Entry System allows the car to lock or unlock without the Mechenical key  
- The key fob doesn't need to be presented to  handle car body . it just needs to be within range for the sensors to pick up the signal
- Here in our Project this system is implemented using Led's 

# Introduction:

- Remote keyless entry (RKE) system is a system designed to remotely lock or unlock access to automobiles
- RKE transmission requires two components - a transmitter and a receiver. 
- 1] Transmitter - RKE key fob, other ID device with RKE integrated 
- 2] Receiver - Body Control ECU, other ECU with integrated RKE 
- RKE operates by broadcasting radio waves on a particular frequency unidirectionally. 
- RKE systems implement encryption and rolling code algorithms to prevent car thieves from intercepting and spoofing the telegrams. 
- The Led's are used to work with the different operating conditions.





# Swot Analysis
## Strengths
- Remote Starting
- Time is saved during urgent situation
- Support for Effecient operation.

## Weakness
- cost of system may be increased
- complex System 
- issues of engine running after parking the car

## opportunities
- Advancement in Technology.


## Threats
- Targated Attacks
- Identity Theft

# 4W's And 1H

## Who??? 
- This system is used by people to lock/unlock car
## What??? 
- This is an keyless entry which can lock/unlock the cars without Mechanical key
## When??? 
- This system can be used whenever there is the need of locking/unlocking of car
## Where??? 
- This System can be used in Automotives
## How??? 
- This system works on buttons when lock button is pressed the car locks and if unlock button is pressed the car unlocks.

# Requirements

## High level requirements:

|RID	|DESCRIPTION |
|---- |----|
|HLR1	|System shall be Remotely locked/unlocked |
|HLR2	|System shall be encrypted |
|HLR3	|System shall be provided with alaram Activation/Deactivation |
|HLR4	|System shall be provided with approach lights  |


## Low Level Requirement:

|RID	|DESCRIPTION |
|---- |----|
|LLR1.1|When switch is ON all the led's must turn on at same time |
|LLR1.2	|When switch is Pressed 2 times all the led's must turn OFF at same time |

|RID	|DESCRIPTION |
|---- |----|
|LLR2|System shall be Provided with the pattern to ensure security |
|LLR3|When the switch is Pressed 3 times all led's shall turn on in clockwise manner  |
|LLR4|When the switch is Pressed 4 times all led's shall turn on in anticlockwise manner  |

# BLOCK DIAGRAM
## Proposed block diagram
![Untitled Diagram drawio](https://user-images.githubusercontent.com/98816316/157724940-5ceb5825-001f-4c74-beab-b931e826d752.png)
# ARCHITECTURAL
## Behavioural Diagram
![Behavioural](https://user-images.githubusercontent.com/98816316/157813710-315d5760-dd64-4169-a640-5f9e030bc1c6.png)
# Use Case STRUCTURAL DIAGRAM
## High level Structural Diagram
![High level diagram](https://user-images.githubusercontent.com/98816316/157828835-38fd328c-ed74-42bc-a9d2-c2af9cf10674.png)

## Low level Structural Diagram
![Low level](https://user-images.githubusercontent.com/98816316/157836122-9eebe235-4928-4c85-adaf-1a2f6e8eaaf1.png)

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
|LLT1 |test for car lock |Switch is pressed |All the led's are turned ON at same time  |All the led's are turned ON at same time |pass |  
|LLT2 |test for car Unlock |Switch is pressed Twice |All the led's are turned OFF at same time  |All the led's are turned OFF at same time |pass |  
|LLT3 |test for Alram (Activation/Deactivation) |Switch is pressed Thrice |All the led's are turned ON in clockwise direction  |All the led's are turned ON in clockwise direction  |pass | 
|LLT4 |test for Approach Light|Switch is pressed 4 times |All the led's are turned ON in anticlockwise direction  |All the led's are turned ON in anticlockwise direction  |pass |
|LLT5 |test for Encryption|- |pattern  |pattern  |pass |  








