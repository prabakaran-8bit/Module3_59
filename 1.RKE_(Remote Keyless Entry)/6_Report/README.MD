# Remote Keyless Entry

# Table of contents
1. Remote Keyless Entry
    * [1.1 Abrstact](#11-abstract)
    * [1.2 Introduction](#12-introduction)
    * [1.3 SWOT Analysis](#14-swot-analysis)
    * [1.5 4W & 1H](#15-4w--1h)
2. Requirements
    * [2.1 High Level requirements](#21-high-level-requirements)
    * [2.2 Low Level requirements](#22-low-level-requirements)
3. Block Diagrams
   
4. Architecture
   * [4.1 Behavioural Diagram](#41-uml-diagram)
   * [4.2 Use Case Structural Diagram (Low & High level)](#42-use-case-structural-diagram)
   *  [4.3 Flow Chart](#43-flow-chart)
   
5. Test plans
   *  [5.1 High level test ](#51-high-level-test)
   * [5.2 Low level test ](#52-low-level-test)



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


