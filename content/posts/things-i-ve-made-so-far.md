+++
categories = []
date = "2019-06-19T21:33:30+01:00"
image = "/uploads/calculator.png"
series = []
slug = "things-ive-made"
tags = ["projects", "odin"]
title = "Things I've made so far"

+++
I can say how much I’ve read about web development or how many tutorials I’ve completed, but the real evidence will be _things._ Things I’ve made that work and that can go on my CV.

So here’s where I’m at in terms of _things._

## CS50x project(s)

In my last blog I mentioned CS50x and why I stopped doing the course. Before that I did make some things, but sadly the course has its own IDE which doesn’t go on to Github, so I don’t have much to share. I will, when it comes to doing my CV, copy my work and upload them to a repository, but for now…

The one _thing_ I can share from that course was from an early lesson and used _Scratch_: MIT’s software which is meant to help young people (did I say I was 31?) understand the building blocks of coding.

So here’s Wanda’s Ghost. A ghost appears after a set amount of time, with a scream from Wanda when they meet. A simple introduction to loops. Nothing impressive but here it is anyway.

* [Wanda’s Ghost](https://scratch.mit.edu/projects/219965348/)

This leads nicely on to another reason why I settled on The Odin Project: it’s all done in your own environment.

You have to download the right software, get an understanding of the command line and git workflow. It isn’t all sitting nicely inside an IDE, such as is the case for CS50x. What this means is when I grasp a concept it means I’ve done it like a real-life web developer would have done and I haven’t just completed a tutorial online and then realised I don’t know where to begin if I’m taken out of that ready-made environment.

So for that reason there’s more from TOP that I can share with the outside world.

## The Odin Project… projects

First section of the course covers HTML and CSS, culminating in doing a **replica of the Google search page**. Eventually I got a result I was happy with:

* [Google UK home page](https://canicodenow.github.io/google-homepage/)
* [Github for the project](https://github.com/canicodenow/google-homepage)

We then move on to javaScript, which combines an actual programming language with HTML and CSS to create interactive web pages. The first project was **Rock, Paper, Scissors**, initially in the JS console, but then as a web page with interactive elements:

* [Rock, Paper, Scissors](https://canicodenow.github.io/rock-paper-scissors/)
* [Github for the project](https://github.com/canicodenow/rock-paper-scissors)

Another trip down memory lane – this time Etch-a-Sketch. This one caused some trouble – I don’t 100% grasp arrow functions yet – and I want to improve on some areas, but for now I’m more than happy:

* [Etch-a-Sketch](https://canicodenow.github.io/etch-a-sketch/)
* [Github for the project](https://github.com/canicodenow/etch-a-sketch)

It was time to create some simple maths functions and put them together into a calculator. I followed (and tweaked) a tutorial for CSS grid to create the look I wanted, and linked it up to javaScript. The code is pretty ugly and I have a list of bugs and todos but mostly it works and I'm pretty pleased:

* [Calculator](https://canicodenow.github.io/calculator/ "Calculator")
* [Github for the project](https://github.com/canicodenow/calculator%20%22Calculator%20project%20on%20Github "Calculator project on Github")

## Things to take into next project

* Use event listener method for the button clicks, as opposed to ‘onclick’. That way I can create a toggle button instead of different buttons for colours and black and white, which I did for this project.
* I still need to fully understand arrow functions – I’ve used them here as but I want to be able to refactor them into longer function declarations, just so that I truly ‘get it’. Something to learn

Here's a bit of code I want to fully understand:

    function changeGrid() {
        let children = document.querySelectorAll(".row");
        children.forEach(child => {
            container.removeChild(child);
        })
        let getGridSize = prompt("Choose number of rows for the grid", "16");
        createGrid(getGridSize);
    }

## Next targets

Ahead of the next section in TOP, which is Ruby, I want to:

* read more DOM manipulation sources, to better understand arrow functions and event listeners
* do two more [javaScript tutorials from Wes Bos](https://javascript30.com/)