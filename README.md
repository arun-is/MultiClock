# Table of Contents

[TOC]

# Introduction
This is a Chrome extension that shows multiple clocks in chrome new tabs. It is useful for remote workers and collaborating across timezones.

This README describes both the app and the design process during conception of the app. Likewise, this repository contains the app itself and documents generated during the design process.

Please read the LICENSE file in this repository before modifying or distributing this software. 

# The Problem
1. It is difficult to plan events across multiple timezones because it requires knowing how everyones' work days overlap.
2. When contacting a remote worker, knowing what time it is in their home requires remembering the time difference or checking using another tool.
3. Existing chrome extensions are ugly, hard to use or both. 
4. Apps and web services exist that solve this problem, but there is high friction (need to open an app or access a page) in starting them up.

# Goals & Requirements
1. App should be intuitive and usable.
2. App should be aesthetically pleasing.
3. Use search API for finding locations (don't limit to a predetermined list)
4. Online & offline support

# Existing Apps & Examples

This list is a limited list of existing apps and examples I have found during my research. Some examples were completely omitted for severely failing the stated goals above i.e. they are extremely ugly or are unusable.

Items in this list are organized like below

[link]() description *critique in italics*

##Chrome Extensions
1. [World Clocks](https://chrome.google.com/webstore/detail/world-clocks/innfmeekncjandlanpgdmmogkcimekgo) multiple clocks shown via icon and popover *current time, multiple clocks*
2. [World Clocks](https://chrome.google.com/webstore/detail/world-clocks/ajnbnekhpkkfaobjalnhdoofajkghidp) multiple clocks shown via icon and popover *current time, unneeded visual embellishments*
3. [World Clocks new tab page](https://chrome.google.com/webstore/detail/world-clocks-new-tab-page/opaffdnccgelcacfhbjigocjaigebbje) current time shown as large digital clock and smaller clocks shown for other timezones *current time, multiple clocks, confusing organization*

##Websites
1. [world time buddy](http://www.worldtimebuddy.com/) *unique timeline style, multiple times, provision for selecting time intervals, unneeded visual embellishments*

##Native Apps (Mac OS X)
1. [The Clock - The Best World Clock](https://itunes.apple.com/us/app/the-clock-the-best-world-clock/id488764545) menubar popover with calendar and list of places and clocks. Connects to Calendar app. *by default doesn't show current location in list, unintuitive method of adding locations (1. click gear icon. 2. click "Show Add World Clock" 3. Search for and add city*
2. [Clocks](https://itunes.apple.com/us/app/clocks/id414554506) Menubar popover with list of locations and times and a slider at the bottom for adjusting time *difficult to read*
3. [World Clock](https://itunes.apple.com/us/app/world-clock/id858446756) [widget](https://itunes.apple.com/app/world-clock-widget/id960527401) Map (with daylight terminus), analog clocks and slider for adjusting time *By far the best because of ease use (drag for changing time) and for aesthetics. widget allows quickly comparing times with slider. Difficult to understand, prominent colors (clocks turn white in dusk and then green in day. doesn't make sense). current time is shown at center at bottom with a timeline of hours, but the times are aligned with the center and not the map. clocks don't match up with locations on map*
4. [Living Earth - Desktop Weather & World Clock](https://itunes.apple.com/us/app/living-earth-desktop-weather/id539362919) menubar popover that shows realistic view of earth (with daylight terminus and weather), list of locations with times and weather. *devoid of unneeded embellishments. doesn't make setting up meetings any easier. focus on weather*
5. [Cities: Menu world clock](https://itunes.apple.com/us/app/cities-menu-world-clock/id933624359) Menubar popover with timeline of locations and times. *timeline layout is clutter when many cities are added. shows differences in days well. *
6. [Hour Lite](https://itunes.apple.com/us/app/hour-lite/id569089415) menubar popover with list of locations and times *unneeded visual embellishments*
7. [Time Zones](https://itunes.apple.com/us/app/time-zones/id448041594) menubar popover with list of locations and times *difficult to read analog clocks*
8. [World Time Zones - Plan Your Trip](https://itunes.apple.com/us/app/world-time-zones-plan-your/id1064366678) menubar popover with list of locations and weather information *too much information on screen with little hierarchy*
9. [Menubar World Clocks](https://itunes.apple.com/us/app/menubar-world-clocks/id827630907) menubar popover with list of locations *aesthetically minimal*aesthetically

##Mockups & Designs
1. [6th Week (Friday) - World Clock](https://dribbble.com/shots/2460483-6th-Week-Friday-World-Clock) mobile app with timeline + slider interface and list of locations and times *intuitive organization. doesn't translate well to desktop because of aspect ratio*

# Initial Sketches

This is a list of quick sketches and prototypes


