Game Development: Harder Than You Think
===

Author: Jim Blow

### Abstract
The hardest part of making a game has always been the engineering. In times past, game engineering was mainly about low-level optimization—writing code that would run quickly on the target computer, leveraging clever little tricks whenever possible.

But in the past ten years, games have ballooned in complexity. Now the primary technical challenge is simply getting the code to work to produce an end result that bears some semblance to the desired functionality. To the extent that we optimize, we are usually concerned with high-level algorithmic choices. There’s such a wide variety of algorithms to know about, so much experience required to implement them in a useful way, and so much work overall that just needs to be done, that we have a perpetual shortage of qualified people in the industry.

### Notes

    * Games used to be about getting this code to run quickly on low-end machines -- now developers just want the code to work. Optimization is rarely used now.
    * "perpetual shortage of qualified people in the industry"
    * Two categories of problems
        * complexity
        * domain-specific

    * games are really complex in size yet lack proper tool support
    * "Console life cycles, however, are about five years long, and there isn’t much motivation for the tool-maker to improve their products toward the end of that cycle. Typically, a console developer will be using an environment with only one to four years of maturity—not an enviable situation."
    * long compile times (2 minute min to 30 min high)
    * takes long time to see effect of even smallest change (5 min)
    * configuration management is hard for multiple platforms
    * often better to write own modules than take time to integrate existing 3rd party modules
        * games are CPU intensive and 3rd party modules often cause bottlenecks

    * Can use existing game engine, but only if not doing any technological new stuff
    * game programmers need lots of math (linear algebra, geometry, calculus, quaternions)
    * gaming is simulation of a world
    * profiling is important, need to determine what causes bottlenecks in performance. This is hard because what causes the bottleneck this second might be different the next second.


### References
1. Fristrom, J. Manager in a Strange Land: Turnaround Time. Gamasutra (Nov. 28, 2003); http://www.gamasutra.com/features/20031128/fristrom_01.shtml(free account and password required).

2. Fristrom, J. Manager in a Strange Land: Content Turnaround. Gamasutra (Dec. 5, 2003); http://www.gamasutra.com/features/20031205/fristrom_01.shtml (free account and password required).

8. Blow, J. Interactive Profiling 1-3. Game Developer Magazine (Dec. 2002-Feb. 2003).
