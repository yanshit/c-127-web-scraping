# Web-Scraping---1
**For anyone reading this that is not not on BYJU's Future School Coding Curriculum, This is a fake story, that they provide to you, so that you have a "problem" to solve with code.**
Story:
Our Sun is dying! The world is in an emergency as we are about to lose our star. All groups
of scientists around the world have gathered together and created a technology to shift our
Earth into another solar system, but which one exactly? Which star out there is safe and
welcoming to our Earth? You have been assigned the task to research about stars so that we
can choose the best one for us!

Getting Started:
1. Open your VS Code editor.
2. Create a virtual environment.
3. Source the virtual environment.
4. Install bs4 and requests using pip.
*We are not going to use Selenium for this project

Specific Tasks to complete the Project:
1. Understand the website we want to scrape first: Brightest stars in universe.
2. Let’s decide the headers we will keep for our study:
● Name
● Distance
● Mass
● Radius
3. Study the page in inspection mode to understand the patterns. You can use the
following questions:
● How have they structured their HTML?
● How many tables have they used?
● Is there any specific pattern in the attributes each of the HTML tags has?
4. Device a strategy on how to scrape and structure your code.
5. Observe the HTML of the page
6. Import all important/relevant modules.
7. Define the START_URL, headers and an empty list to store the star’s data.
8. Get the HTML page with requests module.
9. Try to create a CSV by fetching one row from any of the tables.
● This need not be all the data. This will be continued in the next project and we
will scrape all the data.

Submitting the Project:
1. Upload your completed project to your own github account.
2. Create a new repository named “ Web scraping 1”.
3. Upload working code to this github repository.
4. Enable Github pages for the repository.
5. Copy the link to the github pages link in the Student Dashboard. link to the github
pages link in the Student Dashboard.

Hints:
1. On getting the HTML page with requests module, you might get an
SSL error. Add verify=False with the request and it will not verify for a
secure connection.
2. Notice the unit of dimensions of the star data such as radius, distance
and mass. If you are scraping from different sources make sure the
units are the same, if not then we have to convert them.
3. Your observations may be:
● There is only one table on the page
● Headings of the table are in <th> tag
● All the star’s data rows are <tr> tags
