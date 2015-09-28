# What to Do When Your Data Tells You There Is Something Wrong with the Universe
<br>
_Alessandro Orso_, Georgia Institute of Technology

## Prologue

In "Remember Me", an episode of _Star Trek: The Next Generation_, Dr. Beverly Crusher does not realize that, due to a science experiment gone awry, she has ended up inside a spacetime disturbance.  After a series of unexpected and, to her, unexplainable events, she tries to calm herself and assess her situation in order to find a way out of it.  Thinking back over what has transpired, Dr. Crusher states: "If there's nothing wrong with me, maybe there's something wrong with the universe!"


In the remainder of this chapter, we describe our view, as informed outsiders, of the landscape of the research in and applications of data science for software engineering.  Although our objective is to provide a general overview that can be used to categorize existing work in this area, we do not engage in such a categorization.  Put another way, while we deliberately do not focus on specific projects or papers, our discussion is informed by the work that has appeared in various software engineering venues over the past decade.

##Learning from Data 


###1. Incorrect Conclusions

Incorrect conclusions can be drawn because of reliance on incomplete, tainted, and/or noisy data, poor statistical analysis, wrong inferences, and overgeneralization.  Some of these pitfalls (e.g., bad statistics) can be remedied through appropriate training.  Others (e.g., bad data) cannot be remedied as readily.  Acting on incorrectly drawn conclusions can clearly have serious consequences.

###2. Partially Correct Conclusions

Conclusions regarding complex phenomena may be correct in certain respects, while being wrong in others. Unfortunately, basing important decisions on them may be as detrimental as acting on completely incorrect conclusions.  Especially in software engineering, the extent of our current understanding of the factors that yield such (partially) incorrect conclusions is limited at best.  This is certainly exacerbated by the temptation, as researchers, to highlight and focus on positive results.

###3. Correct but Useless Results

Certain phenomena, while analyzable, are not worthy of analysis, as they provide answers to questions that are not worth asking in the first place.  Many examples of "low hanging fruit" fall in this category.  Although they are often attractive, because they are easy, they should be avoided just the same.  In other words, if a paper "practically writes itself", one should let it and move on to something else.

###4. Correct but Obvious Results

Certain phenomena may be worthy of analysis, but only if it is not already clear ahead of time what results the analysis will yield.  Empirically confirming a hypothesis or a suspicion, even if they appear well founded and likely, is an important part of science.  Answering questions that have already been answered, or that can be answered much more quickly and easily than through a given data analysis procedure, is wasteful. 

###5. Correct But Not Readily Usable Results

Analysis of certain phenomena may correctly yield conclusions that are not at all obvious.  However, those conclusions may be "dead ends" in that they are neither usable to practicing engineers nor do they form a foundation for further studies.  In such cases, the analysis is little more than an intellectual exercise ("we do it because we can")--the kind of work performed by researchers who live in the proverbial ivory tower.

###6. Correct, Non-Obvious, Modest Steps

Certain conclusions may enrich an engineer's palette of methods, techniques, and tools.  Even a moderate improvement over the current state of the art is valuable, regardless of the complexity of the underlying analysis that yielded that improvement.  The assumption is, of course, that the complex analysis was not undertaken in lieu of a simpler, much more straightforward approach that would have yielded the same answers (see above).

###7. Correct, Non-Obvious Game-Changers

This is the "holy grail" of software analytics research and practice--a result that changes how researchers think about and approach their field, as well as how developers think about and do their work.  It is likely a combination of painstaking work, subtle insights, unique perspective, and sometime also luck.  It is not necessarily repeatable,  it cannot be forced, and at least some parts of it cannot be taught. 


![](BellCurve.jpg)<br>

To avoid this situation, we encourage all researchers in the area of data science for software engineering if not to use our (informal) classification, to at least try to assess where their work falls in terms of usefulness and actionability of their findings. We believe that doing so, and acting accordingly (i.e., by holding off or considering more specialized venues in case of non-actionable or unsurprising results) can considerably improve both the quality and the longevity of this area.