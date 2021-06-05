--- Berlin Prayer Times

it was unclear how prayer times were calculated in the many of the Berliner mosques. I used here prayer times code to reverse engineer how the prayer timesin berlin is calculated.

It turns out the following is done:
* coordinates for Berlin are 13.41 and 52.52 with elevation 34m
* MWL method is used, with Farj Angel =15 Degrees
* Angle Based method is used
* Maghrib time = sunset time + 4 minutes
* Isha time = magrib time + 4 minutes
