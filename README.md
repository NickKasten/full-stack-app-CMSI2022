# full-stack-app-CMSI2022

This project was the 4th and final project for the LMU CMSI2022: Mobile App Development Class in Spring 2023.

This group project was completed with users **ntran18**, **Nicholaslee0101**, and **JulianLeonhardt**.

The following is from our original project description:

# Academic Eats

AcademicEats allows college students to find recipes, try them, save them, and reuse them! They can scroll through the home view to explore without searching, or they can search directly by main ingredient. This app is mainly meant for college students, but any one is open to use it!

## Team Overview - NMNJ Quadrant

- Maika Tran - Backend Developer (Firebase, Firestore, API)
- Nicholas Lee - Backend Developer (Firebase, Firestore)
- Nick Katsen - Frontend Developer (UI and a little API)
- Julian Leonhardt - Fullstack Developer (UI and API) 

## User Audience

Our app targets college students who would like to cook but need recipes or instructions to make food. 

## App demo

Home View

<img width="561" alt="Screen Shot 2023-05-03 at 6 09 25 PM" src="https://user-images.githubusercontent.com/89878676/236088178-b78eda0e-9384-42e9-b765-0dafd907d545.png">

Sign-In Screen

<img width="539" alt="Screen Shot 2023-05-03 at 6 09 37 PM" src="https://user-images.githubusercontent.com/89878676/236088452-6eef4175-cd80-4d16-ac2c-dd06f641f379.png">

Sign-In Screen after signing in

<img width="557" alt="Screen Shot 2023-05-03 at 6 10 16 PM" src="https://user-images.githubusercontent.com/89878676/236088626-f0a67d20-32a1-42c7-b6d5-6f40df60c26e.png">

Search view not Signed-In

<img width="564" alt="Screen Shot 2023-05-03 at 6 11 05 PM" src="https://user-images.githubusercontent.com/89878676/236088843-ea61766c-c84e-4c00-a3e6-c36fbee9fdc5.png">

Search View Signed-In

<img width="570" alt="Screen Shot 2023-05-03 at 6 10 37 PM" src="https://user-images.githubusercontent.com/89878676/236088875-f9a3626f-dfe0-4296-81de-a5eb8a03bebe.png">

Recipe Detail View

<img width="563" alt="Screen Shot 2023-05-03 at 6 10 47 PM" src="https://user-images.githubusercontent.com/89878676/236088899-d1400bed-4c4f-4e4a-b94a-3b9c5519d42e.png">



Video Demonstration:

https://user-images.githubusercontent.com/108908370/236127801-195f02fb-9c1b-4c74-8550-87b89499b7c9.mov



## Technology Highlights

#### API - [MealDB API](https://www.themealdb.com/api.php)

A free recipe API that allows users to search different recipes by categories, area, or ingredients. We used different API url to fetch different information. For the home view, we fetch API using filter by categories feature. For the search view, we fetch API using filter by one main ingredient feature. Since this is a free API, it limits the type of ingredients users can search. Whenever the user wants to know more detail about the meal, then we fetch API using look up full meal details by id. 

#### Database

This app uses Firebase as database source. For authentication, users can login by email/password. For the storage, each collection named by user id. Within each collection, we stored meal id, meal name and meal image for each document. 

#### Challenges

We ran to a lot of challenges including how to make object model correctly and fit with the JSON file from the API, how to keep track of the favorite meals saved by user from the database and from app view. Thus, with the limited time, we try our best to finish the app. 

## Credits

- MealDB API
- Firebase
- Hacking with Swift
- Previous projects
- Dondi (special thanks to him)
- DesignCode on Youtube for some help with UI
- Medium with some help on UI
