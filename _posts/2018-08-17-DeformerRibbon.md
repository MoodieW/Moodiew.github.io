---
title: "Deformer Ribbon Tool"

date: 2018-08-17
tags: [maya, Python, PyQt]
header:
  video:
    id: 284256626
    provider: vimeo
excerpt: "As I got familiar with Rigging I found myself making ribbons a lot so I decided to make 
 a script to do it."

---



![image-center](/images/Deformer.PNG){: .align-center}
 
As I got familiar with Rigging I found myself making ribbons a lot so I decided to make a script to do it.
Than I found this <a href="https://vimeo.com/108727407" class="btn btn--primary">video</a> and I decided to 
add all of the functionality of Jorn-Harald Paulsen's ribbon into my script. It worked really well, but came
with its own set of challenges:

* Make sure the ribbon can be built between any two points in space.
* Make sure the blend shape can be created to match the ribbon the user sees.

The answer to both of the question came from vector math. I just happened to be learning basic vector math
for CG application at the same time of making this tool. This tools taught me a lot about vectors and 
matrices.
{: .text-justify}

If you like to take the the tool for a spin or take a  look through my coding feel free
to download it from my  <a href="https://github.com/MoodieW/DeformerRibbon" class="btn btn--primary">Github</a> 
{: .text-justify}

