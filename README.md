# Kata and requirements
https://www.codewars.com/kata/545a4c5a61aa4c6916000755/train/javascript

# User stories

### 📘 #1 Validating the input

As a user  
I want to validate the input  
So that I can find the index of the middle number

#### 📜 #1 Scenario

**GIVEN** input is an array with unique numbers and length 3  
**WHEN** validate input  
**THEN** should return true

#### 📜 #2 Scenario

**GIVEN** input is not an array  
**WHEN** validate input  
**THEN** should return false

#### 📜 #3 Scenario

**GIVEN** input array's length is not 3   
**WHEN** validate input  
**THEN** should return false

#### 📜 #4 Scenario

**GIVEN** input array's elements are not unique   
**WHEN** validate input  
**THEN** should return false

#### 📜 #5 Scenario

**GIVEN** input array has not number elements  
**WHEN** validate input  
**THEN** should return false