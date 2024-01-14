[comment]: <> (Note: These could be hover tooltips when hovering over Build Time)

# The Flanking Mechanic
<sup><sup>(Author: Zeteo)</sup></sup>

Essentially, when a unit is hit, the direction of the hit becomes the frontal flank of the
 unit, where it'll receive 100% damage. If it's then hit from the back, it'll receive 200% damage.

## Flanking Indicators

- BAR has a toggle setting that will display the flanking information on a unit after it receives damage.

![Options - Flanking Direction Indicator](https://github.com/Zete0/Mentor-Guides/assets/47950648/4461362d-06b3-4c7f-b169-cb3692564c31)


### Forward Indicator
- When a unit is hit for the first time in a bit, it recieves a 'Forward' direction, indicated by a pointer towards the attacker.
- This indicates the Frontal direction the unit, where it will receive 100% damage.

![Flanking - Front Indicator](https://github.com/Zete0/Mentor-Guides/assets/47950648/f4d7fe3c-e81c-4deb-aa03-935adcbf7056)

### Back Indicator
- There is also a 'Back' direction indicator, represented by this red partial circle.
- This indicates the full flank direction, where the unit will receive 200% damage.

![Flanking - Back Indicator](https://github.com/Zete0/Mentor-Guides/assets/47950648/062e8d46-2366-458e-8271-3796541794ce)

### Hit From the Side
- When a unit is hit from the side, the flanking damage modifier depepends on the angle. If hit from 90° from the flank, it'll receive 150% damage.

![Flanking - Side](https://github.com/Zete0/Mentor-Guides/assets/47950648/c4f96ee2-094a-4626-a2a6-e822b079e4b2)

## How it Works
- When a unit gets hit, it receives a flank direction if it doesn't already have one, towards the direction of the hit.
- Each hit after the first recieves bonus damage, the closer it is to the back, the more bonus damage there is *(200% if hit from directly behind, where the red bar is)*.
- The flank direction then adjusts and moves towards the new hit - the amount it moves depends on how long it's been since the last hit.

https://github.com/Zete0/Mentor-Guides/assets/47950648/b1aa43bb-d87a-418f-94d7-f8fe427cfe2f

*Here, the centurion is hit by the thug first, placing the indicator towards the thug, then, rapidly hit by a grunt in the back. The grunt is dealing bonus damage and the indicator slowly moves towards the grunt. Since it's attacking quickly, it moves slowly. As it moves towards the grunt, the grunt's attack recieves less of a bonus while the thug's attack bonus increases. The grunt then moves away and the thug, with it's slower attack, moves the indicator in big chunks each time it's shot lands*.

### 3D Flanking Bonus
- The display for the flanking directions is represented in 2D, but the actual direction is 3 dimention al, so a unit's frontal flanking direction can be pointed towards the sky if that unit takes damage from above.

### What this Means for Gameplay

- Moving in ways that prevent your opponent from surrounding you is important
- Running around units can increase damage output and kill that unit quicker
- Hiting with a lesser unit in one direction before a big unit hits in a second will increase the damage of the big unit significantly

[comment]: <> (I also want to insert a video here to demonstrate the differences)




