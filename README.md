# COVID-19 TRACKER README

[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/Weistd/CS455FinalProject/blob/main/README.md)


<img src="https://github.com/Weistd/CS455FinalProject/blob/main/ICON.png" width="250" height="250" />

<img src="https://github.com/Weistd/CS455FinalProject/blob/main/ShowCaseImage/show.gif" width="300" height="550" />
README file for CS455 Final Project COVID-19 TRACKER

COVID-19 TRACKER is a android app which is designed to show the detialed information covid-19 cases over the Canada and the world. This app was implmented by using the android studio and can be downloaded by downloading entire project file and using andoird studio to install it in your android protable devices.

In this README file the usage and the implementation will be explained in detail

## Table of Contents

- [Background](#background)
- [Install](#install)
- [Usage](#usage)
- [DataSource](#DataSource)
- [Features](#Features)
- [Showcases](#Showcases)
- [FixedBugList](#FixedBugList)
- [WireFrame](#WireFrame)
- [License](#license)

## Background
The covid-19 pandemic started in 2020 and many people's life got changed by this pandemic. Since the COVID-19 is still a big threat to our daily life, I decided to design and implement an APP that can do a real-time track of the COVID-19 cases all over Canada. SO, that people who live in Canada can get the information about COVID-19 in a more convenient and timely way.

COVID19 TRACKER is my solution for people who want to have more convenient and timely access to the COVID19 information.

Covid19 Tracker is an APP everyone can download on their phones and use to check the detailed information about the covid-19 cases all over Canada and can also be used to check the total cases on the world.


<img src="https://github.com/Weistd/CS455FinalProject/blob/main/ShowCaseImage/flash_page.png" width="300" height="450" />
## Install
This Project is not published to any app store yet. So the only way to got it installed is to download entire file and use the andoird to install it into your phone

here is the detailed step to use the andoird studio to install 

1.downlaod entire code file

<img src="https://github.com/Weistd/CS455FinalProject/blob/main/ShowCaseImage/install_step1.png" width="450" height="450" />

2.after unzip the file, import the android project into your android studio   
<img src="https://github.com/Weistd/CS455FinalProject/blob/main/ShowCaseImage/install_step2.jpg" width="450" height="450" />

3.plug your USB and select the right device and click the run button 
<img src="https://github.com/Weistd/CS455FinalProject/blob/main/ShowCaseImage/install_step3.jpg" width="450" height="450" />



## Usage

This app is used for real-time tracking COVID-19 information over the Canada.

<img src="https://github.com/Weistd/CS455FinalProject/blob/main/ShowCaseImage/showcase1.png" width="300" height="450" />

## DataSource
Three Covid-19 data API I used in this APP as my data source
If anyone want to use this data source, feel free to read the data source API below


1.[API1](https://opencovid.ca/api/).
-The first one I used to get the detailed data of all province in canda


2. [API2](https://documenter.getpostman.com/view/11073859/Szt5fAr3?version=latest).
-The second API I used to fetch the covid-19 overall cases summary

3. [API3](https://corona.lmao.ninja/).
-The third one here I used to fetch the COVID-19 cases of the world

## Features

Here is the list of features

1.Every data in this app is real-time

2.Every data in this app will automatic updated once the screen got refreshed

3.need double click the back button to exit the application. designed to pervent the touch of the back button by accident

4.not only showing the total of cases, active case, recovered cases, and the death cases, also show the change of number in different data.

5.using by using pie chart to give a more direct view of the data

6.provide the search function to help user easily find the province they want to check

7.search function will search anything related to the letter on the search box, provide more related information in the result list

8.search page will show all basic information such as total cases for all province in the list


## Showcases
<img src="https://github.com/Weistd/CS455FinalProject/blob/main/ShowCaseImage/show.gif" width="300" height="550" />

## FixedBugList

-In MainActivity, The fetch data in the not working  *fixed*

-In MainActivity, wrong order to store the fetched data   *fixed*

-In the StyateWiseDataActivity, the search editbox not working  *fixed*


## WireFrame
<img src="https://github.com/Weistd/CS455FinalProject/blob/main/ShowCaseImage/ModelView.png" width="550" height="550" />

### Contributors
Xiaowei Liang 

2021/04/21




