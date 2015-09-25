---
layout: post
title: Making Tough Project Decisions in Pittsburgh
tags: [Pittsburgh]
preface: Triaging and scoping are difficult aspects of developing software with government partners. This post, which originally appeared on the <a href="http://www.codeforamerica.org/blog/2015/04/30/making-tough-project-decisions-in-pittsburgh/">Code for America blog</a> illustrates how we thought about cutting certain products and focusing on others.
---
![Ben hears from a Fire purchaser](/img/ben_fire.jpg)
_My teammate Ben hears from a purchaser in the Pittsburgh Fire Bureau._

After a month of building prototypes and soliciting feedback from our city partners in Pittsburgh, we’ve started to narrow the scope of what we want to build to help change the outdated ways the city buys everything from software to paperclips. Explicitly choosing not just what to work on, but what to stop actively developing is a difficult part of the user-centered design process. It’s also one of the reasons Code for America encourages fellowship teams to start building early, to get testable prototypes in front of users as soon as possible so that the hard work of scoping can happen sooner rather than later.

At the end of [Ben’s post](http://www.codeforamerica.org/blog/2015/04/09/3-development-tips-from-team-pittsburgh-2/) outlining the principles behind how we build, he listed five things we’ve built since arriving in January. Since that post was written, we went back to Pittsburgh and put some of those wireframes and early-stage applications in front of city staff, and the feedback was overwhelmingly positive. While this is great news, it also means we had to come up with another filter to help us make some tough decisions.

### Breadth, Depth, & Lift

To guide our thinking, we adapted a set of metrics we learned from the [Code for America health team](http://www.codeforamerica.org/our-work/focus-areas/health/):

* _Breadth_: how many people are impacted by a given problem?
* _Depth_: how deeply is the problem is felt?
* _Lift_: how technically or politically difficult is the fix?

Thinking in these terms helps us prioritize, particularly given the relatively narrow window we have in a fellowship year. Inverting _lift_ into a positive metric, we were able to start thinking in terms of _feasibility_, looking to the likelihood of a successful deployment given both the technical demands as well as the surrounding organizational context. We then took our four major projects (a [marketing/outreach site](http://www.buildpgh.com/beacon), [Wexplorer](http://www.buildpgh.com/scout), [Template Maker](https://github.com/codeforamerica/template-maker), and the [Pittsburgh Procurement Explorer](http://www.buildpgh.com/sherpa)) and gave them a high, medium, or low value for each category:

![Project Matrix](/img/project_matrix.png)
_Our decision-making metrics and projects, in one chart._

With this line of thinking, we opened up a conversation about Template Maker.

### Rethinking Our Focus on Documents

After our initial conversations in February, we saw a huge need for common "templating" for all kinds of procurement documents. So we built a prototype:

![Template Maker](/img/template_maker.gif)
_The functionality of Template Maker in action._

With Template Maker, our city partners in the legal department could create a central database of internal procurement documents, which had the potential to transform the entire process. Standardized document templates would become forms, which could remove a lot of the confusion departments face while drafting requests for proposals (RFP), resulting in better documents and less legal back and forth during the final contracting process.

But after looking at our projects using our decision-making categories, __we decided to stop actively developing Template Maker__. Here’s why:

The lift required to bring Template Maker across the finish line is such that we would have to dedicate a majority if not 100 percent of our team’s focus to this single product. Making a [WYSIWYG](http://en.wikipedia.org/wiki/WYSIWYG) editor for procurement documents that doesn’t just work, but is also enjoyable to use is no small feat and ends up replicating much of the same features many of our users already have access to in Microsoft Word or Google Docs. Template Maker also only addresses documents, just one part of the extremely lengthy and involved procurement process. In short, Template Maker would be a large investment for a relatively narrow outcome. By moving our focus off of documents, we can focus on the entire process.

### Next Directions

We think we can have a larger impact for a lower lift by focusing more of our technical efforts in and around city purchasing. Here’s where we’re going:

* Expand Wexplorer into a searchable, categorizable, and regularly updated library of current contracts that department purchasers can use as part of their daily workflow.
* Build a [central Office of Management & Budget (OMB) site](http://www.buildpgh.com/beacon) for marketing upcoming contracting opportunities using a combination of data from Wexplorer as well as department-generated content. A [current site for professional service opportunities exists](http://pittsburghpa.gov/omb/contract-bids), but we think having commodity opportunities more actively marketed would deliver value for city departments.
* Implement a data update workflow that not only helps OMB with shepherding contracts through the extremely complex purchasing process, but also keeps city apps up to date.
* Move away from document-based solutions and explore alternative ways to guide city departments through the process.
* Work with the legal team to help craft templates in tools city departments are already using.

We are really excited to see where this readjustment of focus takes us. Stay tuned.
