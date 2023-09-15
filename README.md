# Git Practice
  [Deferred Lighting](https://catlikecoding.com/unity/tutorials/rendering/part-15/)
    
---
I have an interest in shaders and recently I wanted to explore what is known as
a deferred lighting model. Having work with shaders for several months
now I found this tutorial particularly interesting because of the things I saw as
limitations of forward lighting which is the more standard lighting model. Namely
the inability to use have a large number of lights. I found deferred lighting
interesting in seeing how it reversed many of the typical calculations associated with
shaders. Instead of outputting a color for each part of an object, instead it outputs a
bunch of variables which get put in one big image effect at the end. I think that it
opened a bunch of new possibilities to what I thought was possible with shaders, before
I would use color as substitute channels, but knowing that there is an in-built process
for different kinds of outputs aside from color makes me feel like there are far more
interesting things that can be done with shaders.