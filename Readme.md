# Final project

**Computational Visual Design Lab ([CVDLab](https://github.com/cvdlab))**  
**"Roma Tre" University, Rome, Italy**  
**Computational Graphics 2014**

## Subject: "Your Virtual Home"

Produce a `Three.js` environment which allows to navigate a textured (i.e. pretty good looking) model representing your home (possibly furnished), and to interact with some objects.

## Requirements

The base model must be modelled using `LAR-CC` pacakge. 

This base model must be imported in a `Three.js` based web environment.

The imported model must be provided with doors and windows and some articles of furniture.

Each mesh added to the environment must be pretty good looking (i.e.parametrize material and/or texture and/or bumpmap).

It must be possible to move and look around in the environment (i.e. use some kind of camera controls).

The environment must contain some sort of interaction with the model (i.e. use object-picking in association with object-animation).

### Enhancements

Any improvement to the list of the minimum requirements will be taken into consideration at the time of the final grade assignation.

Some improvement ideas could be:

* use dinamic texturing
* use a camera path to drive the user in a guided tour of your apt
* ...

## Evaluation

The final project aim to test the capabilities learned by the student during the course. Assuming that "no one tends to the ugly", we expect to see something pleasing to the eye. To see something awful could mean that the student does not master the techniques exposed during the lessons.

Do not be afraid to experiment: each step over the boundary of the course program will be appropriately recognized:

* graphic techniques number is boundless, we only lifted the lid (check the textbook for example!!!)

* HTML5 offers a huge variety of tools and APIs you are encouradged to explore


## Delivery

All the files you produce must be contained in a directory entitled `final_project`, pushed into the personal GitHub repository of the student: [https://github.com/cvdlab-cg/xxxxxx](https://github.com/cvdlab-cg/) where `xxxxxx` is the student ID  (matricola).

```
─── xxxxxx
    └── final_project
        ├── (images)
        |   └── (image01.png)
        |   └── (image02.jpg)
        |   └── (etc.jpeg)
        ├── scripts
        |   └── (script01.js)
        |   └── (script02.js)
        |   └── (etc.js)
        ├── (styles)
        |   └── (style01.css)
        |   └── (style02.css)
        |   └── (etc.css)
        ├── index.html
        └── Readme.md
```

Organize the folder structure in a tidy way: put all the JavaScript files into a directory called `scripts`, possibly stylesheet and image files into directories called `styles` and `images` respectively.

All the dependency files **must be included locally**.

Main file must be called `index.html`.

A file called `Readme.md` containing a description of the work must be produced. Use this file to explain how the code has been modularized and which graphic techniques has been applied and where. Use some kind of "dry-style" which can effectively shorten the discussion time by helping us to rapidly understand what you did.

The delivery is required before final project discussion.   
Final project discussions will be scheduled on July 2014, September 2014 and February 2014. Precise dates will be posted on CVDLab Facebook secret group: stay tuned!

## Tips

Don't forget to use the `dat.GUI` object to parametrize your virtual home environment.

## Coaching meetings

We're going to schedule some appointments all of you are strongly encouraged to take part in. During these meetings we'll gather all together in a classroom to share knowledge about graphics methods and techniques adopted by each of you to resolve problems encountered facing the final project.

The first of these meetings is scheduled for **Tuesday Jun 17th, 2:00PM in N14a**. **DON'T MISS IT**
