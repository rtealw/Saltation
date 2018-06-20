## WHAT IS IT?

Saltation describes the movement of sand across an uneven surface in a turbulent flow of air. This saltation project models how sand grains interact with wind at a micro-scale.

## HOW IT WORKS

All sand grains naturally settle downward so that all their lower neighbor patches are occupied by other sand grains.

The one rule for the saltation behavior is that wind displaces sand with erosion-probability and specified velocities from a windward surface. If the sand lands on a windward grain, then that windward grain is displaced. However, if the sand lands on a a non-windward grain, both grains settle.

## HOW TO USE IT

Set-up the model to either a uniformly flat surface or to a randomly configured sand pile (thanks to Prof Dickerson for this code).

From there, you can play with the x, y, and z velocities to attempt to form small ripples in the sand. You can also control the probability that any given windward surface grain is displaced.

For visualization, you can flip a color switch to watch the surface and displaced sand move over time.

## THINGS TO NOTICE

Notice how the magnitude of the velocities and erosion-probability influence the speed at which ripples form.

Set the velocity to only velocity in the x or y direction. Even though there is no interaction between parallel lines of sand, notice that the sand still forms into piles.

## THINGS TO TRY

Find the minimum velocities and erosion-probability at which sand ripples form. Once they form, determine whether ripples stay in place or require a certain velocity to maintain their form.

Once you have ripples going in one direction, pause the model and negate the velocities. What changes in the shape of the ripples?

Once you have ripples going in one direction, pause the model and set the velocities to be perpendicular to what they just were. What changes in the shape of the ripples? How easily do new ripples form?

Play with the z velocity and erosion-probability to try to make as many ripples as possible (four or more) or as few as possible (just one).

## EXTENDING THE MODEL

The model is limited by the computational difficulties of Netlogo 3D. An extension would be to make the code more efficient so we could visualize more sand grains.

## CREDITS AND REFERENCES

I originally completed this model for the final project of CS 390: Spatial Agent Based Modeling at Middlebury College in Spring 2018. Thanks to Professor Dickerson for the code to build sand piles and a great semester of Netlogo modeling!
