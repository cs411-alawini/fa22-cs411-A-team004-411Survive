# Crime Map

## Contributor
[Zhirong Chen](https://github.com/rong-hash)

[Zicheng Ma](https://github.com/ZichengMa)

[Elijah Ye](https://github.com/Elijah-Ye)

[Erkai Yu](https://github.com/silkrow)

## Project Summary
We want to create a web application that can clearly display the crime. Users can use the website to report incidents they have seen as well as locate areas with high crime rates. With the use of this website, we want to reduce crime and improve student safety at UIUC.

## Project Description
Since the crime rate of Champaign and Urbana is almost the highest in Illinois, and UIUC students are the main victims, we decide to develop a web application that can help students and faculty to query and report crime in a map. In the map, Users can intuitively see what, when, where the crime happens in UIUC. 

Based on the data and artificial intelligence, the web can also predict where crime is most likely to occur, so that it can tell the police to raise the level of vigilance in that area, and also helps the public to avoid that area as much as possible. We hope both UIUC students and policemen can not only survive but also thrive in Champaign and Urbana.

## Realness
Our data will be the records of crime within UIUC campus and surrounding areas such as Champaign, Urbana, and Savoy. The best way for us to get our data is from police stations around those areas. That could only happen if they give us access to their database. If not, we might need to do some crawling from local newspapers. We hope to format our data to a table with attributes such as `CrimeId`, `Date`, `Address`, `TypeOfCrime`, and so on. 

## Usefulnesss

​    Our program aims to build a map for students and faculties in UIUC to check crimes around and on campus. Our project will help people avoid meeting crime and have a safer campus life. This is useful especially for those who like going home late at night.


## Code Contribution
1. Zhirong Chen:
    * Embedding Google Map UI
    * Writing triggers for the database
    * Setting up tables in the database
    * Generalizing user infomation for tables
    * Setting up the client and server side of our website
    * CSS design
    * Designing table relations
2. Erkai Yu:
    * Writing advanced queries for the database
    * Adding update supports to the database with stored procedures
    * Adding labels to crime data
    * Analyzing query profermance
    * Setting up GCP SQL server
    * CSS design
    * Designing table relations
3. Zicheng Ma:
    * Loading and cleaning crime data to fit database design, with Python
    * Setting up website
    * CSS design
    * Designing table relations
4. Elijah Ye:
    * CSS design
    * Designing table relations

## Environment

### Client Folder
    npx create-react-app
    npm install react-router-dom 
    npm install --save styled-components
    npm install react-icons
    npm install axios
    npm i -S @react-google-maps/api
    npm install react-date-range
    npm install date-fns
    npm install react-select
    npm install --save react-geocode

### Server Folder
    npm install fs

## demo
https://youtu.be/-z2Pg80oAbs
