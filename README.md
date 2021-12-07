# Join Us

This assignment is designed for the job post of the **Software Developer**.

## Assignment Info

Create a bookmark CRUD application with following steps

Step 1: 
	Create a login page. ( `/login` )
 
* On login page user should be able to login with email and password.
* Show error if email and password doesnt match.
* show error for invalid email address.
* Redirect user to homepage ( `/` ) after successfully login
* Show a forgot password link in login form where user can reset his password

Step 2:
Create a sign up ( `/signup` )

* Signup user with following details
* First Name ( required )
* Last Name ( required )
* Email ( required )
* Phone number ( required )
* Profile pic ( required )
* Password


After successfully signup redirect user to homepage ( `/` )
	
Step 3:
	Create a homepage ( `/` ) with a navbar showing users name and profile pic.

After clicking on profile pic redirect to (/profile) page where user can edit
following details
 
* First Name
* Last Name
* Phone Number
* Profile Pic
* Password

Step 4: 

Show a form with following fields to save bookmark

- Url
- Description ( can be empty )

	After successfully submitting bookmark show alert message as ( "Bookmark saved
	successfully" )

Step 5:
  On Homepage show all existing bookmark list	with pagination. Each page only
	show 10 bookmarks

Step 6:
	Each bookmark card in list also show a button to edit and delete the bookmark.

Step 7:
	Add a logout functionality to logout the user. 


### Bonus Points:

-	Use Google / Facebook / Apple / Github OAuth to register and login user in the application.
-	Implementing the above application using GraphQL.
-	Implementing the API Rate limiting.
- Store opengraph details such as og:title, og:image,
- Preview `og:image` of bookmark in list of saved bookmarks

### Stack:
To develop the application, use any of the below-given stack:

1. Styling: CSS / SCSS / Tailwind CSS / Material Design / Antd / Chakra UI
2. Frontend: ReactJS ( Preferable NextJS )
3. Backend: NodeJS ( ExpressJS )
4. Database: Postgres / MongoDb / Firebase
5. Hosting: AWS / Heroku / Firebase
	

### Important Notes:

1. UI must be responsive.
2. Application should be build using the above stack.
3. For registration, use JWT or a session-based mechanism
4. Proper error handling is required.
5. Write neat, suitable, bug-free, and readable code as per the coding standards.
6. Create a data model as you need. (foregin keys must be used in the data model if using Postgres)
7. Data model should be normalized ( if using Relational database like
		 Postgres )

**The timeline to complete this app is a maximum of three days. Plagiarism is
prohibited and if an applicant submits a plagiarised work then his application
will be rejected.**
