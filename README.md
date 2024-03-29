# The  Diamond Valorization

The  Diamond Valorization is an analytic and visual study of a dataset containing thousands of **diamonds**.

![Diamonds](/home/sergio/Imágenes/Diamonds_shot.png)

## The Worthy Purpose

The purpose of this study is to try and find the influence of different attributes and measures of a diamond in said diamond price. Through a series of calculations and operations, we will clean irrelevant data while learning the basics of the distribution while representing in charts and boxes relevant information. 

The result is a helpful visualization where you could compare performance of each parameter related to the price.  

## The Tour Guide

Project M2 is based on a public dataset (find it in [Kaggle]([https://www.kaggle.com/shivam2503/diamonds](https://www.kaggle.com/shivam2503/diamonds))). The study is divided in two parts, an analytical study made on Jupyter and a visualization made with Tableau. What you need:

**Jupyter Notebook**
___

Most of the exploratory and analytic work was done on Jupyter Notebook, based on Python 3. Data cleaning, calculation, aggregation and pre-visualization require the following libraries:

* pandas
* matplotlib.pyplot
* seaborn
* From IPython.display, set_matplotlib_formats
* cufflinks

**Tableau** 
___

The final step is a dynamic visualization created on Tableau. Take a look at the charts and tables and make good use of filters and pages to understand the relationship between the 4Cs of Diamonds and the price of a diamond. Head over the [Diamonds Dashboard](https://public.tableau.com/profile/sergio.figue#!/vizhome/Diamonds_Dashboard/M2Dashboard?publish=yes) or the [Diamond Support Dashboard](https://public.tableau.com/profile/sergio.figue#!/vizhome/Diamonds_Dashboard_Support/M2Dashboardsupport?publish=yes) and help yourself.


**Basic knowledge**:
___
- The 4Cs of Diamonds: carat, color, cut and clarity:
🔹 Color: GIA's D-to-Z color-grading system measures the degree of colorlessness by comparing a stone under controlled lighting and precise viewing conditions to masterstones of established color value. The scale begins with the letter D, representing colorless, and continues, with increasing presence of color, to the letter Z.

🔹 Clarity: Evaluating diamond clarity involves determining the number, size, relief, nature, and position of 'inclusions' and 'blemishes.', as well as how these affect the overall appearance of the stone. The GIA Clarity Scale has 6 categories, some of which are divided for a total of 11 specific grades.

🔹 Cut: A diamond's cut grade is really about how well a diamond's facets interact with light. The GIA Cut Grading System for the standard round brilliant diamond evaluates seven components.

🔹Carat: Diamond carat weight is the measurement of how much a diamond weighs. A metric "carat" is defined as 200 milligrams. Each carat can be subdivided into 100 'points.' This allows very precise measurements to the hundredth decimal place.
- Calculations of a diamond: % Table and % Depth
- Measurements: x, y and z 


## The Main Conclusions

Through the process, we have learnt that there is a strong relationship between carat and price. Thus between size and price is almost the same. However, there is a breakpoint in the almost linear progression.

Apparently, price varies along the remaining Cs and their own set of values. 

# The Personal Information

The  Diamond Valorization was created by Sergio Figueroa (Github: SerioFigue).
Ironhack Madrid - Data - July 2020
