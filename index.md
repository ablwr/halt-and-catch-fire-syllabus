---
layout: about
title: Halt and Catch Fire Syllabus
permalink: "/"
---



# README

This site features a curriculum developed around the television series, [Halt and Catch Fire](https://www.google.com/search?channel=fs&client=ubuntu&q=halt+and+catch+fire) (2014-2017), a fictional narrative about people working in tech during the 1980s-1990s.  

The intent is for this website to be used by self-forming small groups that want to create a "watching club" (like a book club) and discuss aspects of technology history that are featured in this series.

There are 15 classes, for a "semester-long" course:  
{% for post in site.classes %}~ <a href="{{ site.baseurl }}{{ post.url }}">#{{ post.number }}</a> {% endfor %}~

Brief guide to class layout:
- **Apéritifs** Casual viewing presented before gathering. This is entertainment; not required viewing.
- **RFC as koan** A Request for Comments from the Internet Engineering Task Force, for reflecting on.
- **Emulation as koan** An emulated computer in the browser, also for reflection.
- **Themes** Recommendations for topics to be discussed.
- **Prompts** Questions to inspire conversation when gathering.
- **Readings** Related material for deeper thinking on the class topic.
- **Description** Brief summary of what's going on in the episodes and how it relates to tech history at large / the weekly topic.
- **Episode summaries** A link to summaries of the episodes that should be watched prior to meeting as a group. Watching each episode is not required; if time doesn't allow, refer to the summaries. Content warnings are provided for relevant episodes. If there are specific concerns, this can determine which episodes should be skipped or anticipated before viewing. 
  
<br/><br/>
Curriculum and website designed by [Ashley Blewer](https://ashleyblewer.com).  

![under construction]({{ site.baseurl }}/assets/img/construction.gif)
