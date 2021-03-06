---
title: "Matrix Constraint Tool"

date: 2018-08-19
tags: [maya, Python, PyQt]
header:
  video:
excerpt: "Through my internet searches I came across a method 
that is more cost effective than Maya's built in constraint system. This method uses some of Maya's 
matrix utility nodes to create a constraint system. I decided to make a tool that automates this method
and mirrors Maya's built in constraint tool for easy use."

---


{% include video id="286953727" provider="vimeo" %}

 
Through my internet searches I came across a <a href="https://bindpose.com/maya-matrix-nodes-blending-matrices/" class="btn btn--primary">method</a>
that is more cost effective than Maya's built in constraint system. This method uses some of Maya's
matrix utility nodes to create a constraint system. Why would we want to use this method?
according to Vasil's testing for every 26 matrix constraints that replaced
Maya's constraints he won a frame of performance back. While the
results may be different depending on the system It's safe to say that we want
rigs to evaluate faster. What the problem? Well, the setup for this method is a little
cumbersome. So I decided to make a tool that automates this method
and mirrors Maya's built in constraint tool for easy use.
{: .text-justify}

The goal for this project was fairly simple.

* Create a tool that was similar enough to Maya's built in constraint tool that was familiar.
* Learn how to use the PyQt library to build the UI.
* Make sure the functionality can me separated from the UI.
* Lastly get it done in a weekend for my rigging buddy to test.

Overall I'm pretty happy that I was able get a better handle on Qt and that programmatically I
can see major improvements in my work. From learning python about seven months ago to building three 
tools that my colleague would use in their work flow is awesome!
{: .text-justify}

If you like to take the the tool for a spin or take a  look through my coding feel free
to download it from my  <a href="https://github.com/MoodieW/MatrixConstraint" class="btn btn--primary">Github</a> 

{: .text-justify}

