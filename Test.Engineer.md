

# Grand Luxury Hotels Recruitment Test


Thank you for taking the time to do our technical test. It consists of three parts:

[A coding task](https://github.com/GrandLuxuryGroup/GLH.RecruitmentTests/blob/master/Test.Engineer.md#coding-test)
[A deployment task](https://github.com/GrandLuxuryGroup/GLH.RecruitmentTests/blob/master/Test.Engineer.md#deployment-task)
[A few technical questions](https://github.com/GrandLuxuryGroup/GLH.RecruitmentTests/blob/master/Test.Engineer.md#technical-questions)

In order to avoid bounced emails we would like you to submit your results by uploading the relevant ZIP file to a shared Google Drive folder. In order to obtain the URL for this folder, please supply your Gmail or Google-based email address to either your agent or the Just Eat member of staff who assigned you the test.

Please make this a single zip file named {yourname}-{date}.zip containing:

a single markdown file with the answers to the technical questions
one folder containing the technical test


## Coding Test


**1 - API Creation**

You will find in this folder a file called "xxxx"  

You will have to create an API based on this dataset that returns a list of restaurants that deliver to the outcode SE19, including some basic restaurant information.

The API should require you to specify **a set of valid HTTP request headers**, as shown below. 

Accept-Language: 
Authorization: 

You can create the API using the language and database of your choice. You will have to explain your choices. 

**2 - Web Application** 

The task is to create **a web application** that accepts an outcode as a parameter. The application should then display the following information about each restaurant that delivers to that outcode by querying your API:

Name
Rating
Types of food for the restaurant

**Language and Technology** 

PHP  or/and  JavaScript should be used for this task.
Think about the type of design you would like to do at Grand Luxury and choose an appropriate design, framework and technologies.
You will have to explain your choices. 

**Task requirements**
Feel free to spend as much or as little time on the exercise as you like as long as the following requirements have been met.

 1. Please complete the user story below. 
 2. Your code should compile and run in one step. 
 3. Feel free to use whatever frameworks / libraries / packages you like.
 4. You **must** include tests
 5. Please avoid including artifacts from your local build in your final ZIP file

**User Story**

**As a user** 
I can view a list of restaurants in a user submitted outcode (e.g. SE19)
So that I know which restaurants are currently available

BONUS : If you want you can also include the following:

**As a user** 
I can view the restaurant picture alongside restaurant information
So that I know exactly which restaurants are currently available

**As a user** 
I can use GPS to find my current postcode to retrieve restaurant results
So that I don't need to type it in

**Acceptance criteria**
For the known outcode se19, results are returned
The Name, Cuisine Types and Rating of the restaurant are displayed


## Deployment Task

Now that your web application is created and fully functional.  You will have to deploy on AWS creating ***a small pipeline*** either using the tool of your choice (Jenkins, CodeDeploy, etc.).

You will have to deploy the application on AWS in a resilient and scalable way. 


## Technical questions


Please answer the following questions in a markdown file called AnswersToTechnicalQuestions.md.

 1. How long did you spend on the coding test? What would you add to your solution if you had more time? If you didn't   spend much time on the coding test then use this as an opportunity to explain what you would add. 
 2. What was the most useful feature that was added to the latest version of your chosen language? Please include a snippet of code that shows how you've used it.
 3. How would you track down a performance issue in production? Have you ever had to do this? What would be your main concerns regarding web application performance ? 
 4. How would you improve the API that you just created? 
 5. Please describe yourself using JSON :)

**Thanks for your time, we look forward to hearing from you!**
