# Requirements

## Introduction:  
The Electricity Bill calculator project is the application based mini project, which 
is used to predict the electricity bill of next month by taking input of appliance or load used. The tool used for writing the code in this project is visual studio code. This project has multi file and multiplatform approach (Linux and Windows).

## Research

People who don’t have technical knowledge of calculating electricity bill can use this application to predict electricity bill of upcoming months, however, the defining features of an electricity bill calculator include:

    * power rating of all loads

    * total load calculation

    * unit consumed per day

    * units consumed per month

In addition, high-end electricity bill calculators generally include:

->electricity bill calculation in urban areas

->electricity bill calculation in rural areas

->bill calculation based on units consume


## Detail Requirements:

## High Level Requirements:

| **ID**| **Description** |
| --- | --- |
| HLR1 | Electricity bill calculation at Urban areas if(units<30). |
| HLR2 | Electricity bill calculation at Urban areas if(units>30 && units <100). |
| HLR3 | Electricity bill calculation at Urban areas if(units>101 && units <200). |
| HLR4 | Electricity bill calculation at Urban areas if(units<200). |	
| HLR5 | Electricity bill calculation at Rural areas if(units<30). |
| HLR6 | Electricity bill calculation at Rural areas if(units>30 && units <100). |
| HLR7 | Electricity bill calculation at Rural areas if(units>101 && units <200). |	
| HLR8 | ELectricity bill calculation at Rural areas if(units<200). |

## Low Level Requirement:

| **ID**| **Description** |
| --- | --- |
| LLR1 | Calculates electricity bill at rural areas. |
| LLR2 | Calculates electricity bill at urban areas. |
| LLR3 | Calculates total load at domestics places. |
| LLR | 4Calculates total unit consumed at domestics places. |

## SWOT analysis:

Strengths: Innovative, User-friendly.

Weakness: Cost of calculator increases as features added in the calculator increase.

Opportunities: We know that we mostly use pen and paper for calculation. So tech based market always attracts the youth.

Threats: Slower growth in an innovation always threat for the company in this dynamic world.

## 4’W and 1’H

        What: Electricity bill calculator**

        Where: School, Science, domestic, industries, Technology

        When: Need for calculation.

        How: Calculates the user input as number of loads and gives the output.




## Design

# Behavioural Diagram
  * High level Behavioural Diagram![HIGH LEVEL BEHAVIOURAL DIAGRAM](https://user-images.githubusercontent.com/98833482/154535248-3dc9698b-d20f-4fc8-a9b8-da7206e4c287.jpg)
  
  * Low level Behavioural diagram![LOW LEVEL BEHAVIOURAL DIAGRAM](https://user-images.githubusercontent.com/98833482/154535486-938956fb-46e2-4723-b39b-6ffd7f83510a.jpg)

# Structural Diagram
  * High Level Structural Diagram![HIGH LEVEL STRUCTURAL DIAGRAM](https://user-images.githubusercontent.com/98833482/154538095-b2ec2acf-1208-44c0-bfa4-855d6599c573.jpg)
  * Low Level Structural Diagram![LOW LEVEL STRUCTURAL DIAGRAM](https://user-images.githubusercontent.com/98833482/154538219-140a304a-2d82-4a7d-9627-2d1a8ee227c8.jpg)


# Input And Output

## Table no: High Level test plan

|**Test ID**|**Description**|**Exp i/P**|**Exp O/P**|**Actual O/P**|
| :- | :-: | :-: | :-: | :-: |
|H\_01|Electricity bill calculation at urban areas|Choice|SUCCESS|SUCCESS|
|H\_02|Electricity bill calculation at rural areas|Choice|SUCCESS|SUCCESS|
|H\_03|Units consumed per year|Choice|SUCCESS|SUCCESS|
|H\_04|Calculates total industrial loads|Choice|SUCCESS|SUCCESS|


## Table no: Low Level test plan


|Test ID|HL\_ID|Description|Exp input|Exp Output|Actual Output|
| :- | :- | :- | :- | :- | :- |
|L\_01|H\_01|Electricity bill calculation at Urban areas if(units<30)|22 units|71.5 rupees|71.5 rupees|
|L\_02|H\_01|Electricity bill calculation at Urban areas if(units>30 && units <100)|50|235|235|
|L\_03|H\_01|Electricity bill calculation at Urban areas if(units>101 && units <200)|150|937.5|937.5|
|L\_04|H\_01|Electricity bill calculation at Urban areas if(units<200)|230|1,679|1,679|
|L\_05|H\_02|Electricity bill calculation at Urban areas if(units<30)|12|<p>37.8</p><p></p>|<p>37.8</p><p></p>|
|L\_06|H\_02|Electricity bill calculation at Urban areas if(units>30 && units <100)|67|294.8|294.8|
|L\_07|H\_02|Electricity bill calculation at Urban areas if(units>101 && units <200)|134|797.3|797.3|
|L\_08|H\_02|Electricity bill calculation at Urban areas if(units<200)|344|2,339.2|2,339.2|





