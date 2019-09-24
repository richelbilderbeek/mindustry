# mindustry

My mindustry notes.

## Speedruns

Not proper speedruns, just trying to be fast

Level     |Download                                                            |YouTube                             |Time
----------|--------------------------------------------------------------------|------------------------------------|-----
Overgrowth|[here](http://richelbilderbeek.nl/mindustry_overgrowth_20190924.ogv)|[here](https://youtu.be/NpBBGXgzm60)|22:13

## High APM

In many RTS games, higher Actions-per-Minute rates increase your chance of
winning.

Not in Mindustry:

 * Press space to pause the game
 * Now you can luisurely prepare and plan what you want to build: the
   build tab still works.

## Beginner build order

 * The basic rule: Follow the factories starting from the top-left and going right 
 * If a resource is needed, you do not mine yet, mine that one 

The resource you want to have more of is coal. Use water or oil to arrive 
at producing this.

## Separating lines is a good idea

Separating is a good idea for multiple reasons:

 * If you have mined 9k of that resource, your Core will not accept it anymore
   and the flow of resources will halt. If you've put all your resources on
   one big conveyor belt, the complete flow will stop
 * You can branch off from any flow to deliver those resources elsewhere,
   without clogging the conveyor belts

## Maintain an efficient flow of resources

If you are mining more of a resource then fits on one conveyor belt line, add
a second conveyor belt line. In the late game, use a faster conveyor belt
from the point where two inflows converge towards the final stretch towards
to Core.

If a factory has two inputs, and one input is clogged up, increase inflow of
the other product.

## Understand the special conveyor blocks

 * The junction is essential in keeping lines seperate
 * The sorter is great at unclogging a line: make it sort on the undesired
   product, let a conveyor belt with that product branch of. In the end,
   remove that conveyor belt
 * The distributor allows to keep a flow even when one line is clogged up.
   This is unlike a splitter that stops when one line is clogged up

## Mining efficieny does not increase with more conveyor belts

Connecting a drill to one or multiple squares of conveyor belt: it will
always produce the same amount of resources.

## Mech factories are only useful in Core battles

You may expect your mechs to go to the landing zone, but they do not. 

## How to beat Survive mission

Trick is to surround the landing zone at its edge with cannons.


Do the following build order:



 * Connect a first group of copper drills to your base. Build one drill, connect
   it. Repeat until out of copper
 * Connect a first group of lead drills to your base. Build one drill, connect
   it. Repeat until out of copper
 * Per landing zone path, build a copper drill and get a conveyor belt
   going towards the edge of that path. You do not have the resources
   to do more yet. It does allow to already gather some copper on the
   conveyor belts
 * Build all copper drills in the area where you gather your first copper.
   Build one drill, connect it. Repeat until all drills are connected: you
   will need that copper income
 * Build all lead drills in the area where you gather your first lead.
   Build one drill, connect it. Repeat until all drills are connected. 
   Repeat until out of copper
 * Continue working in the landing zone: make the conveyor belts reach
   a point close to the edge. Build one Duo at the end of the belt. Add
   one copper drill per path (so it can fill up)
 * In your base, connect a first group of coal to a Graphite Press for your 
   first graphite. Put a drill on the complete coal section.
 * In the landing zone, add the first Small Copper walls in front of your Duo
 * Put a Distributor directly on the conveyor belt to the Duo. 
   Add another Duo
 * Finish a first part of the Small Copper Wall. This should hold the first
   wave of enemies

## How to beat Core battles

The AI does not (re)build structures: each time you destroy something, 
it is lost forever.

 * Your role: do surgical strikes: destroy convey belts that supply 
   resourses, destroy power nodes, destroy turrets.
 * Do not attack the Core directly. Facilitate your mechs to do so by helping
   destroy the surrounding defense. 
 * Team up with your mechs to carve out a path: build copper walls to protect
   them and yourself. 
 * You can take out a Duo from far range
 * You cannot take out a Scatter without building walls of copper between you
   and the cannon
 * Be aware: cannons need ammo, so after after cutting supply, it will become
   harmless. Do not waste time on these cannons anymore: your mechs may
   shoot at these while passing by


## How to beat specific levels

### Desolate Rift

A big level, that's why you cannot zoom out on the minimap (yet?).

There is one, but wide, landing zone at the north. The enemies 
are very powerful, with bosses appearing every three or so waves. 
Also, the enemy forces consist of mostly flyers, that can fly over a single
line of cannons.

To counter this:

 * Create a stream of copper from one copper field towards you base
 * Create a stream of lead from one lead field towards you base
 * Create a second stream of copper from one copper field towards you base
 * Create streams of copper to the landing zone for tens of Duo's.
   This is the start to hold of the formidable ground forces
 * Create streams of scrap (lead will be too valuable) 
   to the landing zone for many Scatters behind the first lines. The enemy is
   strong enough to be able to fly over. In the end, you may be using the
   entire area from the landing point in the north to the first choke point
   in the south
 * Build up tech: graphite, silicon, metaglass, etc. You will need Thorium
   walls to hold off the enemy
 * Build thermal generators for electrical power. In this level, electrical
   power is abundant. Use coal for better purposes
 * Build up your cannons to a higher level: many many Duo's, Scatters and
   Arcs are not enough to hold the sixth wave. Replace Arcs by Lancers,
   as power is plentiful, but they cannot hold of air forces.





### How to create the dependency graph from the `.dot` file?

```
dot -Tps dependencies.dot -o dependencies.ps
convert dependencies.ps dependencies.png
```
