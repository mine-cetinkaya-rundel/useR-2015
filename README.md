This repo contains slides and demo materials for the talk 
titled "Using R, RStudio, and Docker for introductory 
statistics" at [useR 2015](http://user2015.math.aau.dk/) 
in Aalborg, Denmark.

If you want to find out more details about the Docker setup,
shoot me an [email](mailto:mine@stat.duke.edu).

## TL;DR

### Why R?

#### Why / why not R?

- Why? Unlike many software designed specifically for
intro stat courses, R is 
    - free & open source, 
    - powerful & flexible, and 
    - **very importantly** relevant beyond the
intro stat classroom
- Why not R?
    - teaching programming in addition to stats concepts
    is challenging:
        * option 1: don't do any hands on data analysis ->
        terrible idea / disservice to students + faculty
        * option 2: use a grad-and-drop type tool -> 
        end up with drag-and-drop instruction hell
        * moral: there's a learning curve for any software,
        if you're going to have your students climb up
        some hill, make it worthwhile beyond just that
        one class
    - command line is intimidating: RStudio not so intimidating

### How R?

- Technical:
    - Short story: use RStudio, in the browser, avoid local
    installation for seamless entry and minimized frustration
    (by students + faculty)
    - Each RStudio session lives in a Docker container, containers
    persist for a semester (or more if you like)
    - See architecture slide in presentation for implementation
    details
- Pedagogical:
    - Reproducibility is the goal, and the tool for teaching R
    - Literate programming in R with RMarkdown
    - Scaffolding: Start with very hand-holdy templates, slowly
    take away the support, with end of semester goal of fully
    reproducible data analysis projects

### Resources:

- [OpenIntro](https://www.openintro.org/) for R labs
- [My github repo](https://github.com/mine-cetinkaya-rundel) for 
specific course details + materials for Sta 101 at Duke (course 
repos usually start with `sta101_` or `sta104_`, latter is the 
online version of the course)