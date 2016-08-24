---
layout: post
title: "GSoc Final Report"
date: 2016-08-20
---

## Summary

My major work in Google Summer of Code was around Calendar component of the project and organisation tabs.The work done by me is in many phases and major one was to integrate the different linked projects to the main project.
The changes are further divided into smaller parts.

## Repo Link

1 You can see the following work [here](https://github.com/sigmah-dev/sigmah/pull/27).


## Work in Parts

1 Integration of different calendartypes of every related project into the main project. [Check Commit here](https://github.com/sigmah-dev/sigmah/pull/27/commits/cce2bebb3099108573a6eac302c66c285bbf1d4a)
    
    a. EnumMap is converted to HashMap.

    b. Successfully sent the all related project calendarType data to the caledarPresenter Class.

    c. Also the calendarPresenter Class Page load functions (Reload & Reloadevents) are changed to Integer mapping.

    d. Also tweaked orgUnit class according to changed conditions.

     Screeshot ![Integrated Project Calendar](https://goo.gl/photos/jZcpCdYFGCdC1tPj8)

2 Organisational calendar was implemented with its other related organisations.[Check Commit here](https://github.com/sigmah-dev/sigmah/pull/27/commits/96f6a43b9e2caf03bb229a78b9652977e0eccb5a)

    a. Integrated the OrgUnit calendars.

    b. changed the setStyle and result variable to suit according to orgunit as well as ProjectUnit.

        Screeshot ![Integrated Organisational Calendar](https://goo.gl/photos/obHCQcEq5WoVuMUUA)

3 Project code was alligned with every calendar event so that its easy to identify which event is of which project.[Check Commit here](https://github.com/sigmah-dev/sigmah/pull/27/commits/e251439ce30be3226f7539e98b18f6f906b15326)
    
    a. Project code was sent dynamically from calendarType class to calendar presenter.

    b. Rather than imposing projectcode to every event in presenter class it is sent to every single event handler and then its implemented there.

    c. Same thing was proposed for organisation but not implemented.

        Screeshot ![Project code](https://goo.gl/photos/YhFkbLroPoCvKfKGA)

4 Little bit tweaking in panel and changing of related project's color in the main calendar panel so that they can be identified easily.[Check Commit here](https://github.com/sigmah-dev/sigmah/pull/27/commits/95e20d56c39a6a4bd4272ccfffe239fef560bd39)

    a. Checkboxes are moved to right and colorboxes are moved to left so that its easy to understand which color belongs to which calendatype.

    b. New colors for related projects in the main panel are introduced which are slightly different from main project calendatypes.SO that we know that which calendar event is main project calendar.

    c. Project code is implemented in offline condition too.

5 Little bit tweaking.[Check Commit here](https://github.com/sigmah-dev/sigmah/pull/27/commits/5afa76dcc9c22babe304924cc26763cef64ca198)

    Screeshot ![Css color edited](https://goo.gl/photos/oz2CgFuDsRKsQcgR8)
## Other Work done

 1 [Change of format](https://github.com/sigmah-dev/sigmah/pull/20) .

 2 [Convert importation framework "successful update" info popup into notification Description](https://github.com/sigmah-dev/sigmah/pull/17)

 3 [Add year in Indicators export monthly table ](https://github.com/sigmah-dev/sigmah/pull/16)

 4 [Indicators values not in order in long period project exports](https://github.com/sigmah-dev/sigmah/pull/15) 