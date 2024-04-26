# Optimal Investment Strategy Using Integer Programming

## Overview
This project involves the development of an integer programming model to aid an angel investor in selecting the most profitable mix of projects. The projects have different financial requirements and returns over a four-year period, and the investor can partially or fully fund these projects.

## Problem Definition
The angel investor is presented with six potential projects, each requiring a certain cash outlay for four consecutive years and offering an expected return at the end of this period. The task was to maximize the total expected return while adhering to the yearly cash availability constraints .

## Mathematical Model
The project required setting up a decision variable x_i to represent the fraction of project _i_ to undertake, with the constraints that the sum of cash outlays of chosen projects must not exceed the available funds for each year and investments must be non-negative .

## Implementation
The implementation was carried out in Python using AMPL and the CBC solver. The Jupyter Notebook 'angel_investor.ipynb' contains the complete implementation details .

## Solution and Results
The optimal solution derived from the model suggested fully investing in projects 1 and 2, partially investing in project 5 with approximately 29.703% of the total cost, and not investing in projects 3, 4, and 6. This strategy resulted in a total Net Present Value (NPV) of $73,605.94 .

## Validation
The model's solution was verified for correctness, ensuring that the investment recommendations conformed to the annual budget constraints while maximizing the returns.

## Conclusions
The project illustrated the effective use of integer programming in financial decision-making processes. The adaptability of the model can be utilized for similar optimization problems, especially where resource allocation within budgetary constraints is a concern.

