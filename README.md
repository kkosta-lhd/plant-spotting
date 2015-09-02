# plant-spotting

9-1-2015－Katherine Kosta
# Plant Spotting − Scope of Work
## Objective/Scope
Team America will develop a web interface to allow users to submit information into a database. The web interface should be simple to use across all devices. After entering simple password, the web interface will allow administrative users to view the information in their browser with the ability to choose a simple reporting format that can be downloaded.

The website will be used by plant enthusiasts in the field to track local flora by entering data into a form on the website. The end users are looking for patterns such as plant behavior and migration. 
## Requirements
1.	The website will consist of a form for user submission that is be useable across all browsers and platforms and must be responsive. 
2.	The form will submit data to a database from which it can be retrieved through a secure admin page.
3.	Each submission will generate a unique identifier that is non-sequential.
4.	After login, the admin page will return all of the information gathered. Download buttons will allow the administrative user to create downloadable files.
5.	API data - current information should be used. User can add notes if their information differs from what the API shows.

## Deliverables
1.	Website Form Fields
    * Name － text field
    * Date/time － calendar (default to current date and time)
    * Plant name － text field
    * Soil conditions － dropdown + other (text field)
	    *Client will provide list of soil conditions*
    * Temperature －text field
    * Weather conditions － text field
    * Locations － GPS if available, text field if not
    * Notes － User may use this field for further explanation
2.	Database
    * Simple database.
3.	Admin Access
    * Single password login for administrative users.
4.	Reporting
    * All views will be ordered by date.
    * Initial view is formatted data dump to screen.
    * Buttons will be visible to enable administrative users to download database information in .XLS, .PDF or comma-delimited files.

## Optional Features
1. Weather API
2. Location API

## Out of Scope
1.	Image integration
2.	Database sorting
