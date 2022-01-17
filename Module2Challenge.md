# Project Overview
The purpose of this profect was to use VBA and Excel functions to loop through the data set and refractor our already exsiting code. The dataset VBA_Challenge.xlms used in this project was refractored to loop though the data of many stock markets that were created over the last few years. This project refractor was created so that the VBA script could execute faster. In these next sections I will be providing screenshots of the analysis I took from this refractored code that compares teh stock performances between 2017 and 2018. 
## Stock Analysis 2017
In this below screenshot, we see the output of executing the code, "yearValue = InputBox("What year would you like to run the analysis on?")"

<img width="495" alt="Screen Shot 2022-01-16 at 10 57 14 PM" src="https://user-images.githubusercontent.com/77857472/149705975-998993ff-9540-4817-934d-0afe771ae8ef.png">
This inputbox then is used to analyze the stock analysis for the year entered, in this example 2017.
You can see from this screenshot the amount of time that is took to run through this data and output this analysis. 
<img width="270" alt="Screen Shot 2022-01-16 at 10 57 27 PM" src="https://user-images.githubusercontent.com/77857472/149706146-489b7d01-fa7c-4b8f-a45d-75f876c0ac4f.png">
<img width="250" alt="Screen Shot 2022-01-16 at 10 57 42 PM" src="https://user-images.githubusercontent.com/77857472/149706159-6aaa9bd6-2aef-454d-8377-71a1345a6ee0.png">
<img width="795" alt="Screen Shot 2022-01-16 at 11 14 20 PM" src="https://user-images.githubusercontent.com/77857472/149707163-cc1ceaa7-7d9a-448f-a602-17a6c657da10.png">

In comparision this is the original performance execution time. You can see the refractored code runs faster.
<img width="250" alt="Screen Shot 2022-01-16 at 11 02 28 PM" src="https://user-images.githubusercontent.com/77857472/149706296-c5d0f330-0428-46a6-8d62-332093c351fb.png">

## Stock Analysis from 2018
This is the execution times of the stock analysis of the refractored code compared to the second screenshot which is the times of the original stock analysis code.
<img width="250" alt="Screen Shot 2022-01-16 at 11 04 35 PM" src="https://user-images.githubusercontent.com/77857472/149706449-a084a35d-e17a-47ca-bec9-e746506044a1.png">

<img width="250" alt="Screen Shot 2022-01-16 at 11 04 50 PM" src="https://user-images.githubusercontent.com/77857472/149706465-eb4d7f43-b2df-4b47-8721-40e2e9972966.png">

## Summary 
1. What are the advantages or disadvantages of refactoring code?
  - The advantages of refractoring code is obvious to improve the quality of the execution times. In this, you are able to improve the overall design of the code and find potention bugs that could become present. 
  - Refracting code could lead to the code no longer being able to be understood by the developers. If the refractored code is too advance for the original developer there could be a loss of concepts.
2. How do these pros and cons apply to refactoring the original VBA script?
  - In essence to the original VBA script the pros are that you can see that the overal execution times have significantly decreased in seconds. Although the time is measured in seconds it is still faster for the computer to execute. 
