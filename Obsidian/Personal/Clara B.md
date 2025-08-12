CLB, QA Specialist
## Personal
- Shares an apartment with friends,
- Runs marathons
- Coffee aficionado
## Conversations
```dataview
list 
	choice(
		contains(oneonone, [[Clara B]]),
		"(1:1)",
		"") +
	choice(
		contains(edd, [[Clara B]]),
		"(edd)",
		"") +
	choice(
		contains(with, [[Clara B]]),
		"(🗣️)",
		"") +
	choice(
		contains(hostedby, [[Clara B]]),
		"(📽️)",
		"")
where contains([oneonone, edd, with, hostedby], [[Clara B]])
sort file.name desc
```
