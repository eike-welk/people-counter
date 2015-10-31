###############################################################################
people-counter
###############################################################################

Count people or objects in images.

This program is based on the paper *Learning To Count Objects in Images* by Lempitsky and Zisserman: The program does not identify individual objects, but computes a density or probability that an object is present for each pixel of the image. This density is then integrated over the image to compute the number of objects. 

The resulting object count is fairly accurate. The method is especially useful when objects overlap.

    http://www.robots.ox.ac.uk/~vgg/research/counting/

