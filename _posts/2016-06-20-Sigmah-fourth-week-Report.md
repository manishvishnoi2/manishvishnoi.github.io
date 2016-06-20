---
layout: post
title: "Fourth Week 13rd May - 18th May"
date: 2016-06-20
---

##Summary
Fourth week was majorly spent in changing orgUnit calendar.Mapping of calendar was already changed last week.So work was to integrate child orgUnits calendars to the parent orgunit calendar.

##Work Done

1 Finally improved the mockup to its best by using example of test project.

2 Integrated the OrgUnit calendars.

3 Looked into the Calendarwrapper class and learned about how grid works.

4 Also looked at different ways to implement project code into the calendar widget.

##Problems Faced and Future Work

The main problem faced in orgUnit calendar integration was that children project were stored in a Set.So i have to use a iterator which generally has no GetId function defined.So i used the next function with a for loop which has hasNext(boolean) function as a condition.Which worked like a charm.

In future, i will look into the the tree rendering method for left panel to divide different projects.Also for calenar widget as i went through and noticed that the project inegration is not done into calendar,so i will have to find a workaround to provide projectId to the calendar.

Most of the work will be done by the next week.Then we will move to the custom range calendar.Whose mockup will be provided by this week.