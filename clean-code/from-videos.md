Clean Code Notes
==

Video: clean code remake
--

> Martin Fowler: THis book is baseed on a fragile principle "Clean Code Matters"

Understanding code rot in detail
--

Rotted system is
- Rigid: modules break other modules, compile/test phase.
- Fragile: seemingly insignificant changes, break other parts of the system. e.g: relying on menu string as a client interface to api.
- Inseparable: Parts that can be profitably used in another system cannot be separated. e.g. trailerattached to back of a car that you want to reuse.
* Opaque Code: WTFs/minute ;) reading says nothing about the code

>We all are impedaded by bad code.
>
>But why?
>* time, pressure, customer.
>
>But we make a mess.
>
>I can fix it later
>WTF, never happens.
>
>Bad code not only slows us down in the long run, as we know by now but also in the short run.

Names
---

### **_reveal intent not content. badname._** 

* remember names are not for your convinence they are your primary tool for communicating intent (CI) 
* and CI is always your first priority
* its even more important than making sure that code works. 

### Avoid disinformation

* names that 
