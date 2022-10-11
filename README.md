# Introduction
This document explains how to run a API test with Postman against a Swagger UI site.    

# Summery    
I have Completed a API test of Book ordering site.   
https://bookstore.toolsqa.com/swagger/#/     

Here in this API new books were orderd list of books were viewed and different tests were performed like GET, POST, PUT,DELETE.

Summary: Test Scripts 11 and Total 24 assertions were done. All of them passed with 0 skipped tests. The number of iteration was 1.

# Requirements  
**Java**  
https://www.oracle.com/java/technologies/downloads/   
**Postman**   
https://www.postman.com/   
**Node JS**   
https://nodejs.org/en/    

# Newman  
  
#### Install Command:  
npm install -g newman    
#### Run Command:  
- newman run “Path/CollectionName.json” -e Path/EnvironmentName.json
- newman run “Collection Link” -e “Path”/EnvironmentName.json    

#### Report:
Creating a HTML Report using Newman    
#### Install Command:    
- npm install -g newman-reporter-html     
**or**   
- npm install -g newman-reporter-htmlextra    

#### Run Command:     
- newman run “Collection Link” -e “Path”/EnvironmentName.json -r cli,html    
**or**    
- newman run “Collection Link” -e “Path”/EnvironmentName.json -r cli,htmlextra    









































