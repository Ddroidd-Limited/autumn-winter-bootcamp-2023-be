# ddroidd Autumn-Winter Dev Bootcamp 2023 - Backend

Hi! Welcome to your take-home coding challenge!
Here are a few guidelines and a brief description of the requirements


**Important Considerations**
* **Deadline: submit your coding challenge by end of day Thursday (12th of October 2023)**
* Use C# or Java to implement the coding challenge
* Push your code to a public git repository and send that link back to your recruiter
* The code should be written to the best of your ability. Ensure it is well-organized and commented where necessary.
* Include any necessary setup instructions in your README
* If you didn't manage to finish all requirements, just send the project in the state it is when the deadline arrives!


## Challenge Description
**Develop a program for an internship application portal where employers can post job listings and applicants can apply for them**


The application form will need to contain at least the information in the following design: https://www.figma.com/file/Fhe6RWSxjRFCwDACqhXzNq/Untitled?type=design&node-id=0-1&mode=design

## Mandatory Requirements
### 1. Data Structure
* Build the data model (classes) that best fit the description above (e.g. Employer, Job Listing, Applicant, etc.)
* All entities defined should be uniquely addressable
* Using the classes defined, create a data structure with at least the following contents: 2 Employers, each with at least 4 job listings and 10 applicants for each employer distributed across the available job listings.
* Display the contents of the data structure defined

### 2. Documentation
* Create a README file that contains a brief description for the data structure breakdown.

### 2. Operations
* Create a method to add a new Job Listing for one of the Employers
	* Validate the input data
	* Using this method, add 2 new Job Listings for both Employers
* Create a method to allow people to apply for a job listing
	* **hint: Use the design file as a guide for the fields expected from an Applicant**
	* Validate the input data
	* Using this method add 5 applicants to the newly created Job Listings
* Create a method to display all Job Listings for an Employer
	* Call the method and display the result
* Create a method that gets all applicants for an Employer
	* Call the method and display the result
* Create a method that gets all applicants for a Job Listing
	* Call the method and display the result
* Create a method to delete a job listing
	* Call the method to delete one of the job listings
	* Call the method to display the job listings for the employer to show the deletion has taken place

### 3. Tests
* Create at least 1 unit test for the validation logic in the Apply method

## Optional Requirements (bonus points)
* Do proper error handling in all operations, and display user-friendly error message
* Add authentication/authorization so that only a certain user can perform actions. Apply this mechanism to at least 2 of the operations
* Expose the operations as a REST API
* Persist the data structure. 
	* You can use a database (if this is the case, include the database file or a diagram describing the table structure). You can use any type of relational database engine and any ORM
	* or static files on disk.

## Expected deliverables
1. Push your code to a public git repository and send that link back to your recruiter
2. The code should be written to the best of your ability. Ensure it is well-organized and commented where necessary.
3. Include any necessary setup instructions in your README
4. If you didn't manage to finish all requirements, just send the project in the state it is when the deadline arrives!

