## Team

```dataview
TABLE 
	dateformat(file.mtime, "yyyy-MM-dd") as "Last edited", 
	quickactions as "Quick actions"
from "Team"
where quickactions
sort file.name
```
## Tasks
```tasks
not done
group by filename
```
