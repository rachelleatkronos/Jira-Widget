# Jira-Widget
Jira widget for project/issue creation.

Still To Do:

	- Design GUI
		
		=> GUI flow as follows:
			
			1. Login page
			
			2. Option to create issue
			
			3. If IC, then allow project creation if selected
	
	- Polish HTML with CSS
	
	- Insert appropriate JS code to run efficiently
	
	- Encode username/password in Base64 like this 
	
		=> Encoded: Base64("username:password")
	
		=> Place in http request after "Authentication: Basic <EncodedInfoHere>"
	
	- After login, return a dictionary with name/value pairs
	
		=> To do this, you must parse the JSON and create a map of projects and IDs
	
	- Record which project is selected by ID and send to server to create ISSUE
	
	--OR--

	- Extract field data from HTML form and allow the creation of a PROJECT
		
		=> This is only possible if the user has capablities and correct permissions
