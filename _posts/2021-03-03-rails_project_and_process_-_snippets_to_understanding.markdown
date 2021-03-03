---
layout: post
title:      "RAILS PROJECT & PROCESS - Snippets to understanding"
date:       2021-03-03 10:16:20 +0000
permalink:  rails_project_and_process_-_snippets_to_understanding
---


The (MVCR) Model View Controller and Routes design pattern funneled with (REST) Representational State Transfer routing is suprisingly straightforward once I became immersed in the build process for my Rails final project. The more I toured through the MVC(R) pattern while building out my application, the more these core concepts become solidified in my visiting mind.
<br><br>
At first glance, Rails appeared to be cluttered with crowded filetrees and (still) too much jargon to process adequately. I was lost and overwhelmed, in the beginning, at the sheer amount of code to build out. Later, to learn that there are shortcuts to call (that we're SUPPOSED TO) on that would replace all those methods I was working out manually, was a sigh of relief. The work became a nice gift of a subtle understanding of how everything was really moving behind the scenes.
<br><br>
Following along the path of where the code flows, I am continually reminded of the code-famous 'Seperation of Concerns' guiding my mind's way for simplistic bundling of code.
Personally walking through the logical steps of what a visitor to my app would likely want to explore, helps me build a user experience that has purpose and direction. I build off of this stage by taking notes. A lot of notes.
<br><br>
As an enthusiast, I have amassed ridiculous piles of Rails notes, still scattering through notepads, text files, sketch pads, screenshots, notebooks, sticky notes, etc. As a coder, I'm still figuring out how to get my brain to figure itself out, and am always on the lookout for new ways to make sense of things. The beauty of how Rails allows us to program, is how convention over configuration is a constant. That cluttered filetree I complained about earlier, is actually an encyclopedic collection of abilities and skills, all returning data for us to manipulate and show off. 
<br><br>
I was able to mimic this collection-gathering by creating 'snippets.' I made note complilations of the smallest amount of code as possible that related to each other, to show how methods fire off of each other from one location to the next. I start off with an understandable path (folder location), underneath, writing in a bit of relevant code to where there is flow. 
<br><br>
My code snippets helped me collect examples of pathways and behaviors I have seen that help explain concepts and conventions. These notes are succinct and clear, their organization eliminating distractions from other bits of code. Comparing and contrasting implementations clarified the point of Rails and reinforced the intention for simplified code flow.
<br><br>

```
	MY NAVBAR CODE SNIPPETS EXAMPLE
--------------------------------------------
/HELPERS/APPLICATION_HELPER.RB/-------------
	def render_nav_bar
		render partial: 'layouts/nav_bar'
	end
--------------------------------------------
/VIEWS/LAYOUTS/APPLICATION.HTML.ERB/-------
	<div>
		<%= render_nav_bar %>
	</div>
--------------------------------------------	
/VIEWS/LAYOUTS/_NAV_BAR.HTML.ERB/----------
	<%= link_to("Hub", '/hub') %>
--------------------------------------------
```
<br>
Adopting this strategy allows me to plan out paths for data to move while building, later being able to revisit these clumps of code when dealing with errors.

