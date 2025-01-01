# Data Analysis Tool

## Introduction
This project was brought to me by a Data Analyst who needed a software solution that ultimately saved hundreds of working hours after it went live in 2024.
<br>
<br>
I designed and built a software solution that allowed them and their colleagues to interface with a program to extract valuable data, refine the scope of their request, and export the filtered and manipulated data in a convenient file format, ready to be included in a presentation.
<br>
<br>
After a few design meetings, we finalised a plan and built it. The details are listed below.

## Spec
An industry-leading data analytics company runs a process each month to extract various elements of data from their data pool and build them into insights, which are then placed in a presentation deck for clients.

### The Problem
The process of extracting the data each month was incredibly repetitive. It was almost the same each time, with minor changes, and the current system had no way of exporting this data in a preset manner.

### The Solution
I developed a lightweight piece of software that provides the user with a simple UI. This allows them to select the data they need, process it automatically for the insights in the presentation, and export it to a usable file format.

## Limitations
Due to company policy, this project needed to be completed entirely in Python. Unfortunately, this meant I was unable to construct the UI in a web framework and instead had to use TKInter.

## Conclusion
By the end of development, I had designed and built a software solution to the client's specification. The tool enables users to extract vast amounts of data, use dynamic UI elements to tailor the information they need, parse the data, and export it to a convenient file format.

This software was built on a tight schedule but still includes various layers of error handling to ensure users do not encounter unexpected results.

## Screenshots

## Geography Filter
All elements on screen are generated dynamically depending on the information given on the initial data import.
<br>
This screen allows the user to filter what information they want to parse, the information present on this screen is influenced by what was selected in the following screenshot.
![](https://github.com/SvenMC/Decomp/blob/main/geography_selection.png)

## Geography Dimensions
This screen allows the user to refine which level they want to select data from, and also which data they want to see in the previous screenshot. 
<br>
<p align="center">
  <img src="https://github.com/SvenMC/Decomp/blob/main/dimension_filter.png" />
</p>


## Geography list
I was concious that this software was going to be used on all kinda of screen sizes, so everything can be scaled up and down as needed. As such I wanted to make sure that any text that gets truncated also is given a tooltip that the user can see on hover.
<p align="center">
  <img src="https://github.com/SvenMC/Decomp/blob/main/geography_tooltip.png" />
</p>
