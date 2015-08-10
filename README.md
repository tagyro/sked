####SKED (code name)

#####Assumptions

1. There are a limited number of spots available (25)
2. There is a limited schedule available (8-18)
3. We want the maximum fill, within the spots/schedule
4. There are mainly 2 categories: **fixed** (aprox. 20) and **variable** (as much as possible); **fixed** have a somewhat stable schedule (x times per week, between y and z hours, every -other- week), **variable** have a more flexible schedule (adjustable by the organiser/attendee)

#####Schedule example

|Name|M|T|W|T|F|Odd|Even|  
|----|-|-|-|-|-|---|----|  
|John|8-12|8-12|-|-|14-18|X|-|  
|Mary|8-18|-|-|-|8-18|X|X|  
|Tom|8-18|8-18|8-18|8-18|8-18|-|X|  
|Jerry|10-16|9:30-14:30|8-17|-|-|X|-|  

In the above example, the app would automatically show the days with less attendees and offer to schedule the **variable** participants in those days/time slots.

Ideally, for UX reasons, when inserting attendees, there would also be a week/month view to show fill/time-slots/distribution (Monday in the above example would have a red-tint background, while Wednesday and Thursday would have a green/yellow-tint background)
