![Totally rad illustrations from Craig Reynolds' 1987 paper where he described his now-classic "boids" algorithm, which mimics the flocking of birds](https://raw.githubusercontent.com/jeffThompson/CreativeProgramming2/master/Images/Week10_Simulation/IllustrationFromCraigReynoldsOriginalBoidsPaper_1987.jpg)

# SIMULATION  
**DUE: MONDAY, APRIL 27**  

> "I think that my job is to observe people and the world" – Haruki Murakami  

> "If you know everything about a given metropolis, from its plumbing standards to its parking requirements, its sewer capacity to the borders of its school districts, then you coud more or less accurately imagine the future form of that city from the ground up." – Michael Sorkin on the game *Sim City*  

For our last regular project of the semester, we'll turn to the natural world for inpsiration. The goal is to bridge research, observation, and the "real world" with code. You should first pick a natural system of some kind and observe it very carefully. From there, you'll create a project in Processing (either the Java version or P5JS) that is inspired by your system. The output doesn't need to mimic or precisely simulate your chosen subject, but can either be a careful a reproduction of that system or a work that is inspired by its details.

Some examples:  
* Observe the way snow falls in the breeze and ways snowflakes form; create a piece that generates a never-ending snowfall  
* Research flower parts; create a flower generator that includes dozens of options that mix-and-match from existing plants  
* Observe the way ants move and interact with each other; build a simulator that creates drawings you can save and print  

Other things to consider: shells, growth/decay, animal hide/fur patterns, weather, terrain, migration patterns, bacteria and viruses, etc etc etc! Go for a walk, watch some *Blue Planet*, observe your cat or even your own body – you're surrounded by amazing things that can inspire your project.

Overall, your goal should be to include as many tiny details as possible. Keep in mind though that full-on, accurate simulations can require years of research and deep knowledge of their domain plus tons of complex math: the definition of a simulation is "an approximate imitation" so embrace that! Don't feel like you have to create a perfect digital version. Instead, think of this as a mixture of careful research, meticulous observation, and creative making to make something new.

*Above: totally rad illustrations from Craig Reynolds' [1987 paper where he described his now-classic "boids" algorithm](http://www.cs.toronto.edu/~dt/siggraph97-course/cwr87), which mimics the flocking of birds*


## DELIVERABLES  
* PDF containing sketches and research notes (upload to Canvas)  
* PDF listing minimum viable product and stretch goals (upload to Canvas)  
* Github repo including:  
	* README explaining your project and the system that inspired it  
	* Sketch code  
	* PDF of your research  
	* Screen recording of your piece running  
	

## TIMELINE  
* **April 6:** Ideation, research, and sketches  
* **April 13:** Create a rough version of your project, list MVP and stretch goals; write `Final Project` proposal  
* **April 20:** Continue working on this and your `Final Project`  
* **April 27:** Project due  


## CODE EXAMPLES/VIDEO TUTORIALS  
Video walkthroughs of the tutorials for this project can be found in this YouTube playlist: [https://www.youtube.com/playlist?list=PLsGCUnpinsDnfiHYpasqrFC5VNzqnXFeh](https://www.youtube.com/playlist?list=PLsGCUnpinsDnfiHYpasqrFC5VNzqnXFeh)

If you need other help, please pop into our open Zoom hours or send me a note! All code examples can be found in this project's `Code` folder.


## FOR MONDAY, APRIL 13  
For next week, pick the natural system you'd like to research and observe. Reading will be useful, but equally important is looking. You should ideally be able to observe your system in real life but if you can't, watch videos on YouTube etc in the same way you would in person. Make notes, draw sketches of different parts – the goal is an understanding that goes beyond the superficial, allowing you later to translate these things into code.

You should also research your topic (Wikipedia and its "related articles" is a great place to start), taking careful notes on anything that seems interesting or helpful. Follow links in Wikipedia articles too – rabbit holes of knowledge are super productive for this kind of work.

When done, photograph all your sketches (if you're working analog) and put them into your notes file using Word, etc. Tidy everything up and arrange it so it feels cohesive, then save as a PDF and upload to Canvas.


## FOR MONDAY, APRIL 20  
Having researched your natural system, your goal for next week is to write up a Minimum Viable Product (MVP) document and to start prototyping your simulation in code. MVPs are part of the [Agile development approach](https://en.wikipedia.org/wiki/Agile_software_development) – as you might suspect, they list what is a baseline version of your project (what, at a minimum, it needs to be "viable" or finished). This might seem overly-simple, but it can be really helpful: an MVP articulates what you need to do first and helps avoid getting distracted by fun features at the expense of the core of your project. 

We won't be following the format of MVPs as they are used for app or product development. Instead, you can think of this as a to-do list. What is the core functionality, features, and visual elements your project needs? You can also list "stretch goals," elements you want to add if time allows.

For example, if we were building a snowfall simulator, our MVP might list:

* Generate various snowflake shapes algorithmically  
* Create realistic falling motion  
* Respawn snowflakes when they hit the bottom of the screen  
* Wind changes direction of snowfall  
* Stretch goal: physics applied to larger/smaller snowflakes  
* Stretch goal: let snowflakes pile up on the ground  

A good MVP becomes a to-do list *and* is kind of like an outline for your code! Write up your MVP in list-form, like above but in as much detail as you can. When done, add it as a comment in the assignment.

Once your MVP is written, start working on your simulation in code. The goal this week should be that you accomplish a few things in your MVP and have a better idea what questions and challenges you need help with.


## FOR MONDAY, APRIL 27  
This week, you should finish up your simulation project – either in its final state or as a check-in if you're extending this into your final project. Be sure to check the `Deliverables` section above for what to turn in (note this includes a screen recording of your piece running, see [this video](https://www.youtube.com/watch?v=RMulAbsNF9I) for doing this with Quicktime and similar software, and [this one](https://www.youtube.com/watch?v=kQDuBzXbUq4) for using FFMPEG).

If you're planning to use this for your final project too, you should still have a working version done by next week. This will allow you to get feedback, then expand the project to be even more amazing.


## RESOURCES  
* Jason Webb's list of [Moprhogenic Resources](https://github.com/jasonwebb/morphogenesis-resources) is a great place to start (however, copying a known algorithm like reaction-diffusion isn't enough here!)  
* Daniel Shiffman's excellent online book [*The Nature of Code*](https://natureofcode.com/book/)  
* D'arcy Wentworth Thompson's amazing 1917 book [*On Growth and Form*](https://archive.org/details/ongrowthform1917thom)  
* [PROCJAM](http://www.procjam.com/), a game jam for projects made using procedural generation – their site includes some [great tutorials](http://www.procjam.com/tutorials/) and sample projects for inspiration  


## PROJECTS SHOWN  
* Craig Reynolds' classic 1986 simulation program [*Boids*](https://en.wikipedia.org/wiki/Boids), which can create complex behavior with very simple rules  
* [Valentino Braitenberg's vehicles](https://en.wikipedia.org/wiki/Braitenberg_vehicle), which use rules similar to Reynolds'  
* Simulation games like [*No Man's Sky*](https://www.youtube.com/watch?v=nLtmEjqzg7M), [*Sim City*](https://www.youtube.com/watch?v=wjxVci-fWj4), [*Roller Coaster Tycoon*](https://www.youtube.com/watch?v=qvHAdeOw3fI), and the insanely-detailed [*Train Simulator*](https://www.youtube.com/watch?v=_ygMfRLjDag)  
* The insanely detailed software package [SpeedTree](http://www.speedtree.com), used for making hyper-realistic trees for games and animations (they offer a free trial, if you want to try it out) – a [few](https://www.youtube.com/watch?v=rucfLNcDnPM) different [examples](https://www.youtube.com/watch?v=r18c7QlWLBQ) of what it can do  
* OpenAI's creepy [*Emergent Tool Use*](https://openai.com/blog/emergent-tool-use/) experiment  
* Procedurally-generated landscape like Martin O'Leary's amazing [*Uncharted Atlas*](https://twitter.com/unchartedatlas) (see his great [writeup on the process](http://mewo2.com/notes/terrain/))  
* Everest Pipkin's [*Moth Generator*](https://twitter.com/mothgenerator)  

