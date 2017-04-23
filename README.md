# workout-tracker
Simple fitness tracking app to input and track workouts.

## High level overview of how it works
Workouts are tracked daily, but can be repeated over a period of time.
Workouts consist of exercises.
Exercises consist of sets, reps, at a certain Tempo followed by a rest period.
Nice to have: Each exercise should keep track of the weights used over the set.

## Models
Workout: parent for exercises, date, repeat occurrences
Exercise: URL to video, Reps, sets, Tempo, rest period, notes, additional options as necessary
