ETR, Product Owner
## Personal
- Married
- Enjoys woodworking
- Has a rescue dog
## Conversations
```dataview
list 
	choice(
		contains(oneonone, [[Ethan R]]),
		"(1:1)",
		"") +
	choice(
		contains(edd, [[Ethan R]]),
		"(edd)",
		"") +
	choice(
		contains(with, [[Ethan R]]),
		"(🗣️)",
		"") +
	choice(
		contains(hostedby, [[Ethan R]]),
		"(📽️)",
		"")
where contains([oneonone, edd, with, hostedby], [[Ethan R]])
sort file.name desc
```
