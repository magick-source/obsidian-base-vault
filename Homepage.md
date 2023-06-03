# Active Goals
```dataviewjs
dv.list(dv.pages("#activeGoal").file.link)
```

#### To Do
> [!warning] Due This Week
> ```tasks
(due before next week) OR (scheduled before tomorrow)
not done
sort by priority
sort by due
short mode
limit 5
> ```

> [!info] Top Tasks without due date
> ```tasks
NOT (path includes Templates)
no due date
no scheduled date
not done
sort by priority
short mode
 limit 5
> ```


> [!done] Done today
> ```tasks
done
done on today
> ```


## Random Notes
```dataviewjs
let limit = 2;
let notes = dv.pages('"RandomNotes"')
	.sort(k => 0.5 - Math.random())
	.limit(limit)
	.map(note => note.file.link);
dv.list(notes);
```

