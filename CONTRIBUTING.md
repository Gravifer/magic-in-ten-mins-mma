# Not a contribution guide

The current state of this branch (typesys/Head) contains a working ADT definition of an integer type.
It has however, been laborious, and any further more (even only slightly) advanced ADTs will be even more laborious.

I will call the issue the _negative inertness pattern_: one need to ensure that the type constructure leave it as is when passed a correct argument, and abort the computation when passed anything else; this is completely backwards to the general convention used in Mathematica. As many people have done ADT (e.g. Roman Maeder in his books from 90's) or even Monads (like [here](https://community.wolfram.com/groups/-/m/t/3478726) or [here](https://github.com/antononcube/WL-MonadMakers-paclet)), it's important to pick a way that can at least stay consistent throughout the magic-in-10-mins tutorial, and preferably atually possible to integrate into the day-to-day mathematica practice.

### possible to-dos

- [ ] make the ADT codegen automated; maybe publish it as a resfunc.
