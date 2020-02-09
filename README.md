I am developing a mobile game where you can trigger buildings to be built on certain areas. During the buildprocess I mark the area that will be used for building with a smoke effect:
Post image

So at times it is possible that a large area of the screen is covered with this effect. While this works pretty well on current phones it is often too much to handle on phones that are a few years older. On android you get low framerates on those and on iOS it can decrease the battery quite fast on phones older than iPhone 8. I was told from a nice godot dev that the cause of my problems is propbably my quads with semi transparent textures overlapping, which makes them mess with the occlusion. I tried finding other ways to create an effect that looks like smoke, but wasn't successfull.

Can someone out there help me or give me some tips how I could create a fitting smoke effect that works better on mobile?
