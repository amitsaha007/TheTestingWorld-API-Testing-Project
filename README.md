# Student_Details_API_Newman

## How to run this project
- Clone this project
- Open with Postman / Command Shell
- Run Command:  
```console 
newman run Student_Details.postman_collection.json -e Student_Details.postman_environment.json
```
- Run Command for Report: 
```console 
newman run Student_Details.postman_collection.json -e Student_Details.postman_environment.json -r cli,htmlextra
```

## Technology used:
- Postman
- Newman

## Prerequisite:
- Jdk
- Node Js
- Newman
- Html Report Library

## Newman and Report Installation Process:
- Newman Install Command:
```console
npm install -g newman-reporter-htmlextra
```
- Newman Html Report Install Command:
```console
npm install -g newman-reporter-htmlextra
```

## API Documentation:
- https://documenter.getpostman.com/view/29362072/2s9YsT7UHv

## Test case list:
1. ### Create Student
	:large_blue_diamond: Create Data Sets Using the Dynamic Random Variables.

2. ### Verify Created Student Details
	:large_blue_diamond: In the test case you need to validate the following field values:
 	1. > ID
 	2. > First Name
 	3. > Middle Name
 	4. > Last Name
	4. > Date of Birth

3. ### Get all students information
	:large_blue_diamond: Fetch all the details of the students from the server.
	:large_blue_diamond: Create a test case to check the length of the response.

5. ### Create Technical skills Create Student Address
	:large_blue_diamond: In the test case you need to validate the following field values:
	1. > Only Message

6. ### Create a Student Address
	:large_blue_diamond: In the test case you need to validate the following field values:
	1. > Status and Message field values

7. ### Get the Student's Full Details
	:large_blue_diamond: In the test case you need to validate the following field values:
	1. > Language
	2. > Year Of Experience
	3. > House Number
	4. > City
	5. > Country
	6. > Current Address
	7. > Mobile


## Newman Report Summary:
![image](https://github.com/amitsaha007/TheTestingWorld-API-Testing-Project/assets/74258760/91bcdcff-ba0e-492e-ad26-0225e4dd68c4)

![image](https://github.com/amitsaha007/TheTestingWorld-API-Testing-Project/assets/74258760/efd34423-da3b-410c-aa71-99d19003d35a)
