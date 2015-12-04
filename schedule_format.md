# schedule format

for [Deggy reformatter](https://github.com/chicks-net/deggy-reformatter)

The `schedule.raw` file is formatted entries like:

* **day** applies to the subsequent schedule lines and at least one should come before any other entries
	* format: `dow month/day/year` as in `Fri 11/27/2015`
* **schedule** entries require a start and end time in military time (`HHMM`, no AM/PM)
	* format: `start - end    who` as in `0200-1000 chicks`
* **event** entries require a start time in military time
	* format: `start   what` as in `0420  party time` 
* **blank** lines are ignored
* **comments** should be preceded by `#` and will be printed out
