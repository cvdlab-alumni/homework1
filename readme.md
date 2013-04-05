# Homework assignment n.1
**Computational Visual Design Lab ([CVDLab](https://github.com/cvdlab))**  
**"Roma Tre" University, Rome, Italy**  
**Computational Graphics 2013**  

# Introduction 

(From [http://www.designventurer.com/prefab](http://www.designventurer.com/prefab/?p=420)):  
  The Maison Citrohan  is one of the basic themes of Le Corbusier's interest in industrialization and new forms of housing, from which was expected to emerge a logical and economic house for all. This prototype reflects in its name the clear purpose that guided the design. Le Corbusier called it **Maison Citrohan**  and also referred to it as *"the machine of living"*, in order to address his main concerns in relation to the house that could be built in series, such as cars. Prefabrication was even suggested, to reduce costs or  minimize the equipment necessary for the building of houses. In short, he was imitating the concept of assembly line manufacturing of cars, ships and planes.

# Notes

Several documentation is stored in this [archive](../citrohan.zip).   
Useful links are [here](http://www.youtube.com/watch?v=bsmWdSI28RY) and [here](http://www.youtube.com/watch?feature=player_detailpage&v=m4QwVi5U5is).

First spend time to fully understand the structure of the building,   
using the given drawings, photographic documentation and movies.   
Only later start the modeling work, **item by item** (exercise by exercise). 

The programming assignment must be produced in Python and JavaScript languages,   
using the [`Plasm.js`](http://cvdlab.github.com/plasm.js/) development environment and the [`Pyplasm`](https://github.com/plasm-language/pyplasm) module for Python.


# Exercises

## Exercise 1

Define, with names `pillars0`, `pillars1`, `pillars2`, and `pillars3`, the models of pillars of the 4 house floors, and put them into the `STRUCT` of an initial `building` model.

## Exercise 2

Define plan by plan, with names `floor0`, `floor1`, `floor2`,  `floor3`, and `floor4`, the 5 models of horizontal partitions, and add them to the `STRUCT` of the `building` model.

## Exercise 3

Define, with names `north`, `south`, `east`, and `west`, the 4 models of vertical enclosures (including the hollows), and add them to the `STRUCT` of the `building` model.

## Exercise 4

Define and color (`BLACK`) the models of (some) windows, and instance them within the `building` model.

# Assignment delivery

For each exercise you must produce a corresponding file `exercise1.js`, `exercise1.py`, etc.  
All the .py file must be enclosed within a directory `python`.   
All the .js file must be enclosed within a directory `javascript`.   
Such directories must be contained in a directory entitled `2013-04-05`,   
pushed into the personal GitHub repository of the student: [https://github.com/cvdlab-cg/xxxxxx](https://github.com/cvdlab-cg/)   
where `xxxxxx` is the student ID  (matricola). 

```
+- xxxxxx
| 
+- 2013-04-05
  |
  +- javascript
  | |
  | +- exercise1.js
  | +- exercise2.js
  | +- exercise3.js
  | +- exercise4.js
  |
  +- python
    |
    +- exercise1.py
    +- exercise2.py
    +- exercise3.py
    +- exercise4.py
```

The delivery is strictly required within 24 hours from the publication of the homework.

# Tips

#### Commit and push as frequently as you can
