# Project Plan: Discourse Advertising Plugin


Team Melbourne (@ladydanger and @snjqi188) plan to contribute to Discourse by creating an advertising plugin.


## 1. About Discourse

Discourse is an open source internet forum software application founded in 2013 by Jeff Atwood, Robin Ward, and Sam Saffron.  It received funding from First Round Capital and Greylock.

Discourse aims to improve online discussion quality through improve forum software.  It is written in Javascript and Ruby on Rails.


## 2. Coaches

The coaches involved in this project are shown below.

**Company/Individual** | **Coach Names**
--- | ---
Coaching Company: Redbubble | Georg Friedrich, [@georg](https://github.com/georg)
 | Dane Natoli, [@link664](https://github.com/link664)
 | Shanon McQuay, [@compactcode](https://github.com/compactcode)
 | David Carlin, [@davich](https://github.com/davich)
 | Joseph Miller, [@joffotron](https://github.com/joffotron)
 | Seb Glazebrook, [@sebglazebrook](https://github.com/sebglazebrook)
 | Michael Milewski, [@saramic](https://github.com/saramic)
 | Myles Eftos, [@madpilot](https://github.com/madpilot)
 | Tom Adams, [@tomjadams](https://github.com/tomjadams)
Individual | Jo Cranford, [@jocranford](https://github.com/jocranford)
Individual | Adel Smee, [@adelsmee](https://github.com/adelsmee)


## 3. Mentor

Robin Ward will be our mentor.  Robin and his business partner built Forumwarz, a well-designed web game about forum culture in Ruby on Rails back in 2006.  He is co-founder at Discourse.

To communicate with our mentor, we will use Discourse for discussions.  We've used it [already](https://meta.discourse.org/t/rails-girls-soc-banter/26875) and have received input from all the co-founders of Discourse.


## 4. Project Issues & Goals

As this project is about creating an advertising plugin, the overall issue it will solve is the need for users of Discourse to monetize their forums and therefore, keep its operation sustainable.

We have split the project issues and goal into baseline and stretch (see **Point 4.1 and 4.2 respectively** ).

The baseline goals are those we will commit to achieving within the Rails Summer of Code period (July – September 2015).  If the baseline goals are achieved before the end of RGSoC, potential stretch goals for the remaining period have been identified.



### 4.1 Baseline Issues and Goals

Issue No. | Issue | Goal 
--- | --- | --- 
4.1.1 | Placement: Advertising can only be put in the header and footer. | Create suitable ad tag positions within the structure of discourse.  By topic and by list view.
4.1.2 | Size: Existing structure only allows fixed size advertising in header and footer. | Creating ad tags for the following sizes and location.  For right size for topics: 300x250, 336x280, 300x600. For horizontal ads between posts and listing of items within a topic: 728x90, 320x100 (mobile)
4.1.3 | Platforms: Google DFP tags don't work along with lesser known advertising platforms. | Create platform support for Google DFP and Adsense within the plugin.
4.1.4 | Known issue: Ads load only when users refresh the site manually. The ads currently stay blank if going from "Latest" section to a "Topic". | Fix up the loading issue.
4.1.5 | Feature: Ads cannot be rotated (static). | Allow users to specify the frequency of ads.
4.1.6 | Feature: Mobile view of discourse. | Structure ads so that mobile view of ads can be enabled.

### 4.2 Stretch Issues and Goals

Issue No. | Issue | Stretch Goal by easiest to most difficult
--- | --- | ---
4.2.1 | Users of Discourse may be with other advertising platforms. | Support for additional ad providers outside of Adsense and Google DFP to be determined based on research of popular providers.
4.2.2 | Plugin provides the basics for showing ads, but it could be changed so that other people could add other ad providers via their own plugins for more esoteric sources | Extensibility of plugin.
4.2.3 | Users may negotiate their own advertising directly without needing to go through an advertising platform.  Existing plugin from baseline plan would not accommodate this. | Support for custom banners so that Discourse administrators can use their own chosen ads without an ad provider.  This will include basic tracking of how many impressions and clicks throughs the ad received.


## 5. What we expect to Learn
* Creating a functioning advertising plugin. (**INCOMPLETE**)
* Advertising plugin specifics, on multiple platforms and devices (PC and Mobile).
* In the process learn Javascript and Ruby (also see **Point 6** and **Point 8** below).
* 
* As we're both beginners in Rails and Javascript, we hope to pick up some skills prior to RGSoC so that we'll be even more adequately prepared for the 8 week-long tasks (see **Point 6**)
* We chose the following issues as they're new concepts to us but are manageable for our skill level:
*  Learning simple hook plugins: for uninstall, deactivation and activation purposes
*  Learning to install google analytics with web tracking purposes for plugins
*  As such, understand the scope and integrity of plugins: its potential and purposes for Discourse
*  From our current understanding, plugins would require a few files of code, and with that base that we aspire to achieve in 8 weeks, we hope to reach our stretch goals by adding advance features (see **Point 4.2**). 


## 6. Project Roadmap

The roadmap breaks down the action items we have planned to achieve the baseline goals shown in **Point 4.1**.  As stretch goals are contingent on meeting baseline goals, stretch goal items are not shown below as they will be determined in discussion with our mentor and coaches if the case arises.

**Item** | **Activity and Goal Achieved**
--- | ---
1 | Set up Discourse development environment
2 | Create basic "Hello World" Discourse plugin
3 | Plan and Create Ad plugin: first step, shows boxes where ads should be on Discourse ( **Goal 1, 2 and 6** )
4 | Separate boxes into an Ember component for re-use
5 | Add support for an ad provider to the component – Adsense and Google DFP, as it's the most popular ( **Goal 3** ).
6 | Add site settings to configure plugin ( **Goal 5** )
7 | Create tests for plugin component and debug ( **Goal 4** )
8 | Package plugin for Distribution


## 7. Required Learning

As stated by Robin Ward (mentor):

> "This plugin will be heavy on the Javascript side and lighter on the Ruby side. We hope that our students can freshen up on the Javascript fundamentals before getting started. Going through the basics of Ember.js will also be helpful but I think we can learn enough to get through that if the Javascript basics are solid."

We will make time to learn the following:

**Prior to RGSoC commencing (before July 2015)**

We intend to make time available before July to complete the following tasks:

* Acquire Javascript fundamentals
⋅⋅* Vi: Javascript basics itunes library course + get fundamental help from codeacademy. Read Agile Web Development with Rails 4.  Go through [http://eloquentjavascipt.net/](http://eloquentjavascipt.net/).

⋅⋅* Sarah: Javascript basics ^itunes library course + get fundamental help from codeacademy and see how much I can cover from the following advice http://code.tutsplus.com/tutorials/the-best-way-to-learn-javascript--net-21954. Also to learn rails http://www.schneems.com/ut-rails/.

* Read through Ember.js - [http://guides.emberjs.com/v1.11.0/](http://guides.emberjs.com/v1.11.0/), [http://todomvc.com/examples/emberjs/](http://todomvc.com/examples/emberjs/).
* Familiarization with Discourse by:
⋅⋅* Installing Discourse locally.
⋅⋅* Playing with the code base.
⋅⋅* Creating a trivial plugin, looking through plugins on meta, install and play with code to try and change things.

**During RGSoC**

* Schedule a Javascript workshop at Redbubble. Particulars of this workshop will relate to building the plugin.
* Update our social media platforms and daily log with current progress. 
* Get in-touch with the community, attend rails meetups, spread the word!
* Keep a weekly blog of our learning adventures.  Vi currently blogs a
* Redbubble = coaching company + our workspace at Melbourne CBD. 


## 8. How It Will Work

To make sure that we work effectively towards achieving our goals, we plan to:

* Have daily stand ups and fortnightly retrospectives with coaches in the coaching company.
* Use pull requests with individual coaches.
* Manage daily tasks and workflow through trello.com
* Schedule coaches and mentor times through a shared Google calendar.
* 
* Overall communication channels: Github private repo (see @snjqi188 discourse-ad-tm), Discourse banter (see link in Point 3), Email, Google hangout, Google calendar
* Overall update channels: Twitter/Blog (to be created), trello
* 
* Coaches' weekly commitment, generic timetable:
* Jo: 8-10am or after 4pm, either Tues, Wed, Thur
* Adel: After 2.30pm on Tues, Thur
* Redbubble (Dane and Georg): Anytime in the office with volunteer coaches to work it out.


## 9. Rationale for Choosing to Work on Issues Identified in Discourse

We believe that Discourse is a fantastic discussion platform and the advertising plugin is a practical contribution that would be valuable for current and future users of Discourse.  That is the reason why we have chosen to work on the issues identified.  Additionally,

* Vi: I intend to use Discourse to create a forum and down the track, advertising is something I would utilize. I would be eager to maintain and further the contribution of the advertising plugin beyond Rails Girls Summer of Code.
* Sarah: Discourse is a relatively well-developed site. Hope to brush up on coding and gain some real experience with rgsoc and discourse with fantastic mentors and coaches. Also, advertising plugins are fairly interesting. Fairly excited to venture into the open-source community.

At the end of the day, we'd like to create something that is requested and needed by the Discourse community.
