---
layout: post
title: "Third Week 6th May - 10th June"
date: 2016-05-30
---
### Summary ###
Finally decided to go with the change in mapping of Project Calendar Page request from enumMap to HashMap.This is done because a enumMap issending the just one projectId for every calendarType but we need to send all related project Ids.

### Work Done ###

* EnumMap is converted to HashMap.
* Successfully sent the all related project calendarType data to the caledarPresenter Class.
* Also the calendarPresenter Class Page load functions (Reload & Reloadevents) are changed to Integer mapping.
* Also tweaked orgUnit class according to changed conditions.
* Also improved the Mock-Up on capture screen and by the help of pencil tool.
### Pull Request ###

You can see the following work [here](https://github.com/sigmah-dev/sigmah/pull/27).

### Mock Up ###
![Improved Mock Up](https://13778736201386859235.googlegroups.com/attach/610605f2bfab7/untitled_page.png?part=0.1&view=1&vt=ANaJVrEkdhKmWuOtWUuG3ucmHIMusQg_bfA_1ulZhVvEpJeUMNcD9Sz4GJh7eFYtiSriFpWtfo-447kFJwnlSVr97oL2aMbBmLIjbX7Qf0leMUkY65gBZck)