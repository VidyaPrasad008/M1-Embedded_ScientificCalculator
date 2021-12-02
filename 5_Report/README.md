# Requirements

# Introduction
 This is a project to make all the basic calculations ike addition, subtraction, multiplication and division using C program. A calculator is a device that performs arithmetic operations on numbers. It is done by using 4* 4 Keypad, 16*2 LCD with the help of ATmega328 microcontroller.
 
 # Components
 1. 4*4 Keypad
 2. 16*2 LCD
 3. ATmega328

# Objective
The main objective of this project is to make all the basic calculations in response to the supplied input instantly with a calculator.

#Features

1.Addition of different numbers
2.Subtraction of different numbers
3.Multiplication of different numbers
4.Division of different numbers

# 4Ws and 1Hs

# Why:
1. It is easy to do and saves a lot of time
2. It gives the exact answer as there won't be any error in calculation

# Where:
1. It can be used in places like shops, offices, etc.,
 
# Who:
1. This function can be performed by anyone like students, office employees, retail shop owners etc., 
2. It can also be used for personal purposes

# When:
1. It can be used daily or whenever there is
a need for calculation

# How:
1. The user can carry the calculator handy with him by a device or use it through integrations with phone or laptop.
 

# SWOT Analysis:

# Strengths:
1. It is not time consuming as human brain's calculation and the results are accurate

# Weakness:
1. Humans might forget the art of calculating instantly.
2. It makes humans lazy.

# Opportunity:

1. This application can be integrated with phone or laptop.

# Threats:
1. Human brains become dependent on this.

## High Level Requirements
| ID | Description | Status |
|----|-------------|--------|
| HLR_1 | Control Unit | Implemented |
| HLR_2 | Input Unit | Implemented |
| HLR_3 | Output Unit | Implemented |
| HLR_4 | Software Design | Implemented |

## Low Level Requirements
| ID | Description | HLR ID | Status |
|----|-------------|--------|--------|
| LLR_1 | Atmega 328 Microcontroller | HLR_1 | Implemented |    
| LLR_2 | 4*4 Keypad Interface | HLR_2 | Implemented |
| LLR_3 | 16*2 LCD Interface | HLR_3 | Implemented |
| LLR_4 | Simulide | HLR_4 | Implemented |

# Simulation

![Screenshot (1)](https://user-images.githubusercontent.com/94363214/144394953-29b2ced4-84dd-446a-acde-3d13dc5eeacd.png)

# Test Plan
## High level test plan
|Test ID | Description | Exp I/P | Exp O/P | Actual Output | Type of Test
|--------|-------------|---------|---------|------------|-------------
| HLTP_1 | Power ON | Power | Display ON | SUCCESS | Requirement Based 
| HLTP_2 | User Input | Input Value | Return Output to the User | SUCCESS | Requirement Based            
| HLTP_3 | Return Output from Input | Inputed Value by User | Shows Output in Display | SUCCESS | Requirement Based

## Low level test plan
|Test ID | Description | Exp I/P | Exp O/P | Actual Output | Type of Test
|--------|-------------|---------|---------|------------|-------------
| LLTP_1 | Addition | (40, 50) | 90 | 90 | Requirement Based        
| LLTP_2 | Subtraction | (70, 20) | 50 | 50 | Requirement Based        
| LLTP_3 | Multiplication | (5, 5) | 25 | 25 | Requirement Based         
| LLTP_4 | Division | (24, 2) | 12 | 12 | Requirement Based


