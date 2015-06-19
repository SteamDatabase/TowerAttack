Historic data of rooms and their levels

### Structure
File names are timestamps when data was collected, in format like `Y-m-d_H-i`.
Times are UTC. Time step is 5 minutes.

File in `levels/` folders are key value pairs,
where key is room id, and value is current level at that time.

All levels are zero based, if you want to display correct level, add one.
