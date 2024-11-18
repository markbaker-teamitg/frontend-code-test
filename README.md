## Frontend Technical Test


### Task Instructions

During your technical test interview we require you to create an Angular application using current frontend development best practices. During the 90 minute Teams interview we'd like you to share your screen so that we can see how you approach this task. At pertinent points we will ask you questions to test your knowledge on topics such as Angular, JavaScript, TypeScript, coding principles, coding patterns, code quality. 

Although the app has simple functionality, we'd like you to design the code solution in a scalable and maintainable manner as if you were setting out creating the structure for an enterprise level application with a larger scope and with multiple developers contributing.

Please use your choice of IDE and development tools and feel free to use your usual online sources by way of reference e.g. to check syntax. If you do not complete the test then do not panic. The aim of this interview is to assess your competency level.

Before your interview feel free to create your Angular app and bring in the assets that we have provided so that you have a basic shell of an application to start the exercise from. Also feel free to install any npm packages that you typically use in your projects.

Designs have been provided in the /designs folder for a simple view that displays images of cars along with some basic sales information relevant to each vehicle displayed. Designs have been provided for desktop, mobile and tablet browsers. It is not necessary to demonstrate this working on a mobile or tablet device, but you need to be able to demonstrate how the view would adapt for each device type / resolution.

Using the APIs detailed below, traverse the API data to dynamically build the views according to the design.

Images for each vehicle returned in the API response can be found in the /images folder.

#### Acceptance Criteria
We have a high focus on attention to details in code

* The formatting of the codebase should be consistent and written in a modular approach
* The solution should be structured appropriately for enterprise scale development
* We expect the data from the two API calls to be retrieved and merged efficiently using appropriate RxJS operators
* We expect the codebase to be written using ES6+ and libraries kept to a minimum
* We expect the code to be written with performance in mind
* We expect you to create an appropriate level of automated test coverage
* We expect to see a best practice approach to error handling
* We prefer native Browser Api over JS libraries
* Mobile-first development approach using min-width media queries
* Solution should be accessible and meet WCAG 2.1
* No CSS framework allowed e.g. bootstrap, but pre-processors are fine, we typically use SCSS.
* Internally, we use BEM - but we are open to other CSS naming conventions as long as it's built with scale and maintenance in mind

We have a high focus on attention to details in design

* We expect the designs to match as closely as possible, ready for a designer to review
* Correct semantic HTML mark-up and/or CSS should be used to achieve the size and aspect ratio of the images in the design
* Interactions and animations to be considered but not distracting users away from the experience
* Minimal visual bugs when going resizing to mobile and large screen sizes

#### Nice to have
If you have achieved primary tasks and would like to showcase your skills by implementing additional feature(s) then you can consider the following:

* An accessible modal implementation which displays the additional vehicle information e.g. emission, bodystyle
* Implement "Read more" which Show/Hide additional vehicle information
* A staggered fade in vehicle cards on load
* Anything else which we cannot think of!


#### API URLs
* [https://frontend-code-test-api-1023992580432.europe-west2.run.app/api/vehicles/](https://frontend-code-test-api-1023992580432.europe-west2.run.app/api/vehicles/)
  Returns a list of vehicles

* [https://frontend-code-test-api-1023992580432.europe-west2.run.app/api/vehicles/{id}](https://frontend-code-test-api-1023992580432.europe-west2.run.app/api/vehicles/xe)
  Returns detail for one vehicle. The vehicle id (provided in the above API call) should be passed as a parameter

