---
author: ankitashukla707
comments: true
date: 2015-03-09 12:49:00+00:00
layout: post
slug: opw-mediawiki-spelling-dictionary-week-13
title: 'OPW MediaWiki Spelling Dictionary: Week 13'
wordpress_id: 41
---

Welcome back! It's the last week of the internship. I have mixed feelings regarding this: I am happy because of the wonderful journey I had and the various new things I learned and sad because it is coming to an end.

I'll start with the accomplishments of this week. After my exams, I had a lot of tasks to do, and am happy to inform you all that I was able to manage it all within time (lots of coffee and a few sleepless nights! ;) )

<!-- more -->

I started the week by learning in great detail about the user groups and rights management on special pages in MediaWiki. Using the knowledge I gained, I created a new user group 'spelladmin' for implementing restricted access on the admin dashboard and other admin-concerned pages. Immediately after this, I was faced with an issue as I was unable to access these pages myself, since I wasn't an administrator on my MediaWiki installed instance. Therefore, I read about how could one add members to any group and figured out it was done using the createAndPromote.php maintenance script. I ran the following command in the vagrant terminal:

    
    mwscript createAndPromote.php <span class="re5">--bureaucrat --sysop --spelladmin</span> <username> --force


And thus I added myself in the sysop, bureaucrat and spelladmin groups. The reason behind using `--force` was that I had to grant rights to an already existing user. Moreover, using `--force` was the reason why password wasn't required here.

Under the final steps of organizing and refactoring the code, I moved parts of code from setup file to newly created separate files for loading resource modules (Resources.php) and for loading classes (Autoload.php). Moreover, I declared the hooks, special pages etc as $GLOBALS in the setup file.

Another major achievement was the fixing of the bug that had been troubling since a long time - the error asking to set a callback on form submit in the ViewByLanguage special page.

Apart from this, I added language options in both the dropdowns (Special:SpellingDictionary and Special:ViewByLanguage) using language codes in languages/Names.php. I took care of making the dropdown language entries lexicographic rather than in any random ordering. :)

In the final phase, I'm improving the documentation for the extension.

I'd like to take up this opportunity to thank gnome for the wonderful opportunity they are providing us with. I extend my gratitude to Marina and Quim for their patience and support. I am honestly very grateful to my mentor Kartik for his all-time support, guidance and friendly attitude. Last but not the least, a big shout out to all my fellow co-interns! You all are truly awesome and it was really amazing to get to know each one of you. :)

Although the internship period might be over, but I'll continue working with MediaWiki and this project in particular. I have worked really hard for this project and would take this to perfection now. :)
