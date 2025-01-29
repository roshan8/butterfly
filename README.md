# Butterfly!
 A task manager for command-line worshippers!! 

## Techonology choices:
- Go - Easy to build cross platform application.
- SQLite - Easy to substitute it with SQL once we chose to sync across devices.
- Goreleaser 

## Featureset

- Add a todo item with optional deadline
```sh
todo add "Submit SRE-3 JD" --due 2025-02-01
```

- List todo's
```sh
todo list
```

- Mark task as done
```sh
todo done 2
```

- Delete a task
```sh
todo delete 2
```

- Assign priority levels
```sh
todo add "Fix SRE-3 pipeline issue" --priority high
```

- List due reminders
```sh
todo list --overdue
```

- Ability to export todo's as json, yaml
```sh
todo export tasks.json
```

- Support multiple profile - work/personal.
- autocompletion with cobra-cli