Episode 2 Names
===

Names
---

### **_reveal intent not content. badname._** 

* remember names are not for your convinence they are your primary tool for communicating intent (CI) 
* and CI is always your first priority
* its even more important than making sure that code works. 

### Avoid disinformation

* names that dont mean what they said, thats disinformation, worst sin a programmer could ever make.
* name, like an honourable human should "say what is means and mean what it says"
* change names when meaning change, but it can be hard, due to many constraints. e.g. public api. etc.
* should be pronounceable

* **my idea look at popular open source projects and apply these principles** great idea.

### avoid encoding

* prefixing names with type, e.g IDate => interface, CDate => class
* IDE and compiler, and unit tests protects us from type errors.
* old 90's style might not be relevant today.

### Parts of speech

* Classes and variables are nouns or noun phrases. Methods are verbs or verb phrases (getPrice, or postPayment)
* avoid noise words, manager, processor, info, data, (what about Handler? Service? )
* boolean variables should be written as predicates, isSomething, hasSomething. isTerminated, isEmpty
* martin prefers getFirstName() to firstName(). Martin school of thought. 
* Enums: adjectives, state or object descriptors.

### Scope length and name length

**Variable Names**
* for variables that are in scope, TestResult tr = something, and its used immediately, its 
perfectly valid name. it reads better. 
* longer the scope of the variable, longer the name. But variable should have short scope.
* if scope is few lines then we could perfectly use variable name e, instead of element. 
 
**Class and Function names**
* they follow the opposite rule, longer the scope shorter the name. File.open
* and private methods tend to have longer names, explaining what they are trying to do. e.g. tryToProcessInstructions()

# Recap
* watch video, it summarises everything very succinctly. 

> Any fool can write code that computer can understand, but it takes a good programmer to write code that humans can understand -- Martin Fowler ;)
