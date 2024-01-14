[BP]: https://github.com/Zete0/Mentor-Guides/blob/main/Starter/Economy%20Fundementals.md#build-power

# Economy Fundementals 
<sup><sup>(Author: Zeteo)</sup></sup>

## Everything Costs Metal(M) / Energy(E) / Build Time(BT)

#### Metal *(White cost)*
- Must be built on Metal Nodes
- Not all metal nodes are created equally
- Different maps have a different amount of nodes
- Metal is hardest to obtain because it requires defending a larger territory
- Metal can be stored easily, so gaining/losing M is slower *(the M bar goes up/down slowly)*
#### Energy *(yellow cost)*
- Most energy structures can be built anywhere
- There are many different ways to get energy - some ways are more efficient on different maps
- Energy isn't as easily stored, so gaining/losing E is faster *(the E bar goes up/down quickly)*
#### Build Time *(green cost)*
- The higher the build time, the longer the building/unit takes to be made
- Constructors can assist constructing buildings from other constructors or assist factories producing units
- The Actual time it takes to build something depends on how much [build power][bp] is applied to it, the more build power applied, the faster the construction, but the more resources that are used/second

<br></br>
## Build Power
- The Build power is essentially the amount of work a constructor/factory/rez bot adds to a project
- Build power is considered a third resource
- Each construction unit has a build power
- Adding more workers to a project speeds up the pace the project gets done by applying more resources/second
- Different constructors/factories have different amount of build power
- The time it takes to build something = Build Time Cost / Build Power applied

### Assisting a Construction

**All Construction type units can assist other constructors with building or factories producing units**

- To assist a construction, select a constructor (or the commander) and issue a repair order on the unit / building being constructed
	- This can easily be done with a simple RMB click
	- The assistant will idle after finishing the construction

- To assist a constructor/factory itself, select the constructor and issue a guard order on the unit / building being constructed
	- This can also be done with a simple RMB click
	- The assistant will assist the construction/factory until told not to, including following around another constructor
 	- If orders are queued up after a guard order, the order will automatically switch to assisting the current project and will continue with the queued orders afterwards

### Construction Turrets

- Construction turrets cannot build anything themselves, but will automatically do these things within it's build radius:
  	- Assist nearby constructing buildings/units
	- Repair nearby friendly units
	- Reclaim nearby neutral objects
- Construction turrets are one of the more efficient ways to add build power to their vicinity

#### [Click here for a deeper dive on how long it takes to build something or resources spent/sec](https://github.com/Zete0/Guides/blob/main/Technical/Calculating%20Resources%20Spent.md)

*This [widget](https://discord.com/channels/549281623154229250/1158860869980139550) (downloaded from the discord) can also be quite useful, it calculates the build power cost per second. Information on installing widgets can be found [here](https://github.com/Zete0/Mentor-Guides/blob/main/Customization/Using%20Widgets.md)*

<br></br><br></br>
## Balancing Economy is First Step to Victory

### Balancing your economy means having enough metal, energy and build power to efficiently construct buildings and units

**When an economy is unbalanced, construction slows down to the pace of the weakest link**

- When any resource is low, __all__ production is slowed and limited by the low resource
- Balancing your economy well means fixing any and all resource issues as soon as possible to effectively gain/spend them, which ultimately allows you to build up more efficiently
- In BAR, resource income is highly dependant on the map and what you able to control, so there is always a bit of management with resources. There is no fixed "get this many of this at this time", because it fluxuates

- Here are some examples:

	Low Energy Example:
	> - (Insert picture here)
	> - In this example, our Energy production doesn't meet demand. The amount of energy available is split between all the different constructors/factories.
	> - *It is especially important to have enough energy, energy is used for more than just construction! It is also used for extracting metal, some weapons, stockpiling missiles and dgun.*

	Low Metal Example:
	> - (Insert picture here)
	> - In this example, our Metal production doesn't meet demand. The amount of metal available is split between all the different constructors/factories.

	Low Build Power Example:
	> - (Insert picture here)
	> - In this example, Metal is starting to increase, which means we could utilize more constructors to assist
	> - To use them more efficiently, we need more constructors working on projects or assisting existing projects

	Balanced Economy Example:
	> - (Insert picture here)
	> - In this example, we're spending our metal well, and we have enough energy for our needs
	> - Also note, our +/- Metal and +/- Energy are not drastically out of proportion

**Note:** *Different buildings/units cost a different amount of Resources/Time, so different projects will drain resources faster/slower* <br>
**Note:** *Adding more Build power speeds up the building process, but only if you have enough resources* 

### Resource Gain and Construction Priority

- In BAR, resources are first gained, then spent
- Each constructor/factory has a high or low priority setting
- Units set to high priority use the resources first, then if there are resources still available, then low priority units use what they can
- The -Amount shown next to each resource reflects the "requested resources" of all high priority constructor/factory and does not include low priority usage
- (show example image and high/low priority button here)
  
	High Build Power Example:
	> - (Insert picture here)
	> - In this example, we have an excess of build power for our resources
	> - This basically means we over spent on build power and some of it is not being utilized
	> - This isn't as easily diagnosed since low priority doesn't show up as a -amount/sec
	> - This is a better issue to have than too little build power
- Default settings for different constructor/factory can be adjusted in the settings
- (show settings image here)





### [Click here for a Guide to Basic Openers](https://github.com/Zete0/Mentor-Guides/blob/main/Basics/1%20Common%20Openers.md)





