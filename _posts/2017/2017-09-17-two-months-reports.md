---
layout: post
title: Two month retrospectives - What your board did so far 
author: Tomas Petricek
date: 2017-09-17
---

Back in July, we asked everyone on the F# Software Foundation board [what are their plans
for the first two months](https://the-fsharp-mirror.github.io/2017/board-member-plans-for-the-first-two-months).
Two months later, in August, I asked everyone to write a brief retrospective:

> Big thanks to everyone who responded to my question about "2 month plans" for their board 
> membership! As you know, I started The F# Mirror to inform the F# community about what the 
> board is up to and [published the commitments there](https://the-fsharp-mirror.github.io/2017/board-member-plans-for-the-first-two-months) 
> together with [an update in the mid-term](https://the-fsharp-mirror.github.io/2017/first-month-board-update). 
> Now that the 2 months are over, I'd like to collect "retrospectives". (...) 
>
> You can share links to what you did, reflect on what are "blocking issues" for some of the 
> ideas or ask the readers for feedback on anything! (I will create GitHub issue for comments.) 
> I'd like to split the retrospectives from more future plans - I will be coming back to 
> collect future plans next week!

## Announcements

Before I share the retrospectives from the board members, I thought that it would be useful to 
highlight the most important news based on the reports from board members. The most important
news from the first two months are:

 * [**Community diversity programme**](http://foundation.fsharp.org/announcing_the_diversity_program) - 
   The F# Software Foundation launched a community diversity programme! The programme currently 
   offers free tickets to F# conferences and other events for members from underrepresented minorities.   
   Thanks to Kit Eason ([@kitlovesfsharp](https://twitter.com/kitlovesfsharp)) who initiated this.
   
 * [**F# Mentorship (round 3)**](http://fsharp.org/mentorship/) - The F# Software foundation organised
   third round of the mentorship programme which pairs students with mentors and provides a great way
   to learn more about F# by meeting regularly for 8 weeks. Thanks to Gien Verschatse ([@selketjah](http://twitter.com/selketjah)
   for getting the round three started. This is happening now, but keep an eye on
   [@fsharporg](https://twitter.com/fsharporg) for future rounds!
   
 * [**Open meeting agenda**](https://github.com/fsharp/fssf-ask-the-board) - The open meeting agenda
   initiative started by Alena Hall ([@lenadroid](http://twitter.com/lenadroid)) allows everyone in 
   the community to suggest topics that the F# board should discuss. Have a look at [the existing 
   discussions](https://github.com/fsharp/fssf-ask-the-board/issues?utf8=%E2%9C%93&q=is%3Aissue%20) 
   and if you have something that  the board should cover, open an issue!
   
 * [**Growing a local community**](https://github.com/fsharp/community.fsharp.org/blob/gh-pages/BUILDING_COMMUNITY.md) - 
   Starting a user group is a huge task. To make it easier to grow the F# community, Mathias Brandewinder
   ([@brandewinder](https://twitter.com/brandewinder)) started collecting ideas, tips and tricks in 
   this document. It is not yet on [fsharp.org](http://fsharp.org), but the plan is to publish it
   there eventually. In the meantime, send Mathias your comments!
   
 * We also have two new or resurrected F# meetups around the world. [**F# |> Quito**](https://www.meetup.com/FSharp-Quito) 
   in Ecuador started by Edgar Sanchez ([@edgarsanchez](http://twitter.com/edgarsanchez)) is the 
   highest F# meetup in the world ([an elevation of 2,850 metres (9,350 ft) above sea level](https://en.wikipedia.org/wiki/Quito))
   and had 4 events already. The [**F#un and MOre Rhein-Main**](https://www.meetup.com/F-un-and-More-Rhein-Main/)
   meetup resumed working thanks to Victor Peter Rouven Müller ([@realvictorprm](http://twitter.com/realvictorprm)).

## Upcoming conferences

We also have two F# conferences coming very soon. Those are not directly organised by the F# Software
Foundation, but they are supported by the F# Foundation community diversity programme. The Open F#
conference is also co-organised by two F# Foundation members (Gien Verschatse ([@selketjah](http://twitter.com/selketjah),
Mathias Brandewinder ([@brandewinder](https://twitter.com/brandewinder))), so they deserve a mention
in the Mirror too!

 * [**Open F#**](http://openfsharp.org/) (28-29 September 2017, San Francisco, USA) is a two day
   F# conference with two tracks full of workshops and talks for both beginners and experts.
   
 * [**FableConf**](http://fable.io/fableconf/) (22-23 September 2017, Bordeaux, France) is a one day
   conference focused on Fable - the awesome F# to JavaScript compiler - featuring talks on Fable,
   Elmish and many other client-side development topics.
 
 
## Retrospectives from members

As mentioned above, I asked everyone to write a brief retrospective. The idea was to learn 
what went well, where there is a room for improvement and also, how the community can help the
F# board. You can find the retrospectives below.

### Alena Hall ([@lenadroid](http://twitter.com/lenadroid))

> I am supper happy that the Board accepted my Community Agenda/Open Agenda proposal. I am even 
> more happy that we have received 4 issues during the first 3 days of fssf-ask-the-board was 
> available! During the August Board meeting we have discussed all of them and responses are on 
> the way (if not already there). 
>
> I strongly believe that the Community should primarily define what we do as a Foundation, 
> therefore, now we have a direct way for each F# Community member to reach us with their 
> ideas and proposals. I really encourage everyone to submit all the proposals you might 
> have, how to make F# even greater, how to increase diversity of the Community, how to bring 
> more contributions to the language, and any other thoughts. 
> They are all welcome, please, don't hesitate.

### Chet Husk ([@chethusk](http://twitter.com/chethusk))

> [With respect to] my board goals, let me point you to what I've been spending my time on recently 
> [F# Projects .Net Core/New SDK Upgrades](https://docs.google.com/spreadsheets/d/1CZZqBX3SWFLH8SSir9a24lpEbJqskCAjNPeF9sGdOYg/edit#gid=0)
> This document is my beginning of auditing the ecosystem, starting with introductory/highly 
> used projects, and identifying what it would take to get those projects updated to .net core 
> and the new SDK.  
>
> This is in line with my experiences with newcomers to F# in my workplace and in my local meetup.  
> One of the biggest stumbling blocks is the lack of a unified way to interact with F# projects, 
> coupled with a distrust of mono from \*Nix folks.  I hope to coordinate PRs against projects 
> identified here with other community members and eventually green up the most common entry 
> points/projects in our ecosystem.  I want things like the koans to be a simple `dotnet watch` + 
> live-coding experience so that newcomers have zero friction. I want headline F# projects to be 
> using the latest and greatest tech so that we combat the perception that F# isn't up to date with how dotnet as a whole does things.
>
> Mostly because the feedback I've gotten from local newcomers who were very confused about how to 
> get F#, difference between mono and dotnet core, and why F# just wasn't on the new thing.

### Edgar Sanchez ([@edgarsanchez](http://twitter.com/edgarsanchez))

> 1. Starting the local F# group was easy, an even having regular monthly meetings hasn't been 
>    hard, getting over 10 or so people coming is hard, getting other speakers is hard (but volunteers are starting to appear)
>
> 2. Presenting F# in universities has been surprisingly popular, even more surprising the fact that 
>    I've made more workshops with teachers than with students, 4 workshops and 3 sessions so far, 
>    and counting :-). The goal of getting teachers to officially use F# in the classroom hasn't 
>    happened yet, but the fact that one uni is already *paying* for a 40-hour workshop for teachers makes me hopeful (edited)
>
> 3. Getting a new F# group in another city is stalled, there is interest but no one has jumped 
>    into it so far, and the success of Point 2 has got most of my focus 
>
> 4. I started a [series of blog posts](https://medium.com/@edgarsanchezg) about very simple introductory F# topics that has been, 
>    to my surprise, well received. I encourage everyone to share whatever little knowledge you've
>    got, there will always be people who will benefit! The next frontier: videos, a lot of people 
>    ask for it, I am slowly getting stamina for the inevitable... :-)

### Mathias Brandewinder ([@brandewinder](https://twitter.com/brandewinder))

> I had 4 goals this quarter, which was probably a bit aggressive.
>
> On the positive side, I kept my commitment to show up for office hours every Friday, 16:00 UTC, 
> in the `#fssf` Slack channel. I started the office hours to make the Foundation and its board 
> less impersonal, by opening up a space where members could bring up their questions, ideas or 
> concerns, and simply have conversations. I am very thankful for all of you who came to chat, 
> the conversations were both useful and fun, and I'll keep going with office hours.
>
> The part that didn't go as well as I hoped is my three other goals. I did make [my notes on 
> growing a meetup/local community publicly available](https://github.com/fsharp/community.fsharp.org/blob/gh-pages/BUILDING_COMMUNITY.md), 
> but the solution feels half-baked. It's editable, but not really easy to find. With Reed's help, 
> I made sure a large inventory of stickers was available in Europe (and South America should be 
> covered soon as well). However, again, that's only a partial solution - there is no good way 
> for members to find about that resource, and the mechanics of distributing stickers is still 
> overly complicated. And I gathered some feedback on what I think will be a simpler Speakers 
> program, but I haven't had time to go further than that.
>
> What were the blockers, and what do I plan to do about them going forward?
>
> One obvious blocker is time; small FSSF-related activities end up eating a surprising amount of 
> bandwidth. As an example, preparing and posting announcements, tweets and Facebook updates for 
> fsharp.org is time consuming, and needs to happen. So one of my goals ahead is for me to 
> become less of a bottleneck in the Communications Working Group; but for that, I need help. 
> So if you have been wondering how to help fsharp.org, one simple first step is to join the 
> Ministry of Propaganda (ping me on Slack to know more about it), and help craft our public messages!
>
> The other blocker is, there is no obvious place to make resources easy to discover. Technically, 
>both goals (stickers, meetup guidebook) are done. But left in their current state, I doubt anyone 
> will find out about them. In that frame, two things I would like to focus on next are, providing 
> a central "community resources" page on community.fsharp.org, with clear links, and making 
> awareness about these resources and programs a priority for the Ministry of Propaganda. 
> Did I mention already that we need your help? :-)

### Victor Peter Rouven Müller ([@realvictorprm](http://twitter.com/realvictorprm))

> Instead of doing much for the F# website I've started looking where my current skills are 
> more helpful. I was blocked during the two months due to personal reasons (final school exams) 
> and due to my experience of what is achievable. 
>
> However during those two months I was able to setup a cooperation with the new .NET group in 
> Frankfurt (I've attended it personally and achieved that the next meetups are going to be 
> about F# mainly!). Also I collected information about in which other topics F# needs more 
> love (discovered game development ;-))
>
> It would be great if people simply show that they're behind us Trustee's. More people and 
> companies are going to listen to us the more people are behind us.

### Yukitoshi Suzuki ([@yukitos](http://twitter.com/yukitos))

> I don't have no updates about web site's language support as a board.
> On the other hand, when I held a local F# meetup one month ago, I asked attendees how often 
> they're using our web site and whether they want to have other language version of the site. 
> Unfortunately the most of their answers were no. However, I felt that they just don't know 
> how useful information can be found on our web site, so I'd rather like to prioritize 
> advertizing our site, then investigate which pages are more useful and worth for the 
> cost of translation. 

### Gien Verschatse ([@selketjah](http://twitter.com/selketjah))

Unfortunately, the retrospective from Gien got lost because of the 10,000 message history 
limit on Slack and sloppy work by your reporter (who should have copied it somewhere else
rather than relying on ephemeral digital archives!) However, Gien reported the following 
things in her retrospective:

 - Became the Chairperson of the Training and Education Working Group and adapted her 2 month goals to focus more on 
   activities related to the mission of this group.
 - Started the third round of the [F# Mentorship programme](http://fsharp.org/mentorship/).
 - Has been running regular office hours on every other Monday (5pm London, 9am West, 
   12pm East, 1am Tokyo). 
 - Became the distributor of F# stickers for Europe. If you need some, ping 
   [@selketjah](http://twitter.com/selketjah)
 - Finally, Gien has also been co-organising the [Open F#](http://openfsharp.org/) conference
   (which is not an activity of the board, but has been taking a lot of time recently)
 
### Kit Eason ([@kitlovesfsharp](https://twitter.com/kitlovesfsharp))

[We did not get a retrospective from Kit, but he was instrumental in starting the 
[Community diversity programme](http://foundation.fsharp.org/announcing_the_diversity_program).]

### Scott Wlaschin ([@ScottWlaschin](http://twitter.com/ScottWlaschin))

[We were not able to get a reply on Slack from Scott.]

### Article history

 - 21 September - The new round of mentorship is third rather than second round as previously reported. (Thanks Gien for the correction!)
