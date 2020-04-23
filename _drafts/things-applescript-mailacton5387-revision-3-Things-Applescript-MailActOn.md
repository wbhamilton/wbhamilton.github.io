---
id: 6398
title: Things + Applescript + MailActOn
date: 2012-08-09T08:55:04-07:00
author: wbhamilton
layout: revision
guid: http://1twentyeight.com/5387-revision-3/
permalink: /5387-revision-3/
---
I&#8217;m a Mac guy. So if you&#8217;re not, this will not be that helpful to you.

[<img class="alignnone size-full wp-image-5388" title="Things" src="http://1twentyeight.com/wp-content/uploads/2010/09/Things.png" alt="" width="610" height="203" srcset="http://1twentyeight.com/wp-content/uploads/2010/09/Things.png 610w, http://1twentyeight.com/wp-content/uploads/2010/09/Things-300x99.png 300w" sizes="(max-width: 610px) 100vw, 610px" />](http://culturedcode.com/)

I use [Things](http://culturedcode.com/) as my task management app. I love it. To-Do items can be tagged, assigned to **Areas** (that you define yourself), and can be assigned to **Projects** as well. For my workflow I have **Areas** such as Personal and CommunityOne. When I start a new CommunityOne project I create a new **Project** container that holds to-do items for that specific project. Non-project related tasks sit in the more general **Area** for CommunityOne. This seems to work well for me.

One of the other aspects of Things that I appreciate are the [keyboard shortcuts](http://culturedcode.com/things/wiki/index.php/Keyboard_Shortcuts). Anything that allows me to keep my hands on the keyboard without reaching for the mouse is a plus. Command-N creates a new task, Option-Space creates a quick entry task, Shift-Command-N creates a new project&#8230;you get the idea.

One specific shortcut is Control-Option-Spacebar which invokes the Quick Entry box, but with Autofill. In practice, say you&#8217;re reading an email with a list of things you need to do for a project. You can select/highlight that list in your email, hit Control-Option-Spacebar and the Quick Entry box will pop up with your highlighted selection pasted in the Notes section of the task, with a link to the original email. Pretty smart.

There are times, however, that I simply want to create a new Task based on an email. I don&#8217;t need to take the time to highlight a portion of the email. I just want a new task with the subject of the email as the name of the task, with a link to that email. As fate would have it, Things has Applescript support built in. And there are clever Things users that have created [scripts](http://culturedcode.com/things/wiki/index.php/User_Contributed_Scripts) to make Things even easier to use. One of the scripts allows Things users to do just was I was looking to do, create a new Task based on an email. There were a couple of small bits that I changed in the script. One, the script originally assigned a tag to the new Task using the senders name. I don&#8217;t need that. I just wanted a tag assigned called &#8217;email&#8217;. That way I can track all my to-do&#8217;s that just pertain to emails. Also, the new Task was created in the Inbox within Things. I hardly ever use the Inbox. But I do use Next quite a bit. So, I changed the script to put my new Task in Next, not the Inbox.

The last piece of the process is invoking the script within Mail to actually create the new Task in Things. To do that I use [Mail Act-On](http://www.indev.ca/MailActOn.html). Mail Act-On is a plugin for Apple Mail that allows the user to create Rules and then invoke those rules using keyboard shortcuts. So if type Control-I it colours the email red, for Important. Or if a bill or invoice email arrives I use Control-M to colour the email green, for Money. To create a new Task in Things (with the Title being the email&#8217;s subject, and being tagged with &#8217;email&#8217;, and being placed in &#8216;Next&#8217;) I created a rule in Mail using Mail Act-On that invokes the Applescript I created anytime I use the shortcut Control-T.

All of this has made the process of reading through emails, deciding which ones required action, and then creating a to-do based on that email, much more streamlined and efficient. If you&#8217;re interested in the Applescript you can grab it here: [MailToThings](http://d.pr/f/1GhK6o)