
- has a 2 year old son
- lives in the city
## Conversations
```dataview
list 
	choice(
		contains(oneonone, [[New Person]]),
		"(1:1)",
		"") +
	choice(
		contains(edd, [[New Person]]),
		"(edd)",
		"") +
	choice(
		contains(with, [[New Person]]),
		"(🗣️)",
		"") +
	choice(
		contains(hostedby, [[New Person]]),
		"(📽️)",
		"")
where contains([oneonone, edd, with, hostedby], [[New Person]])
sort file.name desc
```