0x01. Implement a design with bootstrap
 By Nicolas Philippot, UI/UX designer and Guillaume Salva, CTO at Holberton School
 Weight: 3
 Ongoing project - started Jul 6, 2022, must end by Jul 13, 2022 - you're done with 0% of tasks.
 Manual QA review must be done (request it when you are done with the project)
In this project, you will implement 3 web pages with Bootstrap. You will use all HTML/CSS/Accessibility/Responsive design/Bootstrap knowledges that you learned previously.

You won’t have a lot of instruction, you are free to implement it the way that you want - the objective is simple: Have fully functional web pages that look the same as the designer file.

Here the final result:



This webpage has been designed by Nicolas Philippot, UI/UX designer. You can find final screens here

Requirements
You have to use Bootstrap
Your styles.css must be as small as you can - you must use as much as you can Bootstrap classes
Imports
For this project, you will need: fonts from Google, JQuery, Bootstrap CSS/JS

<link href="https://fonts.googleapis.com/css?family=Source+Sans+Pro&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css?family=Coiny&display=swap" rel="stylesheet">

<script src="https://code.jquery.com/jquery-3.4.1.min.js" integrity="sha256-CSXorXvZcTkaix6Yvo6HppcZGetbYMGWSFlBw8HfCJo=" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>

<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
Tasks
0. Read and be familiar with Figma
mandatory
Create an account in Figma and open these files:

Homepage - fig file
Pricing - fig file
Courses - fig file
And “Duplicate to your Drafts” to have access to all design details.



Important notes with Figma:

if your computer doesn’t have missing fonts, you can find them here: source-sans-pro and Spin-Cycle-OT
some values are in float - feel free to round them
“Be pixel perfect” - yes! but mainly make sure colors, size and position are correct. #C271FF is not purple.
For this task, please write an amazing README.md

Interactions note:

Web pages must switch to the tablet version when the screen width is 768px
Web pages must switch to the mobile version when the screen width is 576px
button hover/active: opacity: 0.9
Repo:

GitHub repository: holbertonschool-smiling-school
File: README.md
 
1. Header first
mandatory
Let’s start by the Homepage: create the header/hero piece

Here an archive of all assets needed (for the entire project):

images_images.zip
holberton_school-icon.zip
Desktop:



Mobile:



Repo:

GitHub repository: holbertonschool-smiling-school
File: 0-homepage.html, styles.css
 
2. Carousel of quotes
mandatory
Create the section “Carousel of quotes”

By using a Carousel component of Bootstrap, create this Carousel of quotes.

You can have for the moment one quote or twice the same for testing (like example below)



Repo:

GitHub repository: holbertonschool-smiling-school
File: 1-homepage.html, styles.css
 
3. Popular videos
mandatory
Create the section “Most popular tutorials”

By using a Carousel component of Bootstrap, create this Carousel of video cards.

Reminder:

Desktop: 4 cards
Tablet: 2 cards
Mobile: 1 card


Repo:

GitHub repository: holbertonschool-smiling-school
File: 2-homepage.html, styles.css
 
4. Row of smiles
mandatory
Create the section “Free membership”



Repo:

GitHub repository: holbertonschool-smiling-school
File: 3-homepage.html, styles.css
 
5. Latest videos
mandatory
Create the section “Latest videos”

Copy the block “Most popular tutorials” to “Latest videos”

Repo:

GitHub repository: holbertonschool-smiling-school
File: 4-homepage.html, styles.css
 
6. ... and the footer!
mandatory
Create the footer



Repo:

GitHub repository: holbertonschool-smiling-school
File: homepage.html, styles.css
 
7. Pricing - header
mandatory
Now, let’s do the pricing page: create the header/hero piece

The mobile version must be the same as the Homepage - it’s time to reuse code!

Desktop:



Repo:

GitHub repository: holbertonschool-smiling-school
File: 0-pricing.html, styles.css
 
8. Prices grid
mandatory
Create the prices grid

Desktop:



Mobile:



Repo:

GitHub repository: holbertonschool-smiling-school
File: 1-pricing.html, styles.css
 
9. Quotes section
mandatory
Same as the Homepage, create the Carousel of quotes

Repo:

GitHub repository: holbertonschool-smiling-school
File: 2-pricing.html, styles.css
 
10. FAQ
mandatory
Create the FAQ grid

Desktop:



Mobile:



Repo:

GitHub repository: holbertonschool-smiling-school
File: 3-pricing.html, styles.css
 
11. Close the page with a footer
mandatory
Same as Homepage, create the footer

Repo:

GitHub repository: holbertonschool-smiling-school
File: pricing.html, styles.css
 
12. Courses - header
mandatory
Now, let’s do the courses page: create the header/hero piece

The mobile version must be the same as the Homepage - it’s time to reuse code!

Desktop:



Repo:

GitHub repository: holbertonschool-smiling-school
File: 0-courses.html, styles.css
 
13. Search filters
mandatory
Create the search filters section

Dropdown is a nice way to create filters.

For the selected/placeholder value of both dropdown, no need to have dynamic value - static content is totally ok.

Desktop:



Tablet/Mobile:



Repo:

GitHub repository: holbertonschool-smiling-school
File: 1-courses.html, styles.css
 
14. List of result
mandatory
Create the result section of courses

You can reuse the same cell for testing. Don’t forget to test with odd and even number of cells.



Repo:

GitHub repository: holbertonschool-smiling-school
File: 2-courses.html, styles.css
 
15. Close the page with a footer
mandatory
Same as Homepage and Pricing page, create the footer

Repo:

GitHub repository: holbertonschool-smiling-school
File: courses.html, styles.css
