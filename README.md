# Product design and development in machine learning
<i> Developing a machine learning product </i>

## Overview
 There have been a lot of articles, videos, research papers, etc. from the machine learning community on MadewithML platform lately and I want to be able to    organize all of it. I want to be able to attach relevant (explicit and implicit) tags to the content so that the users can discover them when they need it.

## Relevance

<b> Core business values </b> One of the core business values of the platform is to provide the curation that the users are not able to find anywhere else. Therefore, it’s a top priority to ensure that the platform meet this core value.

<b> Engagement </b> When the users are able to discover the precise resources for their needs, this drives engagement on the platform and improves perceived value. If they had addressed the search related complaints over the last X months, it would have increased engagement by X% leading to Y% increase in sponsorship fees.
  
## Background
  The current search capabilities involve basic text matching with search queries. Unfortunately, many of the terms that the users are searching for involve queries that are not explicit in the content (ex. natural language processing). I need to be able to tag these implicit tags to all the content so that the users can discover them.

  Q: Why do we even need tags?
  <li> Tags represent core concepts that may be implicit. </li>
  <li> Keywords in a project's title or description may not be a core concept → noisy search results. </li>
  
## Objectives
  <li> Identify the relevant tags for a given content with 70% recall. </li>
  <li> Reduce week-to-week tickets based on search errors by 20% </li>
    
## Solutions
   - Current solutions → simple text matching based search (noisy and incomplete).
   - Identify tags for a given content → use available signals from content.
   - Measure engagement on platform → track engagement after discovery of content.
         ![image](https://user-images.githubusercontent.com/59816103/155352421-f8eb375b-da5c-44ef-aaba-23296aad8aa2.png)
 
   - Alternatives considered
        - Currently, the tagging process involves adding tags into an input box but what if we could separate the process into sections like frameworks, tasks,             algorithms, etc. to guide the user to add relevant tags. This is a very simple solution that should be A/B tested on and could even complement more               sophisticated solutions.
  

Simulation of creativity in Machines
