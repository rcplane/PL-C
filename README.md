# Purpose

Implement a variant of the PL/C persistent diagnostic compiler originally developed at Cornell University to run on the IBM 360 computer.
https://en.m.wikipedia.org/wiki/PL/C

# Why

Self-correcting program compiler design can improve user experience today.
Implementing these ideas in their original form can provide insight into reduced language subsets for efficient computation and programmer facilitation.

# Plan

- Install [Hercules emulator for IBM 360](http://www.hercules-390.org/)

- Load [Turnkey MVT system image](http://www.ibiblio.org/jmaynard/)

- As a parallel effort, evaluate function of a [C interpreter for PL/I](http://www.mpsinc.com/pl1c.html)

- Test PL/I programs http://teampli.net/

- Read more about [PL/C design](https://ecommons.cornell.edu/handle/1813/5952)

- Implement a subset for simple programs

- Progressively expand to more complex PL/I lanugage subsets

- Increase compiler persistence and facilitation

- Consider a concrete benchmark such as [counting with a hashmap](https://benchmarksgame-team.pages.debian.net/benchmarksgame/description/knucleotide.html#knucleotide) to guide development
