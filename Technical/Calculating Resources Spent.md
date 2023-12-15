[comment]: <> (Note: These could be hover tooltips when hovering over Build Time)

# Build Time Calculation
<sup><sup>(Author: Zeteo)</sup></sup>

- The time it takes to build something = Build Time Cost / Build Power applied
- If a unit has costs 2000 build time and the factory has 100 build power, it'll take 20 seconds to produce that unit
###### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2000 BT / 100 BP = 20 sec
- The factory can be assisted with a constructor, adding an additional 80 build power, which would produce the unit in 11.11 sec
###### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2000 BT / (100+80) BP = 11.11 sec
- Multiple constructors can assist the same construction, vastly improving how long it takes to build

<br></br>
# Calculating Metal or Energy Used/sec

- The Resources used/sec when building something = The Resource Cost / Build Time Cost * Build Power
- If a building costs 150 metal and 2800 build time, and the constructor building it has 80 build power, it'll take ~4.2m/sec until completed
###### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 150 (M cost) / 2800 (Build Time Cost) * 80 (Build Power) = ~4.285 metal/sec
