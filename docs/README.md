# Afterwards (aw)

## What is this?

This is (going to be) a task reminder utility for Linux, written in Bash or
Python or something. It will play a user-specified audio track for an alarm
and display an alert on the screen, probably.

### Usage

This is really tentative.

```
aw <date> <time> [-r mins] <task>
```

- date: Either an actual date like '7/5' (for July 5) or relative stuff like
'today' or 'tomorrow'. Maybe even weekday names.

- time: Time in the 24-hour format.

- -r mins: An option to sound the alarm 'mins' minutes before the task as well.

- task: The actual task.

### Possible components

- Language: Bash and/or Python
- Scheduling: the `at` command on Linux
- Data/database: SQLite or MySQL or regular text files
- Visual alert: `notify-send` or `zenity`
- Audio alert: ?

#### Misc

May have one of those `.*rc` runcom files for customization and may store all
the data in a `~/.aw/` directory or something.

## To contribute

Or not to contribute, that is the question.

Please check the [issues](https://github.com/trk9001/afterwards/issues) out,
and if you can help out with any, kindly make a pull request. You are also most
welcome to open an issue to report a bug or just to chat :)

## And by the way

*This is for **beb**.*