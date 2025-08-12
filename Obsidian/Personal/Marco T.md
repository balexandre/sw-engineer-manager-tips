MAT, Senior Designer
## Personal
- Lives alone
- Loves cycling
- Big fan of indie films
## Conversations
```dataview
list 
	choice(
		contains(oneonone, [[Marco T]]),
		"(1:1)",
		"") +
	choice(
		contains(edd, [[Marco T]]),
		"(edd)",
		"") +
	choice(
		contains(with, [[Marco T]]),
		"(🗣️)",
		"") +
	choice(
		contains(hostedby, [[Marco T]]),
		"(📽️)",
		"")
where contains([oneonone, edd, with, hostedby], [[Marco T]])
sort file.name desc
```
