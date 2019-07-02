---
title: The Potatoes Project
---

![The Potatoes Project]({{ site.github.url }}/assets/img/work/proj-2/img1.jpg)

A Java/Python like Language that implements "Double Trouble DSL" from The Units 
Project.

This language has dynamic definition of types, which means that the keywords
for the type declarations are defined by the user, using the Double Trouble DSL, 
and are generated differently for each project.

The language can also handle transitional types, which are non defined types 
created during calculations. For example, if the only defined type is "meter", 
then

```
meter m = (meter) 2;
meter m2 = (m * m) / m;
```

creates the type area (or meter squared) during the 
calculations. This is also handled when printing

```
println("The result is: " + (m * m));
```

where the output will be

```
The result is: 4 m^2
```

even though the area type was not defined.

**This project is an experimental concept to showcase the new possibilities in type 
definition for new languages. It's a work in progress for exploring the new 
language design challenges of the concept.**

<a href="https://github.com/LuisPedroMoura/The_Potatoes_Project" class="btn btn-primary" role="button">Check this Project on GitHub!</a>

