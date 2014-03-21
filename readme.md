# Homework assignment n.1
**Computational Visual Design Lab ([CVDLab](https://github.com/cvdlab))**  
**"Roma Tre" University, Rome, Italy**  
**Computational Graphics 2013**

## Introduction 

The goal of this homework is to assess the student ability to mock-up a significant 3D construction, by:

1. selecting from the history of architecture a single remarkable building,
2. finding on the web adeguate visual descriptions,
3. choosing a suitable part decomposition and assembly using
4. the modelling primitives learned in the first weeks of study.


## Notes

Let start your search from the wikipedia article [*History of architecture*](http://en.wikipedia.org/wiki/History_of_architecture). Search for a building that:

1. is both interesting and well documented on the web, 
2. may be easily decomposed/assembled into/from simpler parts that are 
3. easy to model using the PLASM geometric primitives: `STRUCT`, `QUOTE`, `MAP`, `JOIN`, `Q`, `T`, `S`, `R`, possibly into parametric Python expressions and functions.

First spend time to fully understand the structure of the building,   
using drawings, photographic documentation and other documents found on the web.
   
Only later start the modeling work, **item by item** (exercise by exercise). 

The programming assignment must be produced in Python language,   
using the [`Pyplasm`](https://github.com/plasm-language/pyplasm) module for Python.


## Caveat

The homework is **strictly personal**, and must be worked out by a single student. Violations will be persecuted through very low grades.  We expect that in case of collision of choice (highly unlikely), **very different** model decompositions and modelling results will be submitted.


# Exercises

## Exercise 0  (8/30 points)

Produce an `index.html` HTML page with 

1.  Name of the building; 
2.  Your name and surname;
3.  University ID (matricola);

and with:

* all the links to the web documentation used for your work;
* a short description of the work done; 
* some interesting images of the work;
* links to `exercise1.py`, `exercise2.py`, etc.

## Exercise 1   (8/30 points)

Generate a 2D simplified model of the (main) building floors, separating in different colors the various parts of the building, corresponding to sub-models separately generated; assemble them into a single 2.5D (google the term) `two_and_half_model`;

Use names like `floor0`, `floor1`, `floor2`,  etc., for the 2D horizontal partitions, and add them to the `STRUCT` of a 2.5D `building` model, where each part will be assembled.

## Exercise 2   (8/30 points)

Define, with names `north`, `south`, `east`, and `west`, at least 4 models 2D of vertical enclosures (including the hollows), and add them (by embedding in the appropriate vertical planes) to the `STRUCT` of the 2.5D `two_and_half_model` producing a single `mock_up_3D` assembly.

## Exercise 3   (8/30 points)

Using the (or a very similar) assembly structure of the `mock_up_3D`, produce a `solid_model_3D` of your building.

## Exercise 4 (optional)   (4/30 points)

Define and insert at least one `stair` within either the `mock_up_3D` or the `solid_model_3D` model.


# Assignment delivery

For the exercise 0 you must produce a file named `index.html`.  
For each other exercise you must produce a corresponding file `exercise1.py`, `exercise2.py`, etc. 
All the .py file must be enclosed within a directory `python`.   
Such directories must be contained in a directory entitled `2014-03-21`,   
pushed into the personal GitHub repository of the student: [https://github.com/cvdlab-cg/xxxxxx](https://github.com/cvdlab-cg/)   
where `xxxxxx` is the student ID  (matricola). 

```
─── xxxxxx
    └── 2014-03-21
        ├── images
        │   ├── fig01.png
        │   ├── fig02.png
        │   └── etc.
        ├── index.html
        └── python
            ├── exercise1.py
            ├── exercise2.py
            ├── exercise3.py
            └── exercise4.py
```

The delivery is strictly required within 24 hours from the publication of the homework.

# Tips

#### Commit and push as frequently as you can
