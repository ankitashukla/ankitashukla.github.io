---
author: ankitashukla707
comments: true
date: 2014-12-23 17:22:08+00:00
layout: post
slug: opw-mediawiki-spelling-dictionary-weeks-1-2
title: 'OPW MediaWiki Spelling Dictionary: Weeks 1 & 2'
wordpress_id: 13
summary: 'Progress of Weeks 1 and 2 in the MediaWiki Spelling Dictionary project '
---

The last two weeks have been quite a learning experience. I had already been discussing various aspects of the project like the special pages, database structures and other design aspects with my mentor towards the end phase of the community bonding period. So, the major research part was already handled before the start of week 1! ;)

<!-- more -->

I accomplished the aimed basics in these two weeks and switched among certain objectives of the initial timeline after discussing with my mentor as it seemed better-suited.

I had a hangout with my mentor Kartik and discussed the tasks for the first week. Meanwhile, I had some wonderful time fixing my mediawiki-vagrant install! No, I mean literally! I was getting a page with some cryptic errors! I tried few tricks and tips, couldn't succeed, asked on irc {(un)fortunately during the lazy hours}, got no response and got back to trying myself. And tada! I fixed my mediawiki-vagrant install bugs without any help! :)

Once done with the _adventure_ I next took up some reading where I read extensively about developing an extension from [here](https://www.mediawiki.org/wiki/Manual:Developing_extensions) and [here](https://www.mediawiki.org/wiki/How_to_become_a_MediaWiki_hacker/Extension_Writing_Tutorial). These are well documented wikis providing guidance and insight to new developers towards MediaWiki extension development. My mentor also suggested I browse the code of [TwnMainPage extension](https://github.com/wikimedia/mediawiki-extensions-TwnMainPage) to get an idea of a functional extension. I cloned the extension template and experimented with the code to learn about the various features of extension and extension development.

Additionally, during the first week, I set up the directory structure for SpellingDictionary extension and pushed the code to [github](https://github.com/ankitashukla/mediawiki-spelling-dictionary). Adding a (GPL) License to the project provided me an opportunity to get acquainted with the practice of adding license to a project and the various licenses used by open source software.

The second week started with deciding up on the most suited database for the spelling dictionary based on the previous research done during the community bonding period. I next setup the database and the table for storing words.

We established on setting up the user dashboard on the Spelling Dictionary special page. So, the week was spent deciding upon the dashboard for the project and the UI of the Special page with my mentor. Meanwhile I browsed through the Content Translation (beta) page and the code to attain familiarity with the same. I have been experimenting with the special page.

Next week shall be focusing on setting up a form on the special page for the user to submit words and start the work on the admin page.

Shall keep updating! :)
