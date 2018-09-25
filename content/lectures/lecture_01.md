% Geographic Data Science - Lecture I
% Introduction
%[Dani Arribas-Bel](http://darribas.org)

## Today

- This course
- The (geo-)data revolution
- (Geo-)Data Science 

#
## This course

## Quiz

* Can you think of a **real-world** context where **data** and statistics are being
  used to make a difference?
* Have you ever heard the term **"Data Science"**?
* Have you ever written a line of **computer code**?

## 

<div text-align="center" markdown="1">
*More stats than a GIS course, more GIS than a stats course...*
</div>

<div text-align="center" markdown="1" class="fragment">
*...but in a fun
way!*
</div>

## Philosophy

- (Lots of) **methods** and techniques
    - General overview
    - Intuition
    - Very little math
    - Lots of ways to continue on your own
- Emphasis on the **application** and **use**
- Close connection to **"real world"** applications

## Logistics - Website

[http://darribas.org/gds18](http://darribas.org/gds18)

<iframe src="http://darribas.org/gds18" width=600 height=400 ></iframe>

## Logistics - Format

11 weeks of:

- **Prep. materials**: videos, podcasts, articles... 1h. approx. (most recommended!)
- **1h. Lecture**: concepts, methods, examples
- **2h. Computer practical**: hands-on, application of concepts, Python
  (highly *employable*)
- **Further readings**: how to go beyond the minimum

## Logistics - Content

<ul>
<li class='fragment'> **Weeks 1-3**: "big picture" lectures + introduction to 
    computational tools (learning curve) </li>
<li class='fragment'> **Weeks 4-9**: "meat" of the course (lots of concepts packed) + Week 7 **break** </li>
<li class='fragment'> **Weeks 10-11**: catch up + prepare an awesome Computational Esssay </li>
</ul>

## Code

<iframe width="853" height="480" src="https://www.youtube.com/embed/M_rfujuRHUU" frameborder="0" allowfullscreen></iframe>

**Driving** Vs **automobile engineering**

## Python

<CENTER>
![](../content/lectures/figs/l01_xkcd-python.png)
</CENTER>

## Python

<ul>
* **General purpose** programming language
* Sweet spot between *"proof-of-concept"* and *"production-ready"*
* Industry standard: **GIS** (Esri, QGIS) and **Data Science** (Google, Facebook, Amazon, Netflix, The New York Times, NASA...)
</ul>

## Self-directed learning 

**Prepare** for the labs 

<ul>
<li class='fragment'> **I won't** be leading/lecturing at the computer labs </li>
<li class='fragment'> **Go over the notebooks** before the lecture and the computer lab
--> If the first time you see a notebook is at the lab, you won't be able to
  follow on </li>
<li class='fragment'> **Bring** questions, comments, feedback, (informed) rants to class/labs </li>
<li class='fragment'> Use the **forum** (link on VITAL) </li>
<li class='fragment'> **Collaborate** (it's **NOT** a zero-sum win!!!) </li>
</ul>

## More help!!!

This course is much more about **"learning to learn"** and **problem 
solving** rather than acquiring specific programming tricks or stats wizardry

<ul>
<li class='fragment'> Learn to **ask** questions <span class='fragment'> (but don't expect
    exact answers all the time!!!) </span></li>
<li class='fragment'> **Help** others as much as you can (the best way to learn is to teach) </li>
<li class='fragment'> **Search** heavily on Google + Stack Overflow </li>
</ul>

## Assignments

- In-lab <span class='hlg'>computer tests</span>: W.5 (25%) and W.10 (25%)
- <span class='hlg'>Computational essay</span> (W.12, 50%)
     - Equivalent to 2,500 word
     - Report (*notebook*) with **code**, **figures** (e.g. maps), and **text**
- <span class='hlg'>Discussion board</span> (5%)

**NOTE**: recommendation letters only for great students (**>70**)

#

## The (geo-)data revolution

## The (geo-)data revolution

Exciting times to be a:

* Geographer
* Map fan
* Data fan

The world is being **"datafied"**...

## "Datafication"

*Quantification of phenomena through the systematic recording of data*, *"taking all aspects of life and turning them into data"* [<small style="vertical-align: middle;">(Cukier &
Mayer-Schoenberg)](https://www.foreignaffairs.com/articles/2013-04-03/rise-big-data)</small>

**Examples**: credit transactions, public transit, tweets, facebook likes, spotify songs, etc. 

## "Datafication"

Many **implications**: 

* **Window** into human **behaviour** (this course)
* Opportunities for optimization of systems (Industrial IoT, planning
  systems...)
* Issues with **intentionality** and **privacy**
* ...

## *Why now?*

<div class="fragment">
Advances in:

* Computing power and storage
* Connectivity
* Geospatial technology
</div>

## The (geo-)data revolution

The confluence of the three (computing, communication and geospatial) is
creating large amounts of data.

Now, **data in itself is not very valuable**:

- Data --> Information --> Knowledge --> Action

# 

## Data Science

## 

<div text-align="center" markdown="1">
*Methods, tools and techniques to turn data into **actionable
knowledge** *
</div>

## Data Science

**Statistics** + ...

</ul>
<li class='fragment'> **Computational tools** --> Programming (hence this course's **tutorials**!) </li>
<li class='fragment'> **Comunication skills** --> "Story telling" (hence this course's **assignments**) </li>
<li class='fragment'> **Domain expertise** --> Theories about why the data are the way they are (hence
  the rest of your **degree**) </li>
</ul>

<span class='fragment'> Some examples... </span>

## {data-background=../content/lectures/figs/l01_chocolate.png data-background-size=contain}

## {data-background=../content/lectures/figs/l01_okcupid.png data-background-size=contain}

#
## **Geo**-Data Science
## **Geo**-Data Science

* A (very) large portion of all these new data are inherently **geographic** or can be traced back to some location over space.
* Spatial is special.
* Some of the methods require an explicitly spatial treatment --> (Geo-)Data
  Science

Some examples...

## {data-background=../content/lectures/figs/l01_airbnb.png data-background-size=contain}

## {data-background=../content/lectures/figs/l01_uber.png data-background-size=contain}

## {data-background=../content/lectures/figs/l01_gmaps.png data-background-size=contain}

## {data-background=../content/lectures/figs/l01_jsnow.jpg data-background-size=contain}

#
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Geographic Data Science'18 - Lecture 1</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://darribas.org" property="cc:attributionName" rel="cc:attributionURL">Dani Arribas-Bel</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.


