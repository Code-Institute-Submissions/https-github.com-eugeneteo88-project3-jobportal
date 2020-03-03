# _PROJECT 3 : JOB PORTAL - DATA CENTRIC DEVELOPMENT MILESTONE PROJECT_

### Objective :   
To build a database and create a user interface to allow Create, Read, Update and Delete from DATABASE for the job portal.

#### SCOPE
The website allows User (Employer) to perform the following:
* Employer to add a new job posting
EDIT
* Employer can edit their job posting
READ (DISPLAY)
* Display all job posting from databases
DELETE
* Employer can delete their job posting

#### Demo
A live demo can be found here.https://proj3-job-listing.herokuapp.com/

#### UX
My Considerations for the website:
User : Employers to host a job posting
Considerations :
* they must be able to view, add, edit and remove a job posting
* can be viewed by applicants (Employee)


#### Technologies
1. HTML
2. CSS
3. Bootstrap (3.3.7)
4. MongoDB
5. Python 3

#### Features
					Landing Page
						   |
		  				   |
	Employer	     <——————————>		Employee (display database)
		|
		|
		———-> 	Add a new job posting
		        Edit existing job posting
				Delete existing job posting

**My Design of the site :**
* User can Create / Edit / Delete a job posting in 3 simple steps.
Limitations: 
	User Login not available at the moment
	search function to be implemented for easy search
	Employee application button not function
	Social media links not link to any existing portal

#### Testing
Manual Testing is done to ensure that the all functions are functional.
Manual Testing is done to ensure that the all functions are functional.

*No* | *Steps* | *Expected Results* | *Observations*
--- | --- | --- | ---
1 | `On the Landing Page, click on the "Assign Me a Talent Hunter"`| `Link to the Company listing page and display all job listings`| **Pass** 
2a | `Under the Company tab, Click on 'New Listing' yellow button located on top right` | `Display a new entry form for entering new listing information` | **Pass** 
2b | `Enter the details in form and submit`|`Return to listing page (under Company tab) and new listing is added` | **Pass** 
3a | `Under the Company tab, Click on 'Edit Listing' on right of each listing`|`Show a form to allow user to edit existing car details with current data pre-entered in field` | **Pass** 
3b | `Edit the changes and click submit`|`Return to listing page (under Company tab) and the selected listing is updated` | **Pass** 
4a | `Under the Company tab, Click on 'Remove Listing' on right of each listing` | `Information of the listing is retrieve and displayed, will prompt user to confirm the removal` | **Pass** 
4b | `Click on 'Confirm Remove' on right of each listing` | `Return to listing page (under Company tab) and the selected listing has been removed` | **Pass** 

#### Deployment
This site is hosted using Heroku App Link : 
_https://proj3-job-listing.herokuapp.com/_

All codes are uploaded to GitHub and links are made to Heroku by installing in bash terminal in projects.
Once project is complete, it is being push to heroku to deploy

#### Credits
Uses W3School for many reference (https://www.w3schools.com/)
Uses fontawesome for the social media icons (https://fontawesome.com/)
Uses Bootstrap for templates (https://getbootstrap.com/)

 
