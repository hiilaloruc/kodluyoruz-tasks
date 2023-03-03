## Task 2 - Zoo Management UML
### Requirements
You design a system to track information about animals in a zoo.
#### Animals: 
1. Horses (horses, zebras, donkeys, etc.),
1. Felines (tigers, lions, etc.),
1. It is characterized by species in groups such as rodents (rats, beavers, etc.).
1. Most of the information stored about animals is the same for all groupings. (species name, weight, age, etc.)

- The system should also be able to get the dosage of specific drugs for each animal => **getDosage()**
- System should be able to calculate Feed times => **getFeedSchedule()**

The logic for the system to perform these functions will be different for each grouping. For example, the feeding algorithm will be different for horses and different for tigers.

Using the **polymorphism model**, design a class diagram to handle the situation described above.

## UML :

![This is UML Class Diagram.](https://beeimg.com/images/z59996544921.png "This is UML Class Diagram.")