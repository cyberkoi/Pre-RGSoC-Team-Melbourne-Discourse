# Discourse-Ad-TM
Discourse Ad (Plugin) Team Melbourne. 

Advertising Plugin Project Plan v1
  1. Plugin will allow administrators to:
-	Create ad codes within a dashboard registered against
      -	Ad tags (positions)
      -	Google Adsense or DFP
      -	Publisher ID
-	The ad units available planned are:
      -	Right side for topics
      	300 x 250
      	336x280
      	300x600
      -	Horizontal ads between posts and listing of items within a topic.
      	728x90
      	320x100 (mobile)
-	The created ads can be linked to:
      -	Certain topics
      -	Listing within topics
      -	Listing within posts within topics
-	Specify the frequency of ads – the issue is that the ads never change as Discourse never “reloads”.

  2. Plugin will:
-	Deliver mobile friendly ads.
-	Integrate with DFP (Double Click for Purchasers) and Adsense

  3. Resources:
-	To be completed.
-	Google's DoubleClick For Publishers API

  4. Steps/Roadmap:
-	Write the plugin - Javascript
-	Test the plugin
-	Designing and implementing the advertising dashboard.
-	Connect Advertising Plugin to V0 of the admin plugin UI.
-	Write document for installing, using, troubleshooting and uninstalling for Docker in the Readme.

  5. Needs from Discourse Community:
-	I would like to see a floating 300x250 banner on the right side of topic pages.
-	I would like to be able to put Double Click horizontal banner ads (e.g. 768 by 90, or smaller) horizontally between the postings (every 8 to 10 posts or so) - similar to the way the TechCrunch puts their ads horizontally between every X number of blog posts. See link below for example: https://www.evernote.com/shard/s106/sh/4eed8786-c64b-4123-ab5e-178f038326aa/de54fd2a784f00a6c683ef077c8e740030
-	The right banner ads (e.g 300 by 250, or 160 by 600, etc.) would also be great.



