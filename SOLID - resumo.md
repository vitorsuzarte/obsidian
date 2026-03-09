source #source/full-cycle
area #area/programming
subject #subject/fundamentals
type #raw  
related-notes

## SRP (Single Responsibility Principle)
- A class should only do one thing
- Could be renamed to
	- "A class should only have 1 reason to change"
* A class that sends an email and performs math operations has 2 reasons to change
* A common misconception of this principle is when people assume that a class can not perform a lot of operations, thinking it's doing too much. If the class respect its responsibilities range, that superfine.

## OCP (Open Closed Principle)
- A class should be opened for extension but closed for modification