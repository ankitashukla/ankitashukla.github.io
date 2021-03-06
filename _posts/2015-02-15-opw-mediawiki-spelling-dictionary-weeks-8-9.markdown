---
author: ankitashukla707
comments: true
date: 2015-02-15 02:05:00+00:00
layout: post
slug: opw-mediawiki-spelling-dictionary-weeks-8-9
title: 'OPW MediaWiki Spelling Dictionary: Weeks 8 & 9'
wordpress_id: 34
---

Hello!

I am glad to announce that I have successfully covered half way of a very significant journey of my life. We have just had our mid-term evaluation of the projects! And Spelling Dictionary is ahead of its timeline. :)

With much more enthusiasm, I kicked off Week 8! :D

<!-- more -->

I created a new css file with definitions for the classes I added to the HTML tags. Next, the file was loaded in SpellingDictionary.php . Additionally, I worked on admin page and added a direct link (on the admin dashboard) to the form for adding spellings. Also, added a dropdown for language selection and added corresponding messages in en.json.

Unfortunately, this time there was a significant gap in the MediaWiki code update on my system. Hence, the MediaWiki core update had left the extension code broken at some places. So, I started off the 9th week by fixing errors in form-display due to core update and updated code as per latest form-object definitions. Moving on with the admin functionalities, I wrote the function for deleting any spelling directly from the admin dashboard. Following this, I improved it by using an ajax function for deleting spelling from table (which is called when admin clicks on "Delete" in order to delete any spelling from the table).

Moreover, I removed the originally hard-coded values for language selection and wrote code to select language from drop-downs, thus providing option to choose language to view spellings. Another major modification here was passing of complete formdata to function instead of explicit field data while selecting language to view words.

Finally, as per the regular code-base cleaning regime, I removed some unnecessary (js) files and cleaned up the code.

That was all for these two weeks.
Catch you all back later with the progress of the further weeks.

Cheers! :)
