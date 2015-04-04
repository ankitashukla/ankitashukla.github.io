---
author: ankitashukla707
comments: true
date: 2015-01-11 17:30:35+00:00
layout: post
slug: opw-mediawiki-spelling-dictionary-weeks-3-4
title: 'OPW MediaWiki Spelling Dictionary: Weeks 3 & 4'
wordpress_id: 22
---

Happy new year friends! (Better late than never, right? :)) I wish you all have a wonderful 2015 ahead and hope you had as awesome a start as I had!

Moving on to the progress of the project, weeks 3 and 4 had a greater amount of work done in the former week.

<!-- more -->

However the latter had the timings to be adjusted for my journey to my college. This was further delayed due to the heavy fogs in north India and the resulting zero visibility.

I triggered off the third week by setting up the code for database access. This was required since I had to store the words submitted by users in a database. Related to this, I also wrote a hook for schema update to directly update the database with a corresponding table.

Once, I was done with setting up the table, I next moved on to writing the code for storing words submitted by a user into the table. :)

Next, I created a Special page for admins - /Special:SpellingDictionaryAdmin. I completed week 3 by writing the code to access and display all words on the admin special page. This completes most of the part required to store and retrieve words from database.

Moving on, Kartik and I next discussed about the design of the admin page. We landed upon the decision of using a tree-like-structure as backbone. I read about the various possibilities in this aspect. I also studied the codes of a few extension to get an idea about the implementation part specially [this](https://www.mediawiki.org/wiki/Extension:Admin_Links). Alongside, I fixed several small issues, an important one being the check for an existing table before creating one. I utilized my travel time as much as I could in cleaning up the code. Meanwhile, I updated documentation (README) as well with more elaborate and user friendly guidelines.

(I could not accomplish much this week as I had been travelling for the most part and had some issues with my laptop. It's working fine now after almost killing me by threatening me of complete data as well as environment loss! :) )

That was all folks! :)

I'll soon update about weeks 5 and 6 (Week 5 is going on great with a lot being done, and since most of it is new, I'm learning a lot through the way! :) )
