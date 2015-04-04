---
author: ankitashukla707
comments: true
date: 2015-01-28 04:22:33+00:00
layout: post
slug: opw-mediawiki-spelling-dictionary-weeks-5
title: 'OPW MediaWiki Spelling Dictionary: Weeks 5 & 6'
wordpress_id: 27
---

Hello again!

I'm glad to announce that weeks 5 and 6 saw a significant progress. I started off in the 5th week by some minor tweaks that needed to be fixed and then moved on to other more important issues.

<!-- more -->Week 5 was started by organizing the pages and the display of the pages. So, the first step in this direction was the moving of the spelling-word-list display from admin special page to another special page (Special:ViewAll) meant for displaying all the spellings stored in the database. This was necessary to keep the admin page clear of clutter and supporting the idea that the admin dashboard should only have links to various other pages and sections.

The next move was to write code for organizing the various items/links on admin dashboard. The data structure being used resembles a tree and has various sections (as branches). Each section in turn has items (as leaves) linking to different pages. I wrote class-definitions to be used to display items on admin page which was further sub-divided as:



	
  1. Main tree class for the admin page

	
  2. Class to add section to admin page tree

	
  3. Class to add the various items/links in every section


I completed the above mentioned classes as part of my week 5 to display the various sections. Next, I had to link the items under each section to other pages, so that when admin clicks on any item, he is redirected to that page.  Therefore, I wrote code to retrieve another special page for the same too during week 5 (to be used when admin clicks on one of the links like 'Browse all words').

Finally, I coded and initialized the tree to be displayed and completed week 5 on a happy note. :)

For the sixth week, I startred off by displaying a section's text by writing a function that converts object to string for displaying. I had faced an error saying that an object can't be displayed like a string and therefore made this part really important. Once this was achieved, I wrote code to display the text in each section, which would be links to other pages. In the first phase, the page name was being displayed in the form of Special:PageName format. Therefore, I had to change the code to display text for page name on admin page.

Moreover, I took care of any previous inconsistency that might have happened and reorganized the code in proper MVC architecture by dividing this in sub-tasks like:

	
  * Rewrote the code as per MW coding conventions

	
  * Moved the code to display all words to a class's function, and used that to display all words


I optimized the UI by checking for the number of items in any section while adding an item and ensuring proper spacing between different items.

I then, created a special page for displaying words sorted by language (where the admin could select a language and see the spellings of that language). This was followed by adding a corresponding item on admin page to show words sorted by language.

The end for week 6 was marked by completing several small but important tasks:

	
  * Added alias for ViewByLanguage page

	
  * Modified message names and added more messages in the localisation files

	
  * Added message names to localisation file and updated message names in corresponding file


Thus, the end of both the weeks witnessed a significant progress and have been a great learning experience as always. :)
