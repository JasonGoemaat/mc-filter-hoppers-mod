# Filter Hoppers Mod

This is the first mod I'm working on, following these tutorials partly: https://www.youtube.com/watch?v=7Kg-UvY2DKA&list=PLKGarocXCE1EMYzuBUTYjHnFeBrRFbesk&index=2

The goal is to produce a duplicate of a hopper, but with two inventories.  I am
not 100% this is possible, but a Forge does it with single blocks in 3 zones.
One is the output item which normally is sucked by hoppers under the forge.
Another is the fuel slot which is filled from the back only, and can
also be sucked by hoppers below but only for empty lava buckets I think.
The third is the source item to smelt which can be fed by hoppers from the
top.   

My goal is to have an inventory section that can contain items and not be
interacted with by hoppers, either pushing to or pulling from.   Here you will
place items that you want the hopper to work with, other items will be ignored.
The second section will be the actual inventory of the hopper.   Items that match
one of the items in the filter list will be pulled from above like a normal
hopper.  Neither of these will be able to be pushed into by other blocks
like hoppers or even another Filter Hopper.

I may need to allow pushing to create chains, or else just have a standard
hopper chain above and this should be able to pull any items.


# Misc. Notes:

Resource Distribution: https://staticg.sportskeeda.com/editor/2023/06/144bd-16868397044537-1920.jpg