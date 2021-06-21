# Predictionshade

same configuration as the other prediction software but  added bit for shading of solar  panel.
in panelconf  there are 3 shading arrarys.

here an test example from my yard 
I have tree line on my east side and clump tree to the south
: so basically from 4am to
8:30 bush line if the sun is <= 7 degrees a 100% of my panel is covered and when over 10 degrees the panels is fully exposed

the clump of trees from 10am to 11 am it covers a maximum of 50% of my panel when <= 11 degrees and fully exposed when the sun is higher then 22

example  of an array 
UPPER=(0 0 0 0 0 0 0 0 10 10 10 10 10 10 10 10 10 10 0 0 22 22 0 0 3 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0)    ### 1/2 hr blocks  3,2,1 depicts noon location

LOWER=(0 0 0 0 0 0 0 0 7 7 7 7 7 7 7 7 7 7 0 0 11 11 0 0 2 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0)

PERCENT=(0 0 0 0 0 0 0 100 100 100 100 100 100 100 100 100 100 100 0 0 50 50 0 0 1 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0)

there a  a script called alt. simply run that when the shadow is at it maxuim and minimum on your panel and enter that into the array
